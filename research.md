Q. How can I convert a manually created virtualbox VM into a 'box' consumable by Vagrant? 
A. Use the [vagrant package command](https://www.vagrantup.com/docs/cli/package). 

```
vagrant package --base vault --output cyberark_vault.box
==> vault: Clearing any previously set forwarded ports...
==> vault: Exporting VM...
==> vault: Compressing package to: /Users/markthomsen/lab.markthomsen.org/CyberArk/private_software/boxes/cyberark_vault.box
```

* Troubleshooting Tip: On installing PVWA
- Install as adminstrator
- Do not set host headers in the binding configuration for the site
- Self-signed certificates is OK.