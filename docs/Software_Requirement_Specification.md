# Software Requirements Specification for SF-Agriculture





#### Version 1.0 approved



#### Prepared by Devis Zuccolotto



#### 19/12/2019



### Table of Contents

**Table of Contents ......................................................................................................................................ii**

**Revision History.........................................................................................................................................ii**

**1\. Introduction .........................................................................................................................................1**

​	1.1 Purpose ................................................................................................................................................................1

​	1.2 Document Conventions......................................................................................................................................1

​	1.3 Intended Audience and Reading Suggestions.................................................................................................1

​	1.4 Product Scope......................................................................................................................................................1

​	1.5 References............................................................................................................................................................1

**2\. Overall Description..............................................................................................................................2**

​	2.1 Product Perspective............................................................................................................................................2

​	2.2 Product Functions...............................................................................................................................................2

​	2.3 User Classes and Characteristics.......................................................................................................................2

​	2.4 Operating Environment......................................................................................................................................2

​	2.5 Design and Implementation Constraints.........................................................................................................2

​	2.6 User Documentation...........................................................................................................................................2

**3\. External Interface Requirements.......................................................................................................3**

​	3.1 User Interfaces.....................................................................................................................................................3

​	3.2 Communications Interfaces...............................................................................................................................3

**4\. System Features...................................................................................................................................4**

​	4.1 System Feature 1.................................................................................................................................................4

​	4.2 System Feature 2 (and so on)............................................................................................................................4

​	5\. Other Nonfunctional Requirements...................................................................................................................4

​	Revision History

---------- ---------- ------------------------ -------------
  **Name**   **Date**   **Reason For Changes**   **Version**
                                                 
                                                 
---------- ---------- ------------------------ -------------

# Introduction

## Purpose 

SF-Agricultural is a web application helps farm owners with the choice of the best seed to cultivate during a season based no the place of the field and its size

## Product Scope

The owners of agricultural lands that will benefits from the web application will be able to manage their fields in a simpler and more orderly way, being able to make the calculation of the agricultural yield in an easy and fast way.

## References

Zuccolotto Devis e-mail:devis.zucco@gmail.com

Document: Vision Statement

Document: Software Management Plan

# Overall Description

## Product Perspective

This product come from the needed of a quick way to decide witch seed to plant on a specific field. Is a new self-contained product.

## Product Functions

The major function of this product are:

- managing of the field
- calculating the agricultural yield

## User Classes and Characteristics

The mojority of user that will use this product will be agricultural entrepreneurs, with knowing only a little how use a web page, nothing complicated with a medium privilege level. to use this product he will need only a computer with a internet connection and a browser.

## Operating Environment

This product will operate on a web page, so for using this product the users need to have a computer with a internet connection and a browser.

## Design and Implementation Constraints

We will be using HTML for the web page with a user based security, we will be using database for the list of seeds and for saving the list of field of each user. 

## User Documentation

At the user will be given a video tutorial on how to use the application

# External Interface Requirements

## User Interfaces

Log In Interface

![Log In Interface](https://i.ibb.co/7n7x6cM/Log-In-Interface.jpg)

User Interface

![User Interface](https://i.ibb.co/h9nNdgQ/User-Interface.jpg)

## Communications Interfaces

This product will be using a web browser.

# System Features

\<This template illustrates organizing the functional requirements for the product by system features, the major services provided by the product. You may prefer to organize this section by use case, mode of operation, user class, object class, functional hierarchy, or combinations of these, whatever makes the most logical sense for your product.\>

## Database For The Field

4.1.1 Description and Priority

This feature will be helping the user for managing his field.

4.1.2 Stimulus/Response Sequences

The user can save, modify and delete field on his account.

4.1.3 Functional Requirements

The user need to be log in on their account to view his field and operate on it.

## Calculation Of Agricultural Yield

4.1.1 Description and Priority

This feature will be calculating the agricultural yield on a specific yield with a specific seed.

4.1.2 Stimulus/Response Sequences

The user need to select a field and a seed and give the application the input. 

4.1.3 Functional Requirements

The user need to be log in on their account and at least a field to operate the feture.
