# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|



# Server mit verschiedenen Php-Versionen

  config.vm.define :web1 do |config_web1|
    config_web1.vm.box = "precise32"
    config_web1.vm.box_url = "http://files.vagrantup.com/precise32.box"
    config_web1.vm.host_name = "web1"
    config_web1.vm.network "private_network", ip: "192.168.50.10"
        #virtualbox__intnet: true
    

  end

  config.vm.define :web2 do |config_web2|

    config_web2.vm.box = "precise32"
    config_web2.vm.box_url = "http://files.vagrantup.com/precise32.box"
    config_web2.vm.host_name = "web2"
    config_web2.vm.network "private_network", ip: "192.168.50.11"
    #virtualbox__intnet: true


  end

  config.vm.define :db1 do |config_mysql1|

    config_mysql1.vm.box = "precise32"
    config_mysql1.vm.box_url = "http://files.vagrantup.com/precise32.box"
    config_mysql1.vm.host_name = "db1"
    config_mysql1.vm.network "private_network", ip: "192.168.50.12"
        #virtualbox__intnet: true


  end

end
