# PruebaChristianBallesteros
Prueba Tecnica QA

# Feature: Scenario for a user registration
# Preconditions: 

#The name field must contain at least 2 words

#The email must meet the standard of a valid email address

#The password must be at least 8 characters long, including an uppercase letter, a lowercase letter, a number and a special character.



#Given the user accesses the portal <url>

#Then user then completes the Full name field 

#And the user selects and completes the Email field 

#And the user selects and fills in the fields Password and Repeat your password

#Then user then displays a text confirming whether the passwords match

#And when the user completes all fields the <btn> is enabled

#Examples

|url 					                 |
|https://test-qa.inlaze.com/auth/sign-in | 
|btn                                     |
|Sign Up                                 |

#
#
#

# Feature: Scenario for user login
# Preconditions: The user must already be registered on the platform and must have login enabled.

#Given the user accesses the portal <url>

#Then user then completes the Email field 

#And user then completes the Password field

#When all fields are complete the <btn> is enabled and user select the <btn> and displays his or her user name

#And the user can view and select the option to log out

#Examples

|url 					                 |
|https://test-qa.inlaze.com/auth/sign-in | 
|btn                                     |
|Sign In                                 |
