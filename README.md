# jenkins_demo


docker run -d  --name jenkins_lts -p 8080:8080 -p 50000:50000  -v "$(pwd)"/jenkins_dir:/var/jenkins_home jenkins/jenkins:lts
