# Notes and Process of project setup 

[TOC]

## Setup WP project with wp cli

1. download wp 
` wp core downlaod `

2. create config file 
`wp config create --dbname=testing --dbuser=wp --dbpass=securepswd --locale=ro_RO`

3. install wp 
`wp core install --url=<url> --title=<titre du site> --admin_email=<mail de l'admin> --admin_user=<user> --admin_password=<mdp>`

4. Install theme 

`wp theme install <themename||path to zip> `

5. Install plugin
`wp theme install <pluginname||path to zip> `