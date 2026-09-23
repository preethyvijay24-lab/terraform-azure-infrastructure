# Azure Infrastructure Deployment Using Terraform

## 📌 Project Overview

This is a beginner-level hands-on project to learn how to deploy Azure infrastructure using **Terraform Infrastructure as Code (IaC)**.

Instead of creating Azure resources manually through the Azure Portal, Terraform configuration is used to provision and manage the infrastructure.


## Screenshots

-[All-resource-group](#All-resource-group)

-[Terraform-success](#Terraform-success)

-[VM-logged-in](#VM-logged-in)






## All-resource-group

<img width="1016" height="565" alt="allresou" src="https://github.com/user-attachments/assets/3f1975ea-9827-4c87-b1be-e8babc619b52" />



## Terraform-success


<img width="739" height="262" alt="01 apply" src="https://github.com/user-attachments/assets/ba110eb4-86fb-4871-b998-60c097d462d8" />



## VM-logged-in


<img width="878" height="577" alt="04 vm" src="https://github.com/user-attachments/assets/e81ff2ad-9212-41bc-a835-5ff32443d43a" />





## Azure Resources Created

The project creates:

* Azure Resource Group
* Azure Virtual Network
* Azure Subnet
* Azure Public IP
* Network Security Group
* Network Interface
* Windows Virtual Machine

## 🛠️ Technologies Used

* Microsoft Azure
* Terraform
* Azure CLI
* Visual Studio Code
* Infrastructure as Code (IaC)


```

## 🔄 Terraform Workflow

```text
Write Terraform Configuration
          ↓
    terraform init
          ↓
    terraform validate
          ↓
      terraform plan
          ↓
     terraform apply
          ↓
   Azure Infrastructure
          ↓
    terraform destroy
```

## 🚀 Steps Performed

### 1. Azure Authentication

Logged into Azure using Azure CLI:

```powershell
az login
```

### 2. Initialize Terraform

```powershell
terraform init
```

### 3. Validate Configuration

```powershell
terraform validate
```

### 4. Review Infrastructure Changes

```powershell
terraform plan
```

### 5. Deploy Infrastructure

```powershell
terraform apply
```

### 6. Verify Resources

Verified the deployed resources through the Azure Portal.

### 7. Clean Up

After completing the lab, resources can be removed using:

```powershell
terraform destroy
```



