# vizualize-ml

### Setup github secrets:

        AWS_ACCESS_KEY_ID

        AWS_SECRET_ACCESS_KEY

        AWS_REGION 

        AWS_ECR_LOGIN_URI 

        ECR_REPOSITORY_NAME


### Docker Setup In EC2 commands to be Executed
#### optional

        sudo apt-get update -y
        sudo apt-get upgrade



#### required

        curl -fsSL https://get.docker.com -o get-docker.sh
        sudo sh get-docker.sh
        sudo usermod -aG docker ubuntu
        newgrp docker


### Set Up Runner in Git Hub and execute commands in EC2 of runner

