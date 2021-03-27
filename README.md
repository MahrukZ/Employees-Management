# Employees-Management
![download](https://user-images.githubusercontent.com/68380691/112720989-d2d75a00-8f01-11eb-8945-0c06c0a85215.png)

Developing a prototype web application for National Statistics Wales using Springboot. The application was created within a strict deadline of 4 weeks. As a scrum master for a week, managed the team of 3, ensuring progress was tracked through burn-down chart and cumulative flow diagrams. Arranged and structured sprints by hosting daily scrums and retrospectives. Personally developed end to end clean architecture for the following features: 

▪️Login and registration 
▪️Facebook Authentication - OAuth2 
▪️Search bar to search persistent Database 
▪️Adding/Deleting/Editing an entry the user has made to their profile 
▪️REST API returning JSON data from the database 
▪️Designing RDBMS  Cyber security features:  
▪️Database at Rest Encryption 
▪️Logging 
▪️Authentication 
▪️SQL Injection Countermeasure 
▪️Spring Boot Security  Tools included: Java, Springboot, MySQL, Javascript, Thymeleaf, Git, Html / Css and Agile

# INSTRUCTIONS
Before running the application, seperately run the schema.sql and the data.sql externally on workbench.
LOGIN IN DETAILS
username: nimrod@cardiff.ac.uk
password: nimpass
roles: User
use for: filling out a personal checklist
username: mahruk@cardiff.ac.uk
password: mahpass
roles: User & Author
use for: filling out a personal checklist & creating new checklists template
username: picard@cardiff.ac.uk
password: earlgreyhot
roles: User, Author, Admin
use for: filling out a personal checklist & creating new checklists template & managing user roles
all users created through the register page will be given a default User role
to test email verification, please register with a valid cardiff domain email.  If your email is not verified you
will be unable to change the role of your account
WARNING: whitelabel error page given after Author assigns a checklist, however checklist is still assigned and
functionality still working
