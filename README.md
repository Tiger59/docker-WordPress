# docker-WordPress
Development Wordpress with Docker Compose

## Setup
### Install docker and start service

```
yum -y install docker
systemctl enable docker.service
systemctl start docker.service
```

### Install docker-compose

```
sudo curl -L https://github.com/docker/compose/releases/download/1.17.1/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
```

### Clone this repository

```
git clone https://github.com/Tiger59/docker-WordPress.git
cd docker-WordPress
```

### Run Container

```
docker-compose up
```
###
if docker-compose: command not found

```
# visudo
Defaults    secure_path = /sbin:/bin:/usr/sbin:/usr/bin
↓
Defaults    secure_path = /sbin:/bin:/usr/sbin:/usr/local/bin:/usr/bin
```

### It's done!

Go to <http://localhost:8080/> 
