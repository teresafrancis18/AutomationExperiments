# Context
A sample to demonstrate Selenium test automation of a website using the below:
 - Selenium Webdriver
 - TestNG
 - Maven

# Setup Instructions
  Pre-requisites:
- chromedriver.exe
- Java 1.8 or above
- Maven 3 or above

# Test Execution - Option 1 using Command Line using Maven
1. Navigate to the working directory where the project is downloaded.
> cd filepath
2. Enter the maven instruction as shown below
> mvn clean test -Dwebdriver.chrome.driver=location of chrome.exe

Test Results will be published as .html in target folder in the below path:
> target/surefire-reports/emailable-report.html. Sample file is uploaded.

The report will look like below:
https://teresafrancis18.github.io/AutomationExperiments/Resources/emailable-report.html

# Test Execution - Option 2 using Eclipse IDE and TestNG
Pre-requisite:
Eclipse IDE

Steps:
1. Import the project to Eclipse 
2. Set Run Configurations
> testng.xml->Run As-> Run Configurations
3. Enter Arguments->VM arguments to the below value
> -Dwebdriver.chrome.driver= "chrome drive path"
4. Run the Test
> testng.xml->Run As->TestNG Suite

Results can be viewed in TestNG console.

# Useful Links
Download the required .exe from the below links:
| Installables | Link |
| ------ | ------ |
| ChromeDriver | [https://chromedriver.chromium.org/downloads]|
| Eclispe | [https://www.eclipse.org/downloads/packages/]|
| Java | [https://www.oracle.com/java/technologies/javase-downloads.html]|

# Scenario to be Tested and Approach used for Test:
Scenario:
JUST EAT has a website available at http://www.just-eat.co.uk/ that you can use to find takeaway restaurants in a postcode area.
Feature: Use the website to find restaurants
•	So that I can order food
•	As a hungry customer
•	I want to be able to find restaurants in my area
 Scenario: Search for restaurants in an area
•	Given I want food in "AR51 1AA"
•	When I search for restaurants
•	Then I should see some restaurants in "AR51 1AA"

Approach:
Only First 10 entries of the restaurants retireved matching the postal code is retrevied assuming that best matching entries for entered postal code will be displayed at top. This approach helped in reducing the test execution time considerably less when compared of checking all restaurants with postal code AR51 1AA.


