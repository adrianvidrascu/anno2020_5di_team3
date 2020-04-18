# Test Case Specification For Team 3

10/04/2020





#### Table of contents:

**1 Introduction..........................................................................................................................4**

**2 Test Cases: Android APPLICATION......................................................................................4**

**3 Test Cases: Proxy SERVER.....................................................................................................6**



Revision History:

| **Version** | **Date**   | **Name**     | **Description**                            |
| ----------- | ---------- | ------------ | ------------------------------------------ |
| 1           | 10/03/2020 | Pavan Andrea | Initial Document  and updated Test Cases 2 |
| 2           | 10/04/2020 | Pavan Andrea | Updated Test Cases 3                       |





### 1. Introduction

This document provides the test cases to be carried out for the Roo Balance Application. Each item to be tested is represented by an individual test case. Each case details the input and expected outputs.



### 2. Test Cases: Android Application



| Test ID          | 2.1                                                          |
| ---------------- | ------------------------------------------------------------ |
| Title            | Correct  Login                                               |
| Feature          | Login  to sf-agricolture.com with SF-Agricolture App         |
| Objective        | Confirm  that proper user id an password yields access to the website as expected. |
| Setup            | Android  device or simulator has SF-Agricolture application ready to run. |
| Test Data        | Login information User Email = admin@sf-agricolture.com Password = agricoltureAdmin |
| Test Actions     | 1. Start SF-Agricolture App application                                                                                                       2. Select View Account option                                                                                                               3. Enter login information |
| Expected Results | System  displays account balance with option to logoff. Account balance should match that found on  the database |



| Test ID          | 2.2                                                          |
| ---------------- | ------------------------------------------------------------ |
| Title            | Incorrect  Password                                          |
| Feature          | Login  to sf-agricolture.com with SF-Agricolture App         |
| Objective        | Confirm  that valid user id with an invalid password denies access to the website  without leaving the user stranded. |
| Setup            | Android  device or simulator has SF-Agricolture application ready to run. |
| Test Data        | Correct  user e-mail, incorrect password  User Email = admin@sf-agricolture.com  Password = password |
| Test Actions     | 1.  Start SF-Agricolture App application  2. Select View Account option  3. Enter invalid login information |
| Expected Results | System  displays error message with option to try again.     |



| Test ID          | 2.3                                                          |
| ---------------- | ------------------------------------------------------------ |
| Title            | Incorrect  User E-Mail                                       |
| Feature          | Login  to sf-agricolture.com with SF-Agricolture App         |
| Objective        | Confirm  that invalid user id denies access to the website without leaving the user  stranded. |
| Setup            | Android  device or simulator has SF-Agricolture application ready to run. |
| Test Data        | Incorrect  user e-mail, incorrect password  User Email = [l](mailto:cdbpc@umkc.edu)ogin@umkc.edu  Password = password |
| Test Actions     | 1.  Start SF-Agricolture App application  2. Select View Account option  3. Enter invalid login information |
| Expected Results | System  displays error message with option to try again.     |

 

| Test ID          | 2.4                                                          |
| ---------------- | ------------------------------------------------------------ |
| Title            | Select  Option View Transactions                             |
| Feature          | Display  recent SF-Agricolture account transactions.         |
| Objective        | Confirm  that recent transactions are displayed properly.    |
| Setup            | Android  device or simulator has SF-Agricolture application ready to run. |
| Test Data        | Login information User Email = admin@sf-agricolture.com Password = agricoltureAdmin |
| Test Actions     | 1.  Start SF-Agricolture App application  2. Select View Account option  3. Enter invalid login information |
| Expected Results | System  displays recent transactions legibly with option to logoff. Recent transactions should match that found  on the database |

 

### 3.  Test Cases: Proxy Server

 

| Test ID          | 3.1                                                          |
| ---------------- | ------------------------------------------------------------ |
| Title            | Correct  Login                                               |
| Feature          | Login  to sf-agricolture.com via proxy server                |
| Objective        | Confirm  that proper user id an password yields access to the website as expected. |
| Setup            | Access  to internet:   http://206.123.75.42:7070/post.html   https://206.123.75.42:7071/post.html |
| Test Data        | Login information User Email = admin@sf-agricolture.com Password = agricoltureAdmin |
| Test Actions     | 1.  Go to proxy server http site defined in setup.  2. Enter correct login information  3. Press submit |
| Expected Results | Site  displays numeric balance for account.   Numeric balance matches that from database |

 

| Test ID          | 3.2                                                          |
| ---------------- | ------------------------------------------------------------ |
| Title            | Incorrect  Password                                          |
| Feature          | Login  to sf-agricolture.com via proxy server                |
| Objective        | Confirm  that invalid password denies access to the website and returns an error. |
| Setup            | Access  to internet:   http://206.123.75.42:7070/post.html   https://206.123.75.42:7071/post.html |
| Test Data        | Login  information  User Email = admin@sf-agricolture.com  Password = password |
| Test Actions     | 1.  Go to proxy server http site defined in setup.  2. Enter login information as defined  in test data  3. Press submit  4. View page source. |
| Expected Results | Error  tag is evident in page source.                        |

 

| Test ID          | 3.3                                                          |
| ---------------- | ------------------------------------------------------------ |
| Title            | Incorrect  User E-Mail Login                                 |
| Feature          | Login  to sf-agricolture.com via proxy server                |
| Objective        | Confirm  that invalid user id denies access to the website and returns an error. |
| Setup            | Access  to internet:   http://206.123.75.42:7070/post.html   https://206.123.75.42:7071/post.html |
| Test Data        | Login  information  User Email = login@umkc.edu  Password = password |
| Test Actions     | 1.  Go to proxy server http site defined in setup.  2. Enter login information as defined  in test data  3. Press submit  4. View page source. |
| Expected Results | Error  tag is evident in page source.                        |

 

| Test ID          | 3.4                                                          |
| ---------------- | ------------------------------------------------------------ |
| Title            | View  Transactions via Proxy Server                          |
| Feature          | View  transaction history on sf-agricolture.com via proxy server |
| Objective        | Confirm  that transaction history is accessed and retrieved from the website  correctly. |
| Setup            | Access  to internet:   http://206.123.75.42:7070/post.html   https://206.123.75.42:7071/post.html |
| Test Data        | Login  information  User Email = email@emaul.edu Password = r00bucks |
| Test Actions     | 1.  Go to proxy server http site defined in setup.  2. Enter login information as defined  in test data  3. Press submit  4. View page source. |
| Expected Results | Recent  transactions are displayed and numbers match those on the database |

 