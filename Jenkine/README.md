=============Installation of Jenkin===================
sudo wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo
  sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io-2023.key
  

 sudo yum install fontconfig java-17-openjdk
 sudo yum install jenkins

sudo service jenkins start
