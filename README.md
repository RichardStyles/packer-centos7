Centos 7 x64 (minimum) Packer Vagrant
========================

This repository contains template for CentOS 7.1 x64 that can create Vagrant base box using Packer.

Packer command
-------------
`packer build centos7.json`

This command creates the box for Vagrant.

Vagrant command
-------------
`vagrant box add packer-test build/centos-7.1-x64.box`

This add's the box created from the packer command into Vagrant's local store.

`vagrant up`

Will start up the Centos 7.1 box.
