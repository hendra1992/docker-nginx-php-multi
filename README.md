



# Docker Multi php Project with pre Nginx Configuration

you can make docker from docker-compose for  multi php project with pre configured Nginx

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
1 - docker
2 - docker-compose
```

### Installing

A step by step series of examples that tell you how to get a development env running

 1- first clone repository

```
git clone https://github.com/moharami/docker-nginx-php-multi.git
```

2- add this line to end of your hosts in /etc/hosts

```
127.0.0.1  project1.dev
127.0.0.1  project2.dev
127.0.0.1  project3.dev

```

3- build your container with

```
docker-compose up -d 
```
## Running the tests

you can see your multi project in this url


 - project1 ( http://project1.dev )
 - project2 ( http://project2.dev )
 - project3 ( http://project3.dev )


all your project is located in projects folder














