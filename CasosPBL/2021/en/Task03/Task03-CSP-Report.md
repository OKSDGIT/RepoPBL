# Competency Specification Report: Task2 – Traffic Control

## Introduction

This report applies the **Competency Specification Process (CSP)** to the Problem-Based Learning (PBL) scenario entitled **"Traffic Control"**, which engages students in designing a computational solution using **Turing Machines** to address vehicle monitoring and classification on highways. The task integrates formal methods and systems thinking to model a real-world problem posed by the Bahia Department of Transport Infrastructure (DERBA).

Through the CSP methodology, competencies are extracted and structured based on the analysis of the task description, relevant knowledge domains, learning objectives, and behavioral dispositions. The goal is to define a robust competency framework aligned with both **technical skill development** and **collaborative problem solving**.



## 1. Task Description Analysis

The *Traffic Control* task challenges students to develop a formal computational solution that addresses a real-world issue identified by the **Bahia Department of Transport Infrastructure (DERBA)**: the deterioration of highways due to excessive pressure from nighttime heavy vehicle traffic.

To support pavement wear prevention efforts, students must design a system capable of:

* **Processing sensor data** collected from vehicle entries and exits on the Aratu highway;
* **Classifying vehicles** into three weight categories (light, heavy, and very heavy);
* **Counting occurrences** for each category during the previous night; and
* **Identifying the most frequent category**, enabling DERBA to prioritize interventions.

The system must be modeled using **Turing Machines**, reflecting a theoretical yet expressive model of computation. Deliverables include one or more **JFLAP-based Turing Machine files** and a **technical report** compliant with SBC formatting standards, clearly explaining the classification logic, design rationale, and simulation process.

This task requires learners to:

* **Translate user-defined goals** into formal system specifications based on computability theory;
* **Model real-world constraints** (e.g., sensor input structure, weight classification logic) using Turing Machines;
* **Evaluate the use of Turing Machine variants** (e.g., multi-tape, non-deterministic) when standard models are insufficient;
* **Simulate and test** the model using appropriate tools to ensure functional correctness;
* **Collaborate effectively** during the problem-solving process, documenting all steps and decisions in a structured and reflective manner.

Through this problem-based learning scenario, students are expected to integrate **theoretical knowledge of computation** with **practical modeling and simulation**, producing a solution that is both educationally rigorous and socially relevant.




## 2. Knowledge Enumeration

To successfully complete the *Traffic Control* task, students must mobilize a set of interrelated theoretical and professional knowledge domains. These domains are aligned with recognized taxonomies: the **ACM Computing Classification System (2012)** for computing knowledge and the **ACM/IEEE CC2020** for professional competencies.

This knowledge foundation ensures that the problem is addressed not only from a technical perspective but also through analytical reasoning, formal specification, and effective communication.

### Computing Knowledge

* **Turing Machines**
  Fundamental for representing the computational process required to classify vehicles and compute frequency statistics. Students must understand the structure, behavior, and expressive power of Turing Machines to encode real-world operations in a formal model.

* **Turing Machine Variants**
  Knowledge of multi-tape or non-deterministic Turing Machines is essential when standard models are insufficient for performance or expressiveness. Variants allow for more efficient data manipulation and system simulation under complex constraints.

* **Church-Turing Thesis**
  Provides the theoretical basis for the task, reinforcing the equivalence between algorithmic reasoning and Turing-computable functions. Students are expected to ground their solutions in this foundational concept.

* **Requirements Engineering**
  Enables the identification, analysis, and formalization of user needs (e.g., DERBA’s demand for nighttime traffic classification) into computational requirements that guide system design.

* **Modeling and Simulation**
  Involves abstracting system behaviors into formal representations and validating them through tools such as **JFLAP**. This knowledge area supports iterative refinement and verification of the proposed solution.

### Professional Knowledge (FPK)

* **Analytical and Critical Thinking**
  Required to deconstruct the problem context (e.g., traffic monitoring and classification) into actionable components, and to formulate logical models that meet stakeholder expectations.

* **Problem Solving and Troubleshooting**
  Essential for addressing implementation issues, such as handling non-standard input formats, optimizing tape usage, or debugging Turing Machine simulations.

* **Written Communication**
  Needed to produce a well-structured and technically sound report that documents the design rationale, implementation decisions, and validation strategies. This ensures that results are effectively communicated to technical and non-technical audiences, such as DERBA.




