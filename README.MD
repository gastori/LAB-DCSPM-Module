# Windows 2919 Server VM and Key Vault Demo Environment

This template allows you to deploy:
 - a D2s_v3 size VM with Windows 2019 Server [Generation 2 VM](https://docs.microsoft.com/azure/virtual-machines/generation-2) from old image base containing RCE vulnerabilities. Windows Update is disabled. 
 - a D2s_v3 size VM with with Ubuntu 22.10 Minimal-Install [Generation 2 VM](https://docs.microsoft.com/azure/virtual-machines/generation-2). This Image contains an RCE vulnerability - OpenSLLv3, and it is configured to for manual updates.
 
 Also, it uses the Managed System Identity assigned to the VM to assign permission to access the Key Vault, Storage Account, and Azure SQL Server.



[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https%3A%2F%2Fraw.githubusercontent.com%2Fgastori%2FLAB-DCSPM-Module%2Fv.01.16.23%2Fmain.json)



## Note: for Lab and dev only