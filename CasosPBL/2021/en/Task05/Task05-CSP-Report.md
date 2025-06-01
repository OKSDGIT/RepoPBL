
## Introduction

This report applies the **Competency Specification Process (CSP)** to the Problem-Based Learning (PBL) scenario entitled **"The Farmer Robot and the Feeder Robot"**, which expands on previous challenges by integrating new functionalities and a second robotic agent. In this scenario, students are required to design computational solutions using **Turing Machines** to model the behavior of both the Farmer Robot and the newly introduced Feeder Robot.

The core challenge is to ensure that, during herd traversal and food delivery signaling, the Farmer Robot also communicates the path the Feeder Robot must follow. Furthermore, a unified abstract machine—capable of sequential read and write operations over unlimited memory—must be employed to implement the navigation modules of both robots. This decision aims to support system documentation standardization and simplify maintenance training.

Through the CSP methodology, competencies are extracted and structured from the task description, relevant knowledge domains, learning objectives, and behavioral dispositions. The result is a structured framework for competency-based learning that integrates computational modeling, tool application, and collaborative problem-solving in real-world-inspired scenarios.



## 1. Task Description Analysis

The *Farmer Robot and Feeder Robot* task addresses the ongoing innovation efforts of the Farmer Robot company. After successful deployments of previous modules for signaling and navigation, the company aims to introduce a new robot, the **Feeder Robot**, that works in coordination with the **Farmer Robot** to deliver supplies to herds efficiently.

The main goal is to integrate the identification and navigation logic of both robots using a unified computational model—a **Turing Machine** with sequential read/write access to unbounded memory. The Farmer Robot must not only alert the herd's location but also encode and transmit the path that the Feeder Robot should follow. Additionally, the Farmer Robot's previous signaling module must be revised to allow input of a minimum threshold for herd member count.

The expected deliverables are:

* A **JFLAP file** implementing both robots' navigation modules using the shared abstract machine model.
* A **technical report** following the SBC article format, documenting the logic, design choices, and execution of the developed modules with examples.

This task requires students to:

* Understand the interaction and coordination between multiple robot modules.
* Revise and enhance existing computational solutions.
* Investigate abstract computational models and apply them to new design scenarios.
* Use **JFLAP** to simulate and validate system behavior.
* Collaborate effectively and maintain structured documentation through PBL tools such as the Whiteboard and Logbook.



## 2. Knowledge Enumeration

The successful execution of this task requires mobilizing knowledge from both theoretical computing and professional skills. The knowledge domains are categorized according to the **ACM Computing Classification System (2012)** and **ACM/IEEE CC2020** guidelines.

### Computing Knowledge

* **Turing Machines**
  Essential for modeling both the Farmer Robot and Feeder Robot modules, Turing Machines provide a universal foundation to represent logic that involves memory, control flow, and decision-making.

* **Turing Machine Variants**
  Knowledge of variations, such as multi-tape or non-deterministic Turing Machines, may be necessary to optimize the coordination between the two robots or improve efficiency in navigation logic.

* **Church-Turing Thesis**
  Provides the theoretical basis for the task, reinforcing the equivalence between algorithmic reasoning and Turing-computable functions. Students are expected to ground their solutions in this foundational concept.

  * **Requirements Engineering**
  Enables the identification, analysis, and formalization of user needs (e.g., DERBA’s demand for nighttime traffic classification) into computational requirements that guide system design.

* **Modeling and Simulation**
  Required for representing the robots’ behaviors formally and testing them through simulation environments like JFLAP.


### Professional Knowledge (FPK)

* **Requirements Engineering**
  Enables students to formalize and revise system specifications, such as enhancing existing modules and incorporating thresholds for herd sizes.

* **Analytical and Critical Thinking**
  Supports the analysis of functional dependencies between robots, exploration of abstract machine capabilities, and evaluation of design alternatives.

* **Problem Solving and Solution Design**
  Critical for adapting existing logic, resolving limitations in current modules, and proposing integrated multi-agent navigation strategies.

* **Written Communication**
  Students must produce a structured, technical report that documents the developed modules, justifies design decisions, and communicates results clearly to both technical and non-technical audiences.


Com base no conteúdo do arquivo `Task05-TheFarmingRobotAndFeedingRobot.md` e nas suas instruções, seguem as seções 3 e 4 do relatório, em inglês e no formato apropriado:


## 3. Learning Objectives Identification

### General Objective

Apply knowledge of Turing Machines to develop and integrate identification and navigation modules for both the Farmer Robot and the Feeder Robot.

### Specific Objectives

1. **Understand** the functionalities and new demands related to both robots.
2. **Investigate** the abstract machine model capable of sequential reading and writing to an unlimited memory device and apply it to robotic navigation.
3. **Revise** the food delivery signaling solution, incorporating the specification of minimum herd sizes as input.
4. **Develop** modular and reusable navigation systems for both robots using a unified computational model.
5. **Simulate** robot behavior using the JFLAP tool to validate the modules.

These learning objectives ensure that students combine theoretical and applied knowledge, strengthen algorithmic reasoning, and use simulation tools to prototype functional robotic systems aligned with formal models of computation.


## 4. Competency Specification

To support these learning objectives, the competencies defined for Task 05 are **reused** from Task 02 (*Traffic Control*), as both tasks rely on the design, simulation, and documentation of systems modeled using Turing Machines. This reuse is intentional and pedagogically valuable for the following reasons:

* **Consistency**: Reinforces recurring cognitive and technical skills across different tasks, such as formal modeling and structured problem-solving.
* **Efficiency**: Promotes a streamlined specification process by avoiding redundant competency definitions.
* **Scalability**: Demonstrates how competencies can be applied across different but related domains, enhancing their generalizability and relevance.
* **Traceability**: Supports a competency-based education model by making learning achievements persistent and verifiable across tasks.

