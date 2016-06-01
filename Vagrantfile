# -*- mode: ruby -*-
# vi: set ft=ruby :
Vagrant.configure(2) do |config|
  config.vm.box = 'nodejs-box'
  config.vm.box_url = 'https://s3-ap-northeast-1.amazonaws.com/doridoridoriand/nodejs-vm.box'

  config.vm.provider 'virtualbox' do |vb|
    vb.cpus   = 2
    vb.memory = 2048
  end

  config.vm.network 'private_network', ip: '192.168.33.120'
  config.vm.synced_folder './works', '/home/vagrant/works'

end


