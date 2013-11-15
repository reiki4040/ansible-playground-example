# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

  config.vm.define :ansible_playground do |ansible_playground|
    # please specify url of box file that you use.
    # box list -> http://www.vagrantbox.es/
    # or other box.
    ansible_playground.vm.box_url = "http://files.vagrantup.com/precise64.box"
    ansible_playground.vm.box = "ubuntu12_64"
    ansible_playground.vm.network :private_network, ip: "192.168.50.11"
  end
end
