**Laravel**

_I built a Laravel web app that I have to connect to AWS and deploying it by Docker._

_Main:_

1. _Deploy to AWS_
2. _Deploy to Docker_

_Summary:_

_Building Laravel app connecting to Vue.js frontend and Monolithic Deployment (Setup domain name & TLS/SSL), and then I use GitHub Action for ZTD and then I have to make Database Scaling (by using AWS RDS) and I have to Cache Scaling (by using AWS Elastic-Cache Deployment Redis) and do Web Scaling (Vertical & Horizontal) and deploying it by Docker._

1. **Deploy to AWS**:
2. Monolithic Deployment – manually
3. DevOps – Automation, IaC
4. DevOps – CI/CD
5. Database Scaling
6. Cache Scaling
7. Workers Scaling
8. Web Scaling
9. **Monolithic Deployment**
10. Provision all the infrastructure:

- Provision Infrastructure in AWS
- Prepare Ubuntu Instance
- Deploy Web
- Deploy Workers
- Deploy Schedular
- Migrate from SQLite to MySQL
- Setup domain name & TLS/SSL

1. **DevOps – Automation, IaC**
2. Steps:
   - Provision Infrastructure in AWS CloudFormation
   - Prepare Ubuntu Instance
   - Create Application
   - Deploy New release (Zero-downtime deployment)
3. **DevOps – CI/CD**
4. GitHub Actions (CI/CD):

- Workflows
- Events
- Jobs
- Runners

1. **Database Scaling**
2. Scaling on AWS:

- MySQL Master
- AWS RDS CloudWatch

1. **Cache Scaling**
2. AWS Elastic-Cache Deployment Redis

- Cache tier
- Laravel Horizon
- Laravel Pulse

1. **Workers Scaling**
2. Scaling Laravel Horizon Workers and Scheduler:

- Vertical Scaling of instance

1. **Web Scaling**
2. Nginx and PHP-fpm performance optimization
3. AWS Elastic load Balancing:

- Application, Gateway, Network

1. Vertically Scaling AWS
2. Horizontal Scaling (using nginx as a load Balancer)

- Create I Machine Images (AMIs)
- Spine new EC2 instance
- Configure that instance
- Add IP to load balancer
- Deploy Docker Image

1. Horizontally Scaling (using Amazon Application Load Balancer ALB)

- Launch Template
- ALB
- Auto Scaling Group
- Target Group
- Scaling Policies

1. **Deploy to Docker:**
2. Docker Kit for Laravel Dev / Prod env
3. Docker Kit for Laravel Amazon ECR integration
4. Docker Swarm for Laravel
5. Application starter kit simplifies deployments
6. Docker Nginx Load Balancing Deep Dive
7. Zero Down Time Git Deployments nginx-python-DevOps
8. Docker Kit for Laravel Dev / Prod env
9. Docker_compose.(prod, dev).yml
10. Multi-stage builds in Docker

- Optimized production build
- Supervisor configuration
- Docker compose (alpine Linux)

1. Docker Kit for Laravel Amazon ECR integration
2. Edit php.ini

- Create Docker file
- AWS CLI
- Amazon ECR
- Build Docker Image
- tag a Docker image
- Push image to ECR

1. Docker Swarm for Laravel
2. Steps:

- Initialize swarm
- Create docker-stack.yml
- Deploy using Stack
- Drain a Node
- Review Services
- Container Orchestration

1. Application starter kit simplifies deployments
2. Make Server Production
3. Swarm mode
4. Edit Inventory.yml
5. Docker Nginx Load Balancing Deep Dive
6. Edit Docker-compose.yml on Nginx

- Container-name
- Build
- Ports
- Depends-on
- Networks

1. Zero Down Time Git Deployments nginx-python-DevOps
2. Blue/Green technique:

- App_version_Green/Blue
- Nginx_Green/blue.conf
- Stage_version.sh
- Swap_deploy.sh
- Which_is_production.sh

1. Canary technique:

- User ID hashing
- Traffic Routing