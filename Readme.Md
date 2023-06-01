
# Railway Ticket Booking System Project
## Installation Steps 



* Ensure that you are using MySQL 5. If not, modify the following line in the configuration file (application.properties) to use the appropriate dialect for your   MySQL version: <br>
  *spring.jpa.database-platform=org.hibernate.dialect.MySQL5Dialect*


* Ensure that you are using Spring 3 or a newer version.
* Include the Spring Security 6 library in your project.
* Verify that the default port number 2003 is available for the Tomcat server. If not, change it using the following line in the application.properties file: <br>
  server.port=8081
            (*Note  port numbers 49152 and 65535 are considered safe to use for custom applications)
 

### Final steps

* Download the ZIP file of the project.
* Extract the ZIP file to your preferred location.
* Import the project into Eclipse or Spring Tool Suite.
* Allow the required dependencies to be downloaded automatically.
* Update your Maven file to resolve any missing dependencies.
* Ensure that no other servers are currently running.
* Start the server.

### Running the Application

* Once the application has started successfully, open any web browser on your machine.
* Enter the following address in the browser's address bar: *http://localhost:2003/*
* Follow the instructions provided in the user interface to proceed.


### Thank You
<hr>
<br>
Thank you for using the Railway Ticket Booking System . If you have any further questions or need assistance, please don't hesitate to reach out.
