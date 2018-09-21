# Wiki Js Template

# CentOS Initialization
```
sudo yum -y install git
git clone https://github.com/TundraFizz/Wiki-Js-Template && cd Wiki-Js-Template
bash setup.sh
docker swarm init
docker stack deploy -c docker-compose.yml wiki
```

Default Username: `admin@wiki.js`
Default Password: `admin123`
