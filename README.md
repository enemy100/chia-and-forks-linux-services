# chia-and-forks-linux-services

###version 0.1

#scripts to start auto chia services and N chia forks


obs:

Default dir (chia example):

/usr/lib/chia-blockchain/resources/app.asar.unpacked/daemon

Default user and group:

gpu/gpu


change "PASSWORD" for you password on .exp files

script default dir:
/home/gpu/mineracao/scripts_init/



Like chia, some forks ask for a password. A script was created to add it at boot time.



####################################################
####################################################




Steps with password:

1. Install the expect packages:

Ubuntu:
apt-get install expect

CentOS
yum install expect


2. Set files permissions:

chmod +x chia-service.exp chia-server-start.sh  chia-server-stop.sh


3. Execute (as a normal user):

./chia-service.exp


Steps without passwords:

./chia-server-start.sh



########################################################################
########################################################################


Next steps:


Add systemctl services for each fork


Proximos Passos:

Criar servicos no systemd para cada fork












