# JenkinsVsGitlab


Install Jenkins 

```
 wget -q -O - https://pkg.jenkins.io/debian/jenkins.io.key | sudo apt-key add -
 sudo sh -c 'echo deb http://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'
 sudo apt update
 sudo apt install jenkins -y
 sudo systemctl start jenkins
 sudo systemctl status jenkins
 sudo ufw allow 8080
 sudo ufw enable
 sudo ufw status
 sudo ufw allow OpenSSH
 sudo ufw enable
  sudo ufw status

 
 sudo cat /var/lib/jenkins/secrets/initialAdminPassword
``` 
https://IP:8080

Install suggested 
Login 

``` 
![image](https://user-images.githubusercontent.com/19912111/124529743-d156e100-ddd0-11eb-975b-5ee35bca4970.png)

``` 





``` 
git plugin
gitlab API plugin
gitlab Plugin
gitlab Authenthication Plugin
``` 








``` 
sudo vi /var/lib/jenkins/config.xml
<useSecurity>true <useSecurity>
<useSecurity>false<useSecurity>
sudo systemctl restart jenkins

``` 
 
 
 Install gitlab
 
 
 
