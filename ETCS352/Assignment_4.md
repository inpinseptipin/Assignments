# Assignment 4

## Q1- What do you understand by scrum testing? What is the role of a tester in Scrum? How test reporting has been done?
As Scrum is an implementation of the Agile software development ideolog. It is a team based approach but is interactive and dynamic. As a result, a product's delivery time shortens. The project is divided into time based tasks called sprints. Every single sprint has a fixed duration.

Role of a tester with Scrum - 
During scrum testing, the team has to test a product and see how it turned out from the customer's point of view. Some of the main events a tester has to attend in an agile enviornment should include are:

1. Sprint planning sessions
2. Daily standup meetings
3. Sprint retrospectives

The role of the tester :

1. Facilitate Face to Face communication with the team is the most efficient way to communicate ideas to the time. 
A tester participates planning/release of the sprint. The design meetings are held every time before the sprint planning is done.
The testers can participate in this meeting and ask questions on the stories being discussed.
The tester should make a model in his mind about how the system would look and work based on the discussions.

2. Should work collaboratively and productively with the product owner and the customer to form acceptance criteria.
A scrum tester would be able to describe the feature well. Before any user story is sent for development the tester and other team members would discuss the complete user story 
with the team member to find out what the customer wants.

3. Testers should have good interpersonal skills as well as technical skills apart from that he should have good communication skills to deliver the project to the client.

### Test Reporting in Scrum

Test reporting in scrum provides transperency and visibility to stakeholders about the project.
The metrics that are reported allow a team to analyze their progress and plan their future strategy to improve the product.
There are two metricts that are frequently used to report

**1. Burn Down Chart** : A burndown chart gives a quick overview of the project progres, this chart contains information like the total amount of work
in the project that must be completed, amount of work completed during each sprint.

**2. Velocity Histroy Graph** : The velocity history graph predicts the velocity of the team reached in each sprint.
It is a bar graph and represents how teams output has changed over time.
The additional metrics that may be useful are schedule burn, budget burn, theme percent complete, stories completed - stories remaining and so on.


## Q2- What are the risks associated with automation in agile process? Explain.

The Risks associated in Automation Testing?

### The risks of Automation Testing are:

**1. Do you have skilled resources?**
The automation testing demands resources with some knowledge about programming. Focus on the resources. Identify whether the resources have proper knowledge for automation testing. Are they capable to adapt easily to the new technologies? These measures are to be well assessed for building an automation testing team.

**2. The initial cost for automation is high.**
The initial cost for automation is too high for initial setup. It costs automated tool purchase, training ad maintenance of the test scripts. The unsatisfied customer base is high for automation testing their products. It should be ensured that the cost compensates the testing results.

**3. If UI is not fixed, do not thing about automation:**
Prior to automating the user interface, it should strongly be determined that, whether the UI is changing extensively or the cost of the automated script maintenance is high or not.

**4. Make sure that the application is stable enough:**
To automate the early development cycle unless or otherwise it is Agile environment, would not be a good idea. It costs script maintenance cost very high.

**5. Stop automating the tests which run once:**
Ensure that certain test cases might be running once and not included in the regression testing. Avoid automating such test modules.


## Q3- What is Load and performance testing in Agile? Explain with a real case.

### Performance Testing
It is the superset of load and stress testing. It helps to set the benchmark and standards for the application.
The aim of performance testing is to get an indication of how an application behaves under regular parameters. Resource usage, availability and reliability 
of the product are validated under this testing. In performance testing, Load limit is both below and above the threshold of a break.

**Example of performance testing** : Checking concurrent users, HTTP connections or checking suitable response time.

### Load Testing
A subset of performance testing. To recognize the upper limit of the system, set SLA of the app and check how the system can handle a heavy load.
Generating increasing load on a web application is the main aim of load testing. The attributes which are checked in a load test are peak performance, server quantity and response time.
In load testing load limit is a threshold of a break.

**Example of Load Testing** : Test of a word processor by make change in the large volume of data, test a printer by transferring heavy data, Check mail server with thousands of concurrent users.


## Q4- Write short notes on:

### a) Automated software testing
Automated testing Software is the methodology that helps to validate the functioning of the software before it is moved to production.
In this process, automated testing tools are used by the QA teams for executing the test scripts.

With the use of automated software testing tools, QA teams can quickly test the software, prepare the defect reports, and compare the software results with the expected results.
Also, this automated testing process provides several benefits such as faster delivery, eases regression testing time and also ensures quality software along with reducing manual testing efforts.

Thus, the QA teams can function faster and help to push the software to production quickly as per the given timelines as automated testing ensures faster and quality releases leveraging automated testing tools.

### b) Regression Testing

Regression Testing is defined as a type of software testing to confirm that a recent program or code change has not adversely affected existing features.

Regression Testing is nothing but a full or partial selection of already executed test cases which are re-executed to ensure existing functionalities work fine.

This testing is done to make sure that new code changes should not have side effects on the existing functionalities.
It ensures that the old code still works once the latest code changes are done.

### c) Acceptance Testing

Acceptance testing, a testing technique performed to determine whether or not the software system has met the requirement specifications.
The main purpose of this test is to evaluate the system's compliance with the business requirements and verify if it is has met the required criteria for delivery to end users.

There are various forms of acceptance testing:

1. User acceptance Testing

2. Business acceptance Testing

3. Alpha Testing

4. Beta Testing


### d) All-pair testing

All-pairs testing technique is also known as pairwise testing. It is used to test all the possible discrete combinations of values.
This combinational method is used for testing the application that uses checkbox input, radio button input (radio button is used when you have to select only one option for example when you select gender male or female, you can select only one option), list box, text box, etc.

Suppose, you have a function of a software application for testing, in which there are 10 fields to input the data, so the total number of discrete combinations is 10 ^ 10 (100 billion), but testing of all combinations is complicated because it will take a lot of time.




