VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  
  config.vm.box = "ubuntu/precise64"
  config.vm.network "private_network", ip: "192.168.2.2"
  config.proxy.http     = "http://username:password@server:port"
  config.proxy.https    = "http://username:password@server:port"
  config.vm.provision "shell", path: "rabbitmq.sh"
  
end
