## Start

Before the installation we will need a custom CentOS7 virtual box image with SElinux disabled.

### DON`T FORGET TO EDIT VagrantFile with path to your ssh folder

## Installation

Let's start our virtual machines with Vagrant
```
vagrant up
```
Then let's start our playbook

```
ansible-playbook nginx
```

## Done

You can get yourself a coffee! ☕
