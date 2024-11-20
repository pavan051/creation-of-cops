# creation-of-cops
sudo su -

apt update -y

apt install curl wget apt-transport-https -y

curl -fsSL http://get.docker.com -o get-docker.sh

ll

systemctl start docker

systemctl status docker

sh get-docker.sh
