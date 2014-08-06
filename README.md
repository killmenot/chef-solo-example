chef-solo example
==============

Experiments with Vagrant, Chef and CentOS to use in development purposes

Requirements
------------

 - [Ruby](https://www.ruby-lang.org/en/installation/)
 - [Vagrant](http://www.vagrantup.com/downloads.html)
 - [Chef Client](http://www.getchef.com/chef/install/)
 

Used cookbooks
------------
 - [nginx](https://supermarket.getchef.com/cookbooks/nginx)
 - [iptables](https://supermarket.getchef.com/cookbooks/iptables)

Usage
------------
```
$ vagrant box add centos64-x86_64 http://developer.nrel.gov/downloads/vagrant-boxes/CentOS-6.4-x86_64-v20131103.box
$ git clone git://github.com/killmenot/chef-solo-example
$ cd chef-solo-example
$ bundle
$ librarian-chef install
$ vagrant up
```

References
------------
 - [http://leopard.in.ua/2013/01/04/chef-solo-getting-started-part-1/](http://leopard.in.ua/2013/01/04/chef-solo-getting-started-part-1/)
 - [http://leopard.in.ua/2013/03/25/chef-server-getting-started-part-1-bonus/](http://leopard.in.ua/2013/03/25/chef-server-getting-started-part-1-bonus/)
