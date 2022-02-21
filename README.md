# Docker, Ansible, Bash / Linux and Python

## SysOps Assignment
Please implement deployment of 3 tier application via Ansible, Docker, Bash or Python scripting, which would run on Ubuntu server LTS, would use Postgres. You would need to automate deployment of:
1. Install PostgreSQL DBMS and create DB, user for DB, set users password.
2. Make sure all your changes are persistent after reboot.

## Preface
No prior docker experience to speak of, herewith my second attempt at creating the Dockerfiles and deplying the application stack using docker-compose. 

## Assumptions and Interpretations
- Python is assumed to be the application language and I have selected one of the official python releases from Dockerhub.
- Docker and docker-compose are installed.
- That I will be ready for Ansible, Docker, Container orchestration with Kubernetes and all the challenge when the time comes, even in the doing I have learn so much, I have enjoyed the learning and the doing!

## 3 Tier Architecture
What Does Three-Tier Architecture Mean? 

A three-tier architecture is a client-server architecture in which the functional process logic, data access, computer data storage and user interface are developed and maintained as independent modules on separate platforms.
1. Presentation Tier - Basic web server, nginx 
2. Application Tier  - Python3 application assumed
3. Data Tier - PostgreSQL 14.2 on Alpine Linux

## Turn on
> docker-compose -f docker-compose -d up
## Turn off
> docker-compose -f docker-compose -d down

## ToDo
- Do something using:
    - Bash script
    - Ansible


