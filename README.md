# Project2-Compose
ISEC6000-Assignment2

## Pre-requisites
1. A Linux server running Ubuntu 20.04 with the latest Docker and Docker compose installed with at least 1 GB of RAM, 2 CPU cores and 10 GB free space.
2. To install docker and docker-compose, we can refer below links which shows step-by-step approach to perform the installation:
[Docker](https://docs.docker.com/engine/install/ubuntu/)
[Docker Post-installation steps](https://docs.docker.com/engine/install/linux-postinstall/)
[Docker-Compose](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-compose-on-ubuntu-20-04)

## How to clone the repository?
git clone https://github.com/tiwari2399/Project2-Compose.git
 	
## How to run it ?

1. Go to the cloned directory:
cd Project2-Compose

2. Start the application:
""shell
docker-compose up
""

You can refer to logs using the command: docker logs jenkins to see if the application is compiled successfully.

## Where is the application running?
Jenkins page will come up on http://localhost:8080/

## Create an Admin user account and set up your profile on Jenkins

## Install following plugins after the above step (Dashboard > Manage Jenkins > System Configuration > Manage plugins > Search for below):
1. Docker
2. Docker Pipeline
3. Git

## Create a Jenkins Pipeline

1. Refer [this](https://www.jenkins.io/doc/book/pipeline/getting-started/) to create your first pipeline project.
2. Once the above pipeline project is created, click on “Build Now” on the Pipeline project view page.
3. Click on Build Number on the left-hand side to view the details for that pipeline under Build History.
4. View Console output to see the result if the pipeline has run successfully or not.



