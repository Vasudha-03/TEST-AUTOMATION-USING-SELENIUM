# TEST-AUTOMATION-USING-SELENIUM
*COMPANY*: CODETECH IT SOLUTIONS
*NAME*: VASUDHA M R
*INTERN ID*: CTIS4793
*DOMAIN*: SOFTWARE TESTING
*DURATION*: 4 WEEKS
*MENTOR*: NEELA SANTOSH 

*Title*: Automated Login and Logout Testing Using Selenium WebDriver with TestNG Framework

*Objective*: The objective of this task is to design and implement an automated testing framework using Selenium WebDriver integrated with TestNG to validate the login and logout functionality of a web application. Automation testing helps ensure software reliability, reduces manual effort, and improves testing efficiency.

*Overview*: 
In this task, a web application (SauceDemo) was used to simulate real-world login scenarios. The automation framework performs the following actions:

  ~ Launches a browser
  ~ Navigates to the login page
  ~ Enters valid credentials
  ~ Verifies successful login
  ~ Performs logout operation
  ~ Validates logout success
  
*TOOLS AND TECHNOLOGIES USED* 
1. Programming Language: Java – Used for writing automation scripts due to its platform independence and strong community support.
2. Automation Tool: Selenium WebDriver - Enables interaction with web elements such as buttons, text fields, and links.
3. Testing Framework: TestNG - Provides annotations, assertions, and reporting features for structured test execution.
4. Build Tool: Maven - Manages dependencies and project build lifecycle.
5. Browser: Google Chrome with ChromeDriver for executing automation tests.

*Test Scenarios Implemented*

Test Case 1: Login Verification

Step1:Launch browser
Step2:Open SauceDemo login page
Step3:Enter valid username and password
Step4:Click login button
Step5:Verify navigation to Products page

Expected Result:
User is successfully logged in.

Test Case 2: Logout Verification

Step1: Login with valid credentials
Step2: Click menu button
Step3: Click logout option
Step4: Verify return to login page

Expected Result:
User is successfully logged out.

*Challenges Faced*
  During automation, issues such as element loading delays and synchronization problems were encountered. These were resolved by adding waits to ensure elements were visible before interaction.
Additionally, selecting a stable testing website was crucial for reliable test execution.

*Benefits of Automation in This Task*

✔ Reduces manual testing effort
✔ Ensures repeatable and consistent testing
✔ Detects regressions quickly
✔ Improves software quality
✔ Saves time in long-term testing

*Learning Outcomes*

Through this task, the following skills were developed:

> Understanding Selenium WebDriver architecture
> Implementing Page Object Model (POM)
> Writing automated test scripts using TestNG
> Handling dynamic web elements
> Performing assertions for validation
> Managing Maven dependencies

*Conclusion*
This task successfully demonstrated the automation of login and logout functionality using Selenium WebDriver and TestNG. By applying the Page Object Model design pattern, the framework achieved modularity, maintainability, and scalability.

Automation testing plays a vital role in modern software development by improving efficiency and ensuring application reliability. The knowledge gained from this task forms a strong foundation for advanced automation concepts such as data-driven testing, cross-browser testing, and continuous integration.


