Vagrant.configure("2") do |config|
    config.vm.box = "rockylinux/8"
    config.vm.hostname = "k3s"
    config.vm.provider "virtualbox" do |vb|
      vb.name = "rockylinux-prod-leek"
      vb.cpus = 2
      vb.memory = 2048
    end
end

