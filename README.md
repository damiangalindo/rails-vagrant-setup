First you have to download vagrant http://www.vagrantup.com/downloads.html and virtualbox https://www.virtualbox.org/wiki/Downloads in order to setup the development environment,
install the following plugins for vagrant

`vagrant plugin install vagrant-vbguest`
`vagrant plugin install vagrant-librarian-chef`

after that clone this repository and start vagrant typing in the terminal `vagrant up`, after vagrant is up, use `vagrant ssh` to enter in the virtual machine, once you are there type `cd /vagrant` and start coding using
