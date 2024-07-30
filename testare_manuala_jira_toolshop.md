# Testing Project for ToolShop

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

**Application under test**: ToolShop

**Tools used**: Jira, Zephyr Squad.

## 1. Functional specifications:

The stories attached [here](https://github.com/RusMarcel/Examen_final_IT_Factory_ST3/blob/main/Jira_stories.doc) were created in Jira and describe the functional specifications of the "Categories" module, for which the final project is performed upon.

You can find a example of one of the stories that were created in the picture below:

![image](https://github.com/RusMarcel/Examen_final_IT_Factory_ST3/assets/174935383/ef7ba8bd-62c3-49c3-bc24-5a55e713625d)


## Release

Here you can find the release that was created for this project:

![image](https://github.com/user-attachments/assets/14515794-4cef-445b-8c49-92baabe6a924)

## 2. Testing process

The test process was performed based on the standard test process as described below.

### 1.1 Test planning

The Test Plan is designed to describe all details of testing for the Categories module of the ToolShop e-commerce application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the projects risks associated with the plan. 

The test plan that was created for this project can be found here (inserati link catre documentul cu planul de testare)

#### 1.1.1. Roles asigned to the project and persons allocated
<table>
<tr><td>Project manager </td><td> Gabi Ercsei </td></tr>
<tr><td>Product owner </td><td> Andrei Viman </td></tr>
<tr><td>Software developer </td><td> Narcis Rusu </td></tr>
<tr><td>QA Engineer </td><td> Marcel Rus </td></tr>
</table>

#### 1.1.2 Entry criteria defined

- The business requirements must be completed
- The roles must have been alocated
- The test plan must be finished and sent to the stakeholders
- The entry criteria and exit criteria must be defined
- The project risks must have been identified and mitigated

#### 1.1.3 Exit criteria defined

- 95% of the test can be executed
- not finding bugs of major severity in a specific period of time
- the existing bugs that were reported must have been fixed and followed by retesting and regresion testing
- the deadline has been reached

#### 1.1.4 Test scope

##### Tests in scope:

In order to fulfill the testing objectives we are only going to focus on the Categories module wich has been placed in scope of testing and has been targeted for improvement over the next four months.

There are a few tests in scope for Categories module:

- Adding a category: Adding a category with a valid name, adding a category with an empty name, adding a category with a name that already exists, adding a category with a very long name (if there is a limit on the name length) and adding a category with special characters in the name (if allowed).
- Editing a category: Editing an existing category with a valid name, editing an existing category with an empty name, editing an existing category with a name that already exists (except for the same name it currently has), editing an existing category with a very long name (if there is a limit on the name length), editing an existing category with special characters in the name (if allowed).
- Deleting a category: Deleting a category that does not contain any items (if applicable), deleting a category that contains items (if applicable), deleting a category that does not exist.

From a testing type perspective we are going to use non-functional testing where we are going to cover only usability testing and compatibility testing. Also, positive testing and negative testing are to be done, and retesting and regresion testing will be done when defects are going to be fixed or when modifications of any type are going to be bought to the code.


##### Tests not in scope:

We are not going to cover during the testing process any tehniques related to whitebox testing.

Also, performance and security testing will not be performed during this session of testing.

From the perspective of the modules covered, any other functionality that is located outside of the Categories module are not to be tested.

There are a few tests not in scope for Categories module:

- Performance of the Categories module (how long it takes to add a large number of categories)
- Security of the Categories module (making sure that only authorized users can add, edit, or delete categories)
- Usability of the Categories module (making sure that the user interface is easy to use and understand)


#### 1.1.5 Risks detected

##### Project risks:

We identified a few potential project risks for our website:

- Content Issues: Our website needs high-quality content to engage users. But gathering, writing, and editing content can be time-consuming, and there's always the risk of delays or a lack of high-quality material.
- Technical Issues: Even with the best planning, technical glitches can happen. These could be server problems, compatibility issues, or security vulnerabilities.

##### Product risks:

We identified a few potential product risks for our website:

- User experience issues: Our website could be difficult to navigate, confusing, or lacks user-friendly features, users may abandon it quickly.
- Compatibility issues: Our website will not function properly across different devices and browsers.
- Missing features: The website can lack crucial functionalities that users expect that are necessary to achieve its goals.

#### 1.1.6 Evaluating entry criteria

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

### 1.2 Test Monitoring and Control

- We do periodic reports (daily/weekly/monthly) and will be generated to reflect the current status of the testing process.

![image](https://github.com/RusMarcel/Examen_final_IT_Factory_ST3/assets/174935383/374ad307-a063-4642-bb28-d5e374c3a48b)

### 1.3 Test Analysis

The testing process will be executed based on the application requirements.

You can find below an example of twelve test conditions that were created in the scope of this project:

![image](https://github.com/user-attachments/assets/5faac3c8-6d19-4e32-8d4f-67424459afc2)

You can find the full set of test conditions toghether with all the test cases in the following paragraph.

### 1.4 Test Design

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed [here](https://github.com/RusMarcel/Examen_final_IT_Factory_ST3/blob/main/Jira_TestCases.doc)

### 1.5 Test Implementation

The following elements are needed to be ready before the test execution phase begins:

- Functionality: Features, Performance, Security, Integration
- Usability: Navigation, Content Clarity, User Interface (UI), Accessibility
- Content: Accuracy, Completeness, SEO Optimization
- Additional factors: Mobile Responsiveness, Compliance, Cross-browser Compatibility

### 1.6. Test Execution

Test cases are executed on the created test Cycle summary.

Bugs have been created based on the failed tests. The complete bug reports can be found [here](https://github.com/RusMarcel/Examen_final_IT_Factory_ST3/blob/main/Jira_Bugs.doc)

The following is a summary of the bugs that have been found:

![image](https://github.com/RusMarcel/Examen_final_IT_Factory_ST3/assets/174935383/192d3996-437f-4594-bd79-2e48eb0e8f8e)

- ST3MR-17 -> Priority High, Severity High <br>
- ST3MR-10 -> Priority Low, Severity Low

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

### 1.7 Test Completion

- The traceability matrix was generated and can be found [here](https://github.com/RusMarcel/Examen_final_IT_Factory_ST3/blob/main/Jira_TraceabilityMatrix.xlsx)

![Matricea trasabilitate](https://github.com/user-attachments/assets/2361f93d-3b8b-48cd-94c1-e0d3de02ea98)

- Test execution chart was generated and can be found below:

![image](https://github.com/user-attachments/assets/0caedaf7-9de9-4589-8763-e8f7db016047)

- The final report shows that a number of two tests have failed of a total of twelve tests:

![image](https://github.com/user-attachments/assets/b8c11e53-9583-40dd-b611-730e2edf6dad)

- A number of two total bugs were found, from which the priority is: One is Highest and one is Low.

![image](https://github.com/user-attachments/assets/288f9b0c-13b1-40c9-9a1f-87e2413798e9)

- A total of five test cases were planned for execution and all were executed. The test execution diagram has been generated and you can find a picture below with a test execution by test cycle:

![image](https://github.com/user-attachments/assets/af6e470b-d20b-43d1-a8bd-57636f0810d2)

- The final guidelines for this project are:

1. To fix all critical bugs on a first place who impact the product launch
2. To prevent all potential product and project risks
3. To improve and to do the best for the next projects
