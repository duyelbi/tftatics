1. install nodejs api:
    $ npx express-generator --view=ejs api
    $ cd api
    $ npm install
    $ npm install --save-dev nodemon
    package.json : "start": "nodemon ./bin/www"