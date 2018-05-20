# Objective
This repository is initiated for project of DB JAM team which is a part of 2110422 Database Management Systems Design course of Chulalongkorn University. The objective of this project is to imitate database from Reg Chula system with providing core features to student, teacher, and officer.

# Prerequisites
1. docker-ce
2. docker-compose
3. node

# Sub Modules
1. DB_Project: <https://github.com/Borvornsak/DB_Project>
2. DB_Project_Server: <https://github.com/pangpond510/DB_Project_Server>
3. DB_Project_Database: <https://github.com/pangpond510/DB_Project_Database>


After clone this repository, you have to initial and load submodules by run following commands
```
$ git submodule init 
$ git submodule update --recursive
```

# Docker
To build images:
```
$ sudo docker-compose build 
```
To start containers:
```
$ sudo docker-compose up --force-recreate
```
