Vagrant.configure("2") do |config|
<<<<<<< HEAD
config.vm.define :servidor do |servidorPXE|
servidorPXE.vm.box = "bento/centos-7.9"
servidorPXE.vm.network :private_network, ip: "192.168.50.4",
virtualbox__intnet: "lan1"
servidorPXE.vm.hostname = "servidorPXE"
=======
config.vm.define :cliente do |cliente|
cliente.vm.box = "bento/centos-7.9"
cliente.vm.network :private_network, ip: "192.168.50.2"
cliente.vm.hostname = "cliente"
end
config.vm.define :servidor do |servidor|
servidor.vm.box = "bento/centos-7.9"
servidor.vm.network "forwarded_port", guest: 80, host: 8080
servidor.vm.network :private_network, ip: "192.168.50.3"
servidor.vm.hostname = "servidor"
>>>>>>> archivo vagrant file para realizar vagrant share
end
end