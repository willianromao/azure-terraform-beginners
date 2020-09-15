# azure-terraform-beginners
Beginners Guide to Terraforming Azure
az vm list --query "[[?powerState=='VM deallocated'].name, [?powerState=='VM deallocated'].powerState]" -d -o table
