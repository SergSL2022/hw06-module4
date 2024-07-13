# hw06-module4

## Vault

### 1. Run local k8s cluster: kind/minikube/...
![alt text](<screenshots/1/Знімок екрана з 2024-07-13 14-59-45.png>)


### 2. Install Vault using helm
![alt text](<screenshots/2/Знімок екрана з 2024-07-13 17-07-56.png>)
![alt text](<screenshots/2/Знімок екрана з 2024-07-13 17-08-08.png>)


### 3. Create secret in vault and add other configuration
![alt text](<screenshots/3/Знімок екрана з 2024-07-13 20-10-32.png>)
![alt text](<screenshots/3/Знімок екрана з 2024-07-13 20-11-18.png>)
![alt text](<screenshots/3/Знімок екрана з 2024-07-13 20-38-28.png>)
![alt text](<screenshots/3/Знімок екрана з 2024-07-13 20-38-34.png>)


### 4. Setup test postgres as on lesson
### 5. Confirm that secret was added to the pod


## Operator (Optional)

### 1. Install Vault Secret Operator
### 2. Create a secret from Vault and your namespace
### 3. Update secret in vault and confirm that it was changesd in k8s