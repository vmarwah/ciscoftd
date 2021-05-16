# Cisco Firepower NGFW Virtual (NGFWv) Firewall - ARM template with Availability set configuration

Use this template to deploy Cisco FTD devices in availability set configuration on Azure.

Since marketplace image doesn’t provide Availability set configuration option during the deployment, therefore custom template has to be used to meet such requirements.

This template can be used to deploy any image file of Cisco FTD in Azure. You just have to create the image file for the same version before start deploying the above template. Below link provides steps to be followed prior to template deployment. 

https://www.cisco.com/c/en/us/td/docs/security/firepower/quick_start/azure/ftdv-azure-gsg/ftdv-azure-deploy.html#id_82702

Note:  Change VM image id to your storage account resource ID on Custom template deployment page.
