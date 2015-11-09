# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "hashicorp/precise64"

  # config.vm.network "forwarded_port", guest: 50505, host: 50505

  config.vm.provision "shell", run: "once", path: "provisioning.sh"
end
