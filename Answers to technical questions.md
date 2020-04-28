1.	How long did you spend on the technical test? What would you add to your solution if you had more time? If you didn't spend much time on the technical test then use this as an opportunity to explain what you would add.

- I spend one day in creating the technical test.I created the below for automating the test scenario:
 . Created automation scripts for scenario
 . Applied TestNG annotations to order the test, setup and browserclose operations.
 . Applied TestNG anntations to pass the input parameters URL and postalcodes.
 . Build the project as Maven Project with declaring the dependencies in pom.xml file
- I would like to add the below improvements to the code
 . Input a test data (Eg: postalcode) which doesnot have matching records and to check the test output.
. Scale the test to different test data (Eg: different postal codes) using external source files and capture the results.
  
2.	What do you think is the most interesting trend in test automation?
I think the below areas will be given more importance and will be emerging as interesting areas in the field of test automation:
- Increased usage of Multi experience platforms increases need to levearge automation to new platforms like chat, wearable components etc.
- The emergence of DevOps concepts in testing.
- Introduction of Machine Learning and AI concepts in Automation testing.

3.	How would you implement test automation in a legacy application? Have you ever had to do this?
The below approach should be feasible for autoamting legacy system
- Automate only most critical functionalities of the application.
- Automate the End to end scenario which need more attention.
- Entire Legacy system should not be automated.
I have automated few functionalities of Legacy system while working in my last organisation Dubai Customs. We had a business flow in the Legacy system (To create goods declartaion) which became the pre-requisite for the testing of any other functionalities in the system. I created a test automation framework for creating different types of goods declaration. The scripts were used to automate the functionality whenever there was a new build which used the above business flow.

4.	How would you improve the customer experience of the JUST EAT website?

- While seraching with a particluar postal code, all entries which have exact match should be displayed first followed by the other items. Currently the items are not sorted.
- Performance of application is very poor. search results takes more time to load.
- Loading text can be added if more items have to be loaded and there is delay.
- 
5.	Please describe yourself using JSON.
{
  "Firstname": "Teresa",
  "lastname": "Francis",
  "E-mail": "teresafrancis18@gmail.com",
  "Mobile": "437 249 6112",
  "Adddress": "20 Capistro Street,Brampton",
  "Expertise": [
    "Selenum Automation",
    "Web application testing",
    "Mobile Application Testing",
    "Accessibility Testing"
  ],
  "Experiences": [
    "Dubai Customs 1+ years",
    "EY 2 years",
    "Infosys Limited 4+ years"
  ],
  "Tools and Skills": [
    "Eclispe",
    "Java",
    "Selenium",
    "WCAG 2.0",
    "HP ALM",
    "JIRA",
    "Jenkins"
  ]
}



