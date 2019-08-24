# FullStack Web Design with Spring Framework 

## 1. Create a wireframe for frontend
* [Wireframe.cc](https://wireframe.cc/) - A minimal wireframing tool

https://wireframe.cc/CNfy9P


## 2. Implement design using html and css
This project uses bootstrap framework for responsive effect.
* [Bootstrap](https://getbootstrap.com/) - An open-source CSS framework

navbar for header
container for body
container-fluid for footer

## 3. Setup a local database
* [MySQL](https://www.mysql.com/) - An open-source relational database management system

create table user; userid double primary key, username varchar2(20), password varchar2(50)
create table student; studentid double primary key, name varchar2(20), gpa double

## 4. Create Model class
create two model classes for each table

## 5. Create DAO class
create a DAO class that implements CRUD operations
Load driver, make database connection, write&execute query and work with result.

## 6. Create Service class
Static method. This simply adds another layer to encapsulate DAO class.

## 7. Design CRUD pages
Bootstrap form and input type(text, button)

## 8. Create Controllers
Servlet. doPost or doGet that helps communicate between frontend web components and backend objects.

## 9. Link the CRUD pages with the controllers
Web.xml
