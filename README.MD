# Windows 2919 Server VM and Key Vault Demo Environment

This template allows you to deploy a D2s_v3 size VM with Windows 2019 Server [Generation 2 VM](https://docs.microsoft.com/azure/virtual-machines/generation-2) from old image base containing RCE vulnerabilities. Windows Update is disabled. Also, it deploys a Ke Valut, a Managed System Identity assigned to the VM with permission to access the Key Vault.

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FGastori%2Fcloudmapdemoenv%2Fmain%2Fdeploy.json)



## Note: for Lab and dev only