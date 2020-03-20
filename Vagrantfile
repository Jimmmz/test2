# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure("2") do |config|
    #global config
    config.vm.box = "allthingscloud/web-page-counter"
    config.vm.provider "virtualbox" do |v|
        v.memory = 1024
        v.cpus = 1
    end
    config.vm.define "leader01" do |leader01|
        leader01.vm.hostname = "test"
    end
end
