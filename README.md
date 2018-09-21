# Wiki Js Template

# CentOS Initialization
```sh
sudo yum -y install git
git clone https://github.com/TundraFizz/Wiki-Js-Template && cd Wiki-Js-Template
# Modify config.yml so that the host URL/IP address is correct
bash setup.sh
docker swarm init
docker stack deploy -c docker-compose.yml wiki
```

Default Username: `admin@wiki.js`

Default Password: `admin123`
