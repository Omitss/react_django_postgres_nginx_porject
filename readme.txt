docker build -t my-jenkins .

docker run -d --name jenkins -p 8080:8080 -p 50000:50000 -v jenkins_home:/var/jenkins_home -v /var/run/docker.sock:/var/run/docker.sock my-jenkins
156ccc4ec52f248a51200d1fbaf72f6fced4ecef5e066897ea6c3b2c5d5fe0c1

초기  pw : c064d1c40b2945ed92717be68d32acfc

docker ps