---
title: 'QA Touch Architecture & Security Information'
---

### What is QA Touch? {/*qa-touch-architecture*/}

QA Touch is a Test Management platform that enables you to handle all your testing processes to deliver high-quality software.

### What can I do with QA Touch? {/*what-can-i-do-with-qa-touch*/}

QA Touch is a test management tool, It helps manage the project testing in companies, right from test planning, test execution, tracking and closure of defects and reporting the status of QA activities.

### QA Touch - SaaS-Based Test Management Tool {/*qa-touch---saas-based-test-management-tool*/}

Software as a service (or SaaS) is a way of providing applications over the Internet. Instead of installing and maintaining software, simply access it from the Internet from any part of the world. The Vendor takes care of Applications, Data, Runtime, Middleware, Operating systems, Servers, Storage, and Networking

![SaaS-Based Test Management Tool Image](../../assets/faq-screenshots/overview/saas.png)


### QA Touch Architecture {/*qa-touch-architecture-1*/}

QA Touch follows a 4-Tier architecture pattern which includes the Presentation Layer, Business Layer, Domain Layer, Database Layer

### Presentation Layer {/*presentation-layer*/}

The First layer of the architecture is also known as the Application layer. The layer of communication with the end user. which means with the layer through which the end user can interact directly with the software application.

### Business Layer {/*business-layer*/}

Business Layer in architecture is responsible for implementing the business logic of the product. It contains objects and services responsible for all functions of the application.

The **MVC Architecture** in this layer enables the application to be robust and modular by dividing the application into three parts: the business logic part, which implements data retrieval and manipulation. the user interfaces part, which is what the application users see. the controller part, which routes requests to the proper objects.

### Domain Layer {/*domain-layer*/}

Dedicated Infrastructure layer for Database schema models which is responsible to interact with the database. This serves as an interface between the business layer which has business logic and the database layer which has the information required for business logic.

### Database Layer {/*database-layer*/}

The Layer in which the actual Database resides. It is the Elementary layer that holds all application data.

### QA Touch Architecture {/*qa-touch-architecture1*/}

![QA Touch Architecture Image](../../assets/faq-screenshots/overview/aws.png)


### MVC Architecture {/*mvc-architecture*/}

Model–view–controller is a software architectural pattern generally used for developing applications.

It contains three parts: **Model, View, and Controller.**

- **Model:** Part which is responsible for Data Interactions, Data retrieval, and manipulation.

- **View:** Responsible for rendering information based on request.

- **Controller:** controls the data flow into a model object and updates the view whenever data changes

![QA Touch Architecture Image](../../assets/faq-screenshots/overview/mvc.png)

### Essential Features {/*essential-features*/}

### Simple And Impactful UI: {/*simple-and-impactful-ui*/}

Our ultimate goal has always been, and will continue to be, empowering our users through a simple and impactful User Interface (UI). Most QA Touch clients have reported our UI is simple, friendly, and quick to accustom. The users can quickly start working on their own, on activities like adding test cases, executing test runs, and generating reports. It also helps them get the information they want in just a few clicks, whether it's exporting data, checking test status, issue priorities, managerial reports, and many more.

### Audio Recording of Issues: {/*audio-recording-of-issues*/}

This feature enables voice recording of the issues summary while creating issues in QA Touch. Audio Recording can be done only for the Issues module.

### Case Traceability Summary Report: {/*case-traceability-summary-report*/}

This reporting feature enables you to track and analyze the end-to-end summary of test execution. You just have to select which test run you want to generate the case traceability summary for and download the report with just one click.

### Inbuilt Mindmap: {/*inbuilt-mindmap*/}

In testing, a Mind Map uses symbols, colors, lines, and images to represent the various phases of software testing followed by activities under each phase. In short, a mindmap shows a visual representation of the testing function in its entirety and provides a creative way to plan the testing logically.

### Reports: {/*reports*/}

