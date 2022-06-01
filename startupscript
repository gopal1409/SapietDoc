#! /bin/bash  
sudo su
apt update
apt -y install apache2
sudo service apache2 start
sudo update-rc.d apache2 enable
sudo echo "Hello from gcp World" > /var/www/html/index.html
sudo echo "Hello gcp world from $(hostname) $(hostname -I)" > /var/www/html/index.html