## 3. Learning Objectives Identification

### General Objective

Develop and validate formal computational solutions to real-world problems by applying knowledge of **Turing Machines**, with a focus on modeling, classifying, and analyzing traffic data based on sensor input.

This objective highlights the practical application of theoretical computer science concepts, reinforcing the ability to design algorithmic solutions grounded in formal models.

### Specific Objectives

To achieve the general objective, students are expected to:

1. **Identify** system requirements and constraints based on stakeholder input, particularly the needs expressed by DERBA for traffic data analysis and classification.
2. **Translate and align** these requirements with the computational capabilities and limitations of Turing Machines, ensuring a faithful and executable system design.
3. **Evaluate** the adequacy of standard Turing Machines and determine when the use of **machine variants** (e.g., multi-tape, non-deterministic) is necessary to enhance expressiveness or performance.
4. **Apply** the **Church-Turing Thesis** to justify the feasibility of the proposed system, connecting formal computation models with the intuitive concept of algorithmic problem solving.

### Importance of These Objectives

These learning objectives establish a **structured and progressive pathway** for competency development by integrating:

* **Theoretical understanding** of formal computation models;
* **Contextual analysis** of real-world problems;
* **Modeling and simulation skills** for system implementation and validation;
* **Critical reflection** on computational adequacy and design decisions.

Together, they ensure that learners are equipped to bridge the gap between **abstract theoretical concepts** and **practical problem-solving**, fostering a competency-based learning experience that is both rigorous and relevant to professional contexts in computing.



## 4. Competency Definitions

Competencies are specified based on the **Learning Objectives (LOs)** identified in the task analysis.

As one of the deliverables required for this task is a technical report structured according to the **Brazilian Computer Society (SBC)** academic article template, students are expected to write a formal technical document that explains the problem-solving process in a clear, organized, and rigorous manner.

Given these requirements, we **reuse the previously defined competency in Task01**:
**"Write a Technical Report."**

This competency remains fully applicable here. Its core learning outcomes—including structuring content, integrating team contributions, and communicating technical decisions effectively—are essential for this task as well.

By reusing this competency, we:

* Ensure **consistency in learning expectations** across tasks that involve technical documentation.
* **Reinforce the importance of written communication** as a transversal skill in computing education.
* Promote **competency traceability**, avoiding redundancy and ensuring that learning achievements can be accumulated and evidenced across different instructional contexts.

This reuse also aligns with the **competency-based education model**, in which a single well-defined competency can support multiple learning goals across diverse tasks, provided the context of application remains pedagogically consistent.









### 4.1 Competency A Specification

### A.1 Competency Title

**Develop Problem-Solving Solutions Using Finite State Machines**


### A.2 Textual Description

Design and implement computational solutions using **Finite State Machines (FSMs)** to address real-world or instructional problems involving system modeling through states and transitions. This competency reflects the student's ability to apply theoretical knowledge of automata in constructing reliable and verifiable models that fulfill defined system requirements.

Originally developed for a task involving livestock group identification, the competency has been generalized to promote **reusability** across different learning contexts. The verb was revised from “apply” to **“develop”** to emphasize creative construction, while maintaining the core knowledge domains required for effective implementation.

Students are expected to demonstrate not only mastery of FSMs, but also the ability to analyze system requirements and apply logical reasoning to model behavior, ensuring that the solution is both theoretically sound and practically relevant.



### A.3 Knowledge Specification

The following knowledge areas are critical for this competency:

* **Finite State Machines (FSMs)**
  Understand and apply the structure, behavior, and applications of deterministic and non-deterministic automata to model sequential systems.

* **Requirements Analysis**
  Identify, interpret, and translate system requirements into formal specifications for FSM design.

* **Analytical and Critical Thinking (FPK)**
  Break down the problem, assess constraints and goals, and select appropriate modeling strategies to guide the design process.



### A.4 Disposition Specification

Given the collaborative nature of the task and the need for creative model development, the following behavioral dispositions are essential:

* **Inventive**
  Propose novel modeling strategies and explore different ways of structuring FSMs to reflect system behavior.

* **Collaborative**
  Cooperate with peers in discussing requirements, designing the machine, and validating its behavior.

* **Responsible**
  Take ownership of the solution's quality, ensuring consistency with task expectations and timelines.

