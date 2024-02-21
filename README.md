![image](https://github.com/alinst24/manualTesting/assets/153013663/2d6983b0-7a58-4d1f-b65d-a6ac3ea285eb)



# INTRODUCTION
Personal project done for manual software testing course on : https://demo.prestashop.com/

The website used for manual testing is a demo website that has various functionalities which can be tested. The website subject is an store which has clothes, accesories and art store.
     The manual testing in this project includes “Register” and “Login” pages, “My account” page and “Cart” page with “Checkout” page.
     As a client using this website, we should be able to register, login, modify informations in our account, choose what products we want to buy, add them to cart and checkout them. For this, we need to follow some steps in our manual testing.

1. Registration
2. Logging in 
3. Modifying “My account” details.
4. Product page
5. Proceeding to checkout


### 1.	Registration

![image](https://github.com/alinst24/manualTesting/assets/153013663/d4075200-f545-463d-b65a-ff6b5bfc6788)


Test case 1
	TITLE	Register page
	PRECONDITIONS	A browser is displayed
URL “https://tired-mass.demo.prestashop.com/en/” was accesed
	STEPS	The user clicks on “Create account” button in bottom of the page
	EXPECTED RESULT	A new page with the name "Create account" will be displayed
	Register form will be displayed and contains: 
		- Social title
		- First name
		- Last name
		- Email
		- Password
                        - Birthdate
                        - 4 checkboxes

Test case 2
	TITLE	Registration process with valid values for all the fields
	PRECONDITIONS	Sign up page was displayed
	STEPS	The user enters valid values for all the mandatory fields
The user clicks on “Save” button
	EXPECTED RESULT	The account will be created. And the main page will be displayed with user logged in his account.
		
Test case 3
	TITLE	Registration process with invalid values for all the fields
	PRECONDITIONS	Sign up page was displayed
	STEPS	The user enters invalid values for all the mandatory fields
The user clicks on “Save” button
	EXPECTED RESULT	The account is not created. 
Error message will be displayed: “Please fill out this field.”
		
Test case 4
	TITLE	Registration process with valid value only for first name
	PRECONDITIONS	Sign up page was displayed
	STEPS	The user enters valid value for first name only
The user clicks on “Save” button
	EXPECTED RESULT	The account is not created. Error message will be displayed: “Please fill out this field” in last name field.
		
Test case 5
	TITLE	Registration process with valid value only for last name
	PRECONDITIONS	Sign up page was displayed
	STEPS	The user enters valid value for last name only
The user clicks on “Save” button
	EXPECTED RESULT	The account is not created. Error message will be displayed: “Please fill out this field” in first name field.
		
Test case 6
	TITLE	Registration process with valid value only for email
	PRECONDITIONS	Sign up page was displayed
	STEPS	The user enters valid value for email only
The user clicks on “Save” button
	EXPECTED RESULT	The account is not created. Error message will be displayed: “Please fill out this field” in first name field.
		
Test case 7
	TITLE	Registration process with valid value only for password
	PRECONDITIONS	Sign up page was displayed
	STEPS	The user enters valid value for password only
The user clicks on “Save” button
	EXPECTED RESULT	The account is not created. Error message will be displayed: “Please fill out this field” in first name field.
		
Test case 8
	TITLE	Registration process with valid value only for first name and last name
	PRECONDITIONS	Sign up page was displayed
	STEPS	The user enters valid value for first name and last name only
The user clicks on “Save” button
	EXPECTED RESULT	The account is not created. Error message will be displayed: “Please fill out this field” in email field.
		
Test case 9
	TITLE	Registration process with valid value only for first name and email
	PRECONDITIONS	Sign up page was displayed
	STEPS	The user enters valid value for first name and email only
The user clicks on “Save” button
	EXPECTED RESULT	The account is not created. Error message will be displayed: “Please fill out this field” in last name field.
		
Test case 10
	TITLE	Registration process with valid value only for first name and password
	PRECONDITIONS	Sign up page was displayed
	STEPS	The user enters valid value for first name and password only
The user clicks on “Save” button
	EXPECTED RESULT	The account is not created. Error message will be displayed: “Please fill out this field” in last name field.
		
Test case 11
	TITLE	Registration process with valid value only for first name and first mandatory checkbox
	PRECONDITIONS	Sign up page was displayed
	STEPS	The user enters valid value for first name only and checks the first mandatory checkbox
The user clicks on “Save” button
	EXPECTED RESULT	The account is not created. Error message will be displayed: “Please fill out this field” in last name field.
		
Test case 12
	TITLE	Registration process with valid value only for first name and second mandatory checkbox
	PRECONDITIONS	Sign up page was displayed
	STEPS	The user enters valid value for first name only and checks the second mandatory checkbox
The user clicks on “Save” button
	EXPECTED RESULT	The account is not created. Error message will be displayed: “Please fill out this field” in last name field.
		
Test case 13
	TITLE	Registration process with valid value only for first name and both mandatory checkbox
	PRECONDITIONS	Sign up page was displayed
	STEPS	The user enters valid value for first name only and checks both mandatory checkboxes.
The user clicks on “Save” button
	EXPECTED RESULT	The account is not created. Error message will be displayed: “Please fill out this field” in last name field.
		
Test case 14
	TITLE	Registration process with valid value only for last name and email
	PRECONDITIONS	Sign up page was displayed
	STEPS	The user enters valid value for last name and email only
The user clicks on “Save” button
	EXPECTED RESULT	The account is not created. Error message will be displayed: “Please fill out this field” in first name field.
		
Test case 15
	TITLE	Registration process with valid value only for last name and password
	PRECONDITIONS	Sign up page was displayed
	STEPS	The user enters valid value for last name and password only
The user clicks on “Save” button
	EXPECTED RESULT	The account is not created. Error message will be displayed: “Please fill out this field” in first name field.
		
Test case 16
	TITLE	Registration process with valid value only for last name and first mandatory checkbox
	PRECONDITIONS	Sign up page was displayed
	STEPS	The user enters valid value for last name and password only and checks the first mandatory checkbox
The user clicks on “Save” button
	EXPECTED RESULT	The account is not created. Error message will be displayed: “Please fill out this field” in first name field.
		
Test case 17
	TITLE	Registration process with valid value only for last name and second mandatory checkbox
	PRECONDITIONS	Sign up page was displayed
	STEPS	The user enters valid value for last name and password only and checks the second mandatory checkbox
The user clicks on “Save” button
	EXPECTED RESULT	The account is not created. Error message will be displayed: “Please fill out this field” in first name field.
		
Test case 18
	TITLE	Registration process with valid value only for last name and both mandatory checkboxes
	PRECONDITIONS	Sign up page was displayed
	STEPS	The user enters valid value for last name and password only and checks both mandatory checkboxes
The user clicks on “Save” button
	EXPECTED RESULT	The account is not created. Error message will be displayed: “Please fill out this field” in first name field.
		
Test case 19
	TITLE	Registration process with valid value only for email and password
	PRECONDITIONS	Sign up page was displayed
	STEPS	The user enters valid value for email and password only
The user clicks on “Save” button
	EXPECTED RESULT	The account is not created. Error message will be displayed: “Please fill out this field” in first name field.
		
Test case 20
	TITLE	Registration process with valid value only email and first mandatory checkbox
	PRECONDITIONS	Sign up page was displayed
	STEPS	The user enters valid value for email only and checks the first mandatory checkbox
The user clicks on “Save” button
	EXPECTED RESULT	The account is not created. Error message will be displayed: “Please fill out this field” in first name field.
		
Test case 21
	TITLE	Registration process with valid value only for email and second mandatory checkbox
	PRECONDITIONS	Sign up page was displayed
	STEPS	The user enters valid value for email only and checks the second mandatory checkbox
The user clicks on “Save” button
	EXPECTED RESULT	The account is not created. Error message will be displayed: “Please fill out this field” in first name field.
		
Test case 22
	TITLE	Registration process with valid value only for email and both mandatory checkboxes
	PRECONDITIONS	Sign up page was displayed
	STEPS	The user enters valid value for email only and checks both mandatory checkboxes
The user clicks on “Save” button
	EXPECTED RESULT	The account is not created. Error message will be displayed: “Please fill out this field” in first name field.
		
Test case 23
	TITLE	Registration process with valid value password only and first mandatory checkbox
	PRECONDITIONS	Sign up page was displayed
	STEPS	The user enters valid value for password only and checks only the first mandatory checkbox
The user clicks on “Save” button
	EXPECTED RESULT	The account is not created. Error message will be displayed: “Please fill out this field” in first name field.
		
Test case 24
	TITLE	Registration process with valid value password only and second mandatory checkbox
	PRECONDITIONS	Sign up page was displayed
	STEPS	The user enters valid value for password only and checks only the second mandatory checkbox
The user clicks on “Save” button
	EXPECTED RESULT	The account is not created. Error message will be displayed: “Please fill out this field” in first name field.
		
Test case 25
	TITLE	Registration process with valid value password only and both mandatory checkboxes
	PRECONDITIONS	Sign up page was displayed
	STEPS	The user enters valid value for password only and checks both mandatory checkboxes
The user clicks on “Save” button
	EXPECTED RESULT	The account is not created. Error message will be displayed: “Please fill out this field” in first name field.
		
Test case 26
	TITLE	Registration process with invalid values and checked first mandatory checkbox 
	PRECONDITIONS	Sign up page was displayed
	STEPS	The user enters invalid values for password only and checks only the first mandatory checkbox
The user clicks on “Save” button
	EXPECTED RESULT	The account is not created. Error message will be displayed: “Please fill out this field” in first name field.
		
Test case 27
	TITLE	Registration process with invalid values and checked second mandatory checkbox 
	PRECONDITIONS	Sign up page was displayed
	STEPS	The user enters invalid values for all fields but checks only the second checkbox
The user clicks on “Save” button
	EXPECTED RESULT	The account is not created. Error message will be displayed: “Please fill out this field” in first name field.
		
Test case 28
	TITLE	Registration process with invalid values and checked both mandatory checkboxes
	PRECONDITIONS	Sign up page was displayed
	STEPS	The user enters invalid values for all mandatory fields, but checks both mandatory checkboxes
The user clicks on “Save” button
	EXPECTED RESULT	The account is not created. Error message will be displayed: “Please fill out this field” in first name field
		
Test case 29
	TITLE	Register process with empty fields
	PRECONDITIONS	Sign up page was displayed
	STEPS	The user clicks on “Save” button
	EXPECTED RESULT	The user is not logged in. Error message will be displayed: “Please fill out this field” in first name field

### 2.	Logging into account

![image](https://github.com/alinst24/manualTesting/assets/153013663/b3be08f9-3aca-4e68-9f5a-2986fdc042b6)


Test case 1
	TITLE	Login process with valid values for all fields
	PRECONDITIONS	A browser is displayed
	URL  https://tired-mass.demo.prestashop.com/en/ was accesed
	STEPS	The user clicks on “Sign in” from top page
	EXPECTED RESULT	A new page with the name "Log in to your account" will be displayed
	Login form will be displayed and contains: 
		- Email
        - Password


Test case 2
	TITLE	Login process with valid values for all fields
	PRECONDITIONS	Login page was displayed
	STEPS	The user fills with valid values both mandatory fields
The user clicks on “Sign in” button
	EXPECTED RESULT	The user gets logged in his account and main page is displayed
		
Test case 3
	TITLE	Login process with invalid values for all fields
	PRECONDITIONS	Login page was displayed
	STEPS	The user fills with invalid values both mandatory fields
The user clicks on “Sign in” button
	EXPECTED RESULT	The user does not gets logged in, and an "Authentication failed.” error appears
		
Test case 4
	TITLE	Login process with valid value for email only
	PRECONDITIONS	Login page was displayed
	STEPS	The user fills with valid value only email field
The user clicks on “Sign in” button
	EXPECTED RESULT	The user is not logged in. Error message will be displayed: “Please fill out this field” in password field
		
Test case 5
	TITLE	Login process with valid value for password only
	PRECONDITIONS	Login page was displayed
	STEPS	The user fills with valid value only password field
The user clicks on “Sign in” button
	EXPECTED RESULT	The user is not logged in. Error message will be displayed: “Please fill out this field” in email field
		
Test case 6
	TITLE	Login process with empty fields
	PRECONDITIONS	Login page was displayed
	STEPS	The user clicks on “Sign in” button
	EXPECTED RESULT	The user is not logged in. Error message will be displayed: “Please fill out this field” in email field
		
Test case 7
	TITLE	Login process with valid value for email field and invalid value for password field
	PRECONDITIONS	Login page was displayed
	STEPS	The user fills with valid value for email field and invalid value for password field
The user clicks on “Sign in” button
	EXPECTED RESULT	The user is not logged in. Error message will be displayed: “Please fill out this field” in password field
		
Test case 8
	TITLE	Login process with valid value for password field and invalid value for email field
	PRECONDITIONS	Login page was displayed
	STEPS	The user fills with valid value for password field and invalid value for email field
The user clicks on “Sign in” button
	EXPECTED RESULT	The user is not logged in. Error message will be displayed: “Please fill out this field” in email field

### 3.	Modifying “My account” details.

![image](https://github.com/alinst24/manualTesting/assets/153013663/449f37bb-e251-4b8d-8776-5dcf620bc497)


#### 3.1	Information

![image](https://github.com/alinst24/manualTesting/assets/153013663/ad0308df-147b-4a79-aba1-b96b2f5874ae)

Test case 1
	TITLE	Updating information with empty fields
	PRECONDITIONS	The user is logged in his account
The “personal information” page is displayed
	STEPS	The user changes the social title to “Mrs.” (Mr. being default)
The user clicks on “Save” button
	EXPECTED RESULT	The information will not be updated. Error message “Please fill out this field.” will be displayed in first name field
		
Test case 2
	TITLE	Updating information with valid values for all fields
	PRECONDITIONS	The user is logged in his account
The “personal information” page is displayed
	STEPS	The user changes the social title to “Mrs.” (Mr. being default)
The user fills with valid values all mandatory fields
The user clicks on “Save” button
	EXPECTED RESULT	The information will be updated. A message “Information succesfully updated” is displayed.
		
Test case 3
	TITLE	Updating information with valid value only for first name
	PRECONDITIONS	The user is logged in his account
The “personal information” page is displayed
	STEPS	The user changes the social title to “Mrs.” (Mr. being default)
The user fills with valid value first name field
The user clicks on “Save” button
	EXPECTED RESULT	The information will not be updated. Error message “Please fill out this field.” will be displayed in last name field
		
Test case 4
	TITLE	Updating information with valid value only for last name
	PRECONDITIONS	The user is logged in his account
The “personal information” page is displayed
	STEPS	The user changes the social title to “Mrs.” (Mr. being default)
The user fills with valid value last name field
The user clicks on “Save” button
	EXPECTED RESULT	The information will not be updated. Error message “Please fill out this field.” will be displayed in first name field
		
Test case 5
	TITLE	Updating information with valid value only for email
	PRECONDITIONS	The user is logged in his account
The “personal information” page is displayed
	STEPS	The user changes the social title to “Mrs.” (Mr. being default)
The user fills with valid value email field
The user clicks on “Save” button
	EXPECTED RESULT	The information will not be updated. Error message “Please fill out this field.” will be displayed in first name field
		
Test case 6
	TITLE	Updating information with valid value only for password
	PRECONDITIONS	The user is logged in his account
The “personal information” page is displayed
	STEPS	The user changes the social title to “Mrs.” (Mr. being default)
The user fills with valid value password field
The user clicks on “Save” button
	EXPECTED RESULT	The information will not be updated. Error message “Please fill out this field.” will be displayed in first name field
		
Test case 7
	TITLE	Updating information with first checkbox only
	PRECONDITIONS	The user is logged in his account
The “personal information” page is displayed
	STEPS	The user changes the social title to “Mrs.” (Mr. being default)
The user tick first checkbox
The user clicks on “Save” button
	EXPECTED RESULT	The information will not be updated. Error message “Please fill out this field.” will be displayed in first name field
		
Test case 8
	TITLE	Updating information with second checkbox only
	PRECONDITIONS	The user is logged in his account
The “personal information” page is displayed
	STEPS	The user changes the social title to “Mrs.” (Mr. being default)
The user tick second checkbox
The user clicks on “Save” button
	EXPECTED RESULT	The information will not be updated. Error message “Please fill out this field.” will be displayed in first name field
		
Test case 9
	TITLE	Updating information with both checkboxes only
	PRECONDITIONS	The user is logged in his account
The “personal information” page is displayed
	STEPS	The user changes the social title to “Mrs.” (Mr. being default)
The user ticks both checkboxes
The user clicks on “Save” button
	EXPECTED RESULT	The information will not be updated. Error message “Please fill out this field.” will be displayed in first name field

Test case 10
	TITLE	Updating information with first name and last name only
	PRECONDITIONS	The user is logged in his account
The “personal information” page is displayed
	STEPS	The user changes the social title to “Mrs.” (Mr. being default)
The user fills with valid values first name and last name
The user clicks on “Save” button
	EXPECTED RESULT	The information will not be updated. Error message “Please fill out this field.” will be displayed in emailfield
		
Test case 11
	TITLE	Updating information with first name and email only
	PRECONDITIONS	The user is logged in his account
The “personal information” page is displayed
	STEPS	The user changes the social title to “Mrs.” (Mr. being default)
The user fills with valid values first name and email
The user clicks on “Save” button
	EXPECTED RESULT	The information will not be updated. Error message “Please fill out this field.” will be displayed in last name field
		
Test case 12
	TITLE	Updating information with first name and password
	PRECONDITIONS	The user is logged in his account
The “personal information” page is displayed
	STEPS	The user changes the social title to “Mrs.” (Mr. being default)
The user fills with valid values first name and password
The user clicks on “Save” button
	EXPECTED RESULT	The information will not be updated. Error message “Please fill out this field.” will be displayed in last name field
		
Test case 13
	TITLE	Updating information with first name and first checkbox
	PRECONDITIONS	The user is logged in his account
The “personal information” page is displayed
	STEPS	The user changes the social title to “Mrs.” (Mr. being default)
The user fills with valid values first name and ticks first checkbox
The user clicks on “Save” button
	EXPECTED RESULT	The information will not be updated. Error message “Please fill out this field.” will be displayed in last name field
Test case 14
	TITLE	Updating information with first name and second checkbox
	PRECONDITIONS	The user is logged in his account
The “personal information” page is displayed
	STEPS	The user changes the social title to “Mrs.” (Mr. being default)
The user fills with valid values first name and ticks second checkbox
The user clicks on “Save” button
	EXPECTED RESULT	The information will not be updated. Error message “Please fill out this field.” will be displayed in last name field
		
Test case 15
	TITLE	Updating information with first name and both checkboxes
	PRECONDITIONS	The user is logged in his account
The “personal information” page is displayed
	STEPS	The user changes the social title to “Mrs.” (Mr. being default)
The user fills with valid values first name and ticks both checkboxes
The user clicks on “Save” button
	EXPECTED RESULT	The information will not be updated. Error message “Please fill out this field.” will be displayed in last name field
		
Test case 16
	TITLE	Updating information with last name and first checkbox
	PRECONDITIONS	The user is logged in his account
The “personal information” page is displayed
	STEPS	The user changes the social title to “Mrs.” (Mr. being default)
The user fills with valid values last name and ticks first checkbox
The user clicks on “Save” button
	EXPECTED RESULT	The information will not be updated. Error message “Please fill out this field.” will be displayed in first name field
		
Test case 17
	TITLE	Updating information with last name and second checkbox
	PRECONDITIONS	The user is logged in his account
The “personal information” page is displayed
	STEPS	The user changes the social title to “Mrs.” (Mr. being default)
The user fills with valid values last name and ticks second checkbox
The user clicks on “Save” button
	EXPECTED RESULT	The information will not be updated. Error message “Please fill out this field.” will be displayed in first name field
		
Test case 18
	TITLE	Updating information with last name and both checkboxes
	PRECONDITIONS	The user is logged in his account
The “personal information” page is displayed
	STEPS	The user changes the social title to “Mrs.” (Mr. being default)
The user fills with valid values last name and ticks both checkboxes
The user clicks on “Save” button
	EXPECTED RESULT	The information will not be updated. Error message “Please fill out this field.” will be displayed in first name field
		
Test case 19
	TITLE	Updating information with email and first checkbox
	PRECONDITIONS	The user is logged in his account
The “personal information” page is displayed
	STEPS	The user changes the social title to “Mrs.” (Mr. being default)
The user fills with valid values email and ticks first checkbox
The user clicks on “Save” button
	EXPECTED RESULT	The information will not be updated. Error message “Please fill out this field.” will be displayed in first name field
		
Test case 20
	TITLE	Updating information with email and second checkbox
	PRECONDITIONS	The user is logged in his account
The “personal information” page is displayed
	STEPS	The user changes the social title to “Mrs.” (Mr. being default)
The user fills with valid values email and ticks second checkbox
The user clicks on “Save” button
	EXPECTED RESULT	The information will not be updated. Error message “Please fill out this field.” will be displayed in first name field
		
Test case 21
	TITLE	Updating information with email and both checkboxes
	PRECONDITIONS	The user is logged in his account
The “personal information” page is displayed
	STEPS	The user changes the social title to “Mrs.” (Mr. being default)
The user fills with valid values email and ticks both checkboxes
The user clicks on “Save” button
	EXPECTED RESULT	The information will not be updated. Error message “Please fill out this field.” will be displayed in first name field
		
Test case 22
	TITLE	Updating information with password and first checkbox
	PRECONDITIONS	The user is logged in his account
The “personal information” page is displayed
	STEPS	The user changes the social title to “Mrs.” (Mr. being default)
The user fills with valid values password and ticks first checkbox
The user clicks on “Save” button
	EXPECTED RESULT	The information will not be updated. Error message “Please fill out this field.” will be displayed in first name field
		
Test case 23
	TITLE	Updating information with password and second checkbox
	PRECONDITIONS	The user is logged in his account
The “personal information” page is displayed
	STEPS	The user changes the social title to “Mrs.” (Mr. being default)
The user fills with valid values password and ticks second checkbox
The user clicks on “Save” button
	EXPECTED RESULT	The information will not be updated. Error message “Please fill out this field.” will be displayed in first name field
		
Test case 24
	TITLE	Updating information with password and both checkboxes
	PRECONDITIONS	The user is logged in his account
The “personal information” page is displayed
	STEPS	The user changes the social title to “Mrs.” (Mr. being default)
The user fills with valid values password and ticks both checkboxes
The user clicks on “Save” button
	EXPECTED RESULT	The information will not be updated. Error message “Please fill out this field.” will be displayed in first name field
		
Test case 25
	TITLE	Updating information with invalid values for first name and valid values for the rest of fields
	PRECONDITIONS	The user is logged in his account
The “personal information” page is displayed
	STEPS	The user fills the first name field with invalid value
The user fills with valid values the rest of mandatory fields
The user clicks on “Save” button
	EXPECTED RESULT	The information will not be updated. Error message “Could not update your information,please check your data.” is displayed
		
Test case 26
	TITLE	Updating information with invalid values for last name and valid values for the rest of fields
	PRECONDITIONS	The user is logged in his account
The “personal information” page is displayed
	STEPS	The user fills the last name field with invalid value
The user fills with valid values the rest of mandatory fields
The user clicks on “Save” button
	EXPECTED RESULT	The information will not be updated. Error message “Could not update your information,please check your data.” is displayed
		
Test case 27
	TITLE	Updating information with invalid values for password and valid values for the rest of fields
	PRECONDITIONS	The user is logged in his account
The “personal information” page is displayed
	STEPS	The user fills the password field with invalid value
The user fills with valid values the rest of mandatory fields
The user clicks on “Save” button
	EXPECTED RESULT	The information will not be updated. Error message “Could not update your information,please check your data.” is displayed



**BUG**
Test case 28
	TITLE	Updating information with invalid values for email and valid values for the rest of fields
	PRECONDITIONS	The user is logged in his account
The “personal information” page is displayed
	STEPS	The user fills the email field with invalid value (e.g. ~!`21sqas@yahoo.com)
The user fills with valid values the rest of mandatory fields
The user clicks on “Save” button
	EXPECTED RESULT	The information will not be updated. Error message “Could not update your information,please check your data.” is displayed
	ACTUAL RESULT	Information is updated and message “Information successfully updated.” is displayed
		
Test case 29
	TITLE	Updating password information with valid values
	PRECONDITIONS	The user is logged in his account
The “personal information” page is displayed
	STEPS	The user fills the password field with valid value
The user fills with valid values the rest of mandatory fields
The user fills with valid value new password field
The user clicks on “Save” button
	EXPECTED RESULT	The information is updated and the account has a new password
		
**BUG**
Test case 30
	TITLE	Updating password information with invalid value for new password
	PRECONDITIONS	The user is logged in his account
The “personal information” page is displayed
	STEPS	The user fills the password field with valid value
The user fills with valid values the rest of mandatory fields
The user fills with invalid value new password field
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and error message “Could not update your information,please check your data.” is displayed
	ACTUAL RESULT	The information is updated and the account has a new password
		
Test case 31
	TITLE	Updating password information with invalid values
	PRECONDITIONS	The user is logged in his account
The “personal information” page is displayed
	STEPS	The user fills the password field with invalid value
The user fills with valid values the rest of mandatory fields
The user fills with invalid invalue new password field
The user clicks on “Save” button
	EXPECTED RESULT	The information will not be updated. Error message “Could not update your information,please check your data.” is displayed
		
Test case 32
	TITLE	Updating password information with invalid value for password and valid value for new password
	PRECONDITIONS	The user is logged in his account
The “personal information” page is displayed
	STEPS	The user fills the password field with invalid value
The user fills with valid values the rest of mandatory fields
The user fills with valid invalue new password field
The user clicks on “Save” button
	EXPECTED RESULT	The information will not be updated. Error message “Could not update your information,please check your data.” is displayed

#### 3.2	New address

![image](https://github.com/alinst24/manualTesting/assets/153013663/e116cde6-e12f-4dea-a9d3-cb183df05408)


Test case 1
	TITLE	Updating new address with valid values
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user fills all mandatory fields with valid values
The user clicks on “Save” button
	EXPECTED RESULT	The information is updated and message “Address succsesfully updated.”
		
Test case 2
	TITLE	Updating new address with empty values
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user leaves empty all mandatory fields
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and message “Please fill out this field.” is displayed in first name field
		
Test case 3
	TITLE	Updating new address with valid value for first name only
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user fills first name field with valid value
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and message “Please fill out this field.” is displayed in last name field
		
Test case 4
	TITLE	Updating new address with valid value for last name only
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user fills last name field with valid value
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and message “Please fill out this field.” is displayed in first name field
		
Test case 5
	TITLE	Updating new address with valid value for address only
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user fills address field with valid value
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and message “Please fill out this field.” is displayed in first name field
		
Test case 6
	TITLE	Updating new address with valid value for zip/postal code only
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user fills zip/postal code field with valid value
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and message “Please fill out this field.” is displayed in first name field
		
Test case 7
	TITLE	Updating new address with valid value for city only
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user fills city field with valid value
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and message “Please fill out this field.” is displayed in first name field
		
Test case 8
	TITLE	Updating new address with valid value for country only
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user chooses a valid value for country field
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and message “Please fill out this field.” is displayed in first name field
		
Test case 9
	TITLE	Updating new address with valid value for first name and last name only
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user fills first name and last name fields with valid values
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and message “Please fill out this field.” is displayed in address field
		
Test case 10
	TITLE	Updating new address with valid value for first name and address only
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user fills first name and address fields with valid values
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and message “Please fill out this field.” is displayed in last name field
		
Test case 11
	TITLE	Updating new address with valid value for first name and zip/postal code only
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user fills first name and zip/postal code fields with valid values
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and message “Please fill out this field.” is displayed in last name field
		
Test case 12
	TITLE	Updating new address with valid value for first name and city only
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user fills first name and city fields with valid values
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and message “Please fill out this field.” is displayed in last name field
		
Test case 13
	TITLE	Updating new address with valid value for first name and country only
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user fills first name and country fields with valid values
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and message “Please fill out this field.” is displayed in last name field
		
Test case 14
	TITLE	Updating new address with valid value for last name and address only
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user fills last name and address fields with valid values
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and message “Please fill out this field.” is displayed in first name field
		
Test case 15
	TITLE	Updating new address with valid value for address and zip/postal code only
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user fills address and zip/postal code fields with valid values
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and message “Please fill out this field.” is displayed in first name field
		
Test case 16
	TITLE	Updating new address with valid value for address and city only
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user fills address and city fields with valid values
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and message “Please fill out this field.” is displayed in first name field
		
Test case 17
	TITLE	Updating new address with valid value for address and country only
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user fills address and country fields with valid values
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and message “Please fill out this field.” is displayed in first name field
		
Test case 17
	TITLE	Updating new address with valid value for zip/postal code and city only
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user fills zip/postal code and city fields with valid values
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and message “Please fill out this field.” is displayed in first name field
		
Test case 18
	TITLE	Updating new address with valid value for zip/postal code and country only
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user fills zip/postal code and country fields with valid values
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and message “Please fill out this field.” is displayed in first name field
		
Test case 19
	TITLE	Updating new address with valid value for zip/postal code and city only
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user fills zip/postal code and city fields with valid values
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and message “Please fill out this field.” is displayed in first name field
		
Test case 20
	TITLE	Updating new address with valid values for first name,last name and address only
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user fills first name, last name and address fields with valid values
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and message “Please fill out this field.” is displayed in zip/postal code field
		
Test case 21
	TITLE	Updating new address with valid values for first name,last name and zip/postal code only
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user fills first name, last name and zip/postal code fields with valid values
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and message “Please fill out this field.” is displayed in city field
		
Test case 22
	TITLE	Updating new address with valid values for first name,last name and city only
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user fills first name, last name and city fields with valid values
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and message “Please fill out this field.” is displayed in address field
		
Test case 23
	TITLE	Updating new address with valid values for first name,last name and country only
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user fills first name, last name and country fields with valid values
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and message “Please fill out this field.” is displayed in address field
		
Test case 24
	TITLE	Updating new address with valid values for first name,last name, address and zip/postal code only
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user fills first name, last name, address and zip/postal code fields with valid values
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and message “Please fill out this field.” is displayed in city field
		
Test case 25
	TITLE	Updating new address with valid values for first name,last name, address and city only
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user fills first name, last name, address and city fields with valid values
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and message “Please fill out this field.” is displayed in zip/postal code field
		
Test case 26
	TITLE	Updating new address with valid values for first name,last name address and country only
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user fills first name, last name, address and country fields with valid values
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and message “Please fill out this field.” is displayed in zip/postal code field
		
Test case 27
	TITLE	Updating new address with valid values for first name,last name,address,zip/postal code only
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user fills first name, last name, address ,zip/postal and city code fields with valid values
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and message “Please fill out this field.” is displayed in country field
		
Test case 28
	TITLE	Updating new address with invalid first name
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user fills first name with invalid values and valid values for all the rest of mandatory fields
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and message “Please fix error below.” and “Invalid name” message is displayed
		
Test case 28
	TITLE	Updating new address with invalid last name
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user fills last name with invalid values and valid values for all the rest of mandatory fields
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and message “Please fix error below.” and “Invalid name” message is displayed
		
Test case 29
	TITLE	Updating new address with invalid zip/postal code
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user fills zip/postal code with invalid values and valid values for the rest of mandatory fields
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and message “Invalid postcode – should be look like ‘NNNNN’” is displayed
		
Test case 30
	TITLE	Updating new address with invalid address
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user fills address field with invalid value and the rest of the mandatory fields with valid values
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and message “Invalid format” is displayed
		
**BUG**
Test case
31
	TITLE	Updating new address with invalid city
	PRECONDITIONS	The user is logged in his account
The “new address” page is displayed
	STEPS	The user fills the city field with invalid values and valid values for the rest of mandatory fields
The user clicks on “Save” button
	EXPECTED RESULT	The information is not updated and message “Please fix error below.” and “Invalid city” message is displayed
	ACTUAL RESULT	Information is updated.














#### 3.3	Order history

![image](https://github.com/alinst24/manualTesting/assets/153013663/d83c8a97-f015-4544-a330-9b1939e5f64f)

Test case 1
	TITLE	Details button in order history page
	PRECONDITIONS	The user is logged in his account and made a product checkout
The “order history” page is displayed
	STEPS	The user clicks on “Details” button
	EXPECTED RESULT	A new page with the name “Order details” is displayed

		
Test case 2
	TITLE	Reorder button in order history page
	PRECONDITIONS	The user is logged in his account and made a product checkout
The “order history” page is displayed
	STEPS	The user clicks on “Reorder” button
	EXPECTED RESULT	A new page is displayed where user can reorder the product

		
**BUG**
Test case 3
	TITLE	Adding message to order with invalid product selected
	PRECONDITIONS	The user is logged in his account and made a product checkout
The “order history” page is displayed
	STEPS	The user clicks on “Details” button 
The user scrolls down to “add message” section
The user enters a message in textbox then clicks “Send”
	EXPECTED RESULT	The update should not be done due to not choosing product
	ACTUAL RESULT	Information is updated and message “Message successfully sent” is displayed



Test case 4
	TITLE	Adding message to order with valid product
	PRECONDITIONS	The user is logged in his account and made a product checkout
The “order history” page is displayed
	STEPS	The user clicks on “Details” button 
The user scrolls down to “add message” section
The user selects a product
The user enters a message in textbox then clicks “Send”
	EXPECTED RESULT	Information is updated and message “Message succsessfully sent” is displayed

		
Test case 5
	TITLE	Adding empty message to order
	PRECONDITIONS	The user is logged in his account and made a product checkout
The “order history” page is displayed
	STEPS	The user clicks on “Details” button 
The user scrolls down to “add message” section
The user clicks “Send”
	EXPECTED RESULT	Information is not updated and message “The message cannot be blank.” is displayed





#### 3.4	My wishlists

![image](https://github.com/alinst24/manualTesting/assets/153013663/aa978fd8-a69e-49a4-b09e-a5b4252d0dc0)


Test case 1
	TITLE	Creating new list button
	PRECONDITIONS	The user is logged in his account
The “My wishlists” page is displayed
	STEPS	The user clicks on “Create new list” button 
	EXPECTED RESULT	A form is displayed where user can name a new wishlist

		
Test case 2
	TITLE	Creating new wishlist
	PRECONDITIONS	The user is logged in his account
The “My wishlists” page is displayed
The user clicks on “Create new list” button
	STEPS	The user enters a name for the wishlist
The user clicks on “Create wishlist” 
	EXPECTED RESULT	A new wishlist is created and displayed

		
Test case 3
	TITLE	Renaming wishlist button
	PRECONDITIONS	The user is logged in his account
The “My wishlists” page is displayed
The user has created a wishlist
	STEPS	The user clicks on “Rename”. 
	EXPECTED RESULT	A form is displayed where user can rename the wishlist
		
Test case 3
	TITLE	Renaming wishlist
	PRECONDITIONS	The user is logged in his account
The “My wishlists” page is displayed
The user has created a wishlist
The user clicks on “Rename”.
	STEPS	The user enters a value for wishlist name
The user clicks on “Rename wishlist”
	EXPECTED RESULT	The wishlist name is updated and message “List has been renamed” is displayed
		
Test case 5
	TITLE	Sharing wishlist button
	PRECONDITIONS	The user is logged in his account
The “My wishlists” page is displayed
The user has created a wishlist
	STEPS	The user clicks on “Share” button 
	EXPECTED RESULT	A form is displayed where user can share the link of wishlist

		
Test case 6
	TITLE	Sharing wishlist
	PRECONDITIONS	The user is logged in his account
The “My wishlists” page is displayed
The user has created a wishlist
The user clicks on “Share” button
	STEPS	The user clicks on “Copy text” button
	EXPECTED RESULT	The link from wishlist is copied and message “Share link copied!” is displayed

		
Test case 7
	TITLE	Delete wishlist button
	PRECONDITIONS	The user is logged in his account
The “My wishlists” page is displayed
The user has created a wishlist
	STEPS	The user clicks on trash bin icon
	EXPECTED RESULT	A form is displayed where user can delete the wishlist

		
Test case 8
	TITLE	Deleting wishlist
	PRECONDITIONS	The user is logged in his account
The “My wishlists” page is displayed
The user has created a wishlist
The user clicks on trash bin icon
	STEPS	The user clicks on “Delete” button
	EXPECTED RESULT	The wishlist is deleted and message “List has been removed” is displayed

		
Test case 7
	TITLE	Viewing the wishlist
	PRECONDITIONS	The user is logged in his account
The “My wishlists” page is displayed
The user has created a wishlist
	STEPS	The user clicks on wishlist
	EXPECTED RESULT	The products from wishlist are being shown

		
Test case 8
	TITLE	Adding to cart item from wishlist
	PRECONDITIONS	The user is logged in his account
The “My wishlists” page is displayed
The user has created a wishlist
The user clicks on “Share” button
	STEPS	The user clicks on “Copy text” button
	EXPECTED RESULT	The link from wishlist is copied and message “Share link copied!” is displayed

		
Test case 9
	TITLE	Sorting the wishlist by name Z to A
	PRECONDITIONS	The user is logged in his account
The “My wishlists” page is displayed
The user has created a wishlist with more products
The user clicks on wishlist
	STEPS	The user clicks on “Sort by” button and selects “Name Z to A”
	EXPECTED RESULT	The wishlist is sorted by selected order
		
Test case 10
	TITLE	Sorting the wishlist by name A to Z
	PRECONDITIONS	The user is logged in his account
The “My wishlists” page is displayed
The user has created a wishlist with more products
The user clicks on wishlist
	STEPS	The user clicks on “Sort by” button and selects “Name A to Z”
	EXPECTED RESULT	The wishlist is sorted by selected order
		
Test case 11
	TITLE	Sorting the wishlist by relevance
	PRECONDITIONS	The user is logged in his account
The “My wishlists” page is displayed
The user has created a wishlist with more products
The user clicks on wishlist
	STEPS	The user clicks on “Sort by” button and selects “relevance”
	EXPECTED RESULT	The wishlist is sorted by selected order
		
Test case 12
	TITLE	Sorting the wishlist by price,low to high
	PRECONDITIONS	The user is logged in his account
The “My wishlists” page is displayed
The user has created a wishlist with more products
The user clicks on wishlist
	STEPS	The user clicks on “Sort by” button and selects “price, low to high”
	EXPECTED RESULT	The wishlist is sorted by selected order
		
Test case 12
	TITLE	Sorting the wishlist by price,high to low
	PRECONDITIONS	The user is logged in his account
The “My wishlists” page is displayed
The user has created a wishlist with more products
The user clicks on wishlist
	STEPS	The user clicks on “Sort by” button and selects “price, high to low”
	EXPECTED RESULT	The wishlist is sorted by selected order

#### 3.5	GDPR – PERSONAL DATA

![image](https://github.com/alinst24/manualTesting/assets/153013663/fab145af-d2d6-496f-9e86-8491b265a390)


Test case 1
	TITLE	Getting data to pdf
	PRECONDITIONS	The user is logged in his account
The “GDPR – Personal data” page is displayed
	STEPS	The user clicks on “Get my data to pdf” button
	EXPECTED RESULT	The user gets to download GDPR data in .pdf format
		
Test case 2
	TITLE	Getting data to csv
	PRECONDITIONS	The user is logged in his account
The “GDPR – Personal data” page is displayed
	STEPS	The user clicks on “Get my data to csv” button
	EXPECTED RESULT	The user gets to download GDPR data in .word format






### 4.	Product page

![image](https://github.com/alinst24/manualTesting/assets/153013663/eb557425-262f-4166-951c-9cbe841f0d76)


Test case 1
	TITLE	Adding a product to cart
	PRECONDITIONS	The user is logged in his account
The product page is displayed
	STEPS	The user clicks on “Add to cart” button
	EXPECTED RESULT	The product is added to cart
		
Test case 2
	TITLE	Adding another product to cart
	PRECONDITIONS	The user is logged in his account
The product page is displayed
	STEPS	The user clicks on “Add to cart” button
	EXPECTED RESULT	The product is added to cart
		
Test case 3
	TITLE	Adding product with different item type to cart
	PRECONDITIONS	The user is logged in his account
The product page is displayed
	STEPS	The user clicks on product type
The user chooses another product type
The user clicks on “Add to cart” button
	EXPECTED RESULT	The product is added to cart with specified type
		
Test case 4
	TITLE	Editing quantity of a product and adding to cart
	PRECONDITIONS	The user is logged in his account
The product page is displayed
	STEPS	The user clicks on upside arrow where quantity is located
The user clicks on “Add to cart” button
	EXPECTED RESULT	The product is added to cart with specified quantity
		
Test case 5
	TITLE	Sharing product to facebook
	PRECONDITIONS	The user is logged in his account
The product page is displayed
	STEPS	The user clicks on facebook icon
	EXPECTED RESULT	A new page is displayed where user can share to facebook the product
		
Test case 6
	TITLE	Sharing product to twitter
	PRECONDITIONS	The user is logged in his account
The product page is displayed
	STEPS	The user clicks on twitter icon
	EXPECTED RESULT	A new page is displayed where user can share to twitter the product
		
Test case 7
	TITLE	Sharing product to pinterest
	PRECONDITIONS	The user is logged in his account
The product page is displayed
	STEPS	The user clicks on pinterest icon
	EXPECTED RESULT	A new page is displayed where user can share to twitter the product
		
Test case 8
	TITLE	Review of a product
	PRECONDITIONS	The user is logged in his account
The product page is displayed
	STEPS	The user clicks on “Write your review” button
	EXPECTED RESULT	A form is displayed where user can write a review about a product



Test case 9
	TITLE	Writing a review of a product
	PRECONDITIONS	The user is logged in his account
The product page is displayed
The user clicks on “Write your review” button
	STEPS	The user fills mandatory fields
The user clicks on “Send” button
	EXPECTED RESULT	The review is sent to be approved by a moderator








### 5.	Proceeding to checkout

![image](https://github.com/alinst24/manualTesting/assets/153013663/008be2f0-4504-4562-aec3-2bbdf708cc0b)


Test case 1
	TITLE	Proceeding to checkout
	PRECONDITIONS	The user is logged in his account
The user has at least one item in shopping cart
The shopping cart page is displayed
	STEPS	The user clicks on proceed to checkout
	EXPECTED RESULT	Addresses page is displayed.
		
Test case 2
	TITLE	Proceeding to checkout through addresses
	PRECONDITIONS	The user is logged in his account
The user has at least one item in shopping cart
The user proceeds to checkout
The addresses page is displayed
	STEPS	The user selects an address
The user clicks “Continue”
	EXPECTED RESULT	Shopping method page is displayed
		
Test case 3
	TITLE	Proceeding to checkout through shipping method
	PRECONDITIONS	The user is logged in his account
The user has at least one item in shopping cart
The user proceds to checkout
The user proceeds through addresses
The user proceeds to shipping method
	STEPS	The user selects the preferred shipping method
The user clicks on “Continue”
	EXPECTED RESULT	Shopping method page is displayed
		
Test case 4
	TITLE	Proceeding to checkout through payment
	PRECONDITIONS	The user is logged in his account
The user has at least one item in shopping cart
The user proceds to checkout
The user proceeds through addresses
The user proceeds through shipping method
The user proceeds to payment
	STEPS	The user selects the preferred payment method
The user ticks the checkbox
The user clicks on “Place order” button
	EXPECTED RESULT	The order is placed and the message “Your order is confirmed “ is displayed

