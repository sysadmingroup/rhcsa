# RHCSA 8 Automated Practice Deployment <br>
_Powered by Ansible and Vagrant_  <br>
# SysAdminGroup http://www.sysadmin.co.in <br>

# Installation options below: <br>
## Windows 10 OS <br>
#Prerequisites <br>
Download and install Virtual Box from https://www.virtualbox.org/wiki/Downloads <br>
Download and install Vagrant from https://www.vagrantup.com/downloads <br>
Download and install Git from https://git-scm.com/download/win <br>

## open cmd and run below commands 

mkdir %HOMEPATH%\bin <br>
cd %HOMEPATH%\bin <br>
git clone https://github.com/sysadmingroup/rhcsa.git . <br>
vagrant up <br>


## steps to distroy all VM images (if you want to recreate from scratch) <br>
open cmd and run below commands<br>
cd %HOMEPATH%\bin<br>
vagrant destroy -f<br>

## again run below command to recreate VM setup<br>
open cmd and run below commands<br>
cd %HOMEPATH%\bin<br>
vagrant up<br>

## Note:
Repo URLs
BaseOS http://192.168.55.149/BaseOS
AppStream http://192.168.55.149/AppStream 