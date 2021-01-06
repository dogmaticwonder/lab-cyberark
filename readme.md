# Lab Information 

Vault
- Master/Administrator Password to Vault: 'Passw0rd'
- IPs - see file


## Release schedule

__Release 1__
   - Basic lab with one vault, one PVWA and one CPM
   - Components talk to one another, but application isn't configured beyond that
   - No safes beyond those created during install
   - CyberArk authentication for PVWA
   - Flat network
   - No hardening anywhere
   - Default install
   - No special drive partioning 
   - Boxes for each component created and uploaded



__Release 2__
- Expand architecture to include a Windows and Linux end-point
- Add PSM for SSH component 
- Add very basic configuration that can be built upon
- Windows end-point has development tools
- Create entries in hosts file for components


__Release 3__
- Vagrantfile revised to include downloading of pre-built boxes from a password-protected URL


