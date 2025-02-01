# Competency Specification Report: Task1 - The Vending Machine for Sodas and Snacks

## 1. Introduction

This report presents the application of the **Competency Specification Process** to the **Task1 - The Vending Machine for Sodas and Snacks**, a Problem-Based Learning (PBL) scenario that explores the use of **finite automata and regular expressions** in the design of vending machine software and hardware solutions. The full description of the task can be accessed at:  
[Task1 - The Vending Machine for Sodas and Snacks](https://github.com/EduKnowUFBA/RepoPBL/blob/main/CasosPBL/2021/en/Task01/Problem01-TheVendingMachine.md).

The **Competency Specification Process** is a structured methodology designed to **identify, classify, and document competencies** embedded within an educational task. By analyzing the task description, required knowledge, learning objectives, and behavioral dispositions, this process enables educators to define a competency framework that aligns with **real-world problem-solving and educational objectives**.

### **Objective of this Report**
The primary goal of this report is to demonstrate how the **Competency Specification Process** is applied to **Task1** by systematically identifying:
- The **knowledge components** required to solve the problem.
- The **learning objectives** explicitly and implicitly embedded in the task.
- The **skills and competencies** necessary for effective task resolution.
- The **behavioral dispositions** that contribute to a successful learning experience.

### **Structure of this Report**
The document is structured as follows:
1. **Task Analysis**: A breakdown of the task description, identifying its key elements.
2. **Knowledge Enumeration**: Specification of the domain-specific knowledge required for task resolution.
3. **Learning Objectives Identification**: Mapping explicit and implicit learning objectives from the task.
4. **Competency Definition**: Classification and detailed description of the competencies involved.
5. **Knowledge-Skill Pairing**: Association of knowledge components with specific skills using Bloom’s Taxonomy.
6. **Conclusion**: Reflection on how the process enhances competency-based learning.

By applying this structured approach, we aim to highlight the **alignment between problem-based learning and competency development**, ensuring that learners acquire both **technical expertise and essential cognitive and behavioral skills** needed for real-world applications.


## 1. Task Description Analysis

The PBL task titled **"The Vending Machine for Sodas and Snacks"** presents a problem related to **change calculation in vending machine transactions**, where payments are made using coins and banknotes. The task requires students to design a solution that enables the vending machine to accept payments, dispense change accurately, and operate according to predefined functional requirements.

To successfully address this problem, students must demonstrate their ability to:
- **Apply finite automata** concepts to model the vending machine’s behavior.
- **Simulate and validate** the automaton’s functionality using computational tools.
- **Document the development process** in a structured and technical manner.

This task not only assesses students’ understanding of **automata theory** but also evaluates their ability to:
1. **Analyze real-world constraints** and translate them into a formal computational model.
2. **Design and implement** an automaton that meets functional requirements.
3. **Justify and explain** design decisions through a well-structured technical report.

Additionally, the task introduces an optional challenge: implementing a **randomized bonus change feature**, where the vending machine occasionally provides an extra R$1.00 when the exact product price is paid. This adds a **stochastic element** to the system, encouraging students to consider **probabilistic behaviors** within their automaton design.

Through this structured **Problem-Based Learning (PBL) scenario**, students engage with a **real-world problem**, bridging theoretical knowledge with **practical computational modeling**, simulation, and technical documentation.


## 2. Knowledge Enumeration

To systematically enumerate the computing knowledge required for this task, the **ACM Computing Classification System (2012)** was used as a controlled vocabulary. This classification system is widely recognized and globally adopted, ensuring standardization and consistency in the categorization of computing knowledge.  

For **professional knowledge (FPK)**, we referenced the **ACM Computing Curriculum (CC) 2020**, which provides a structured framework for essential professional competencies.  

Based on the **task description**, the following set of required knowledge components was identified:  

### **Computing Knowledge**  
- **Automata over Infinite Objects (Deterministic Finite Automata - DFA)**  
  - Involves the study and application of mathematical models that describe computational systems using **states and transitions**.  
  - Essential for designing **state-based vending machine logic**.  

- **Regular Languages (Regular Expressions - RE)**  
  - Requires understanding and applying **formal techniques** to represent and manipulate string sets.  
  - Used primarily in **text processing, lexical analysis, and pattern matching** within the vending machine’s operational logic.  

- **Requirements Analysis (Software Requirements Engineering)**  
  - A systematic process for **collecting, analyzing, and specifying system requirements**.  
  - Ensures that **user needs and system expectations** are clearly understood and documented.  

- **Simulation Tools**  
  - Involves the use of **automata simulation tools** (such as JFLAP) to validate and analyze **proposed solutions**.  
  - Enables **testing, debugging, and refining** the vending machine’s automaton before implementation.  

### **Professional Knowledge (FPK)**  
- **Analytical and Critical Thinking**  
  - The ability to **break down complex problems into fundamental components**, evaluate results, and make well-reasoned decisions based on rigorous analysis.  

- **Problem Solving and Troubleshooting**  
  - Requires identifying, analyzing, and resolving **task-specific challenges** using **effective strategies and computational methods** to develop optimal solutions.  

- **Written Communication**  
  - The ability to **compose clear and structured technical reports** detailing the design, implementation, and validation processes.  
  - Ensures that findings and decisions are effectively communicated to stakeholders.  

This **knowledge enumeration** serves as the foundation for competency specification, ensuring that students acquire both **theoretical and practical expertise** necessary to complete the task successfully.


## 3. Learning Objectives Identification

The **general objective** of this task is to develop **finite automata and regular expressions** to solve **real-world problems** by modeling a vending machine system. This objective emphasizes the practical application of **automata theory** in computational problem-solving.

### **Specific Learning Objectives**
To achieve this general objective, students must demonstrate the ability to:

1. **Identify system functionalities**  
   - Analyze the user’s conceptual model of the vending machine and define its expected behaviors.

2. **Align user requirements with automaton functionalities**  
   - Reconcile the vending machine's desired functionalities with the constraints and capabilities of the automaton being developed.

3. **Evaluate the role of non-determinism in finite automata**  
   - Assess when and how **non-deterministic finite automata (NFA)** can be used effectively in the system’s design.

4. **Understand equivalences between deterministic and non-deterministic automata**  
   - Demonstrate an understanding of the equivalence between **Deterministic Finite Automata (DFA)** and **Non-Deterministic Finite Automata (NFA)**, highlighting scenarios where one might be preferable over the other.

5. **Understand the equivalence between Finite Automata (FA) and Regular Expressions (RE)**  
   - Establish connections between **finite automata representations** and **regular expressions**, reinforcing their theoretical and practical interchangeability.

6. **Apply FA-to-RE equivalence in the development of regular expressions**  
   - Utilize existing finite automata to derive **corresponding regular expressions**, applying formal methods to convert automata into equivalent regex patterns.

7. **Associate vending machine options, coins, and banknotes with alphabet symbols**  
   - Map real-world elements of the vending machine (such as product selections and payment methods) onto the **formal alphabet** used in automaton design.

8. **Develop technical reports**  
   - Document the **design, implementation, and validation** of the automaton, ensuring clarity and precision in technical writing.

9. **Use finite automata simulation tools**  
   - Apply tools such as **JFLAP** to simulate, analyze, and verify the functionality of the designed automaton.

### **Importance of These Objectives**
These learning objectives provide a **structured pathway** for competency development, ensuring that students acquire:
- **A strong theoretical foundation** in automata and formal languages.
- **The ability to bridge theory and practice**, applying formal methods to solve computational problems.
- **Hands-on experience with simulation tools**, reinforcing practical problem-solving skills.
- **Technical communication skills**, essential for conveying solutions in professional and academic contexts.

By achieving these objectives, students will be equipped with both the **computational and analytical skills** necessary for modeling real-world systems using **finite automata and regular expressions**.


## 4. Competency Definition

Competencies are specified based on the **Learning Objectives (LOs)** identified in the task analysis.


### **Competency 1: Designing Efficient Solutions with Automata**  

#### **4.1 Competency Title**  
**Designing Efficient Solutions with Automata**  

#### **4.2 Textual Description**  
This competency focuses on the ability to design and implement **effective and optimized solutions** using **finite automata**. It requires a **deep understanding of automata theory**, including the identification of functional requirements, translating those into **feasible technical implementations**, and ensuring that the **final automaton is efficient, reliable, and meets user expectations**.

Students must **balance user-defined needs with automata constraints**, ensuring that the vending machine system performs correctly under different conditions. This competency also emphasizes the **importance of validation**, requiring students to **simulate, test, and refine their models** to guarantee accuracy and performance in **real-world applications**.

Additionally, the competency includes the **ability to handle additional constraints**, such as implementing the **bonus change mechanism** introduced as an extra challenge by the IT technician.

## 4.3 Knowledge Specification  
The following knowledge areas are critical for this competency:  

- **Automata over Infinite Objects**  
  - Fundamental for modeling the vending machine’s operational logic.  
  - Involves designing states and transitions to represent system functionalities.  

- **Requirements Analysis**  
  - Ensures an accurate **identification and documentation of system requirements**.  
  - Bridges user needs with the technical capabilities of finite automata.  

- **Analytical and Critical Thinking (FPK)**  
  - Required for **problem decomposition and strategic planning**.  
  - Helps in aligning user requirements with technical feasibility while optimizing computational resources.  


## 4.4 Attitude Specification  
The **"Vending Machine for Sodas and Snacks"** task highlights key behavioral attributes necessary for problem-solving and effective team collaboration. These include:  

### **Collaboration**  
- The task follows the **Problem-Based Learning (PBL) methodology**, requiring continuous team interaction.  
- Essential for developing solutions collaboratively through **PBL whiteboard sessions**, maintaining the **logbook**, and **documenting each project phase**.  
- Encourages **knowledge-sharing** and iterative improvements.  

### **Responsibility**  
- Ensures adherence to **project deadlines**, accurate **documentation**, and a **functional automaton design**.  
- Requires individual accountability for contributions, ensuring that the **final deliverable meets user expectations** and project standards.  

### **Proactivity**  
- Encourages anticipating challenges, such as the **randomized bonus change feature (R$1.00 extra)**, which requires **additional research and technical adjustments**.  
- Involves actively seeking knowledge, including the **relationship between regular expressions and finite automata**.  
- Supports a proactive approach to debugging, refining, and improving the system.  

### **Creativity**  
- Necessary for adapting automata **functionalities to specific user requirements**.  
- Encourages exploring **alternative implementations**, such as incorporating **randomized elements** in automata behavior.  
- Enhances **technical documentation**, making system operations visually and conceptually engaging.  


## 4.5 Knowledge-Skill Pairing  

This step maps **knowledge areas to the corresponding skills** required to successfully demonstrate competency in this task.  

### **4.5.1 Mapping Knowledge to Skills**  
To achieve this competency, students must demonstrate the ability to:  

- **Apply** Analytical and Critical Thinking along with knowledge of **Automata over Infinite Objects** to **solve the vending machine’s change calculation problem**.  
- **Identify and interpret** system requirements, demonstrating proficiency in **Requirements Analysis**.  


### **4.5.2 Bloom’s Taxonomy Alignment**  
To accurately assess the required skills for this competency, each knowledge component is aligned with **Bloom’s Revised Taxonomy** to ensure a structured and progressive learning approach.

- **Analytical and Critical Thinking (FPK) – Apply**  
  - Assesses the student's ability to **decompose complex problems** into fundamental components.  
  - Evaluates the ability to **analyze relationships, identify patterns, and formulate logical strategies** for problem-solving.  
  - Ensures students can effectively **bridge theoretical knowledge with practical implementation**.  

- **Automata over Infinite Objects – Apply**  
  - Measures the student's capability to **design and implement automata-based solutions** for a defined problem.  
  - Assesses the ability to **translate real-world system constraints into automata models** using states and transitions.  
  - Ensures that students can effectively **apply computational modeling techniques** to solve vending machine transaction issues.  

- **Requirements Analysis – Understand**  
  - Evaluates the student's proficiency in **interpreting system constraints and user requirements**.  
  - Ensures comprehension of **functional and non-functional system requirements** before implementation.  
  - Assesses the ability to **logically structure and organize** requirements for a formal computational model.  

---

### **4.5.3 Verb Annotation**  
To provide clarity on competency expectations, the following verb annotations define the required actions:  

- **Apply** → Automata over Infinite Objects → **Solve** vending machine payment and change-related problems using automata.  
- **Understand** → Requirements Analysis → **Interpret and structure** system constraints to define an effective computational model.  




### **4.5.4 Summary Table for Competency 1**  

| **Competency** | **Attitudes (Dispositions)** | **Knowledge-Skill Mapping** |
|---------------|-----------------------------|-----------------------------|
| **Develop problem solutions using Automata** | **Collaborative, Responsible, Proactive, Creative** | |
| **Knowledge** | **Skill** | |
| Automata over Infinite Objects | **Apply (Solve)** |
| Requirements Analysis | **Understand (Interpret & Structure)** |
| Analytical and Critical Thinking (FPK) | **Apply (Analyze & Synthesize)** |

