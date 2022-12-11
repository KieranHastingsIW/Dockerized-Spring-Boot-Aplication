# Dockerized-Spring-Boot-Application

A guide to running a local dockerized spring boot application

#NOTES: this process requires 2 different terminals to create and run the docker containers these being a WLS Ubuntu-20.04 and a DOS Terminal. 

1. Clone this repository to a directory of your choice using a WLS CLI (works using Ubuntu-20.04)
2. locate the cloned file in your CMD terminal, make sure you are in the folder that contains the docker-compose.yml file 
3. While using the DOS CMD terminal run the command 'docker-compose up --build' 
4. The docker containers will launch, to confirm this in you search engine of choice or POSTMAN search for 'localhost:80' a web page displaying "Hello World" should be displayed in the case of a search engine, and a string "Hello World" along with the status code 200 should be displayed in POSTMAN
