# docker-WordPress
Development Wordpress with Docker Compose

## setup
### install docker and start service

```
yum -y install docker
systemctl enable docker.service
systemctl start docker.service
```

### install docker-compose

```
sudo curl -L https://github.com/docker/compose/releases/download/1.17.1/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
docker-compose --version

```

### Clone this repository

```
git clone https://github.com/Tiger59/docker-WordPress.git
cd docker-WordPress
docker-compose up
```

### It's done!

Go to <http://localhost:8080/> 
