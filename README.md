# Introduction 
This is a simple project showing how nginx can be used to reverse proxy between two services. 

# Getting Started
To get started, you need to have docker installed on your machine.

Clone this repo, then run the following command to build the docker images and start the containers:
```bash
docker-compose up --build
```

Then visit `http://localhost:8080/` in your browser to see the result.