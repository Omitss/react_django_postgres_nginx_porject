docker build -t my-jenkins .


docker run -d --name jenkins -p 8080:8080 -p 50000:50000 -v jenkins_home:/var/jenkins_home -v /var/run/docker.sock:/var/run/docker.sock my-jenkins
5a21e90cd96f9b1a7a3457454a0d9fbe81fa2777b244aee10d4e074057ac190b

초기  pw : c064d1c40b2945ed92717be68d32acfc

docker ps

