## Question and Answer 

Q. How can I convert a manually created virtualbox VM into a 'box' consumable by Vagrant? 
A. Use the [vagrant package command](https://www.vagrantup.com/docs/cli/package). 

```
vagrant package --base vault --output cyberark_vault.box
==> vault: Clearing any previously set forwarded ports...
==> vault: Exporting VM...
==> vault: Compressing package to: /Users/markthomsen/lab.markthomsen.org/CyberArk/private_software/boxes/cyberark_vault.box
```

--------

* Troubleshooting Tip: On installing PVWA
- Install as adminstrator
- Do not set host headers in the binding configuration for the site
- Self-signed certificates is OK.


--------

Q. How do I configure BGinfo.exe? 
A. Go here to learn how to configure BGinfo.exe [Link](https://www.howtogeek.com/school/sysinternals-pro/lesson7/)

----

## References
[PVWA Server Role Requirements](https://docs.cyberark.com/Product-Doc/OnlineHelp/PAS/Latest/en/Content/PAS%20INST/Before-Password-Vault-Web-Access-Installation.htm?tocpath=Installation%7CInstalling%20the%20PAS%C2%A0Solution%7CManual%20Installation%7CEnterprise%20Password%20Vault%7CInstall%20the%20PVWA%7C_____2)

https://github.com/hollodotme/Helpers/blob/master/Tutorials/vagrant/self-hosted-vagrant-boxes-with-versioning.md

## Scratch pad
########################
### Ubuntu end-points ###
########################
config.vm.box = "bento/ubuntu-18.04"
config.vm.box = "ubuntu/trusty64"