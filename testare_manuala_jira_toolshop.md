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

![image](https://github.com/RusMarcel/Examen_final_IT_Factory_ST3/assets/174935383/77c17248-485f-4fa2-8d77-fed96a11452c)

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
(enumerati aici toate riscurile de proiect pe care le-ati identificat pentru proiectul vostru)

##### Product risks:
(enumerati aici toate riscurile de produs pe care le-ati identificat pentru proiectul vostru)

#### 1.1.6 Evaluating entry criteria
The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

### 1.2 Test Monitoring and Control
(inserati aici motivul pentru care a fost facuta etapa de monitorizare si control si respectiv cum s-a facut aceasta etapa. Aici veti insera de asemenea si raportul de status (test status report) din zephyr - test metrics - primul din lista care sa reflecte activitatea si evolutia testarii. Recomand aici sa executati teste aproape in fiecare zi ca sa vada angajatorul implicarea voastra in testare)

### 1.3 Test Analysis

The testing process will be executed based on the application requirements.

You can find below an example of five test conditions that were created in the scope of this project:

![image](https://github.com/RusMarcel/Examen_final_IT_Factory_ST3/assets/174935383/8ced12fd-2477-45bf-8135-0f8793dd368e)

You can find the full set of test conditions toghether with all the test cases in the following paragraph.

### 1.4 Test Design

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed [here](https://github.com/RusMarcel/Examen_final_IT_Factory_ST3/blob/main/Jira_TestCases.doc)

### 1.5 Test Implementation
The following elements are needed to be ready before the test execution phase begins:

(inserati lista de elemente care sunt evaluate in etapa de implementare)

### 1.6. Test Execution
Test cases are executed on the created test Cycle summary: (inserati aici numele cycle-ului pe care l-ati creat)

Bugs have been created based on the failed tests. The complete bug reports can be found here: (inserati aici fisierul cu bug-urile pe care le-ati identificat)

The following is a summary of the bugs that have been found (inserati o lista cu titlurile bug-urilor identificate impreuna cu prioritatea si severitatea fiecaruia)

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

### 1.7 Test Completion As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: (inserati aici fie o poza cu matricea de trasabilitate din jira, fie linkul catre fiserul excel exportat din jira cu matricea de trasabilitate. Nu uitati sa faceti filtrare dupa type = story)

Test execution chart was generated and can be found below.

(inserati aici raportul de executie generat din jira din sectiunea de dashboards)

The final report shows that a number (inserati numarul de teste) tests have failed of a total of (inserati numarul de teste)

A number of (inserati numarul de bug-uri) total bugs were found, from which the priority is: (inserati numarul de bug-uri) are high and (inserati numarul de bug-uri) are medium.

(inserati aici o concluzie generala a testarii care sa cuprinda cate teste au fost create si executate, ce procentaj aproximativ din cerintele in scop au fost acoperite, daca exista vreo functionalitate pe care nu ai apucat sa o testezi, daca bug-urile gasite impacteaza lansarea produsului in productie sau se pot fixa si ulterior, daca ai identificat riscuri de produs care trebuie mitigate, daca e vreo reecomandare pe care vrei sa o faci pentru lansare, daca sunt ceva lessons learned de care trebuie sa se tina cont la proiectele viitoare etc.)
