
BURGER
===

Full stack MVC application using NodeJS, Express, Handlebars and MySQL and deployed to Heroku.
User is able to create database entries from their own input and alter the data, which is then written to the MySQL database via a homemade ORM using the MVC design pattern.

This app is a burger logger with MySQL, Node, Express, Handlebars and a homemade ORM using the MVC design pattern.

Node and MySQL to query and route data in the application, and Handlebars is used to generate the HTML.
---


When a user submits a burger's name, after saving the user's entry into a Sequel database, the application dynamically generates the burger on the left side of the page with a "Devour" button using a Handlebars template. When the user clicks clicks devour, that aspect of the database entry is updated and then displayed in a different section.

**INSTRUCTIONS**

1. User enters the name of any burger they would like to enter into the database and clicks Make Burger.

2. The burger the user entered is then saved into the database and retrieved to be displayed in the Burgers to be Eaten panel.

3. The user can then alter the burger in the datbase by clicking devoured. When a burger is devoured, it is then displayed in the devoured section.


[Click here to go to the live link](https://sheltered-reaches-31441.herokuapp.com/)


SCREENSHOT FROM APP


![](/public/assets/img/screenshot1.JPG)