* **Proactive**
  Anticipate implementation challenges and adapt the design to improve accuracy and functionality.

* **Creative**
  Transform system requirements into intuitive and innovative models, making abstract behaviors operational through states and transitions.



### A.5 Knowledge-Skill Pairing

This step maps **knowledge areas to the corresponding skills** required to successfully demonstrate competency in this task.

**A.5.1 Mapping Knowledge to Skills**
To demonstrate this competency, students must show the ability to:

* **Apply** knowledge of **Finite State Machines** to design models that reflect real-world behaviors through structured state transitions.

* **Apply** **Requirements Analysis** to understand the user’s expectations and translate them into clear formal specifications that guide FSM design.

* **Apply** **Analytical and Critical Thinking (FPK)** to interpret the problem, analyze possible design paths, and justify modeling decisions based on logic and feasibility.



**A.5.2 Bloom’s Taxonomy Alignment**

* *Apply* is used for all three knowledge areas to assess students’ ability to transfer theoretical knowledge into practice.
* *Create* is applied to evaluate the student's ability to design and construct original FSMs that meet specified requirements.



**A.5.3 Verb Annotation**
To provide clarity on competency expectations, the following verb annotations define the required actions:

* **Apply** → Finite State Machines → *Use, Implement, Simulate*
* **Apply** → Requirements Analysis → *Interpret, Specify, Translate*
* **Apply** → Analytical and Critical Thinking → *Analyze, Justify, Evaluate*
* **Create** → Finite State Machines → *Construct, Design, Develop*



### A.6 Summary Table for Competency A

| **Competency**                                                    | **Dispositions**                                           | **Knowledge**                          | **Skill**                                 |
| ----------------------------------------------------------------- | ---------------------------------------------------------- | -------------------------------------- | ----------------------------------------- |
| **Develop Problem-Solving Solutions Using Finite State Machines** | Inventive, Collaborative, Responsible, Proactive, Creative | Finite State Machines                  | **Apply / Create**                        |
|                                                                   |                                                            | Requirements Analysis                  | **Apply (Interpret, Specify, Translate)** |
|                                                                   |                                                            | Analytical and Critical Thinking (FPK) | **Apply (Analyze, Justify, Evaluate)**    |




### 4.3 Competency B Specification

### B.1 Competency Title

**Determine Regular Expressions that Represent Automata**



### B.2 Textual Description

Develop and refine **regular expressions** that represent the behavior of finite automata. This competency involves translating automata structures—either fully or partially—into equivalent formal language representations, demonstrating both theoretical understanding and practical modeling skills.

Originally formulated to guide students in documenting a specific automaton segment, the competency was generalized to ensure **reusability** across different learning tasks. It now encompasses the ability to define regular expressions for any automaton, reinforcing its application in varied contexts involving formal language specification.



### B.3 Knowledge Specification

The following knowledge areas are critical for this competency:

* **Regular Languages**
  Understand the syntax, semantics, and expressive power of regular expressions and their equivalence to finite automata.

* **Finite State Machines (FSMs)**
  Provide the structural basis for identifying language patterns that regular expressions must represent.

* **Problem Solving and Troubleshooting (FPK)**
  Support the analysis of automaton behavior and the iterative refinement of regular expressions to ensure correctness.



### B.4 Disposition Specification

Given that the task involves formal modeling, precision, and teamwork, the following behavioral dispositions are essential:

* **Inventive**
  Explore different strategies to minimize or optimize regular expressions while preserving equivalence with automata.

* **Collaborative**
  Work with peers to compare interpretations, validate equivalence, and improve expression quality.

* **Responsible**
  Ensure theoretical correctness and clarity in the representation of automaton behavior.

* **Proactive**
  Take initiative to test, revise, and document the regular expressions developed.

* **Creative**
  Construct clear and elegant expressions that balance simplicity and descriptive power.



### B.5 Knowledge-Skill Pairing

This step maps **knowledge areas to the corresponding skills** required to successfully demonstrate competency in this task.

**B.5.1 Mapping Knowledge to Skills**
To demonstrate this competency, students must show the ability to:

* **Apply** knowledge of **Regular Languages** to construct expressions that accurately capture the behavior of finite automata.

* **Apply** knowledge of **Finite State Machines** to decompose their behavior into regular language patterns.

