# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.define :my_site do |site|
    site.vm.box = "centos/7"
    site.vm.network :private_network, ip: "192.168.33.101"

    site.vm.provider "virtualbox" do |vb|
      vb.memory = "8192"
    end
  end
end
