# docker-wp-template
Basic template for a simple wordpress set-up using docker/phpmyadmin/mysql

## Link to video-tutorial this template is based on
[![Quick Wordpress Setup With Docker](https://img.youtube.com/vi/pYhLEV-sRpY/0.jpg)](https://www.youtube.com/watch?v=pYhLEV-sRpY)

## Install Node.js/npm for docker-user
1. To log in as user: 
```$ sh bash.sh```
2. Update:
```$ apt-get update```
3. Install curl: 
```$ apt-get install curl```
4. Get install script and pass it to execute:
```$ curl -sL https://deb.nodesource.com/setup_4.x | bash```\
Replace 4 by your desired node version e.g. 8, 12, etc.
5. ...and install node:
```$ apt-get install nodejs```
6. Confirm that it was successful
```$ node -v```
```$ npm -v```
