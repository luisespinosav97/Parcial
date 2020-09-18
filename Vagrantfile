# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

 config.vm.define :serverPXE do |serverPXE| 

  serverPXE.vm.box = "bento/centos-7.8"
  serverPXE.vm.network "private_network", ip: "192.168.33.10"
  serverPXE.vm.hostname = "serverPXE"

 end
end
