#Vagrant.configure("2") do |config|
#  config.vm.box = "ubuntu/xenial64"
#end
Vagrant.configure("2") do |config|
config.vm.box = "ubuntu/xenial64"
config.vm.network "forwarded_port", guest: 80, host: 1080
config.vm.network "forwarded_port", guest: 1337, host: 1337
config.vm.network "forwarded_port", guest: 9292, host: 9292
config.vm.network "forwarded_port", guest: 8080, host: 17080
config.vm.network "forwarded_port", guest: 8081, host: 17081
config.vm.provider "virtualbox" do |vb|
vb.memory = "2048"
end
end
