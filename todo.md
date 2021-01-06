## Issues

## Ideas
Low
- Update provisioning script to install latest version of vmwarebox tools
- Update BGINFO script to display less information. 
- Provisioning scripts for different server roles (i.e. Vault, PVWA, CPM)
- Answer files for CyberArk installs 
- Automatic configuration of IIS on PVWA, including self-signed certificate 
- Improve the domain join power shell script 
- Automatically disable all firewalls
- Removing the bad key sequences within vmwarebox that prevents accidentally rebooting vm. [Documentation](https://www.virtualbox.org/manual/ch08.html)
- Figure out how/why two network adapters are configured by scripts
- Software management within the architecture

Moderate
- Automatically generate a report that illustrates architecture of lab and credentials.
- Sequencing of booting up architecture 
- Conversion of Vagrant file to new HCL2 that mirrors Terraform language (better for learning)


### Completed
- Being using git/github to manage configure files. 
- Power shell script that prepares an existing VM into packer. 
   -- CLI command instead of power shell. 


### Dispensed
- Creating a VM with all the troubleshooting tools for creating CyberArk profiles
  	- Added to Release 2 scope
- Automatically update DNS/Host file with proper names
	- Added to Release 2; manually create records since IPs are hard-coded


