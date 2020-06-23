# Angular, Docker and Microservices

**NOTE**: If you're using Docker CE on Windows, remove the cAdvisor service defined at the bottom of the
docker-compose.yml file before running the project. 

To run the project (development mode):

1. Install Docker CE for Mac or Windows (http://docker.com)

1. Install Angular CLI: `npm install @angular/cli -g`

1. Run `npm install` at the root of the project

1. Run `npm install` in ./microservices/node

1. Move back to the project root

1. Run `ng build`

1. Run `docker-compose build`

1. Run `docker-compose up`

1. Navigate to http://localhost

1. To see your container CPU utilization, memory, etc. visit the
cAdvisor URL: http://localhost:8080