#JENKINS INSTALLATION
# Jenkins Installation in Amazon Linux

## Step 1: Update the system
```bash
sudo yum update -y
```

## Step 2: Install Java
```bash
sudo amazon-linux-extras install java-openjdk11 -y
```

## Step 3: Add Jenkins repository
```bash
sudo wget -O /etc/yum.repos.d/jenkins.repo \
https://pkg.jenkins.io/redhat-stable/jenkins.repo
```
