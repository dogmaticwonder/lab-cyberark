## Release schedule

__Release 1__
- Lab contains one of each: vault, cpm, and pvwa
- Vagrantfile points to manually built boxes from detectionLab
- The password for everything set manually is 'Passw0rd'
- All components appear have been been successfully installed as per their install logs
- No safes were created beyond those created by the software install itself (i.e. CPM)
- Authenticate to CyberArk PVWA with 'administrator' and 'Passw0rd'. It's using 'CyberArk Authentication
- When the option was presented, hardening was declined. CPM may have done it since an option to decline wasn't presented. 
- Network is a flat class C - 10.130.50.x/24
- Default install for everything 
- No special drive partitioning
- PVWA does reflect a failed CPM installation earlier; needs to be removed in next release
- Vagrant boxes were created for each component and uploaded to [my GSA drive](https://drive.google.com/drive/u/1/folders/1wBNLx2AZbOvOkNuI4pQQx0-74RvYX14c)
- This concludes release 1

__Release 1.1__
- Expand architecture to include a Windows and Linux end-point
- Bridged networking for splitting across multiple hosting platforms 
   -- Hosting system modifications not included (i.e. adding a new adapter to access the lab)





__Release 3__
- Windows end-point has development tools
- Implement this style of Vagrant file || https://gist.github.com/dlutzy/2469037
- Convert Vagrant file to new format and implement some of the ruby stuff here:https://github.com/patrickdlee/vagrant-examples/blob/master/example6/Vagrantfile
- Vagrantfile revised to include downloading of pre-built boxes from a password-protected URL
- Create a shell script that wraps Vagrant into different parts of the lab (i.e. core, vs end-points)
- Add PSM for SSH component 
- Add very basic configuration that can be built upon
- Revise Vagrantfile to pull from 
- Create entries in hosts file for components
- Approach to running lab across multiple Vagrant hosts
