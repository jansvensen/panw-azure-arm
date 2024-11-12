
# **Deploy a two-tiered application environment secured by the VM-Series firewall**

This ARM template deploys a VM-Series next generation firewall VM in an Azure resource group along with a web and db server similar to a typical two tier architecture. It also adds the relevant User-Defined Route (UDR) tables to send all traffic through the VM-Series firewall.

![alt_text](azure-topology.png?raw=true)

# <a href="https://github.com/PaloAltoNetworks/azure/blob/master/two-tier-sample/Azure_ARM_template_deployment_guide.pdf">Deployment Guide</a> 

# **Support Policy**
This ARM template is released under an as-is, best effort, support policy. These scripts should be seen as community supported and Palo Alto Networks will contribute our expertise as and when possible. We do not provide technical support or help in using or troubleshooting the components of the project through our normal support options such as Palo Alto Networks support teams, or ASC (Authorized Support Centers) partners and backline support options. The underlying product used (the VM-Series firewall) by the scripts or templates are still supported, but the support is only for the product functionality and not for help in deploying or using the template or script itself.
Unless explicitly tagged, all projects or work posted in our GitHub repository (at https://github.com/PaloAltoNetworks) or sites other than our official Downloads page on https://support.paloaltonetworks.com are provided under the best effort policy.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fjansvensen%2Fpanw-azure-arm%2Fmaster%2Ftwo-tier-sample%2FazureDeploy.json" target="_blank">Deploy in Azure</a> 

<a href="https://raw.githubusercontent.com/jansvensen/panw-azure-arm/master/two-tier-sample/azureDeploy.json" target="_blank">Visualize</a> 