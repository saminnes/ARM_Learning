# Create Remote Desktop Sesson Collection deployment

This template deploys the following resources:

<ul><li>storage account;</li><li>vnet, public ip, load balancer;</li><li>domain controller vm;</li><li>Three availability sets for DC, ADFS and WAP;</li><li>a number of ADFS hosts (number defined by 'numberOfADFSInstances' parameter)</li><li>a number of WAP hosts (number defined by 'numberOfWAPInstances' parameter)</li></ul>

The template will deploy DC, join all vms to the domain and configure ADFS and WAP roles in the deployment.

Click the button below to deploy

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fsaminnes%2FARM_Learning%2Fmaster%2FADFS%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fsaminnes%2FARM_Learning%2Fmaster%2FADFS%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>