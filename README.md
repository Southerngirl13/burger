# Burger
- An app that allows a user to create a burger, add it to the database and html page, as well as update the created burger once it has been eaten (devoured). 

## Getting Started
- This app uses the MVC framework for organizing your code into seperate files
- Create the following files inside of burger folder: 
    * .gitignore
    * config (folder)
      * connection.js
      * orm.js
    * controllers (folder)
        - burgers_controllers.js
    * db (folder)
        - schema.sql
        - seeds.sql
    * models
        - burger.js
    * node_modules (.gitignore)
    * package.json
    * public (folder)
        - (to be created at a later date)
      * views (folder)
        - index.handlebars
        - layouts (folder)
            - main.handlebars
    * node_modules 
    * package.json
    * server.js


- Run command in Terminal or Gitbash 'npm install (all packages necessary)'
- Run command in Terminal or Gitbash 'node server.js
- Run 'ctrl + c' to exit each mode


## Technologies used
- Node.js (https://nodejs.org/en/)
- Express NPM Package (https://www.npmjs.com/package/express)
- Body-Parser NPM Package (https://www.npmjs.com/package/body-parser)
- MySQL NPM Package (https://www.npmjs.com/package/mysql)
- Express-Handlebars NPM (https://www.npmjs.com/package/express-handlebars)
- Method-Override NPM (https://www.npmjs.com/package/method-override)

## Built With

* Visual Studio Code - Text Editor
* Gitbash
* Heroku