* **Apply** **Problem Solving and Troubleshooting (FPK)** to analyze, test, and refine regular expressions until they align with the intended automaton structure.



**B.5.2 Bloom’s Taxonomy Alignment**

* *Apply* level is used across all knowledge areas to assess the student's ability to use formal representations in practice, aligning automaton structures with regular expressions and iteratively validating their equivalence.



**B.5.3 Verb Annotation**
To provide clarity on competency expectations, the following verb annotations define the required actions:

* **Apply** → Regular Languages → *Construct, Express, Represent*
* **Apply** → Finite State Machines → *Decompose, Translate, Compare*
* **Apply** → Problem Solving and Troubleshooting → *Analyze, Test, Refine*



### B.6 Summary Table for Competency C

| **Competency**                                            | **Dispositions**                                           | **Knowledge**                             | **Skill**                                 |
| --------------------------------------------------------- | ---------------------------------------------------------- | ----------------------------------------- | ----------------------------------------- |
| **Determine Regular Expressions that Represent Automata** | Inventive, Collaborative, Responsible, Proactive, Creative | Regular Languages                         | **Apply (Construct, Express, Represent)** |
|                                                           |                                                            | Finite State Machines                     | **Apply (Decompose, Translate, Compare)** |
|                                                           |                                                            | Problem Solving and Troubleshooting (FPK) | **Apply (Analyze, Test, Refine)**         |


---

### 4.3 Competency C Specification

### C.1 Competency Title

**Infer and Identify Patterns in Finite State Machines**



### C.2 Textual Description

Analyze the structure and behavior of **Finite State Machines (FSMs)** to draw inferences and identify emerging patterns that influence model complexity and performance. This competency involves recognizing relationships between input classifications, state transitions, and the number of states required for effective modeling.

Originally derived from a context involving herd identification and state minimization, the competency was generalized to ensure **reusability** across learning tasks where pattern recognition and structural analysis are essential to problem solving.

Students are expected to demonstrate the ability to **analyze FSMs**, detect design regularities or redundancies, and apply **Analytical and Critical Thinking (FPK)** to refine and interpret system behavior.



### C.3 Knowledge Specification

The following knowledge areas are critical for this competency:

* **Finite State Machines**
  Understand structural properties of FSMs, including states, transitions, and minimization principles, and how these influence computational modeling.

* **Analytical and Critical Thinking (FPK)**
  Apply logical reasoning to identify hidden structures, draw meaningful conclusions, and justify design decisions based on pattern recognition and model analysis.



### C.4 Disposition Specification

Given the abstract nature of the task and the cognitive demands of pattern recognition and inference, the following behavioral dispositions are essential:

* **Inventive**
  Approach FSM analysis with originality, exploring non-obvious or alternative interpretations of structural behavior.

* **Creative**
  Devise innovative methods to visualize, interpret, or generalize state-based patterns.

* **Meticulous**
  Pay careful attention to detail when identifying similarities, redundancies, or inefficiencies in state design and transitions.



### C.5 Knowledge-Skill Pairing

This step maps **knowledge areas to the corresponding skills** required to successfully demonstrate competency in this task.

**C.5.1 Mapping Knowledge to Skills**
To demonstrate this competency, students must show the ability to:

* **Apply** knowledge of **Finite State Machines** to analyze state structures and identify how input categories relate to the number of states and transitions required.

* **Apply** **Analytical and Critical Thinking (FPK)** to make accurate inferences, recognize behavioral patterns, and refine FSM designs accordingly.



**C.5.2 Bloom’s Taxonomy Alignment**

* *Apply* level is used to evaluate the ability to recognize and explain patterns in FSMs and justify design improvements based on evidence and reasoning.



**C.5.3 Verb Annotation**
To provide clarity on competency expectations, the following verb annotations define the required actions:

* **Apply** → Finite State Machines → *Analyze, Evaluate, Compare*
* **Apply** → Analytical and Critical Thinking → *Infer, Justify, Interpret*



### C.6 Summary Table for Competency C

| **Competency**                                           | **Dispositions**                | **Knowledge**                          | **Skill**                              |
| -------------------------------------------------------- | ------------------------------- | -------------------------------------- | -------------------------------------- |
| **Infer and Identify Patterns in Finite State Machines** | Inventive, Creative, Meticulous | Finite State Machines                  | **Apply (Analyze, Evaluate, Compare)** |
|                                                          |                                 | Analytical and Critical Thinking (FPK) | **Apply (Infer, Justify, Interpret)**  |


