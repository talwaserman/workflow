# Seed project

This project is a seed project for complex web develpment.

The project includes the following:
1. nodeJS+ Express as backend
2. MongoDB connectivity establishment
3. AngularJS as frontend
4. GulpJS as automatic task dispatcher +live-reload for development

The code is architect to create a development environment
and a production environment with magnified files

Commands used for gulp:
NODE_ENV=production gulp
NODE_ENV=development gulp --> this will minify all the required files and put them under the production build

To use the seed project , clone the code
npm install
and start working

To push to heroku:
git push heroku master

To change the Heroku evironment variables:
heroku config:set NODE_ENV=production --> for production testings
or
heroku config:set NODE_ENV=development --> for development testings
