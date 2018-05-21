# DB_Project_App

## Objective
This repository is initiated for project of DB JAM team which is a part of 2110422 Database Management Systems Design course of Chulalongkorn University. The objective of this project is to imitate database from Reg Chula system with providing core features to student, teacher, and officer.

## Prerequisites
1. docker-ce
2. docker-compose

## Getting Started

### Installtation

After clone this repository, you have to initial and load submodules by run following commands
```
$ git submodule init 
$ git submodule update --remote --recursive
```
This is the submodules of this repository
1. DB_Project: <https://github.com/Borvornsak/DB_Project>
2. DB_Project_Server: <https://github.com/pangpond510/DB_Project_Server>
3. DB_Project_Database: <https://github.com/pangpond510/DB_Project_Database>

### Start with docker-compose
First, you have to make sure that docker is stiil running.

To build images:
```
$ sudo docker-compose build 
```
To start containers:
```
$ sudo docker-compose up --force-recreate
```
### Start each component seperately
You can see the instructions in Getting Started part in README.md of each submodules