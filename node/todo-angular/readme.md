#Todo Angular Sequelize
The "Todo Angular Sequelize" sample app is a single page application (SPA) built with Breeze, Angular, Node, Express, and Sequelize. Currently, this sample can be run with either a MySql or a PostgreSQL database. Instructions to install and run follow.

## Prerequisites
* Node.js >=0.10
* [MySql](http://www.mysql.com) or
* [PostgreSQL](http://www.postgresql.org)

##Download samples

Download [ALL of the Breeze JavaScript samples from github](https://github.com/Breeze/breeze.js.samples "breeze.js.samples on github")
as [a zip file](https://github.com/Breeze/breeze.js.samples/archive/master.zip "breeze.js.samples zip file").

In this case we're interested in the "todo-angular" sample, located in the *node/todo-angular* directory.
These instructions assume this will be your current working directory.

##Install MySql and run sql script to create demo user

Run the *~/node/todo-angular/db-script/mysql/create-demo-user.sql* script

**OR**

##Install PostgreSQL and run the following sql scripts in order

Run the *~/node/todo-angular/db-script/postgres/#1 - create-demo-user.sql* script

Run the *~/node/todo-angular/db-script/postgres/#2 - create-todos-database.sql* script

Switch the current connection to the new `todos` database and run the *~/node/todo-angular/db-script/postgres/#3 - init-todos-table.sql* script

##Install dependencies and launch app server

Navigate to the server folder, *~/node/todo-angular/server*

Install dependencies and launch the app server: `npm start`

>This command will install both client and server dependencies. You can ignore the sea of red describing rebuild failures  of nested packages. It's OK; you'll be using the pre-build versions of those packages. Do make sure the install finishes completely without error.

Console output should indicate that app server started successfully and is **listening on port 3000**.

##Launch Todo-Angular in a browser

Start your browser with address [**http://localhost:3000**](http://localhost:3000)