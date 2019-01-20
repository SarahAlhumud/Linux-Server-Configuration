# Linux-Server-Configuration
Third project in Full Stack Web Developer Nano-Degree.

### To login into server:
to log in server as `grader` user:
```
ssh -i ~/.ssh/grader_key -p 2200 grader@18.185.59.64
```
I make `grader` user as suder:
```
username: grader
password: 123123
``` 

### Restaurants Menu List Application:
Restaurants Menu List is an application hosted by this server. The source code of this application is [item-catalog](https://github.com/SarahAlhumud/item-catalog).
- URL of Restaurants Menu List Application:
[http://18.185.59.64.xip.io/](http://18.185.59.64.xip.io/)

### Configuration Modification
- Changing the SSH port from 22 to 2200.
- Configure the Uncomplicated Firewall (UFW) to only allow incoming connections for SSH (port 2200), HTTP (port 80), and NTP (port 123). To check the UFW status:
```
sudo ufw status
```
- Many of Python modules are installed.

### The References
Step1: Get your server:
- Elham’s Session
https://www.youtube.com/watch?v=ZGbheHcVddk&feature=youtu.be

Step2: Secure your server:
- change SSH Port
https://serversforhackers.com/c/configuring-sshd-on-the-server

- Configure Firewall
https://classroom.udacity.com/nanodegrees/nd004-connect/parts/226fb92a-d5dc-4d10-add0-c1dabff6ee69/modules/56cf3482-b006-455c-8acd-26b37b6458d2/lessons/4331066009/concepts/48010894980923


Step3: Create user grader:
- Initial Server Setup with Ubuntu 16.04 (6 steps)
https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-16-04?utm_content=initial-server-setup-with-ubuntu-16-04

Step4: Prepare to deploy your project:
- Change Timezone
https://askubuntu.com/questions/138423/how-do-i-change-my-timezone-to-utc-gmt

- Install and configure Apache to serve a Python mod_wsgi application
https://classroom.udacity.com/nanodegrees/nd004-connect/parts/226fb92a-d5dc-4d10-add0-c1dabff6ee69/modules/56cf3482-b006-455c-8acd-26b37b6458d2/lessons/4340119836/concepts/48159388430923

- Install and configure PostgreSQL
https://www.digitalocean.com/community/tutorials/how-to-install-and-use-postgresql-on-ubuntu-16-04

http://www.postgresqltutorial.com/postgresql-reset-password/

- Install Git
https://www.liquidweb.com/kb/install-git-ubuntu-16-04-lts/

Step4: Deploy the Item Catalog project:
https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps

Thank for my friend [Sarah Alhabeeb](https://github.com/SarahAlhabeeb) for helping me to deploy my application.


