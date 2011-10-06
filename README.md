# Kohana-Veewee-Template

Builds Vagrant base box using Veewee and ubuntu-10.04.3-server-i386.

Additional packages installed:

* libaugeas-ruby

## Tutorial

From your veewee directory:

    git clone https://github.com/ernestas/Kohana-Veewee-Template.git definitions/vagrant-ubuntu-10.04.3-server-i386
    vagrant basebox build vagrant-ubuntu-10.04.3-server-i386 -n
	vagrant basebox validate vagrant-ubuntu-10.04.3-server-i386
	vagrant basebox export vagrant-ubuntu-10.04.3-server-i386
	vagrant box add vagrant-ubuntu-10.04.3-server-i386 vagrant-ubuntu-10.04.3-server-i386.box
