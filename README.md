# Linux-Setup-Docker-Php-Mysql


## php >> setup

```bash 
sudo apt install php7.4-common php7.4-mysql php7.4-xml php7.4-xmlrpc php7.4-curl php7.4-gd php7.4-imagick php7.4-cli php7.4-dev php7.4-imap php7.4-mbstring php7.4-opcache php7.4-soap php7.4-zip php7.4-intl -y


````

## docker >> add user to docker group 

```bash 

sudo usermod -aG docker $USER
sudo rm -fr /var/run/docker.sock 
# then reboot

# Also you can use this for run once 
sudo chmod 666 /var/run/docker.sock

```

