## 📌 Project Overview

This project demonstrates how to manage Azure Resource Groups using multiple Azure tools including Cloud Shell, Azure CLI, and Azure PowerShell. The tasks walk through the complete lifecycle of resource groups—creation, listing, and deletion—across different regions.

---

## 🔷 Task Summary

### 1️⃣ Azure Cloud Shell
Azure Cloud Shell is launched directly from the Azure Portal, and a resource group named `new-rg` is created in the South Central US region. This shows how resource deployment can be done from a browser without installing any tools locally.

### 2️⃣ Azure PowerShell
Azure PowerShell is connected to the Azure subscription, and a new resource group named `rg-powershell` is created in the South Central US region. This demonstrates resource provisioning using PowerShell cmdlets.

### 3️⃣ Create & List Resource Groups (CLI + PowerShell)
Three additional resource groups are created in the West US region using both Azure CLI and PowerShell. The project also lists and filters only the resource groups located in that region, showing how cloud resources can be queried using different command-line tools.

### 4️⃣ Delete Resource Groups
All resource groups created in the West US region are deleted using a single Azure CLI command and a PowerShell script. This step validates resource cleanup and cost control using automation.

---

## 🎯 Outcome

By completing these tasks, the project provides hands-on experience with:
- Azure Cloud Shell
- Azure CLI command usage
- Azure PowerShell scripting
- Resource group lifecycle management
- Automation of creation, filtering, and deletion of Azure resources

This project builds confidence in working with Azure administration across multiple tools and environments.
