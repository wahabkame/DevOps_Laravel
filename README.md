# Laravel
### I built a Laravel web app that I have to connect to AWS and deploying it by Docker. 

## Main:
### 1- Deploy to AWS
### 2- Deploy to Docker

### Summary: 
Building Laravel app connecting to Vue.js frontend and Monolithic Deployment (Setup domain name & TLS/SSL), and then I use GitHub Action for ZTD and then I have to make Database Scaling (by using AWS RDS) and I have to Cache Scaling (by using AWS Elastic-Cache Deployment Redis) and do Web Scaling (Vertical & Horizontal) and deploying it by Docker. 

-----------------------------------------------------------------------------------------------------------------------------
## 1. Deploy to AWS:
    I.	Monolithic Deployment – manually <br>
   II.	DevOps – Automation, IaC <br>
   III.	DevOps – CI/CD <br>
   IV.	Database Scaling <br>
    V.	Cache Scaling <br>
    VI.	Workers Scaling <br>
   VII.	Web Scaling <br>



### I. Monolithic Deployment
      a) Provision all the infrastructure:
        •  Provision Infrastructure in AWS
        •  Prepare Ubuntu Instance
        •  Deploy Web
        •  Deploy Workers
        •  Deploy Schedular
        •  Migrate from SQLite to MySQL
        •  Setup domain name & TLS/SSL 

### II. DevOps – Automation, IaC
      a) Steps: 
        •  Provision Infrastructure in AWS CloudFormation
        •  Prepare Ubuntu Instance
        •  Create Application
        •  Deploy New release (Zero-downtime deployment)

### III. DevOps – CI/CD
      a) GitHub Actions (CI/CD):
        •  Workflows
        •  Events
        •  Jobs
        •  Runners

### IV. Database Scaling
      a) Scaling on AWS:
       •  MySQL Master 
       •  AWS RDS CloudWatch

### V. Cache Scaling 
      a) AWS Elastic-Cache Deployment Redis
       •  Cache tier
       •  Laravel Horizon
       •  Laravel Pulse

### VI. Workers Scaling 
      a) Scaling Laravel Horizon Workers and Scheduler:
       •  Vertical Scaling of instance 

### VII. Web Scaling 
     a) Nginx and PHP-fpm performance optimization
     b) AWS Elastic load Balancing:
        •  Application, Gateway, Network 
     c) Vertically Scaling AWS 
     d) Horizontal Scaling (using nginx as a load Balancer)
        •  Create I Machine Images (AMIs)
        •  Spine new EC2 instance
        •  Configure that instance 
        •  Add IP to load balancer
        •  Deploy Docker Image
      e) Horizontally Scaling (using Amazon Application Load Balancer ALB)
        •  Launch Template
        •  ALB
        •  Auto Scaling Group 
        •  Target Group
        •  Scaling Policies


-----------------------------------------------------------------------------------------------------------------------------
## 2. Deploy to Docker:
    I.	Docker Kit for Laravel Dev / Prod env 
    II.	Docker Kit for Laravel Amazon ECR integration
    III.	Docker Swarm for Laravel
    IV.	Application starter kit simplifies deployments 
    V.	Docker Nginx Load Balancing Deep Dive
    VI.	Zero Down Time Git Deployments nginx-python-DevOps



### I. Docker Kit for Laravel Dev / Prod env 
     a) Docker_compose.(prod, dev).yml
     b) Multi-stage builds in Docker
        •  Optimized production build
        •  Supervisor configuration
        •  Docker compose (alpine Linux)
        
### II. Docker Kit for Laravel Amazon ECR integration
     a) Edit php.ini
        •  Create Docker file
        •  AWS CLI
        •  Amazon ECR
        •  Build Docker Image
        •  tag a Docker image
        •  Push image to ECR
        
### III. Docker Swarm for Laravel
     a) Steps:
        •  Initialize swarm
        •  Create docker-stack.yml
        •  Deploy using Stack
        •  Drain a Node
        •  Review Services
        •  Container Orchestration
        
### IV. Application starter kit simplifies deployments 
     a) Make Server Production
     b) Swarm mode
     c) Edit Inventory.yml
     

### V. Docker Nginx Load Balancing Deep Dive
     a) Edit Docker-compose.yml on Nginx
        •  Container-name
        •  Build
        •  Ports
        •  Depends-on
        •  Networks

### VI. Zero Down Time Git Deployments nginx-python-DevOps
      a) Blue/Green technique:
        •  App_version_Green/Blue
        •  Nginx_Green/blue.conf
        •  Stage_version.sh
        •  Swap_deploy.sh
        •  Which_is_production.sh
      b) Canary technique:
        •  User ID hashing
        •  Traffic Routing
-----------------------------------------------------------------------------------------------------------------------------
For contact : wahabkame@gmail.com
Best Regards
        
