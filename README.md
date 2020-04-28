# Automation Assignment 1- To automate search of restaurants with a postal code provided
The test is intended to automate search of restaurants using a postal code provided and to check if the site is retrieving results with that post code.

# File Retrieval 
Download the below files from the Github to loacl machine:
- src
- pom.xml
- testng.xml

#Pre-requisites
- Download chrome.exe for the browser used in the targeted machine.
- Java should be installed.
- Maven should be installed.
- Eclispe should be installed.(For approach 2) 

# Test Execution - Approach 1
1. Open Command Prompt
2. Change directory to the loaction of the artifacts (cd filepath)
3. Enter the below command
4. mvn clean test -Dwebdriver.chrome.driver=<location of chrome.exe>
Test execution results can be viewed in the command prompt.

# Test Execution - Approach 2
1. Import the project to Eclipse 
2. Run pom.xml
3. Enter Goals=clean test-Dwebdriver.chrome.driver=C:\chromedriver\chromedriver.exe
4. Run the maven build
Test execution results can be viewed in Console.

# Reports
You can also view the reports in the below path
target/surefire-reports/emailable-report.html

# Useful Links
Download the required .exe from the below links:
| Installables | Link |
| ------ | ------ |
| ChromeDriver | [https://chromedriver.chromium.org/downloads][PlDb] |
| Eclispe | [https://www.eclipse.org/downloads/packages/][PlGh] |
| Java | [https://www.oracle.com/java/technologies/javase-downloads.html][PlGd] |

# Approach used for Test
Only First 10 entries of the restaurants retireved matching the postal code is retrevied assuming that best matching entries for entered postal code will be displayed at top. This approach helped in reducing the test execution time considerably less when compared of checking all restaurants with postal code AR51 1AA.


