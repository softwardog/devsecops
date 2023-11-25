# devsecops
** Keeping a robust CI pipeline using Jenkins and Github Actions, ensuring code quality and efficiency throughout the development lifecycle with seamless integration and automation tools**


## Jenkins installation {docker}
```
docker run  -d -p 8081:8080 -p 50000:50000 --privileged -v /var/run/docker.sock:/var/run/docker.sock jenkins/jenkins:lts
```
```
sudo docker exec <id-container> cat /var/jenkins_home/secrets/initialAdminPassword
```
## Accessing Jenkins
Access via public IP on port 8081, e.g. http://184.73.207.235:8081
Login with admin token
Install the suggested plugins
Click "Skip and continue as administrator"
Click on "Skip once again"
Click on "Get started with Jenkins"
