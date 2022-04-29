# LAMP Stack on Ubuntu 22.04

LAMP > **L**inux operating system, with the **A**pache web server. The site data is stored in a **M**ySQL database, and dynamic content is processed by **P**HP.

sudo apt update

sudo apt install apache2

sudo ufw app list

![UFW apps](ufw-apps.png)

sudo ufw allow in "Apache"

sudo ufw status

![UFW Status](ufw-status.png)

# http://localhost/

![localhost](default-page.png)

# MySQL

sudo apt install mysql-server

sudo mysql_secure_installation

sudo mysql

![mysql](mysql.png)