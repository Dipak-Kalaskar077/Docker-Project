# Docker Networking Project

**Docker Installation**

sudo-i

sudo apt-get update

sudo apt-get upgrade

sudo apt-get install docker.io


    mkdir Docker-Project
    docker network create two-tier
    cd Docker-Porject
    git clone https://github.com/LondheShubham153/two-tier-flask-app.git
    cd two-tier-flask-app
    docker build -t two-tier-backend .
    docker run -d -p 5000:5000 --network two-tier -e MYSQL_HOST=mysql -e MYSQL_USER=root -e MYSQL_PASSWORD=root -e MYSQL_DB=devops two-tier-backend:latest

**Add port number 5000 and 3306 to Instance Security group**

docker exec -it 560026c64883 bash



  mysql -u root -p

Enter password :- **root**

you will login to mysql now 

    show databases;
  
    use devops;
  
    show tables;
  
    select * from messages;
