# Create a new Sharepoint Farm with 3 VMs

This template creates three new Azure VMs, each with a public IP address and load balancer and a VNet, it configures one VM to be an AD DC for a new Forest and Domain, one with SQL Server 2014 SP1 domain joined and a third VM with a Sharepoint 2013 farm and site, all VMs have public facing RDP

Click the button below to deploy

<<<<<<< HEAD
<a href="https%3A%2F%2Fraw.githubusercontent.com%2Faverkinderen%2FAzure%2Fmaster%2Fsharepoint-three-vm%2Fazuredeploy.json" target="_blank">
=======
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Faverkinderen%2FAzure%2Fmaster%2Fsharepoint-three-vm%2Fazuredeploy.json" target="_blank">
>>>>>>> 4d3f6e0c68ce423114fcb262d320ad306be5ff91
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2Fsharepoint-three-vm%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

Notes: Sharepoint farm name must not contain spaces.
