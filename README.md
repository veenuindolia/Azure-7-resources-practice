# Azure-7-resources-practice

## Terraform code written for 7 Resources

### In this Repo code written for all resources for creating simple Landing zone in which 3 Virtual machines are created

In this code 2 Vnets are created, In one Vnet, three subnets are created, one for frontend VM, one for backend VM and one for Azure bastion. In second Vnet, one subnet is created for database VM.

frontend VM - Windows VM
backend VM - Linux VM
database VM - Linux VM

Azure bastion will be used to access VM's.

First we will coneect to windows VM through Azure bastion & will access linux VM of first VM through ssh login using private ip of backend VM.

Also Vnet peering is done between both Vnets. So will also access linux VM of Vnet throuh windows VM..