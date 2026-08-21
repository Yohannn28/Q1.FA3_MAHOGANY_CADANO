# Problem 1
## Password
- Enter a password 8 - 15 character long.

## Sample
```
enter password: StrongPW123
Password accepted
```
## Psuedocode

START

INPUT password

WHILE password length is less than 8 OR password length is greater than 15
    OUTPUT "Password must be between 8 and 15 characters long"
    INPUT password
END WHILE

OUTPUT "Password accepted"

# Problem 2

## Loan requirement checker
- checks if you have requirements for loan

## Sample
```
credit score: 850
annual income: 40000
years at current job: 3
Loan accepted
```

## Psuedocode
START

INPUT credit score
INPUT rannual income
INPUT years at current job

IF credit score is greater than or equal to 700
   AND annual income is greater than or equal to 35000
   AND years at current job is greater than or equal to 2
THEN
    OUTPUT "Loan accepted"
ELSE
    OUTPUT "Loan denied"
END IF

END
## 
- Author: Cadano, Yohan Mikael C.
- Section: 8 - Mahogany

