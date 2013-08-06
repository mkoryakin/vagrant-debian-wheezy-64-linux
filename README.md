## About

#### This script was upgraded to work in arch linux env

This script will:

 1. download the `Debian 7.1 "Wheezy"` server, 64bit iso
 2. ... do some magic to turn it into a vagrant box file
 3. output package.box

## Usage

    ./build.sh

This should do everything you need.

To add `package.box` with name `debian-71` into vagrant:

    vagrant box add "debian-71" package.box

### Notes

#### This script is clone of [repo](https://github.com/dotzero/vagrant-debian-wheezy-64) with some changes to work on Arch Linux 
This script basted on original Carl's [repo](https://github.com/cal/vagrant-ubuntu-precise-64) and with some tweaks to be compatible Debian 7.1.
