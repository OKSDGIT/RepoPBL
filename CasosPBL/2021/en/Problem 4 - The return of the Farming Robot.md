 **Problem 4 (Task): The farmer robot returns**
 
 Authors: Luiz Gavaza &nbsp; Lais Salvador &nbsp; Roberta Oliveira &nbsp; Jessica Santana &nbsp; Otávio Neto
 
 Contributors: Edeyson Gomes
 
## Task: The farmer robot returns

### **1. Introduction**

The Farmer Robot company was very pleased with the proposed solution to the food delivery signaling problem and is excited to implement a new feature: the robot, in addition to going through the herd and issuing a food delivery alert, should be able to return to the starting point and thus perform another task. The company already has "external sensor" kits that direct the robot's path to the herds, the problem is how to get the robot back to the starting point. As we know, the minimum number of individuals in the herd required to issue a food delivery alert has already been agreed upon with the farmer.

The UFBA student team responsible for developing the initial prototype, when studying this navigation problem, realized that a simple finite state machine does not solve the problem: how they reached this conclusion is a good question. By detailing a little more about the study in relation to the return to the starting point problem, the students realized that, with the coupling of an auxiliary memory device to the state machine, it is possible to model a solution to support the navigation of the farmer robot.

The students also realized that the Food Delivery module of the Farmer Robot Problem can be extended with the navigation module proposed in this new problem or the two modules can be separate solutions that work in parallel, but can communicate in some way. The company is also interested in a notation that specifies rules for generating location sequences, for documentation and improvement of the robot's navigation module.

The suggested tool to simulate the robot's navigation module process and the generation of location sequences is JFLAP1


### **2. Process**
During the process of building the solution, the Problem Based Learning (PBL) teaching and learning methodology will be used. This methodology is characterized by the use of real-world problems to stimulate the development of critical thinking, teamwork, and problem-solving skills, in addition to contributing to the construction of knowledge about a specific topic.
The process should be documented through the PBL whiteboard, which consists of the QUESTIONS, FACTS, IDEAS/HYPOTHESES and ACTIONS columns. In each team meeting, a version of the whiteboard should be built, and thus we will have the documentation of the steps for building the solution. In addition, a shared document will be made available for filling in the Logbook, which must contain the minutes of the meetings with the names of the participants, points discussed and challenges encountered. The description of this process will be part of the group's evaluation. In this process, the participation/contribution of each member of the team is essential, so each student will also be individually evaluated based on the observation of the tutors and the feedback of their colleagues.


### **3. Product**
By 8:20 p.m. on April 28, 2021, a team member must post to Virtual Learning Environment (VLE) UFBA, in the appropriate space, a file for the JFLAP simulator with the robot's navigation module, as well as a report in the SBC (Brazilian Computer Society) article model that describes in as much detail as possible the idealization of the robot's navigation module's operation. The report must contain the operations executed for the system to function and, at least, 2 (two) examples of how it works. If a rule-based notation has been developed, this report must also contain examples of generating location sequences. If it has not been developed, present the main difficulties in the report.


### **4. Knowledge/Concepts Involved**
1\. Pushdown automaton
2\. Context-free grammars

   
### **5. Learning Objectives** 

#### **5.1 General Objective**

Develop a navigation module for the farmer robot that allows it to return to the starting point after issuing the food delivery alert.

#### **5.2 Specific Objectives**

1\. **Understand** the functionalities and challenges of the farmer robot's navigation problem

2\. **Investigate** the use of auxiliary memory devices in a finite state machine to model a solution to the return to the starting point problem

3\. **Analyze** the possibility of extending the food delivery module with the proposed navigation module or developing separate solutions that work in parallel and can communicate

4\. **Research** and propose a notation that specifies rules for generating location sequences for documentation and improvement of the navigation module.

5\. **Use** the JFLAP tool to simulate the robot's navigation process and the generation of location sequences.



