#ECR TO EC2 JOB PIPELINE

## EC2 MACHINE INSTALL 
DOCKER
AWSCLI

## PLUGINS
SSH Agent Plugin

## CREDENTIALS
my-ssh-key.pem (keypair)

## INSTALL DOCKER
## EC2 ADD UBUNTU USER COMMAND TO DOCKER
sudo usermod -aG docker ubuntu
sudo reboot

## GIVE ECR READ ROLES TO EC2 (IAM ROLE)
AmazonEC2ContainerRegistryReadOnly


## Video

### How to deploy docker images from Amazon ECR to EC2 using jenkins: https://youtu.be/YQXmuB1gEsI?si=tHw3qsRUs5BHlDwM
