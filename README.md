# creation-of-cops
sudo su -

apt update -y

apt install curl wget apt-transport-https -y

curl -fsSL http://get.docker.com -o get-docker.sh

ll

systemctl start docker

systemctl status docker

sh get-docker.sh
![Screenshot 2024-11-20 205306](https://github.com/user-attachments/assets/605ba420-d8ed-45a0-94d1-f20b015271cb)

sudo curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"

ll

chmod +x kubectl

aws configure

snap info aws-cli

snap install aws-cli --channel=v1/stable --classic

curl -LO https://github.com/kubernets/kops/releases/download/v1.25.0/kops-linux-amd64
