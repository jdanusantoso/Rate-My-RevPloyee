# employee-rater


ABOUT RevRater is a social media application developed as our team's P3 Project. RevRater is designed to be a service where you can rate employees of revature anonymously, giving them a score between 1-10. You give a rational behind your rating when you make a post about a specific employee. To be absolutely clear, this service is a lot like RateYourProfessor, a similar social media application, but with a focus specifically on Revature.

The service is configurable to an extent, allowing you to easily generate base operating table entries for the RDS that contains information about what tags may be utilized while rating an employee, and a configurable department file, which allows you to expand or contract the scope of the service based on the company this service is utilized at. Not everything is currently configurable via config files, but this would be a good feature to add in future Sprints.

CONTAINED IN THIS REPO This Git Repository features 3 main folders:

rate-my-revployee-python-SQL-Generator
rate-my-revployee-React-Front
rate-my-revployee-Spring-Back
The Python Folder contains code that is useful for instantiating the RDS once it has been created. The React-Dev Folder contains all of the React components used in the creation of the app. You will need to install some dependencies detailed in STARTUP.md The Spring-Main Folder contains a Spring Boot application designed in IntelliJ. Maven is the dependency manager, and we utilized Application Context for the Spring Container

TECHNOLOGY UTILIZED To Utilize this Project, the following technologies will need to be installed locally to make changes and prepare the service to go live:

Python 3
Java JDK 11
IntelliJ
DBeaver or your choice of RDS connection utility
ReactJS
Git (Optional, but may make it easier to obtain this repo and stay up to date) Prior to starting the steps below, be sure to install the above technologies locally.

For external tools, it is recommended that you use a service provider of your choice to host the application:

React App portion (located in Social-Media-React-Dev) will be the client side portion.
Java Server portion (located in Social-Media-Spring-Main) will be the server side portion.
