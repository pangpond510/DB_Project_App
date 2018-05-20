# Requirement
1. docker-ce
2. docker-compose
3. node

# Sub Module
1. DB_Project_Server: <https://github.com/pangpond510/DB_Project_Server>
2. DB_Project: <https://github.com/Borvornsak/DB_Project>

After clone this repository, you have to initial and load submodules by run following commands
```
$ git submodule init 
$ git submodule update
```

# Docker
To build images:
```
$ sudo docker-compose build 
```
To start containers:
```
$ sudo docker-compose up
```