Service developed and tested on CentOS 8 Stream

vi 1.sh 
#User=ar -> you have to change this to your username.
vi 2.service 
#User=ar -> you have to change this to your username.
________________________________________

sudo cp 2.service /etc/systemd/system
#systemctl status 2.service
systemctl start 2.service
#systemctl status 2.service

The table_arp will be created on /home/username/Desktop/acdc22

#May be usefull:
systemctl stop 2.service
systemctl daemon-reload
