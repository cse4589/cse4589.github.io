---
layout: default
---

# Introduction
This is a set of _three_ **networking programming assignments** (PAs), along with an automated tester/grader, available to both students and instructors. The assignments have been used in CSE 489/589, a joint senior undergraduate/introductory graduate class, in the [CSE department](https://engineering.buffalo.edu/computer-science-engineering.html){:target="_blank"} at the [University at Buffalo](http://www.buffalo.edu/){:target="_blank"}. For each PA, we provide:

* Detailed description of the assignment
* Grading rubric
* Code template to serve as a starting point for students
* Automated grader
* Instructions for students to use the template and the grader
* Instructions for the course staff to setup the grader

Currently, both C and C++ are supported.

# Motivation
While similar programming assignments are used in many computer networking classes, we are not aware of any similar project including standardized assignments, test cases, and an automated tester/grader for a networking class, although such projects are quite common in other CS courses, in particular in OS (e.g., Pintos, Nachos). Our experience with CSE 489/589 has shown that the use of automated grading reduces the grading load from instructors and TAs and offers a better learning experience for students. Since students know their grade at the time of submission, instructors and TAs can utilize office hours much more efficiently, helping students with their assignments instead of dealing with complaints about grades, which are unavoidable when manual grading is involved. In addition, the grader prevents students from losing points for failing to follow certain specifications (e.g., naming conventions) and allows them instead to focus their debugging efforts on the networking components of each assignment.​

* * *

## Programming Assignment 1 (PA1)
### Overview
PA1 introduces students to **TCP socket programming**, asking them to develop the client and server components of a _text chat application_, consisting of one chat server (handling client registration, relaying messages, maintaining statistics, etc.) and multiple chat clients. As a bonus, students can implement file transfers between clients over P2P connections.

### Links
* [Description](https://goo.gl/bqf2E1){:target="_blank"}
* [Grading Rubric](https://goo.gl/UAVWgY){:target="_blank"}
* [Automated Grader (Source)](https://github.com/cse4589/cse4589-pa1){:target="_blank"}
* [Instructions: Using code template and auto grader (Students)](https://goo.gl/L2kgb5){:target="_blank"}
* [Instructions: Automated grader setup (Course staff)](https://github.com/cse4589/cse4589-pa1/blob/master/README.md){:target="_blank"}

### Suggested workload/time
5 weeks

* * *

## Programming Assignment 2 (PA2)
### Overview
PA2 asks students to implement three **reliable data transport protocols**: _Alternating-Bit (ABT)_, _Go-Back-N (GBN)_, and _Selective-Repeat (SR)_, in a simple _simulator_ initially developed by Kurose-Ross, and compare their performance under different settings. In addition to understanding reliable protocols in depth, students obtain a basic understanding of how a discrete event simulator works and the differences between a simulator and a real system.

### Links
* [Description](https://goo.gl/KzTh0J){:target="_blank"}
* [Grading Rubric](https://goo.gl/s74dAe){:target="_blank"}
* [Automated Grader (Source)](https://github.com/cse4589/cse4589-pa2){:target="_blank"}
* [Instructions: Using code template and auto grader (Students)](https://goo.gl/G4cPfH){:target="_blank"}
* [Instructions: Automated grader setup (Course staff)](https://github.com/cse4589/cse4589-pa2/blob/master/README.md){:target="_blank"}

### Suggested workload/time
3-4 weeks

* * *

## Programming Assignment 3 (PA3)
### Overview
PA3 asks students to implement a simplified version of the **Distance Vector routing protocol** running as an application over simulated routers (Linux servers) in a simulated _Software-Defined Networking (SDN)_ setting. Both TCP and UDP socket programming are involved. Students are provided with detailed protocol specifications for the communication between routers on the control and data plane as well as for the communication between a router and a controller. The controller binary is also provided to students for testing, but not the source code; students have to ensure that they follow exactly the protocol specifications to enable communication between the routers and the controller.

### Links
* [Description](https://goo.gl/HYHcyQ){:target="_blank"}
* [Grading Rubric](https://goo.gl/DfBSBH){:target="_blank"}
* [Automated Grader (Source)](https://github.com/cse4589/cse4589-pa3){:target="_blank"}
* [Instructions: Using code template and auto grader (Students)](https://goo.gl/I56HSu){:target="_blank"}
* [Instructions: Automated grader setup (Course staff)](https://github.com/cse4589/cse4589-pa3/blob/master/README.md){:target="_blank"}

### Suggested workload/time
5 weeks
