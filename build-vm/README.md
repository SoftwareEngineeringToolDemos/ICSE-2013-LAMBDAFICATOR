## Please follow these steps to spinup a Virtual Machine for Lambdaficator:

1. Install <a href="https://www.vagrantup.com/downloads.html">Vagrant</a> and <a href="https://www.virtualbox.org/wiki/Downloads">VirtualBox</a> on the host machine.
2. Download the <a href="https://github.com/SoftwareEngineeringToolDemos/ICSE-2013-LAMBDAFICATOR/blob/master/build-vm/Vagrantfile">Vagrantfile</a> from <a href="https://github.com/SoftwareEngineeringToolDemos/ICSE-2013-LAMBDAFICATOR/tree/master/build-vm">build-vm</a> directory to your machine.
3. In the host, cd into the directory that contains the Vagrantfile and run the command "vagrant up"

## Note:

* The VM boots up quickly and can be viewed from Virtual Box. But the "vagrant up" command runs for approximately an hour.
* The base box on which this VM is built is <a href=https://atlas.hashicorp.com/hashicorp/boxes/precise32>Ubuntu Server 12.04</a>
* VM login details:
  Username: vagrant
  Password: vagrant

## Acknowledgements:
* The commands for installing Java 8 have been taken from <a href="https://github.com/aglover">Andrew Glover's<a> <a href="https://github.com/aglover/ubuntu-equip">github repository</a>.
* The commands for installing Netbeans in have been taken from 
* <a href="http://thoughtfulsoftware.blogspot.com/2013/04/how-to-run-ide-inside-vagrant-vm.html">this blog</a>.
