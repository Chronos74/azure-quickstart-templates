# Create Remote Desktop Sesson Collection deployment

This template deploys the following resources:

<ul><li>RD Gateway/RD Web Access vm</li><li>RD Connection Broker/RD Licensing Server vm</li><li>A number of RD Session hosts (number defined by 'numberOfRdshInstances' parameter)</li></ul>

The template will use existing DC, join all vms to the domain and configure RDS roles in the deployment.

If you're using AD DS you must enter a global administrators credentials for the Admin Username and Admin Password variables'

Click the button below to deploy

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FChronos74%2Fazure-quickstart-templates%2Fmaster%2Frds-deployment-existing-ad%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FChronos74%2Fazure-quickstart-templates%2Fmaster%2Frds-deployment-existing-ad%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>
