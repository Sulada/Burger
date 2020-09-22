# Node Express Handlebars
# "Sulada Burger"

### Overview
This is a burger logger with MySQL, Node, Express, Handlebars and a homemade ORM. Follow by the MVC design pattern; use Node and MySQL to query and route data in the app, and Handlebars to generate HTML.

* Sulada Burger is a restaurant app that lets users input the names of burgers they'd like to eat.

* Whenever a user submits a burger's name, the app will display the burger on the left side of the page -- waiting to be devoured.

* Each burger in the waiting area also has a `Devour` button. When the user clicks it, the burger will move to the right side of the page.

* This app is store every burger in a database, whether devoured or not.

## Instructions

#### App Setup

1. Make a package.json file by running `npm init` from the command line.

2. Make a package-lock.json file and node_modules folder by running `npm install` from the command line.

3. Install the Express npm package: `npm install express`.

4. Install the Handlebars npm package: `npm install express-handlebars`.

5. Install MySQL npm package: `npm install mysql`.

#### DB Setup

1. Run the `schema.sql` and `seeds.sql` files into the mysql server from the command line or MySQL Workbench

2. If you use command line.

Follow this :

   * Make sure you're in the `db` folder of your app.

   * Start MySQL command line tool and login: `mysql -u root -p`.

   * With the `mysql>` command line tool running, enter the command `source schema.sql`. This will run your schema file and all of the queries in it -- in other words, you'll be creating your database.

   * Now insert the entries you defined in `seeds.sql` by running the file: `source seeds.sql`.

   * Close out of the MySQL command line tool: `exit`.