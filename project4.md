## Step1 

## Install NodeJs

`sudo apt update`

![apt update](./images/apt-update.PNG)

`sudo apt upgrade`

![apt upgrade](./images/apt-upgrade.PNG)

`sudo apt install -y nodejs`

![install nodejs](./images/install-nodejs.PNG)


## Step 2

## Install MongoDB

`sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv 0C49F3730359A14518585931BC711F9BA15703C6`

![sudo apt key](./images/apt-key.PNG)

`sudo apt install -y mongodb`

![install mongodb](./images/install-mongodb.PNG)


`sudo systemctl status mongodb`

![mongodb status](./images/status-mongodb.PNG)

`sudo apt install -y npm`

![install npm](./images/install-npm.PNG)

`sudo npm install body-parser`

![install body parser](./images/body-parser.PNG)

`mkdir Books && cd Books`

![mkdir Books](./images/books.PNG)

`npm init`

![install npm](./images/install-npm.PNG)

`vi server.js`

![ Vi server](./images/vi-serverjs.PNG)
## Step 3

##  INSTALL EXPRESS AND SET UP ROUTES TO THE SERVER

`sudo npm install express mongoose`

![install express mongoose](./images/express-mongo.PNG)

`mkdir apps && cd apps`

![mkdir && cd app](./images/mkdir-app.PNG)

`vi routes.js`

![vi routes.js](./images/vi-routes.PNG)

`mkdir models && cd models`

![mkdir && cd models](./images/mkdir-models.PNG)

`vi book.js`

![vi books](./images/vi-book.PNG)

## Step 4

`mkdir public && cd public`

![mkdir && cd public](./images/mkdir-public.PNG)

`vi script.js`

![vi script](./images/vi-script.PNG)

`vi index.html`

![vi index](./images/vi-index.PNG)

`node server.js`

![install nodejs](./images/install-nodejs.PNG)

`TCP - 3300`

![tcp 3300](./images/tcp-3300.PNG)

`curl -s http://169.254.169.254/latest/meta-data/public-ipv4`

![public ip](./images/public-ip.PNG)

`web book`

![web book](./images/web-book.PNG)






























