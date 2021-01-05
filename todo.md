## Release 1
- Working architecture with one vault, one CPM, and one PVWA
- Built manually 
- VMs saved as Vagrant boxes, or similar format, for re-provisioning later. 

## Release 2


## Ideas
Powershell script that prepares an existing VM into packer. 
Creating a VM with all the troubleshooting tools for creating CyberArk profiles
Update provisioning script to install latest version of vmwarebox tools
Provisioning scripts for different server roles (i.e. Vault, PVWA, CPM)
Automatically update DNS/Host file with proper names
Answer files for CyberArk installs 
Automatic configuration of IIS on PVWA, including self-signed certificate 
Improve the domain join power shell script 
Automatically disable all firewalls
Removing the bad key sequences within vmwarebox that prevents accidentally rebooting vm. [Documentation](https://www.virtualbox.org/manual/ch08.html)
Figure out how/why two network adapters are configured by scripts
Automatically generate a report that illustrates architecture of lab and credentials. 
Sequencing of booting up architecture
Conversion of Vagrant file to new HCL2 that mirrors terraform language (better for learning)
Software management within the architecture

### Completed
Being using git/github to manage configure files. 


## References
[PVWA Server Role Requirements](https://docs.cyberark.com/Product-Doc/OnlineHelp/PAS/Latest/en/Content/PAS%20INST/Before-Password-Vault-Web-Access-Installation.htm?tocpath=Installation%7CInstalling%20the%20PAS%C2%A0Solution%7CManual%20Installation%7CEnterprise%20Password%20Vault%7CInstall%20the%20PVWA%7C_____2)