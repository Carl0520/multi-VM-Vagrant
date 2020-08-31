
Vagrant.configure("2") do |config|
  VAGRANT_VM_PROVIDER = "virtualbox"
  ##### DEFINE VM #####
  config.vm.define "offlinenode1" do |machine|
    machine.vm.hostname = "offlinenode1"
    machine.vm.box = "generic/ubuntu1804"
    machine.vm.box_check_update = false
    machine.vm.network "private_network", ip: "192.168.11.151"
    machine.vm.provider "virtualbox" do |node|
      node.name ='offlinenode1'
      node.memory = 4096
      node.cpus = 2
    end
  end

  config.vm.define "offlinenode2" do |machine|
    machine.vm.hostname = "offlinenode2"
    machine.vm.box = "generic/ubuntu1804"
    machine.vm.box_check_update = false
    machine.vm.network "private_network", ip: "192.168.11.152"
    machine.vm.provider "virtualbox" do |node|
      node.name ='offlinenode2'
      node.memory = 4096
      node.cpus = 2
    end
  end
end
