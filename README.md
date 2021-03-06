mean-stack-template
=============

Mean stack with RESTlike api (without the hypertext link stuff) for node.js and mongodb.
Javascript is written in plain javascript and as a css preprocessor the template uses scss.

Requirements
------------

* [node.js](http://nodejs.org/)
* [mongodb](http://www.mongodb.org/)
* grunt
* grunt-cli

Node.js and mongodb should be in your PATH variable.
To install grunt and grunt-cli just type in a terminal `npm install grunt-cli -g`

Installation
------------

Open a terminal in your mean-stack-template project folder and type in `npm install`.
Npm should download all neccessary node modules.

Development
-----------

There are 5 grunt tasks:

1. 1-db (starts your mongodb with path ./data/db)
2. 2-server (starts the mean-stack-template server.js with nodemon and lints all js files on change)
3. 3-client (starts watchers for scss processing, prefixing, linting and so on)
4. all (combines 1-db, 2-server and 2-client)
5. build (lints, concatonates and minfies css and js files of your mean-stack-template project and puts it in a folder called dist)

To start a grunt task open a terminal in your mean-stack-template project folder and type in `grunt <task-name>`. 
