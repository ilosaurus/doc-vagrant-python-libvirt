Vagrant.configure("2") do |config|
  config.vm.box = "generic/ubuntu1804"
  config.vm.network "private_network", 
    :libvirt__network_name => 'net-10.10.10',
    :libvirt__network_address => '10.10.10.0',
    :ip => '10.10.10.20'
  config.vm.provider "libvirt" do |v|
    v.memory = 2048
    v.cpus = 2
  end
end
