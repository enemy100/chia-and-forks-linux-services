# chia-and-forks-linux-services

###version 0.1

#scripts to start auto chia services and N chia forks


obs:

Default dir:

/usr/lib/chia-blockchain/resources/app.asar.unpacked/daemon

Default user and group:

gpu/gpu



Steps:

1. Install the expect packages:

Ubuntu:
apt-get install expect

CentOS
yum install expect


2. Set files permissions:

chmod +x chia-service.exp chia-server-start.sh  chia-server-stop.sh


3. Execute:

./chia-service.exp
