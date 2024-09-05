"I... have become, comfortably numb"
<sup>Pink Floyd - Comfortably Numb</sup>

#### Below is a Brief TLDR Of Implementing Software Testing Before we get into the Specifics.

***1. Requirement Phase***:
    • Identify Scope
        ***2. Test Planning***:
             • Determine Roles and Responsibilities 
             • Tools Selection
                 ***3. Test Case Design and Development:***
                     • Create Test Cases & Test Scripts 
                     • Prepares Test Data
                         ***4. Test Environment Setup:***
                             • Depends on Hardware and Software
                                 ***5. Test Execution:***
                                     • Execute Test Cases with Pass/Fail Result
                                         ***6. Test Cycle Closure:*** 
                                             • Evaluate Cycle Completion Criteria


## The Software Testing Life Cycle

#### Requirement Phase:
   • Identify scope by studying and clarifying testing requirements based on user requirement

#### Test Planning
   • Determine roles and responsibilities of the testers, test tools, prioritise the tasks, and monitor the test coverage

#### Test Case Design and Development
   • Create test cases, automation scripts (if applicable) 
   • Prepare test data (If Test Environment is available)

#### Test Environment Setup
   • Decides the software and hardware conditions under which a work product is tested 
   • Setup test Environment and test data

#### Test Execution
   • Execute the test cases and record the test result

#### Test Cycle Closure
   • Evaluate cycle completion criteria 
   • A final review report on the testing to signify the end of testing is generated

## SDLC VS STLC

**SDLC is responsible for:**
     ◦ collecting requirements  
     ◦ creating features accordingly

**STLC is responsible for:**
     ◦ creating tests for the collected requirements 
     ◦ verifying that features meet those requirements

## Testing Artifacts(Documents Required Before Testing)

### Testing Artifacts (Before Testing)

**1. Test Plan:**
     Test Plan outlines the test strategy, testing objectives, resources required for testing, test schedule and test deliverables.
         **2. Test Cases:**
             Test Cases will examine the expected and actual result and gives a pass or fail
              status. 
                 Usually contains test ID, description, test procedure, test data, expected result, actual result, pass/fail status.
                 **3. Test Design:**
                     Test Design specification refines the test approach and identifies the features to be covered by the design and its associated tests.


### Writing a Test Case

#### Example of How to Write a Test Case

![[Screenshot 2024-09-04 203729.png]]


## Test Scripts

**Test Scripts:**
     A set of instructions to test an application automatically.
         **Test Data:**
             Use relevant historical data from the client or create meaningful contextual data for testing.
                 **Test Data + Test Scripts = :**
                     Test Data and Test Scripts are required for automated testing during test execution phase

##### Ways to Create Test Scripts are:
   - Record/playback 
   - Keyword/data-driven scripting 
   - Writing Code Using Programming Language


## Record/Playback

Why use this for creating Test Scripts? Because it is the Easiest Way To Start Automating Tests.

**Steps to use Record/Playback to start automating:** 
     1. Use tool to capture the actions and automatically turn them into a test script.
     2. Then “playback” or rerun the test steps to make sure they can run like it’s supposed to.

***Downside of Record/Playback:***
     Can become stressful when the UI of the application changes frequently. 
     In these cases, the recorded tests might easily become broken.

An Example of a Testing Tool of Record and Playback is Katalon.


## Keyword/data-driven scripting

Definition: Keyword/data-driven scripting is a scripting technique that uses data files which contain keywords related to the application being tested.

A set of keywords are associated with actions (or functions).

An Example would be :

| Keywords | Description          |
| -------- | -------------------- |
| Login    | Login to website     |
| Email    | Send Email           |
| Logout   | Log out from website |
**Refer to Chapter 9 ,Page 11 for more Examples and Page 12 for an Example of a Test Script**

## Difference Between Test Case and Test Script

#### Test Case:

- Test case is a step by step procedure that is used to test an application.
- Test cases are used for manual testing environment.
- It is done manually.
- The test case template contain test ID, description, test procedure, test data, expected result, actual result, pass/fail status, etc.

#### Test Script:

- Test script is a set of instructions to test an application automatically.
- Test script is used in the automation testing environment.
- It is done according to the scripting format.
- In the Test Script, we can use different commands to develop a script.

# User Acceptance Testing:

**What is UAT?:**
     User Acceptance Testing (UAT), also known as end-user testing, is defined as testing the software by the user or client to determine whether it can be accepted or not.
         **When Is It Performed?:**
             This is typically the last step before the product goes live or before the delivery of the product is accepted.
                 **Who Performs UAT?:**
                     Users or client – someone who is buying a product or who has had a software custom-built through a software service provider or the end-user
                         **Key activities of each UAT phase:**
                             UAT Test Initiation, UAT Test Design, UAT Test Execution, UAT Test Closure

---
This Ends the SDP Notes Happy Studying :}....(Mikhail you end it off)

Yeah, that's it. Good luck for your tests, and we will see you in the next term over. Best Wishes!

\- Mikhail, Jabriel


