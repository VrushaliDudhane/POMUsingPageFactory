# POMUsingPageFactory
This project demonstrate the design of Page Object Model with Page Factory Using Selenium and TestNG as Testing Framework 

This repository is based on following scenario

Problem Statement:Automate Registration Page Using Selenium and Java

Scenario:
•	Open a 2 browser at a time for example – Chrome Browser and Microsoft Edge (Use a headless mode for choosing browser).
•	Navigate to https://www.lambdatest.com/webpage.
•	Click on ‘Free Signup’ button and reach to the Registration page of the Lambda Test
•	Check the Functional fields on this Registration page (write every test case single function and create one java library).
1.	Organization / Company Name (function 1)
2.	Full Name of the user ((function 2)
3.	Email Id ((function 3)
4.	Desired Password ((function 4)
5.	Phone number of the user ((function 5)
6.	Terms and Privacy Policy ((function 6)
7.	Free Signup ((function 7)
•	Enter all the required fields: Full Name, Work Email, Desired Password, Phone number, Terms and Privacy policy checkbox.
Validate the fields:
1.	Email: Should not be an existing user, valid email. (Function 1)
2.	Password: Should provide minimum required length for password. (Function 2)
3.	Phone Number. (Function 3)
4.	Terms and Privacy policy checkbox (function 4)
•	After crating library of registration page call this library in sign up page create test cases for every individual element which is available in signup page.
•	 For locate every element use ‘id', ‘classname’, ‘xpath’ (usingid for one script, using classname crate 2nd script, and 3rd script use xpath).
•	Give every test case 2 sec delay (time).
•	Create Test case report HTML, JSON and Gmail format using Test NG.
