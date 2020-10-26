
Vagrant.configure("2") do |config|
    config.vm.box = "ubuntu/bionic64"
    config.vm.network "private_network", ip: "192.168.33.11"
    config.vm.provision "shell", inline:
"apt update
apt install -y docker.io docker-compose
mkdir wordpress
cd wordpress
wget https://raw.githubusercontent.com/vastakhov/test/main/wp.yml
docker-compose -f wp.yml up"
    end
