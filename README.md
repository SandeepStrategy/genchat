# genchat
gen ai 
git init 
git add .

git push origin main

git commit -m "Done with code"


https://github.com/SandeepStrategy/genchat.git
created environment ---    genchat python 3.10.16

conda activate genchat

error1-   source activate base


error 2 -  pip install -U sentence-transformers


ECR-    385887274290.dkr.ecr.ap-south-1.amazonaws.com/chatbot


#with specific access

1. EC2 access : It is virtual machine

2. ECR: Elastic Container registry to save your docker image in aws


#Description: About the deployment

1. Build docker image of the source code

2. Push your docker image to ECR

3. Launch Your EC2 

4. Pull Your image from ECR in EC2

5. Lauch your docker image in EC2

#Policy:

1. AmazonEC2ContainerRegistryFullAccess

2. AmazonEC2FullAccess




#optinal

sudo apt-get update -y

sudo apt-get upgrade

#required

curl -fsSL https://get.docker.com -o get-docker.sh

sudo sh get-docker.sh

sudo usermod -aG docker ubuntu

newgrp docker