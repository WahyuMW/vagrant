Vagrant.configure("2") do |config|
    config.vm.box = "debian/jessie64"
	#devbox.vm.network "private_network", ip: "192.168.199.9"
	config.vm.hostname = "wahyu-node-debian"
    config.vm.box_version = "8.11.0"
 	config.vm.provision "shell", path: "scripts/install.sh"
	config.vm.provider "virtualbox" do |v|
	  v.memory = 4096
	  v.cpus = 2
	end
end
