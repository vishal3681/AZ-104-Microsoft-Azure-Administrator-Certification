## Azure Web Apps
<img width="1916" height="839" alt="image" src="https://github.com/user-attachments/assets/64383981-f917-47c1-8bf6-5b64b6062842" />
Web App working fine
<img width="1913" height="950" alt="image" src="https://github.com/user-attachments/assets/b2235121-5b67-41c8-9e54-96a8c4355009" />
After making some changes in WEB APP html file 
<img width="1919" height="935" alt="image" src="https://github.com/user-attachments/assets/24efe644-bd36-49e4-a748-fe54f166b80d" />

## Azure Web Apps - Deployment Slots
in this we can upgrade service plan of our webapp
<img width="1918" height="769" alt="image" src="https://github.com/user-attachments/assets/ce87cd71-ef79-4677-8ffd-d62b6867e6a6" />
we can swap staging and production slots 

### Autoscaling for Web Apps
with the standard app service plan and higher we can schedule autoscalling based on rule
with the premium app service plan and higher we can configure automatic scalling 

### Deploying Docker on a virtual machine
ubuntu VM created 
<img width="1898" height="746" alt="image" src="https://github.com/user-attachments/assets/01c7b976-b2a9-4a6a-b93a-10baf3dfec2a" />
VM Successfully connect and installing docker in VM
<img width="1678" height="823" alt="image" src="https://github.com/user-attachments/assets/ef55b780-7b81-45e4-a978-3c91c65ba7cd" />
<img width="1764" height="834" alt="image" src="https://github.com/user-attachments/assets/bbfbc07d-4d84-419f-a6a1-fc9fa704931b" />
<img width="1917" height="826" alt="image" src="https://github.com/user-attachments/assets/892264c4-4a1f-4f87-bd1f-7e51a2a20cfe" />

#### Azure Container Registry
Creating container registry 
<img width="1908" height="814" alt="image" src="https://github.com/user-attachments/assets/f48d72d3-c051-450f-9f14-86aee485313f" />
Hosting docker image 
<img width="1916" height="939" alt="image" src="https://github.com/user-attachments/assets/60e3a0a2-205f-469c-93bf-e7621da42fa7" />
image successfully push on container registry
<img width="1701" height="639" alt="image" src="https://github.com/user-attachments/assets/e956592b-e167-418e-9578-7f8888623909" />

creating zure Container Instances
<img width="1915" height="862" alt="image" src="https://github.com/user-attachments/assets/9b56913f-aad5-4c07-90a3-332788614cb9" />
<img width="1906" height="926" alt="image" src="https://github.com/user-attachments/assets/12948298-65e9-4708-9c8a-f131da119692" />
Azure Container Apps - Resources
The following commands can be used as a reference for the prior chapter

1. We first need to create the Azure Container App environment

az containerapp env create --name "phpapp-env" --resource-group "app-grp" --location "North Europe"

2. Then we can create the Azure Container app

az containerapp create --name "phpapp-service" --resource-group "app-grp" --environment "phpapp-env" --image "appregistry34000.azurecr.io/phpapp" --target-port 80 --ingress 'external' --registry-server appregistry34000.azurecr.io --query properties.configuration.ingress.fqdn

<img width="1906" height="813" alt="image" src="https://github.com/user-attachments/assets/2cdcda7c-8a03-4b0c-8e98-d4e59c16904a" />

### Section 4: Configure and manage virtual networking
Creating Virtual Network 
<img width="1919" height="764" alt="image" src="https://github.com/user-attachments/assets/ac8640c1-5dc5-4504-955a-1207c6e0a2a1" />

Deploying a machine to the virtual network
<img width="1914" height="768" alt="image" src="https://github.com/user-attachments/assets/e17309dc-dc26-477a-a9c3-aa1b74e2c9cf" />







