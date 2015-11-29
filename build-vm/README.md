### Please follow these steps to spinup a Virtual Machine for Lambdificator:

1. Install <a href="https://www.vagrantup.com/downloads.html">Vagrant</a> and <a href="https://www.virtualbox.org/wiki/Downloads">VirtualBox</a> on the host machine.
2. Install <a href="https://github.com/aidanns/vagrant-reload">vagrant reload plugin</a> using the command "vagrant plugin install vagrant-reload"
3. Download the <a href="https://github.com/SoftwareEngineeringToolDemos/ICSE-2013-LAMBDAFICATOR/blob/master/build-vm/Vagrantfile">Vagrantfile</a> from <a href="https://github.com/SoftwareEngineeringToolDemos/ICSE-2013-LAMBDAFICATOR/tree/master/build-vm"> directory </a> to your machine.
4. In the host, cd into the directory that contains the Vagrantfile and run the command "vagrant up"

## Note:

1. The VM boots up quickly and can be viewed from Virtual Box. During the installation of NetBeans, there may not be any verbose. That <b>doesn't</b> mean the provisioning is stuck. Please be patient and the provisioning completes in 35-40 minutes.
2. Once the provisioning is done, you'll see Netbeans opened in the VM. The project demonstrating Lambdaficator is available on the Desktop (Lambda_Test). Please open this project in NetBeans and the working of the tool can be observed as it is shown in the video demo.
3. The base box on which this VM is built is <a href=https://atlas.hashicorp.com/hashicorp/boxes/precise32>Ubuntu Server 12.04</a>
4. VM login details:<br/>
Username: vagrant<br/>
Password: vagrant

## Acknowledgements:
1. The commands for installing Java 8 have been taken from <a href="https://github.com/aglover">Andrew Glover's<a> <a href="https://github.com/aglover/ubuntu-equip">github repository</a>.
2. The commands for installing Netbeans in have been taken from <a href="http://thoughtfulsoftware.blogspot.com/2013/04/how-to-run-ide-inside-vagrant-vm.html">this blog</a>.
3. <a href="http://www.dev9.com/article/2014/9/dev-environments-with-vagrant">Vagrant tutorial</a> by Dustin Barnes

## Troubleshooting in case of any failure:
1. If "vagrant up" fails during the provisioning with errors related to VBoxManage.exe (the chances of this happenning are very slim), please run "vagrant reload --provision" and vagrant picks up the provisioning from where it left off. 
