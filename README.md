# vagrant-env-setup
Step by step guide to setup virtual box and use vagrant for env setup
Please follow below instructions to setup the virtual machines:
1. Download and install vagrant:
https://www.vagrantup.com/downloads.html

 2. Download and install virtual box:
https://www.virtualbox.org/wiki/Downloads

 3. Download this github repo and extract the zip file.
    https://github.com/ScaledV/vagrant-env-setup.git
4.	For Windows, download and install GITBashshell (https://git-scm.com/downloads) 
Note: If you are working in Mac, you can use Terminal instead
5.	Open git bash shell
cat ~/.ssh/config << ServerAliveInterval 20
6.	For Windows, restart the machine and press F2 or F10 to go into Bios mode. VT-x/AMD-v virtualization must be enabled in BIOS 
7.	Open git bash shell or Terminal, navigate to the unzipped vagrant directory:
     #cd  ~/vagrant-env-setup      #vagrant up <machinename from node.json>
8.	Enter ip address through putty: #vagrant ssh <machine name>
username /password :  vagrant/vagrant 

9.	Sudo -i
