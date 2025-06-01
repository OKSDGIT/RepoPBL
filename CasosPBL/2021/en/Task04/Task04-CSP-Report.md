
## Introduction

This report applies the **Competency Specification Process (CSP)** to the Problem-Based Learning (PBL) scenario titled **"The Return of the Farmer Robot"**. The task challenges students to design a navigation module that allows the robot to autonomously return to its initial location after issuing food delivery alerts. The module must be implemented using computational models and validated through simulation.

This scenario is rooted in a real-world agricultural context and emphasizes the application of **formal methods**, including **automata theory** and **context-free grammars**, to address autonomous navigation problems. The proposed solution must be developed in **JFLAP**, with results documented in a formal technical report following SBC (Brazilian Computing Society) standards.

Through the application of CSP, this report identifies and structures the competencies needed to complete the task, focusing on the integration of theoretical knowledge, analytical reasoning, and collaborative problem-solving practices.



## 1. Task Description Analysis

The *Return of the Farmer Robot* task was proposed by the company **Farmer Robot**, following the successful implementation of a previous food delivery signaling module. The new challenge is to enable the robot to autonomously return to its starting point once the alert has been issued.

The student team from UFBA identified that a **finite state machine (FSM)** alone is insufficient to solve the problem. By analyzing the navigation requirements, they concluded that an **auxiliary memory component**—such as a **stack**—was necessary to allow the robot to track its path and reverse its trajectory. This led to the adoption of **Pushdown Automata (PDA)** as the modeling solution.

The solution must simulate the robot’s navigation using **JFLAP**, and document the rules or notations used for path definition and return logic. Additionally, the task encourages teams to consider extending the original Food Delivery Module or designing a parallel solution capable of inter-module communication.

To solve this task, students must:

* Analyze the problem of robotic return navigation and identify the associated computational challenges;
* Use automata theory and memory-augmented machines (e.g., PDA) to model the return behavior;
* Investigate **formal notations** to express location-based rules;
* Implement and test the navigation logic using JFLAP;
* Produce a structured report detailing the solution and reflecting on modeling decisions.



## 2. Knowledge Enumeration

The task requires a combination of computing and professional knowledge domains. Some knowledge was explicitly stated in the task; others were inferred based on the expected activities.

### Computing Knowledge

Aligned with ACM CCS (2012):

* **Finite Automata – Pushdown Automata (PDA)**
  Used to model the robot’s navigation with memory, enabling stack-based return logic.

* **Regular Languages – Context-Free Grammars**
  Supports the definition of formal rules and pattern generation for sequences of locations.

* **Finite Automata – Formal Grammars and Language Classification**
  Provides the theoretical basis for identifying the computational class of the problem and selecting suitable models.

* **Requirements Engineering**
  Essential for identifying and formalizing the system’s functional requirements and constraints.

* **Modeling and Simulation**
  Applied through tools like JFLAP to test the correctness and feasibility of the proposed automaton.

### Professional Knowledge (CC2020 FPK)

* **Analytical and Critical Thinking**
  Enables decomposition of the navigation problem and evaluation of alternatives for the return path.

* **Problem Solving and Solution Development**
  Required to identify, structure, and validate computational approaches to the navigation task.

* **Written Communication**
  Necessary to document the system’s design and simulation results in a formal technical report.



## 3. Learning Objectives Identification

### General Objective

Apply formal computational models—specifically memory-based automata and formal grammars—to develop and validate a robotic navigation system capable of returning to its point of origin.

### Specific Learning Objectives

1. **Understand** the navigation challenges and design constraints of the Farmer Robot system.
2. **Investigate** the use of stack-based memory in automata to enable path tracking and return.
3. **Analyze** the trade-offs between integrating the new module with the existing system or deploying a parallel solution.
4. **Research and define** formal rules using notations or grammars to specify location sequences.
5. **Simulate and test** the return logic using JFLAP, ensuring reliability and accuracy.


Com base nas anotações e no formato solicitado, segue a seção **4. Competency Specification** com as competências A a E para a tarefa *"O Retorno do Robô Fazendeiro"*:



## 4. Competency Specification

### Competency Reuse 

To fulfill **Objective 4 — Use simulation tools for finite automata**, we **reuse the competency "Test Computational Automata Using Simulators"** previously defined in *Task01 – The Vending Machine for Sodas and Snacks*:

> **Testing Automata Using Simulators**

This competency remains fully relevant in the current task, where students are expected to validate their automaton models through formal simulation tools such as JFLAP. The learning outcomes include the ability to execute, observe, and analyze automata behavior in a simulated environment, ensuring functional correctness and alignment with system specifications.

Additionally, since one of the deliverables for this task is a **technical report** formatted according to the academic standards of the **Brazilian Computer Society (SBC)**, we also **reuse the previously defined competency from Task01**:

> **Write a Technical Report**

This competency involves planning, structuring, and composing a comprehensive document that clearly communicates the problem-solving process, decisions made, and justifications for the implemented model. It reinforces essential skills in technical writing, team collaboration, and documentation.

The reuse of these competencies supports the following principles:

* **Pedagogical consistency** in competency development across different learning tasks.
* **Recognition and reinforcement of transversal skills**, such as documentation and tool-based validation.
* **Avoidance of redundancy** through structured competency traceability.
* **Alignment with competency-based education**, where a well-defined learning outcome may be demonstrated in multiple instructional contexts.

