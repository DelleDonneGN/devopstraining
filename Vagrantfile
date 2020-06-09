# -*- mode: ruby -*-
# vi: set ft=ruby :

  Vagrant.configure("2") do |config|
 #	config.vm.provider "virtualbox" do |vb|
#	config.vm.box = "ubuntu/xenial64"
  	config.vm.box = "hashicorp/bionic64"
	

config.vm.provision "ansible_local" do |ansible|
	ansible.compatibility_mode="2.0"
	ansible.playbook ="playbook.yml"
	end
  
end
