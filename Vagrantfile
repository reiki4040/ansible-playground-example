# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

  config.vm.define :ansible_example_env do |ansible_example_env|
    # please specify url of box file that you use.
    # box list -> http://www.vagrantbox.es/
    # or other box.
    ansible_example_env.vm.box_url = "http://files.vagrantup.com/precise64.box"
    ansible_example_env.vm.box = "ubuntu12_64"
    ansible_example_env.vm.network :private_network, ip: "192.168.50.11"
  end
end
