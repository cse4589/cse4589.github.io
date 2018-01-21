---
layout: default
---

# Introduction
This is a set of _three_ **networking programming assignments** (PAs), along with an automated tester/grader, available to both students and instructors. The assignments have been used in CSE 489/589, a joint senior undergraduate/introductory graduate class, in the [CSE department](https://engineering.buffalo.edu/computer-science-engineering.html){:target="_blank"} at the [University at Buffalo (UB)](http://www.buffalo.edu/){:target="_blank"}. For each PA, we provide:

* Detailed description of the assignment
* Grading rubric
* Code template to serve as a starting point for students
* Automated grader
* Instructions for students to use the template and the grader
* Instructions for the course staff to setup the grader (if required)

Currently, both C and C++ are supported.

# Motivation
While similar programming assignments are used in many computer networking classes, we are not aware of any similar project including standardized assignments, test cases, and an automated tester/grader for a networking class, although such projects are quite common in other CS courses, in particular in OS (e.g., Pintos, Nachos). Our experience with CSE 489/589 has shown that the use of automated grading reduces the grading load from instructors and TAs and offers a better learning experience for students. Since students know their grade at the time of submission, instructors and TAs can utilize office hours much more efficiently, helping students with their assignments instead of dealing with complaints about grades, which are unavoidable when manual grading is involved. In addition, the grader prevents students from losing points for failing to follow certain specifications (e.g., naming conventions) and allows them instead to focus their debugging efforts on the networking components of each assignment.​

The assignments are designed in a way that they are usable by similar courses **outside UB**'s CSE department, with _little to no changes_. Our instructions, in fact, provide usage/setup guides for both inside and outside UB scenarios.

* * *

# Programming Assignments

## Use
The assignments are designed in such a way that course instructors can use them by simply distributing to the students the link to a single document: **assignment handout** for a given PA, which contains the full description of the assignment problem, grading rubric, download links to the template and automated grader, and the link to the instructions for using the template and the automated grader. The document contains all the information required for the students to be able to complete the assignment (and even for the course staff to be able to grade student submissions).

The _Details_ section below provides the links to web-pages containing all details/resources for each of the three PAs. The _assignment handout_ for the PA can be accessed through the link labeled: _**Description**_ on the it's web-page. Although the page includes additional resources for each assignment, the _assignment handout_ is the **only** link/document that needs to be provided to the students by the instructor. For quick reference, the links to the _assignment handout_ are provided here:

* [PA1 assignment handout](https://goo.gl/bqf2E1){:target="_blank"}
* [PA2 assignment handout](https://goo.gl/KzTh0J){:target="_blank"}
* [PA3 assignment handout](https://goo.gl/HYHcyQ){:target="_blank"}

The three assignments are completely independent of each other and the instructor might choose to use any subset of them. However, note that students may find it difficult to attempt PA3 without doing PA1 first.

## AutoGrader Setup (for Instructors/Course staff)
The AutoGrader is designed to test the student submissions on a "real" network (except PA2). To be able to achieve this, the AutoGrader has specific requirements in terms of physical infrastructure (host machines, disk space, user accounts etc.) and in certain cases needs a one-time setup/installation to be able to perform the grading. AutoGrader setup needs to be performed by the instructor/course staff before the assignment is released to the students.

We provide detailed setup instructions for each PA on it's web-page (accessed through the links mentioned below in the _Details_ section).
These can be accessed through the **Instructions: Automated grader setup (Course staff)** link listed on each PA's web-page. The instructions list the infrastructure (servers, networking, etc.) required for each PA and a guide to install any components needed by the automated grader to function.

The setup/usage instructions lists separately the steps required by instructors at UB and for instructors/course staff outside UB. Although the PAs are generic in nature and not tied to UB specifically, UB-specific instructions take into account the specific infrastructure made available by UB's CSE-IT team to reduce the setup workload for UB course instructors/staff.

### UB Specific Instructions
Setup/Usage instructions specific to UB are marked as:

> ***
>
> ##### <img src="http://cse4589.github.io/assets/site/images/UB_BLU_RGB.png" width=30></img>
> ....
> ....
> ***

If you are setting up the grader inside UB CSE, you **MUST** read those parts of the setup guide carefully. If you are using the PAs outside UB, you can safely skip these sections.

## Details
### [Programming Assignment 1 (PA1)](/pa1/){:target="_blank"}
### [Programming Assignment 2 (PA2)](/pa2/){:target="_blank"}
### [Programming Assignment 3 (PA3)](/pa3/){:target="_blank"}

* * *

# Contact Us
We would love to hear any feedback/comments regarding any aspect of the PAs. For bugs, feature requests, etc. in the automated grader use the github repository linked under **Automated Grader (Source)** on each PA's web-page. Specifically, if you are trying to setup the PAs for a course outside UB, feel free to contact us with any questions regarding setup or any changes that you might like to make to adapt the PAs for your specific needs.

<dl>
<dt>Lead Developer</dt>
<dd>Swetank Kumar Saha (swetankk [at] buffalo [dot] edu)</dd>
<dt>Course Instructor</dt>
<dd>Dimitrios Koutsonikolas (dimitrio [at] buffalo [dot] edu)</dd>
</dl>
