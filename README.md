# :movie_camera: ***Cinema*** :movie_camera:
___
### :pushpin: ***Project description*** :pushpin:
***Web-application that supports user registration, authentication, authorization
and CRUD operations with movies, movie sessions, cinema halls, orders, shopping carts and tickets***
___
### :bookmark: ***Features:*** :bookmark:
+ :pencil2: ***register, authenticate, authorize a user***
+ :unlock: ***log in/out***
+ :notebook: ***create/read a movie***
+ :notebook: ***create/read/update/delete a movie session***
+ :notebook: ***create/read a cinema hall***
+ :notebook: ***read/update a shopping cart***
+ :notebook: ***create/read an order***
___
### :open_file_folder: ***Structure:*** :open_file_folder:
+ ***Controller - accepts requests from the client, passes them to the service layer***
+ ***Service - accepts requests from the controller, passes them to the DAO layer and performs all business logic***
+ ***DAO - accepts requests from the service, passes them to the DB and executes all sql queries***
___
### :page_with_curl: ***Technologies:*** :page_with_curl:
+ ***[Tomcat 9.0.50](https://archive.apache.org/dist/tomcat/tomcat-9/v9.0.50/bin/)***
+ ***[Maven](https://maven.apache.org/download.cgi)***
+ ***[MySQL](https://dev.mysql.com/downloads/installer/)***
+ ***Spring***
+ ***Hibernate***
+ ***[Java 11](https://www.oracle.com/java/technologies/javase/jdk11-archive-downloads.html)***
___
### :question: ***How to run this project: :question:***
- [x] ***Fork this project to your repository***
- [x] ***Press "Code" and choose HTTPS or SSH url to clone the project***
- [x] ***Create new project from Version Control and write this url***
- [x] ***Write your properties to db.properties file***
```java
        db.driver="YOUR_DATABASE_DRIVER"
        db.url="YOUR_DATABASE_URL"
        db.user="YOUR_DATABASE_USERNAME"
        db.password="YOUR_DATABASE_PASSWORD"
```
- [x] ***Install Tomcat and configure it in your IDEA***
- [x] ***Run the project***    
