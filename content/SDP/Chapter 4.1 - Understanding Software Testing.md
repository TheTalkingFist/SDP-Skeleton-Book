"For we who grew up tall and proud, in the shadow of the mushroom cloud"
<sup>Queen - Hammer To Fall</sup>

## The Uses of Software Testing

• Detect Defects and Failures 
• Reduce Development Cost 
• Improve Performance

## Definition and Purpose of Software Testing(ST)

(In this Chapter I will be referring to software testing as ST)

Definition: 
	ST is an investigation conducted to provide stakeholders with information about the <u>quality</u> of the software product or service under test.


Purpose: 
	ST includes a process which <u>evaluate the functionality of a software application</u> with an intent to find <u>whether the developed software met the specified requirements</u> and to identify the defects to ensure that the product is defect-free in order to produce a quality product.


## Importance of Software Testing

Why is it important?: Because defects in software systems can cause a significant effect on our day-to-day lives

One Example Would Be:
	 The Honda Company's. Where they are forced to recall the 2.49 million cars and minivans worldwide because of a software problem that could damage the automatic transmission

An Issue as such can cause loss of life and the reputation of a company.

## Evolution of Software Testing

![[Screenshot 2024-09-04 135243.png]]



### Now we shall go through the Testing Approach(Principles Methods and Framework)

## Principles of Software Testing

There are 4 Principles:
 - Early Testing:
	 - <u>save money when issues are discovered and fixed early</u>.
    
- Detect Cluster Together:
	- <u>certain components or modules of software usually contain the most no. of issues</u>. 
	 
- Pesticide Paradox:
	- Same <u>tests ran repeatedly will fail to find new issues. Find new effective way to test</u>. 
	
- Testing is Context Dependent:
	 - testing is <u>all about context</u>.


## Test Methods

#Blackbox
	 - focuses on the input and output <u>without knowing the internal implementation</u>.
#Whitebox 
	-focuses majorly on internal implementation
	     ◦ Common Technique:
	         ◦ Loop Testing 
	         ◦ Data Flow Testing 
	         ◦ Condition Testing ◦ Static Testing Methods
#Greybox 
	 -an effective <u>combination of Black Box Testing and White Box Testing</u>.

## Testing Framework

Testing-Driven Development(TDD):
     ◦ development technique that <u>practices of writing a test and implementation of a features and writing unit test case</u>.

Behavioural Driven Development(BDD):
     ◦ development technique that <u>practices of creating simple scenarios on how an application should behave</u>.

Acceptance Test-Driven Development(ATDD):
     ◦ development technique that <u>practices of capturing user requirement criteria to tests</u>.


### Now we shall go through the Second Part of Testing Approach(Understanding Testing Levels)

##  The Verification and Validation Model

![[Screenshot 2024-09-04 171228.png]]

## Static and Dynamic Testing:

### Static Testing Techniques

Definition: Static Testing is part of the  verification activities where in you have to <u>verify that we  are building the product right as per the standards set by the organisation</u>.

**No Code is Executed.**

### Static Testing Techniques(2)

**Informal Review:**
     ◦ the creator of the <u>documents put the contents in front of audience</u>, and <u>everyone gives their opinion and thus defects are identified in the early stage</u>.

**Walkthrough:**
     ◦ is basically <u>performed by experienced person or expert to check the defects so that there might not be problem further in the development or testing phase</u>.

**Peer Review:**
     ◦ means <u>checking documents of one-another to detect and fix the defects</u>. It is basically <u>done in a team of colleagues</u>.

**Inspection:**
     ◦ is basically the <u>verification of document by higher authority like the verification of software requirement specifications</u>.

**Static Analysis:**
     ◦ includes the <u>evaluation of the code quality that is written by developers</u>. <u>Different tools are used to do the analysis of the code and comparison of the same with the standard</u>. 
         ◦ Control flow structure 
         ◦ Data flow structure


### Dynamic Testing

Definition: Dynamic Testing is related to Validation activities where in you are giving an input and expect an output.

### Dynamic Testing Techniques(Functional Testing):

Definition: Functional Testing is defined as a type of testing which verifies that each function of the software application operates in conformance with the requirement specification.

**Unit Testing:**
     Unit Testing <u>involves testing individual components of the software program or application</u>.
 
**Integration Testing:**
     Integration Testing is <u>a type of software testing, which is performed on software to determine the flow between two or more modules by combining them</u>.

**System Testing:**
     System Testing is <u>a level of testing that validates the complete and fully integrated software product</u>.
	     Purpose of System Testing: to evaluate the end-to-end system specifications.

**Acceptance Testing:**
     Acceptance Testing is <u>a level of software testing where a system is tested for acceptability</u>.
         Purpose of Acceptance Testing: to evaluate the system’s compliance with the business requirements and assess whether it is acceptable for delivery.


### Dynamic Testing Techniques(Non-Functional Testing):

Definition: Non-Functional Testing are used to determine the performance of the system and to validate or verify the quality attribute of the system.

**Performance Testing:**
     Performance Testing is <u>a software testing process used for testing the speed, response time, stability, reliability, scalability and resource usage of a software application under particular workload</u>.

**Security Testing:**
     Security testing is <u>a type of software testing that uncovers vulnerabilities, threats, risks in a software application and prevents malicious attacks from intruders</u>.

**Compatibility Testing:**
     Compatibility Testing is a type of software testing <u>to check whether your software is able of operating on different hardware, operating systems, applications, network environments or Mobile devices</u>.


### Now we shall go through the Last Part. Manual and Automation Testing

## Manual and Automated Testing(Traditional, Agile and DevOps Methodology)

**Manual Testing:**
     Manual testing is the <u>process in which QA analysts execute tests one-by-one in an individual manner</u>.
         In manual testing, a human performs the tests step by step, without test scripts.
                Purpose of Manual Testing: to catch bugs and feature issues before a software application goes live.

**Automation Testing:**
     Automation testing is the <u>process in which testers utilize tools and scripts to automate testing efforts</u>.
         In automated testing, tests are executed automatically via test automation frameworks, along with other tools and software.


Testers should learn the skills of Agile and DevOps methodologies. The Agile method of working provides speed to the test project.

### Implementing  Automated Testing For Agile and Traditional Methodology 

![[Screenshot 2024-09-04 175311.png]]


### Implementing  DevOps Automated Testing Continuous Integration And Delivery

![[Screenshot 2024-09-04 175333.png]]

***If Blurry, Please Check out Chapter8 Pages 23 & 24***

---
Jabriel






