Generate unique general and managerial reports from test cases to releases and communicate them through mail to your project stakeholders.

### Audit Log: {/*audit-log*/}

Get a general overview and a project-wise overview of the testing progress in terms of test cases, runs, issues, and user activity logs.


### QA Touch Security {/*qa-touch-security*/}

We are very keen on the security and data privacy of our customers. We follow standard security measures which include technical and organizational security controls to avoid data loss, information leaks, or unauthorized data processing activities. Our security statement can be reviewed below.

QA Touch based on AWS with full compliance. AWS Cloud offers 99.9% uptime and data confidentiality. If there are any changes in the services,

All our files and data are stored in Amazon Web Services (AWS) Cloud. The following is a partial list of assurance programs with which AWS complies:

- SOC 1/ISAE 3402, SOC 2, SOC 3
- FISMA, DIACAP, and FedRAMP
- PCI DSS Level 1
- ISO 9001, ISO 27001, ISO 27017, ISO 27018

To learn more about AWS Security and Compliance, click here.

Entry to the development center is strictly authorized by access control systems. Apart from this, the network is protected by firewalls. The campus is monitored by surveillance cameras 24×7.

Our servers are hosted in reputed hosting and maintained by leading data centers. We monitor the application by a 24×7 monitoring system.

Our staff are trained in security measures and strictly adhere to security policies.

### Access Control {/*access-control*/}
Access to data is strictly authorized by access control systems. The network is protected by firewalls. The campus is monitored by surveillance cameras 24×7. Apart from this, QA touch customers can restrict access permissions, roles to the users.

### Development Practices {/*development-practices*/}

We follow the industry-standard best practices in writing the code and peer code reviews to deliver the quality product. Our product uses standard SSL and follows the HTTPS protocol. QA Touch has also taken preventive measures to handle the Xss site scripting and the SQL injection.

##### Application Security {/*application-security*/}
Our application supports encrypted storage of select data as well as backups and hashed passwords with a firewall.

##### Account Passwords Hashing {/*account-passwords-hashing*/}

All the user account passwords provided by the users are encrypted using MD5 Algorithm (One Way Secure Hashing Technique) and stored in the cloud.

### How Do We Maintain The Confidentiality Of Your Records? {/*how-do-we-maintain-the-confidentiality-of-your-records*/}

We are committed to protecting your privacy and will only use information collected lawfully in accordance with the GDPR.

All of our staff, contractors, and board members receive appropriate and ongoing training to ensure they are aware of their personal responsibilities and have contractual obligations to uphold confidentiality, enforceable through disciplinary procedures. Only a limited number of authorized staff have access to personal information both electronic as well as physical where it is appropriate to their role and is strictly on a need-to-know basis.

QA Touch has also implemented a range of internal controls that provide structure to how data is stored, managed, transmitted, and ultimately destroyed.


### Authentication and Password Management {/*authentication-and-password-management*/}

- Require authentication for all pages and resources, except those specifically intended to be public.

- All authentication controls must be enforced on a trusted system (e.g., The server)

- Establish and utilize standard, tested, authentication services whenever possible.

- Use a centralized implementation for all authentication controls, including libraries that call external authentication services.

- Segregate authentication logic from the resource being requested and use redirection to and from the centralized authentication control.

- All authentication controls should fail securely.

- All administrative and account management functions must be at least as secure as the primary authentication mechanism.

- If your application manages a credential store, it should ensure that only cryptographically strong one-way salted hashes of passwords are stored and that the table/file that stores the passwords and keys is write-able only by the application. (Do not use the MD5 algorithm if it can be avoided)

- Password hashing must be implemented on a trusted system (e.g., The server).

- Validate the authentication data only on completion of all data input, especially for sequential authentication implementations

- Authentication failure responses should not indicate which part of the authentication data was incorrect. For example, instead of "Invalid username" or "Invalid password", just use "Invalid username and/or password" for both. Error responses must be truly identical in both display and source code
