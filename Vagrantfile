Vagrant.configure("2") do |config|
config.vm.define :servidor do |servidorPXE|
servidorPXE.vm.box = "bento/centos-7.9"
servidorPXE.vm.network :private_network, ip: "192.168.50.4",
virtualbox__intnet: "lan1"
servidorPXE.vm.hostname = "servidorPXE"
end
end