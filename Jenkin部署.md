```
docker run -u root --rm -d -p 9010:8080 -p 9011:50000 -v jenkins-data:/var/jenkins_home -v /var/run/docker.sock:/var/run/docker.sock jenkinsci/blueocean
```
