In this project, we use PHP and  MySQL database. It has three modules

Admin
User(Patients)
Admin Module

Admin is the superuser of the website who can manage everything on the website. Admin can log in through the login page

Dashboard: In this section, the admin can see all detail in brief like the total, assigned and the sample collected and completed tests.
Phlebotomist: In this section, the admin can manage Phlebotomist (add, update, delete).
Testing: In this section, the admin can manage all the tests like assign the test to Phlebotomist and update the history.
Report: In this section, the admin can generate two types of report. One is between dates reports and another one is by search. Admin can search the report by order number, name and mobile number.
Notification: In this section, the admin will get a notification for every new test request (notification bell).
Admin can also update his profile, change the password and recover the password.
User(Patient) Module

User can visit the application through a URL.
Testing: This section divided into two parts. One is for new user and another one is for registered user. New user(First-time user) needs to provide personal and testing Information. A registered user only needs to provide test information, their personal information will be fetched from the database.
Report: In this section, Users can search their test report using order number, name and registered mobile number.
Dashboard: In this section, the User can see the in which State of how many tests are done.



How to run the COVID19 Testing Management System Using PHP and MySQL

Download the zip file
Extract the file and copy covid-tms folder
Paste inside root directory(for xampp xampp/htdocs, for wamp wamp/www, for lamp var/www/html)
Open PHPMyAdmin (http://localhost/phpmyadmin)
Create a database with name covidtmsdb
Import covidtmsdb.sql file(given inside the zip package in SQL file folder)
Run the script http://localhost/covid-tms

Admin Credential
Username: admin
Password: kavita