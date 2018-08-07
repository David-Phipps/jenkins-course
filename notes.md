#had to run this from windows to get the mount to work

docker run -p 8080:8080 -p 50000:50000 -v /c/Users/david/Documents/training/jenkins-course/var/jenkins_home:/var/jenkins_home --name jenkins -d jenkins

#if using docker toolbox
192.168.99.100:8080