Abaixo está a **Competência D** elaborada em **inglês e Markdown**, no formato do CSP-Report, com foco na clareza conceitual, reusabilidade e estrutura pedagógica alinhada ao objetivo 3.

---

### 4.4 Competency D Specification

### D.1 Competency Title

**Differentiate the Classifications of Formal Grammars**



### D.2 Textual Description

Understand and differentiate the various **classes of formal grammars**—as defined by the Chomsky hierarchy—based on their generative power and relation to automata. This competency involves identifying characteristics that distinguish regular, context-free, context-sensitive, and unrestricted grammars, and recognizing their applicability to computational problem-solving.

In the context of the *Robotic Farmer* task, this competency reinforces the theoretical foundation required to select and justify the appropriate computational model (e.g., Finite Automaton) based on system constraints and requirements. Although originally tied to a specific task, the competency has been generalized to promote **reusability** in any learning scenario involving formal languages and automata theory.

Students are expected to demonstrate a **conceptual understanding** of grammar classification and apply this understanding when specifying system behaviors, translating requirements into executable logic through **Requirements Engineering** and **Analytical and Critical Thinking (FPK).**



### D.3 Knowledge Specification

The following knowledge areas are critical for this competency:

* **Formal Grammars and Language Classification**
  Understand the hierarchical organization of grammars and their relationship to classes of automata and language recognition.

* **Requirements Engineering**
  Translate user needs into system specifications that are compatible with the expressive power of the selected formal language model.

* **Analytical and Critical Thinking (FPK)**
  Interpret system constraints, evaluate grammar applicability, and reason about which classification best suits a given computational problem.



### D.4 Disposition Specification

Given the analytical depth and collaborative demands of the task, the following behavioral dispositions are essential:

* **Collaborative**
  Participate actively in team-based discussions to classify grammars and align them with solution strategies.

* **Responsible**
  Ensure accuracy in theoretical classification and maintain alignment between system specifications and computational models.

* **Proactive**
  Anticipate limitations in modeling choices and explore alternatives within the Chomsky hierarchy.

* **Investigative**
  Explore the theoretical implications of grammar choice and examine edge cases in grammar-automaton equivalence.



### D.5 Knowledge-Skill Pairing

This step maps **knowledge areas to the corresponding skills** required to successfully demonstrate competency in this task.

**D.5.1 Mapping Knowledge to Skills**
To demonstrate this competency, students must show the ability to:

* **Understand** the classes of **Formal Grammars** and relate them to their corresponding automata and computational properties.

* **Apply** **Requirements Engineering** to ensure that chosen formal models meet stakeholder needs and system constraints.

* **Apply** **Analytical and Critical Thinking (FPK)** to reason through grammar selection, justify modeling choices, and interpret theoretical implications in practical contexts.



**D.5.2 Bloom’s Taxonomy Alignment**

* *Understand* level is used to assess the student’s conceptual ability to classify grammars and associate them with the correct type of automaton.
* *Apply* level is used to evaluate the student’s capacity to translate system requirements and theoretical knowledge into appropriate model selection and implementation.



**D.5.3 Verb Annotation**
To provide clarity on competency expectations, the following verb annotations define the required actions:

* **Understand** → Formal Grammars → *Differentiate, Compare, Classify*
* **Apply** → Requirements Engineering → *Specify, Translate, Align*
* **Apply** → Analytical and Critical Thinking → *Interpret, Justify, Evaluate*



### D.6 Summary Table for Competency D

| **Competency**                                           | **Dispositions**                                     | **Knowledge**                               | **Skill**                                         |
| -------------------------------------------------------- | ---------------------------------------------------- | ------------------------------------------- | ------------------------------------------------- |
| **Differentiate the Classifications of Formal Grammars** | Collaborative, Responsible, Proactive, Investigative | Formal Grammars and Language Classification | **Understand (Differentiate, Compare, Classify)** |
|                                                          |                                                      | Requirements Engineering                    | **Apply (Specify, Translate, Align)**             |
|                                                          |                                                      | Analytical and Critical Thinking (FPK)      | **Apply (Interpret, Justify, Evaluate)**          |


