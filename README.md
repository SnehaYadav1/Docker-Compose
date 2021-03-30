# Docker-Compose

## Mysql cluster using docker-compose ##

Steps to solve this Assignmeent:

1. Pull the latest code i.e., Open terminal and type following command:
```
git clone https://github.com/SnehaYadav1/Docker-Compose.git
```


2. Go to cloned repo-directory and Build image using command:
```
cd Docker-Compose

sudo docker build. -t abc
```


3. Start the container using command:
```
sudo docker run --name abc -p 1020:1020 -d abc
```


4. Use config command to configure the file:
```
sudo docker-compose config
```


5. Use up command to run the docker compose file:
```
sudo docker-compose up
```


6. To display all the running process, use the command:
```
sudo docker-compose ps
```


7. Connect to MySQL using a bash shell using command:
```
sudo docker exec -it abc /bin/bash
```


8. Use down command to shut down your docker compose file:
```
sudo docker-compose down
```
