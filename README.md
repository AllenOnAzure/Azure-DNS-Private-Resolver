# Azure-DNS-Private-Resolver
Provisioning Azure DNS Private Resolver using PowerShell

The first script provisions 3 virtual networks (to emulate a DNS HUB vnet, a spoke vnet and an on premise vnet) into a single RG,
With tagging and locks, 
With vnet peering between the spoke and HUB vnet, 
To will need to CREATE and divide your vnets into 3 rgs for PROD. 
