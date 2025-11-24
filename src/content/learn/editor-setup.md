---
title: Preparing the Data to Import Test Cases
---

### Objective: {/*objective*/}

Converting test cases written in google sheets to an uploadable format supported by QATouch with help of a script.

#### Why use a script? {/*why-use-a-script*/}

The current test case has the below limitations and needs to be formatted in a way that is compatible with QATouch migration.

Please download **APP Script Code**

**Existing Test Case Template (Limitations):**

1. Every step added is entered in the next new cell.
2. We do not mention the Module name for the test case.
3. Merged rows are present in between the test cases.
4. Test name column allows duplicate values.

#### The existing Test Case Step Template {/*the-existing-test-case-step-template*/}

![sample image](../assets/faq-screenshots/excelimport/sample.png)

### QATouch Supported Format (Expected): {/*qatouch-supported-format-expected*/}

1. Module and test case name field is mandatory in the tool.
2. All field values of a test case should be on a single cell.
3. Merged rows are not accepted.
4. Test name field won't allow duplicate values.

### QA Touch Template {/*qa-touch-template*/}

![sample1 image](../assets/faq-screenshots/excelimport/sample1.png)

<iframe width="50%" height="315" src="https://www.youtube.com/embed/pRDKhCXzfsY?si=FwbLR948w0fGxcBr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### Script logic: {/*script-logic*/}

The script will identify the row type of each row using the following conditions.

***table content ***

![sample3 image](../assets/faq-screenshots/excelimport/sample3.png)
Please download [APP Script Code](https://www.qatouch.com/img/appscript.js)

Excel sheet - APP Script

![image1](../assets/faq-screenshots/excelimport/1.png)

Here you can download the script Copy and Paste [APP Script Code](https://www.qatouch.com/img/appscript.js) in the editor.

![image2](../assets/faq-screenshots/excelimport/2.png)

![image3](../assets/faq-screenshots/excelimport/3.png)

![image4](../assets/faq-screenshots/excelimport/4.png)

![image5](../assets/faq-screenshots/excelimport/5.png)

![image6](../assets/faq-screenshots/excelimport/6.png)

![image7](../assets/faq-screenshots/excelimport/7.png)

![image8](../assets/faq-screenshots/excelimport/8.png)

![image9](../assets/faq-screenshots/excelimport/9.png)

![image10](../assets/faq-screenshots/excelimport/10.png)

If you getting above error message, need to add a Service,

- Click Services enable **"Google Sheets API"**
- Click Save button

![image11](../assets/faq-screenshots/excelimport/12.png)

![image13](../assets/faq-screenshots/excelimport/13.png)

Success message

![image14](../assets/faq-screenshots/excelimport/13.png)
