
# Burst Oralcare – Manual Test Cases
This project contains manual test cases written for [Burst Oralcare](https://burstoralcare.com/), a real-world oral care e-commerce website. The purpose of this project is to practice manual testing on a live production website, covering sign-up functionality and product search.

Application Under Test :
Website         : https://burstoralcare.com/ 
Type            : Real-world e-commerce website (oral care products) 
Test Email Used : helloworld@test.com 

Test Case Structure :
Each test case includes the following fields:

- SR No. :  Serial number
- Test Scenario ID : Unique ID for the scenario
- Module : Feature being tested
- Test Scenario Description : High-level description of what is being tested
- Test Case ID : Unique ID for each test case
- Test Case Description :Detailed description of the test
- Test Steps : Step-by-step instructions to execute the test
- Test Data : Input data used during testing
- Expected Result : What should happen
- Actual Result : What actually happened during testing
- Status : Pass / Fail
 
 Bugs Found :
1. TC_001_06 – Sign-up allowed with existing email
Description:The application allows a user to sign up using an email that is already registered. No duplicate check is performed.  
Expected:An error message should appear — "This email is already registered."  
Actual:Sign-up proceeds without any error.
![TC_001_06 Screenshot](screenshots/TC_001_06_existing_email_fail.png)

2. TC_001_08 – Empty email field does not show error popup
Description:When the sign-up button is clicked with an empty email field, the application does not show any error pop-up message to the user.  
Expected:An error pop-up should appear — "Please enter your email."  
Actual:No pop-up shown — silent failure.
![TC_001_08 Screenshot](screenshots/TC_001_08_empty_email_no_popup_fail.png)

3. TC_001_10 – Facebook sign-up is not working
Description:Clicking the Facebook sign-up option redirects to Facebook login but the authentication fails and the user cannot sign up via Facebook.  
Expected:User should be able to sign up using valid Facebook credentials.  
Actual:Facebook login fails — "The password you've entered is incorrect."
![TC_001_10 Screenshot](screenshots/TC_001_10_facebook_signup_fail.png)

Testing Type :
- Manual Testing
- Functional Testing
- Negative Testing
- Boundary / Edge Case Testing

Tools Used :
- Microsoft Excel (test case documentation)
- Browser: Chrome (primary)
 
QA Tester  
GitHub: [nikitad-QA](https://github.com/nikitad-QA)
