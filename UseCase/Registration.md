##Version: 1.0

##Summary: New user registers an account

##Actors: Visitor

##Preconditions:

1. access registration page

##Scenario:

1. the visitor enters a user name
2. the visitor enters a password
3. the visitor enters the verification password
4. the visitor clicks on the submit button

##Alternative Scenario:

[the chosen username already exists]

1. the system displays an error message the user already exists
2. continue with 1

[password does not match verification password]

1. the system displays error passwords do not match
2. continue with 2

##Postconditions:

1. the visitor has a valid user session
2. the home page is shown 
