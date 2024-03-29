# Guru99 Software Testing Project 1: 
# Testing the Net Banking Facility of Guru99 Bank

The testing process consists of four main parts:

----------------------------------------------------------------------------
## 1. Requirement Gathering

This process is the initial phase of the project, and it involves converting the SRS document into a table with all the modules and their functionalities associated with each of the two roles, in addition to the technical requirements and functional validations.

There are two main roles in the system:

**Manager role**: Has access to all the modules.

**Customer role**:  Accesses only some features of the system.

### System Chart:
This is the overall system chart using Creately.

<img src="https://github.com/MahmoudFawzyAOE2/Guru99-SW-Tesing-Project-1/assets/76012086/43adb325-f762-4615-b3a1-8948b61fb0cc" width="750">

----------------------------------------------------------------------------
## 2. Unit Testing

Testing modules associated with the Manager role.
* Test cases are in the file "TestCaseSuite".
* This mainly focuses on validating each input field required in each module.

In the Project Objectives sent by Guru99, only some modules are required to be tested: [New Customer, Edit Customer, New Account, Edit Account, Delete Account, Delete Customer, Mini Statement, Customized Statement].
* Other modules have their test cases written but have not been tested.
* Test cases for the Customer role will be similar to those of the Manager role (not created yet).
* Modules are only tested in the first two versions (v1 & v2).

----------------------------------------------------------------------------
## 3. Integration Testing

Testing the integration of the modules and verifying their functionalities.
* This is done for these modules associated with the Manager role: [New Customer, Edit Customer, New Account, Edit Account, Delete Account, Delete Customer, Mini Statement, Customized Statement].
* Integration is only tested in versions v2 & v3.

----------------------------------------------------------------------------
## 4. System Testing

Testing the system as a whole and verifying the modules in real scenarios.
* This is done for all modules and for both the Manager and Customer roles.
* In addition to that, verification of Webservice Software Interfaces for [Mini Statement, Balance Enquiry] modules is done as part of System Verification. {delayed for now}
* System testing is only performed in versions v3 & v4.

----------------------------------------------------------------------------
## Conclusion

Guru99's banking testing project offered a compact yet impactful intro to web testing practices. It deepened my understanding of test methodologies and their real-world application, setting the stage for future exploration in this dynamic field. I'm eager to expand my knowledge and apply it to increasingly complex challenges.
