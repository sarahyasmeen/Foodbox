# Foodbox
This project aims to design and develop an E-commerce website that lets people shop food items of different cuisines at affordable prices and deliver the products to their addresses. It was developed using Angular and Spring boot It was created as the Capstone Project for the Full Stack Java Developer course.

Product Backlog:
Programming:
Create database and tables.
Add some rows and metadata to the tables
Initialize a Spring Boot project for the Back-End side.
Create REST APIs with spring Data JPA Repositories.
Create desired DAO methods for the Back-End side
Create a new Angular project for the Front-End side.
Create login and register pages and components.
Add cache to the login user
Logout user and remove cache
Show all products to the home page.
Show all products as cards.
Create a product details component.
Search a product by a category.
Search a product by a keyword.
Add products pages
Filter by page number
Sort product by different options
Add products to the cart.
Update total price in the cart status.
Show the payment gate and review the list
Add and remove products from the review list
Update the total price in the payment gate
Create the admin view
Update/Remove a product for the admin
Add a new product for the admin
Update the CSS design
Add bootstrap and font awesome to the components.
Debug and test the project.
Deployment:
Upload project to GitHub.
Create a t3.medium instance for master.
Create a t3.micro instance for slave.
Connect the two instances to the system
Create a Pipeline project on Jenkins.
Create a Jenkins file.
Generate a SSH key for GitHub.
Build the pipeline project.
Deploy the project.
Technologies and tools Used
Angular: used in the front-end side to build modern single-page applications
Spring Boot: used in the back-end side to create the REST API and retrieve data from a database.
AWS EC2 instance: to use the instances as a VM and deploy the application
AWS RDS: to upload the database online.
Jenkins: to build the project from GitHub.
GitHub: to upload the source code of the project.
MobaXterm: to the instance from Windows OS.
Selenium: for automation and testing.
Apache: to use it as a web server.
HTML/CSS: to create and format the content of the pages.
Bootstrap: to use some CSS and JavaScript designs.
Maven: to manage the project.
Visual Studio Code: to write and run the Angular code.
IntelliJ: to write and run the Spring Boot code.
MySQL: to use it as database management system.
phpMyAdmin: to administrate and manage the database manually.
Flowcharts of The Application
Blank Diagram

Core concepts used in the project.
Object-Oriented: used to create and model objects for users and their credentials.
REST API: used to communicate between the back-end and the front-end sides.
Data Access Object: to abstract and encapsulate all access to the data source.
Object–Relational Mapping: to map the objects to the database.
Databases: used to store and retrieve data.
Data Sources: used to define a set of properties required to identify and access the database.
Collections: used some collections such Arraylist to store collection of data.
Deployment: to deploy the local project to the end-users.
Virtual Machine: use virtual instances to help to build, deploy and manage websites.
Exception Handling: used to catch problems that arises in the code especially in I/O blocks.
Single Web Page: apply the concept of a website that only contains one HTML page.
AWS Website Link
http://ec2-15-185-146-219.me-south-1.compute.amazonaws.com/

How to run the program locally
clone project clone git : git clone https://github.com/MujtabaMohsin/Foodbox

Import the “\Back-End\foodbox\database\foodbox.sql” file to your database administration tool.

Go to “\Back-End\foodbox\src\main\resources\application.properties” file, open it.

Edit some values of the database’ properties to be suit to your database administration tool.

Run the back-end project as a maven project: cd to your project “Back-end\foodbox” mvn compile mvn exec:java -Dexec.mainClass=com.simplilearn.foodbox

Open another command line for the front-end part.

cd to your project “Front-end-end\foodbox”

install the following:

npm install --save-dev

npm install @angular/localize --save

npm install bootstrap --save

npm install font-awesome –save

Run using ng serve –open
It would be displayed in http://localhost:4200/
