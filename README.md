# Final project for ITF Manual Testing Course

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application. 

Application under test:
https://www.cropp.com/ro/ro/

Tools used: JIRA, Zephyr Squad

# Functional specifications

The below Story was created in JIRA and describes the functionality of the login page

![Story DB-3](https://github.com/brahutz/Proiect-Practic-Testare-Manuala/assets/130207713/e742ebc1-a285-49ea-9c2d-5f25410f0fe2)

# 1 Testing section

## 1.1 Test Planning

The Test Plan is designed to describe all details of testing the https://www.cropp.com/ro/ro/ site.
 

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the resources and schedule required to complete testing, and the risks associated with the plan

#### 1.1.1 Entry criteria defined

* functional specifications are defined
* roles needed for the project are allocated
* initial project risks were detected and mitigated

#### 1.1.2 Exit criteria defined

* number of unresolved bugs is insignificant or they have low priority
* all tests have been executed
* all resolved bugs have been re-tested and approved by the QA team
* deadline was reached
* no detected major risk remained un-mitigated

#### 1.1.3 Test scope

* __Tests in scope:__ All the feature of Login Page module which were defined in software requirement specs need to be teste
* __Tests not in scope:__ performance testing, integrations of the dependents module with other modules, compatibility testing with multiple browsers

#### 1.1.4 Risks detected

* Project risks: lack of experience of the QA team, short deadline of Zephyr Squad trial, unavailability of test environment
* Product risks: The website may not render correctly or function properly on different web browsers such as Chrome, Firefox, Safari, and Internet Explorer.

#### 1.1.5 Evaluating entry criteria

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue. 

## 1.2 Test Monitoring and Control

Various periodic reports were generated to reflect the current status of the testing process, in case of major problems control measures could be taken.
The following status report was generated after 100% of the test cases were executed, on September 24, 2023:

![Test Execution](https://github.com/brahutz/Proiect-Practic-Testare-Manuala/assets/130207713/0f98aaf6-8114-46e4-be49-123ad54e97d8)

## 1.3 Test Analysis

The testing process will be executed based on the above requirements for the Dependents module. The following test conditions were found:
 * Enter data only for mandatory fields and check that the dependant is created/updated
 * Enter data for all available fields and check that the dependant is created/updated
 * Leave mandatory fields empty and check that the dependant cannot be created/updated
 * View dependant details and check they are correct
 * View all dependants in a list
 * Check all validation constraints for the fields

## 1.4 Test Design

Functional test cases were created in Zephyr Squad. Based on the analysis of the specifications, the test design techniques used for generating test cases 
are boundary value analysis, equivalence partitioning and use case testing.

**Test cases:**
![Test Cases](https://github.com/brahutz/Proiect-Practic-Testare-Manuala/assets/130207713/56483d16-fa15-49db-b91e-d1f4a1e418ed)

## 1.5 Test Implementation

The following elements are needed to be ready before the test execution phase begins:

* Testing environment is up and running: https://www.cropp.com/ro/ro/
* Access to the testing environment is given: Username : Admin | Password : admin123
* Cycle summary was created 
* Test cases were added to the cycle summary


## 1.6 Test Execution

* Test cases are executed on the created test Cycle summary:
* ![Test Cases1](https://github.com/brahutz/Proiect-Practic-Testare-Manuala/assets/130207713/ac70259d-859d-467c-b87a-6a40b606cec2)

* Bugs have been created based on the failed tests. The complete bug reports can be found here: [DB-11(Bug).pdf](https://github.com/brahutz/Proiect-Practic-Testare-Manuala/files/12708493/DB-11.Bug.pdf)
  [DB-10(Bug).pdf](https://github.com/brahutz/Proiect-Practic-Testare-Manuala/files/12708494/DB-10.Bug.pdf)

* Full regression testing is needed after the bugs are fixed

## 1.7 Test Completion

* As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team
* The traceability matrix was generated and can be found here:
* ![Traceability Matrix2](https://github.com/brahutz/Proiect-Practic-Testare-Manuala/assets/130207713/2f45c051-d461-45d1-aef4-bd99c5994f98)

* Test execution chart was generated, the final report shows that a number 1 tests have failed of a total of 10 
* A number of 10 test cases were planned for execution and all of them were executed
* A number of 2 total bugs were found, from which the priority is: 2 are high

![Tese Execution 2](https://github.com/brahutz/Proiect-Practic-Testare-Manuala/assets/130207713/d0473f30-cb04-461b-8a00-28a563428793)
