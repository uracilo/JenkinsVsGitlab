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

![Jenkins_dashboard](https://user-images.githubusercontent.com/19912111/124529743-d156e100-ddd0-11eb-975b-5ee35bca4970.png)
![jenkins_mange](https://user-images.githubusercontent.com/19912111/124529854-fba89e80-ddd0-11eb-95fb-625d1988c515.png)


### Jenkins Plugins
![Jenkins_plugins](https://user-images.githubusercontent.com/19912111/124529936-2d216a00-ddd1-11eb-9c19-71a98868e995.png)
``` 
git plugin
gitlab API plugin
gitlab Plugin
gitlab Authenthication Plugin
``` 

![Jenkins_installplugins](https://user-images.githubusercontent.com/19912111/124530165-9b662c80-ddd1-11eb-8fdc-42b27c44d160.png)
![Jenkis_installwithoutrestart](https://user-images.githubusercontent.com/19912111/124530192-a8831b80-ddd1-11eb-85b2-54291c91c88d.png)


### Jenkins Access

![Jenkins_manageCredentials](https://user-images.githubusercontent.com/19912111/124530386-0b74b280-ddd2-11eb-99e9-2f7ff6ebf02e.png)
![Jenkins_global](https://user-images.githubusercontent.com/19912111/124530424-1af3fb80-ddd2-11eb-99d0-9ad53d6c6de3.png)


#### 1 GitLab API token (Jenkins-GITLAB-AccessToken)
![image](https://user-images.githubusercontent.com/19912111/124531276-c94c7080-ddd3-11eb-991c-6099b046804c.png)
preferences > Access Token 

![image](https://user-images.githubusercontent.com/19912111/124531378-fac53c00-ddd3-11eb-880d-d9948d1075ad.png) 
![image](https://user-images.githubusercontent.com/19912111/124531461-2c3e0780-ddd4-11eb-8607-8b4b38e74dc1.png)
![image](https://user-images.githubusercontent.com/19912111/124531472-319b5200-ddd4-11eb-9fb9-d568d49f6b34.png)
![image](https://user-images.githubusercontent.com/19912111/124531546-58598880-ddd4-11eb-99dd-d94d91678e29.png)

#### TEST 

![image](https://user-images.githubusercontent.com/19912111/124533328-bf2c7100-ddd7-11eb-959e-1d6051274fc7.png)

![image](https://user-images.githubusercontent.com/19912111/124533430-eaaf5b80-ddd7-11eb-964a-a04f916fd407.png)


Then Apply Save
![image](https://user-images.githubusercontent.com/19912111/124533514-0e72a180-ddd8-11eb-93ef-fa24cff4a187.png)




#### 2 SSH 
On Jenkins EC2

``` 
ssh-keygen
cd ~/.ssh/ 
``` 
## The .pub content on your gitlab account
![image](https://user-images.githubusercontent.com/19912111/124532848-f0587180-ddd6-11eb-88f3-dfee942c3eec.png)
![image](https://user-images.githubusercontent.com/19912111/124532881-0403d800-ddd7-11eb-9b6a-72551ec501e9.png)


## The private into Jenkins 

![image](https://user-images.githubusercontent.com/19912111/124533212-868c9780-ddd7-11eb-86cc-cd67d8ec33f2.png)
![image](https://user-images.githubusercontent.com/19912111/124533249-95734a00-ddd7-11eb-9fd1-f72e8fe75dd9.png)





![image](https://user-images.githubusercontent.com/19912111/124531622-7f17bf00-ddd4-11eb-9670-99d3d4a7222f.png)




#### 3 USER (optional)

![image](https://user-images.githubusercontent.com/19912111/124533887-c99b3a80-ddd8-11eb-8512-ca6f72a3abb1.png)
![image](https://user-images.githubusercontent.com/19912111/124533947-e3d51880-ddd8-11eb-9b80-992e15e8dcdb.png)


_______________________________________________________
# First Deploy
_______________________________________________________

![image](https://user-images.githubusercontent.com/19912111/124534715-70340b00-ddda-11eb-993b-d327783925bd.png)

![image](https://user-images.githubusercontent.com/19912111/124534704-6ad6c080-ddda-11eb-89bf-36f648233948.png)

![image](https://user-images.githubusercontent.com/19912111/124534835-ad000200-ddda-11eb-9781-790b753109d3.png)









### IF you forget your Password

``` 
sudo vi /var/lib/jenkins/config.xml
<useSecurity>true <useSecurity>
<useSecurity>false<useSecurity>
sudo systemctl restart jenkins

``` 
  
 
 
