# Hologic Terraform Templates

## Azure Linux VM

This template deploys a Linux virtual machine (VM) with infrastructure that includes a virtual network, subnet, public IP address, Apache web server and more.

## Azure Windows VM

This template deploys a Windows virtual machine (VM) with infrastructure that includes a virtual network, subnet, public IP address, IIS web server and more.

## Terraform resource types

- [random_pet](https://registry.terraform.io/providers/hashicorp/random/latest/docs/resources/pet)
- [azurerm_resource_group](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/resource_group)

- [azurerm_virtual_network](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/virtual_network)
- [azurerm_subnet](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/subnet)
- [azurerm_public_ip](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/public_ip)
- [azurerm_network_security_group](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/network_security_group)
- [azurerm_network_interface](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/network_interface)
- [azurerm_network_interface_security_group_association](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/network_interface_security_group_association)
- [random_id](https://registry.terraform.io/providers/hashicorp/random/latest/docs/resources/id)
- [azurerm_storage_account](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/storage_account)
- [azurerm_linux_virtual_machine](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/linux_virtual_machine)
- [azapi_resource](https://registry.terraform.io/providers/Azure/azapi/latest/docs/resources/azapi_resource)
- [azapi_resource_action](https://registry.terraform.io/providers/Azure/azapi/latest/docs/resources/azapi_resource_action)

## Variables

| **Name** | **Description** | **Default** |
|---|---|---|
| `resource_group_location` | Location of the resource group. | westus2 |
| `resource_group_name_prefix` | Prefix of the resource group name that's combined with a random ID so name is unique in your Azure subscription. | rg |
| `resource_name_prefix` | Prefix of the resource name combined with other resources in your Azure resource group. | holx |
| `username` | The username for the local account that will be created on the new VM. | xxxx |
| `password` | The password for the local account that will be created on the new VM. | xxxx |
| `disaster_recovery_copies` | The number of disaster recovery copies or replicas. | 2 |