By **reusing validated competencies**, we ensure that students build upon previously acquired abilities, promote cumulative learning, and facilitate assessment practices based on observable and transferable performance indicators.

### 4.1 Competency A Specification

#### A.1 Competency Title

**Develop problem-solving solutions using Pushdown Automata**

#### A.2 Textual Description

Design and implement a Pushdown Automaton (PDA) capable of representing a navigation strategy for a robotic system, focusing on the return path after food delivery. The solution must simulate how memory structures enable backtracking and route inference.

#### A.3 Knowledge Specification

The following knowledge areas are critical for this competency:

* **Pushdown Automata – Finite Automata**
* **Requirements Engineering**
* **Analytical and Critical Thinking (FPK)**

#### A.4 Disposition Specification

The task analysis highlights essential behavioral dispositions required to structure the solution effectively and collaboratively. These include:

* Inventive
* Collaborative
* Responsible
* Proactive
* Creative

#### A.5 Knowledge-Skill Pairing

**A.5.1 Mapping Knowledge to Skills**
To demonstrate this competency, students must:

* Apply their understanding of **Pushdown Automata** to simulate navigation decisions.
* Understand and structure **requirements** aligned with the system’s behavior.
* Apply **analytical and critical thinking** to translate requirements into a functional model.

**A.5.2 Bloom’s Taxonomy Alignment**

* **Apply** is used for modeling and solving with Pushdown Automata and analytical reasoning.
* **Understand** is employed for interpreting and organizing system requirements.

**A.5.3 Verb Annotation**
Develop, Apply, Interpret, Solve, Construct

#### A.6 Summary Table for Competency A

| **Competency**                                            | **Dispositions**                                               | **Knowledge**                          | **Skill**                  |
| --------------------------------------------------------- | -------------------------------------------------------------- | -------------------------------------- | -------------------------- |
| Develop problem-solving solutions using Pushdown Automata | Inventive, Collaborative, Responsible, Proactive, Creative | Pushdown Automata                      | **Apply (Solve, Develop)** |
|                                                           |                                                                | Requirements Engineering               | **Understand**             |
|                                                           |                                                                | Analytical and Critical Thinking (FPK) | **Apply**                  |



### 4.2 Competency B Specification

#### B.1 Competency Title

**Interpret rule-based notation**

#### B.2 Textual Description

Understand and interpret formal notations based on production rules, such as context-free grammars, to represent system behavior and enable navigation control through symbol sequences.

#### B.3 Knowledge Specification

* **Pushdown Automata – Finite Automata**
* **Regular Languages – Context-Free Grammars**
* **Analytical and Critical Thinking (FPK)**

#### B.4 Disposition Specification

As this task involves rule interpretation and documentation modeling, the following dispositions are essential:

* Inventive
* Collaborative
* Responsible
* Proactive
* Creative

#### B.5 Knowledge-Skill Pairing

**B.5.1 Mapping Knowledge to Skills**
Students must:

* Understand **Pushdown Automata** and their correspondence with formal notations.
* Apply **grammar rules** to document and simulate robot path decisions.
* Apply **analytical thinking** to connect system states with symbolic rules.

**B.5.2 Bloom’s Taxonomy Alignment**

* **Understand** for recognizing structure in rule-based models.
* **Apply** for building behavior logic using context-free languages.

**B.5.3 Verb Annotation**
Interpret, Apply, Recognize, Analyze

#### B.6 Summary Table for Competency B

| **Competency**                | **Dispositions**                                               | **Knowledge**                          | **Skill**                  |
| ----------------------------- | -------------------------------------------------------------- | -------------------------------------- | -------------------------- |
| Interpret rule-based notation | Inventive, Collaborative, Responsible, Proactive, Creative | Pushdown Automata                      | **Understand**             |
|                               |                                                                | Regular Languages                      | **Apply (Utilize, Solve)** |
|                               |                                                                | Analytical and Critical Thinking (FPK) | **Apply**                  |


### 4.3 Competency C Specification

#### C.1 Competency Title

**Differentiate classifications of formal grammars**

#### C.2 Textual Description

Understand and distinguish among formal grammar types (e.g., regular, context-free) and their corresponding automata. Use these distinctions to model and evaluate the behavior of language-based control systems.

#### C.3 Knowledge Specification

* **Regular Languages – Formal Grammars and Language Classification**
* **Analytical and Critical Thinking (FPK)**

#### C.4 Disposition Specification

This classification task requires:

* Inventive
* Collaborative
* Responsible
* Proactive

#### C.5 Knowledge-Skill Pairing

**C.5.1 Mapping Knowledge to Skills**
Students must:

* Understand grammar types and their expressive power.
* Apply analytical reasoning to distinguish and relate them to robot behavior modeling.

**C.5.2 Bloom’s Taxonomy Alignment**

* **Understand** for recognizing distinctions between grammar types.
* **Apply** for linking grammars to system specifications.

**C.5.3 Verb Annotation**
Differentiate, Classify, Compare, Contrast

#### C.6 Summary Table for Competency D

| **Competency**                                   | **Dispositions**                                     | **Knowledge**                          | **Skill**                          |
| ------------------------------------------------ | ---------------------------------------------------- | -------------------------------------- | ---------------------------------- |
| Differentiate classifications of formal grammars | Inventive, Collaborative, Responsible, Proactive | Formal Grammars                        | **Understand (Compare, Contrast)** |
|                                                  |                                                      | Analytical and Critical Thinking (FPK) | **Apply**                          |

