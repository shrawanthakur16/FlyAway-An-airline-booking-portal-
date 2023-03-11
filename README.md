# FlyAway-An-airline-booking-portal-
This is a FlyAway Airline Reservation System built using hibernate, MySQL and TomCat server. It all provides all basic features that a flight booking website or a system should have like flight search, booking flights, payment facilities, etc.




Table of Contents
Problem Statement
Using the application
Technologies
Setup
Description
Project objective:
The website needs to have the following features:
A search form in the homepage to allow entry of travel details, like the date of travel, source, destination, and the number of persons.
Admin login panel
An admin login page where the admin can change the password after login, if he wishes
An admin panel to add new flight entries
All flight list details in admin panel page
Flight search details entry page from user side
Based on the route entered, it will show the available flights and their ticket prices.
A list of flights where each flight has a source, destination, airline, and ticket price
The flow and features of the application:
Planned two sprints to complete the application
Document the flow of the application and prepare a flow chart
List the core concepts and algorithms being used to complete this application
Implement the appropriate concepts such as exceptions, collections, and sorting techniques for source code optimization and increased performance
The following must be used:
Eclipse/IntelliJ: An IDE to code for the application
Java: A programming language to develop the web pages, databases, and others
SQL: To create tables for admin, airlines, and other specifics
Maven: To create a web-enabled Maven project
Git: To connect and push files from the local system to GitHub
GitHub: To store the application code and track its versions
Scrum: An efficient agile framework to deliver the product incrementally
Search and Sort techniques: Data structures used for the project
Specification document: Any open-source document or Google Docs
Following requirements should be met:
The source code should be pushed to your GitHub repository. You need to document the steps and write the algorithms in it.
The submission of your GitHub repository link is mandatory. In order to track your task, you need to share the link of the repository. You can add a section in your document.
Document the step-by-step process starting from sprint planning to the product release.
Application should not close, exit, or throw an exception if the user specifies an invalid input.
You need to submit the final specification document which includes:
Project and developer details
Sprints planned and the tasks achieved in them
Algorithms and flowcharts of the application
Core concepts used in the project
Links to the GitHub repository to verify the project completion
Sprints Planned:
Sprint 1:
Developed Home Page
Developed admin login page and admin panel
Developed master flights addition page
Developed flights listing page on admin side
	


Sprint 2:
Developed flights details page on user side
Developed passenger details entry page
Developed flight summary page and payment page

Using the application
An introduction Home Page containing two sections Admin and Booking from the passenger side.
Two options in the home page.
a. If a user selects the “admin” section.
b. If the user goes to the passenger side through registering all booking details.
Once a user selects admin, it will prompt for admin email and admin password.
An admin main page will be displayed containing three options and showing a list of flights that admin has entered.
a. Add Flights.
b. Change Password.
c. Logout and go back to the Home Page.
A new window will be shown where admin can enter flight details.
For changing password, it will ask for a new and confirmation password from the admin. Once it is validated correctly it will go back to the home page.
This will show a window having flight details that are filtered out through booking details. And the user has to select the flight for further action.
Once, the user has selected the flight, the user has to register his/her details and should be less than or equal to the number of persons that user has specified.
After continuation, it will show the summary of the user's flight and will prompt the user for payment (Dummy Payment Gateway).
Once payment is successful, it will take the user back to the starting page.
Technologies Used:
Technologies used in project include:
Java 8
Spring Tool Suite based on top of eclipse (Trainer advised the same)
Tomcat v8.5 server
MySql database
Maven Web App and Hibernate Integration


