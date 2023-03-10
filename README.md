# Kantox
Kantox Technical Evaluation

1-Overview
This project is a Java implementation of automated testing using the Selenium WebDriver. Selenium is an open-source tool that allows you to automate web browsers, making it an ideal choice for testing web applications. 

2- Requirements

Java Development Kit (JDK) 8 or later
Apache Maven 3.5.0 or later
Selenium WebDriver 3.14.0 or later
Firefox or Chrome web browser



3- Installation

Clone the repository to your local machine:
git clone https://github.com/[username]/java-selenium-project.git


Navigate to the project directory:
cd java-selenium-project


Compile the project using Maven:
mvn clean install




4- Usage
The project contains several tests a Simple cashier function that adds products to a cart and displays the total price. 
To run a test, simply execute the following command:


mvn test -Dtest=[test_class_name]
Replace [test_class_name] with the name of the test class you wish to run. For example, to run the test class LoginTest, execute the following command:
mvn test -Dtest=LoginTest



5- Configuration
The project can be configured to use either Firefox or Chrome as the web browser for testing. To configure the browser, open the src/main/resources/config.properties file and set the browser property to either firefox or chrome.
