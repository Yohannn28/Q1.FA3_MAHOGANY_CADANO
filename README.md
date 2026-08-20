# Problem 1

## Code
```
# User enters password here
password = input("enter password: ")

# Check if password length is between 8 and 15 characters
while len(password) < 8 or len(password) > 15:

# if not then prompt user to enter a valid password
     password = input("Password must be between 8 and 15 characters long, enter a valid password: ")

# If password is valid, print "Password accepted"
else:
     print("Password accepted")
```

##Psuedocode

START

INPUT password

WHILE password length is less than 8 OR password length is greater than 15
    OUTPUT "Password must be between 8 and 15 characters long"
    INPUT password
END WHILE

OUTPUT "Password accepted"

# Problem 2

## Code
```
# user requirements for loan eligibility
cs = input("credit score: ")

an = input("annual income: ")

y =  input("years at current job: ")

# check eligibility
if int(cs) >= 700 and int(an) >= 35000 and int(y) >= 2:

     # if requirements are met, print "Loan accepted"
     print ("Loan accepted")
else:
     # if not, then print "Loan denied"
     print ("Loan denied")

```

##Psuedocode

Author: Cadano, Yohan Mikael C.
Section: 8 - Mahogany

