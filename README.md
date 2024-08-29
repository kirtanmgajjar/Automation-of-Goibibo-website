About the Project:

This project consist of Automation of Goibibo Website for Login, Flight Booking and Hotel Booking scenario.


src/main/java has the packages baseClass and utilities
-baseClass package has the BaseClass which contains methods to be performed at the start and the end of suite, test and class for all the test classes. 
-utilities package has the java class for driver setup,  excel reading and writing, Listener class which interfaces ITestNGListener, test Report generator for the tests run, locators to be used in the Test Classes, properties file reader and capturing the screen shot. 
-pages package has the pages for the required page of the website.

src/main/resources folder has the config.proprties file which contains the name of the browser used to run the tests and the link of the main page of the website namely the baseUrl

src/test/java folder has the test classes LoginTest, FlightTest and HotelsTest. 


Reports folder has the Report.html file which is the report generated after running the tests.

Screenshot folder will contain the screenshots for the failed tests. 
 
pom.xml contains the dependencies required by the project.
 
testng.xml file is for running the test cases.


Tools and Technologies used:
-Selenium with Java in Eclipse IDE
-TestNG
-Maven
-WebDriverManager- Boni García
-Apache POI
-ExtentReports


By: Kirtan Gajjar
