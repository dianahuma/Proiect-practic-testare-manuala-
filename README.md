# Final project for ITF Manual Testing Course

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application. 

Application under test: [PetMart](https://www.petmart.ro/)

API Documentation: JIRA, Zephyr Squad

**The final project will be split into 2 sections: [Testing section](https://github.com/dianahuma/Proiect-practic-testare-manuala-/edit/main/README.md#1-testing-section) and [SQL section](https://github.com/dianahuma/Proiect-practic-testare-manuala-/edit/main/README.md#2-sql-section).**

Tools used: Jira 

# Functional specifications

The stories below were created in JIRA and describe the functional specifications of the Search, Cart, Order, and Reviews modules.

![image](https://github.com/dianahuma/Proiect-practic-testare-manuala-/blob/main/Stories.PNG)




# 1 Testing section

## 1.1 Test Planning

The Test Plan is designed to describe all details of testing for the Search, Cart, Order, and Reviews modules from the PetMart application. 

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan

#### 1.1.1 Roles assigned to the project and persons allocated
* Project manager: Valeriu Escu 
* QA Lead: Tania Leonte 
* QA Tester: Diana Huma 

#### 1.1.2 Entry criteria defined
* All the necessary documentation, design, and requirements information is available(that will allow testers to operate the system and judge the correct behavior).
* Functional specifications are defined.
* Roles needed for the project are allocated.
* Initial project risks were detected and mitigated.

#### 1.1.3 Exit criteria defined
* A certain level of requirements coverage has been achieved.
* All tests have been executed.
* No high-priority or severe bugs are left outstanding.
* All resolved bugs have been re-tested and approved by the QA team.
* All high-risk areas have been fully tested, with only minor residual risks left outstanding.
* The schedule has been achieved.
#### 1.1.4 Test scope

* __Tests in scope:__ The scope of this project is limited to the testing of the features in the succeeding sections of this document. All module features that have been defined in the software requirements specification must be tested.
* __Tests not in scope:__ Non-functional testing like performance, security testing, and compatibility testing is beyond this project's scope.

#### 1.1.5 Risks detected

* Project risks: Insufficient resources for testing: (e.g. time or staff), Repeated Requirements Changes, Dependence on Other Teams or Third Parties, Inadequate Communication 
* Product risks: Security Issues, Browser and Device Incompatibility, Low performance, Defective Functionality, Incorrect or Outdated Content

#### 1.1.6 Evaluating entry criteria

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue. 

## 1.2 Test Monitoring and Control

Periodic reports were generated to reflect the current status of the testing process, in case of major problems, control measures could be taken. 
![image](https://github.com/dianahuma/Proiect-practic-testare-manuala-/blob/main/test%20metrics.png)

## 1.3 Test Analysis

The testing process will be executed based on the above requirements. The following test conditions were found:
 * Verify if the user can apply discount coupons to receive discounts during the checkout process
 * Verify the shopping cart functionality
 * Verify if the user can reach the checkout page and place an order
 * Verify if the user can access the order check feature from the website.
 * Verify if the user can access the order check function without being logged in
 * Verify the search functionality for complete queries (ex: Royal Canin Hypoallergenic Small Dog, 3.5 kg)
 * Verify the search functionality for partial queries (ex: royal canin)
 * Verify that the user can view product reviews and ratings on the product page
 * Verify that authenticated users can successfully add a review to a product they have purchased
 * Verify that each review displays the author's name and the review date.

## 1.4 Test Design

The test cases with steps can be viewed here: [test_cases.pdf](https://github.com/dianahuma/Proiect-practic-testare-manuala-/blob/main/test%20cases.pdf)

## 1.5 Test Implementation

Testing environment is up and running: [petmart.ro](https://www.petmart.ro/)
Access to the testing environment is given: Email address: ene.ionel@gmail.com  |  Password: eneionel12345
Cycle summary was created.
Test cases were added to the cycle summary: 
*[Cycle summary](https://github.com/dianahuma/Proiect-practic-testare-manuala-/blob/main/cycle%20summary.pdf)


## 1.6 Test Execution

* Test cases are executed on the created test Cycle summary.
* Bugs have been created based on the failed tests.The complete bug reports can be found here: [Bugs report](https://github.com/dianahuma/Proiect-practic-testare-manuala-/blob/main/Bugsreport.pdf)
    *   Incorrect product pricing displayed on petmart.ro
    *   Unable to Submit Review with Special Characters


## 1.7 Test Completion

* Exit criteria was evaluated and passed
* The traceability matrix was generated and can be found here: [Traceability matrix](https://github.com/dianahuma/Proiect-practic-testare-manuala-/blob/main/Forward%20Traceability_22_9_2023%20(2).csv)
* Test execution chart was generated: ![image](https://github.com/dianahuma/Proiect-practic-testare-manuala-/blob/main/Test%20execution%20chart.png)

  ## 1.8 Conclusions:
* During this testing, all 10 test cases planned for execution were tested.
* From the 10 tests, a total number of 2 bugs were discovered, whose priorities are: HIGH and MEDIUM.
* The reported defects were fixed and retested.
* Product risks have been reduced by upgrading the application.
* Retesting and regression testing will be done for the new version of the application.


