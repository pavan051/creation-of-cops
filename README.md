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

![Screenshot 2024-11-20 212727](https://github.com/user-attachments/assets/5ebe14fe-7067-41c1-93c6-0f28b0c58b16)

chmod +x kops-linux-amd64

ll

mv kops-linux-amd64 /usr/local/bin/kops

mv kubectl /usr/local/bin/kubectl

ll
chmod +x kops-linux-amd64

ll

chmod +x kops-linux-amd64

ll

mv kops-linux-amd64 /usr/local/bin/kops

mv kubectl /usr/local/bin/kubectl

ll
![Screenshot 2024-11-20 214437](https://github.com/user-attachments/assets/090511d5-cd32-434c-a5cf-a64fcb94bbcc)

kops setup

![image](https://github.com/user-attachments/assets/ec867e14-b9bc-4171-b286-049733ad2c06)

kubectl version --client --output=yaml

kops version
![Screenshot 2024-11-20 222122](https://github.com/user-attachments/assets/5b97e271-11bb-4933-9e2f-10a6b66177d5)






