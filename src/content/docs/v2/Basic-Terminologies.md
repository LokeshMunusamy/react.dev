---
title: Basic Terminologies
---

### Basic Terminologies {/*basic-terminologies*/}

QA Touch is a smarter test management tool for QA teams across the globe. With over 1,000 customers, QA Touch has been delivering seamless test management solutions for all of them, including facilitating testers, developers, and managers, to organize their testing process. With innumerable features, such as managing test cases, bundling test suites, executing test runs, third-party tool integrations and generating seamless test reports, all from a single interface.


### Here are some of the benefits of using QA Touch for your test management {/*here-are-some-of-the-benefits-of-using-qa-touch-for-your-test-management*/}

#### Centralized Repository of Test Assets {/*centralized-repository-of-test-assets*/}

The very purpose of using a test management tool is to manage your testing processes from a single dashboard. Testing is a complex process which involves large amounts of data and numerous activities to be performed. Teams need to create test suites, implement test runs, assign and collaborate with the team, manage code at various stages of release, and much more. Without a test management tool, teams would be using different tools to perform all these activities, making it cumbersome to put it all together. With a test management tool like QA Touch, which offers seamless integration with several other tools like Jira, GitHub, Slack, GitLab, and more, you can handle all these activities from a single dashboard and eliminate switching between these different tools.

#### Implementing Test Cases and Executing Runs {/*implementing-test-cases-and-executing-runs*/}

With QA Touch, you can easily create test cases, organize them into buckets according to your requirements, assign testers and developers either individually or in groups, execute test runs, and much more. Traditional test management methodologies use tools like Excel and chat boxes to document test cases and make assignments, which makes it more difficult for the team to manage test cases. That is where QA Touch comes to your aid, so you can effortlessly manage all these tasks from one dashboard.


#### Save Time and Enhance Productivity {/*save-time-and-enhance-productivity*/}

Implementing test management solutions all in one QA Touch platform, along with integration of third-party tools, helps you plan and execute testing processes from one dashboard, thereby saving loads of time. Simplified accounts and user management, along with detailed assignment of test cases, runs, and custom functionalities help enhance productivity in testing. Team members can clearly understand requirements, priorities and deadlines, allowing them to work with improved efficiency.

#### Seamless Reporting to Project Stakeholders {/*seamless-reporting-to-project-stakeholders*/}

The QA Touch reporting feature enables you to create, download and share the report in various formats. You can conveniently summarize the work progress mentioned above and generate reports that are scalable. Using QA Touch, you can also share reports of test cases, test runs, releases, requirements, and issues to the relevant stakeholders. They can then make relevant decisions and forecasts based on the data.

### QA Touch Dashboard {/*qa-touch-dashboard*/}

There are two dashboards you can see in the platform; a general dashboard and a team dashboard. The general dashboard provides you project information such as total test cases, test runs, and users assigned. You can see a graph with the number of activities done each day in the project and the recent activities list at the right. In the team dashboard, you can see the above metrics and activities per user, per project, or for all projects as a whole. You can also select the project and/or user for whom you want to see the dashboard.Team Dashboard can be shared publicly with a URL. It can be viewed without login in QA Touch.

### Projects {/*projects*/}

Projects are the major anchor around which all the developmental and testing activities are planned and executed. It is the product or service which you implement for all the stakeholders. The first step you must do in QA Touch is to create a project, and then all test cases, test runs, releases and requirements fall under a specific project.

### Requirements {/*requirements*/}

Requirements are the expected way the project should perform and be delivered after development. It is often derived at before starting the project during the planning phase, while discussing the project needs with the clients and as documented in the Business Requirements Document (BRD). The requirements in the document at the planning stage are the major requirements, which are further broken down into minor requirements at the implementation stage, then developed and tested for verifying the same.

### Test Cases {/*test-cases*/}

A test case is a series of steps for verification and validation of the application being worked upon. It has a test case description, the steps needed to execute the test case, the expected result(s) of the entire test case and individual steps, prerequisites for the test case execution and the requirements (if any) linked to the test case.

A functionality can have a single test case or multiple test case associated with it. In these cases, it’s advisable to categorize test cases into a collective section called module. A module helps group test cases according to functionality, if multiple test cases confirm to one feature. The way test cases are grouped depends on the project requirement and varies from one to another.

In QA Touch, you can easily add test cases, steps associated with each test case, link requirements, and group test cases under modules and tags.

### Releases {/*releases*/}

Releases can be any key deliverable or target that is scheduled to be completed on a specific date. It can be a software version update, a new feature release, key deliverables for the month, revamps and so on, either released in beta or the completed stage. Testing, development, and operations teams work together in delivering a release. It accompanies test cases, modules, requirements, and test runs. A project can have multiple releases, and the duration of each release can be a few days to several months depending on the release. Today, most project teams are shifting to Agile project methodology, where they work on short release cycles called sprints, which usually last for a week or two. In QA Touch, you can create releases and within a release you can create pre-built and custom test suites, multiple test cases with different modules and package them in test runs for execution.

### Test Runs {/*test-runs*/}

If test cases are statements that verify one or more functionalities, test runs are the actual execution of the test cases. It helps to find out whether the test cases have been successfully implemented or not, and whether the requirements have been fulfilled or not. Mostly, the responsibility of a test run is assigned to a single person, even though many people may work on the run. For example, there can be multiple test cases to verify a particular section of the product being worked on, like a homepage features verification. So, it is logical to group these test cases under a single test run. Similarly, you can group multiple test runs under a single test suite or release. For example, a test run might not be 100% successful in the first release sprint, which means that multiple test runs should be run, in multiple sprints, until it is completely successful.

After a test run, you will see the test results, which conveys how the run has performed. It reports the status of test cases and issues.
The status of test cases can be one of the following:

**Passed :** All steps of the test case have been verified and are working properly.


**Failed :** One of the test steps failed to work properly and/or the whole test case failed to meet the expected result.


**Untested :** The test case has not been executed in a test run and remains untested. By default, the status of a new test case is untested.


**Retested :** A developer will set a test case status to ‘retest’ if it has failed previously, after he/she has corrected it and is pushing to test again.


**Blocked :** A blocked test case indicates that the test case cannot be executed for the time being. This can be for several reasons, such as another implementation is pending, without which the test case cannot be executed.

### Issues {/*issues*/}
All test cases might not be successful in the run. Certain requirements for which test cases have been written might not have been implemented properly, or the test results may have delivered different results than expected. Such scenarios result in defects/bugs and testers raising issues for the defect. Issues are generally created by the tester after testing and are assigned to the developer to fix the issue. The developer works on fixing the bugs and assigns the test case for retest. Issues have a status indicating the current position of the issue, a priority as to how important it is to be fixed, and a severity level indicating the impact the issue has on the project.

