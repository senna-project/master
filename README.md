Senna Master
========

[![Build Status](https://travis-ci.org/senna-project/master.svg)](https://travis-ci.org/senna-project/master)

Installation
------------

Requirements:

``` bash
sudo aptitude install libmicrohttpd-dev libjsoncpp-dev libcurl4-openssl-dev libconfig++-dev libboost-signals-dev build-essential automake

$ git clone https://github.com/senna-project/master
$ cd master
$ make 

# Configure master  
$ vim ydle.conf 

# Run master  
 
$ sudo sh master.sh