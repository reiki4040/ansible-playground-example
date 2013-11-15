# ansible-playground-example

This project is environment for ansible practice.  

MacOS(ansible) --(provisioning)--> VM(Virtualbox)

### environment infomations.

This project default environment of vagrant box(Vagrantfile)

* Ubuntu 12.04
* VM IP is 192.168.50.11

## Getting started

### install Virtualbox

Download and install [VirtualBox](https://www.virtualbox.org/)

### install ansible

#### MacOS(homebrew)

    brew update  
    brew install ansible

if you don't installed homebrew, install it right now!  
[homebrew](http://brew.sh/) is very useful!

#### other installation

please read [ansibleworks](http://www.ansibleworks.com/docs/intro_installation.html
) or ask Google!

### clone this project

    git clone https://github.com/reiki4040/ansible-playground-example.git
    cd ansible-playground-example


### ssh configuration

add ssh configuration of vagrant box to ssh config file.

    cat ssh_config >> ~/.ssh/config

please change permission if you create ssh config first time.

    chmod 600 ~/.ssh/config

### ansible ping

run box.
    
    vagrant up

ping to VM.

    ansible -i hosts all -m ping

show below message (success) is OK.

    192.168.50.11 | success >> {
        "changed": false, 
        "ping": "pong"
    }

### Got ready?

**Let's learn ansible!!**

## TODO

* create sample playbook