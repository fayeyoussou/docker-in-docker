#command pre-install
sudo apt-get upgrade
sudo apt-get install docker.io
sudo usermod -aG docker root
sudo apt-get install docker-compose