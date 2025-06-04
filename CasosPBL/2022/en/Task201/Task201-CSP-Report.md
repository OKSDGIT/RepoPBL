# **Surveillance Drone Prototype: Competency-Oriented Report**

**Team Members**: Lais Salvador, Edeyson A. Gomes, Luiz Gavaza
**Date**: March 21, 2022


## 1. Task Description Analysis

The problem scenario presented by SOS Florestal involves the development of a prototype surveillance module for a drone used in forest monitoring. The module must be capable of detecting and reporting deforestation, river siltation, and forest fires using optical, thermal, and positional data. The real-time transmission of photos and videos, enriched with GPS coordinates and sensor readings, enables the system to identify critical events and respond accordingly.

Given the functional requirements and limited budget, students proposed modeling the system behavior using a **Finite State Machine (FSM)**. This approach allows for representing the system's states and transitions triggered by input events, ensuring a deterministic and transparent operation model. The use of FSM also aligns with the learning objectives of the course, enabling students to apply theoretical concepts to a practical, real-world problem.


## 2. Knowledge Specification

To solve the problem effectively, the following core knowledge areas are required:

* **Finite State Machines**: Understanding states, transitions, determinism, and simulation in tools like JFLAP.
* **Regular Languages**: Grasping the class of languages recognizable by FSMs.
* **Regular Expressions**: Using concise notation to describe language patterns that can be accepted by FSMs.

* **Chomsky Hierarchy**: Positioning FSMs and regular languages in the broader hierarchy of language classes.

This knowledge will be mobilized to model the system's behavior, validate it using simulation tools, and evaluate the feasibility of minimizing the number of states and transitions based on the number of monitored events.


## 3. Learning Objectives and Expected Outcomes

### General Objective

Develop and consolidate the ability to model, implement, and document computational systems grounded in formal language theory—particularly Finite State Machines—through the resolution of real-world problems.

### Specific Learning Objectives

* Model the system’s behavior using Finite State Machines (FSMs) to represent event monitoring, transmission, and control actions of the drone.

* Simulate and validate the FSM using tools such as JFLAP, demonstrating correct operation and consistent handling of input scenarios (e.g., zoom level changes, new coordinates, transmission triggers).

* Apply the concept of Regular Languages and Regular Expressions to express behavior rules and transitions within the FSM.

* Interpret the Chomsky Hierarchy to position FSMs within the broader classification of formal languages and justify their suitability for the problem.

* Design a rule or formula that estimates the minimum number of states and transitions in the FSM, based on the number of monitored events (e.g., deforestation, fire, siltation).

* Produce a technical report in SBC format that documents the design rationale, formal modeling process, simulation results, and mathematical justifications for decisions (e.g., budget estimations, modeling choices).


## 4. Competency Definition


### Reusability Note 

To address the Learning Objectives, we reuse the competency defined in Task01 – The Vending Machine for Sodas and Snacks. As tarefas são semelhantes em termos de propósito (modelagem e simulação de sistemas com autômatos finitos), o que permite o reuso direto das seguintes competências:

* Develop problem solutions using Automata
  * Justificativa: A Task201 requer modelar o comportamento do sistema do drone com autômatos finitos. A competência A cobre design, construção e validação desses modelos.

  * Conhecimentos: Finite State Machines, Requirements Engineering, Critical Thinking. 

* Justify the use of Deterministic Finite Automata (DFAs)
  * Justificativa: A Task201 exige justificar como os alunos chegaram à decisão de usar autômatos finitos, o que envolve diferenciar modelos determinísticos.

  * Conhecimentos: DFAs, Requirements Engineering, Critical Thinking.

* Test automata using simulators
  * Justificativa: A entrega inclui um arquivo JFLAP e simulações do comportamento do drone, exatamente o que essa competência cobre.

  * Conhecimentos: Finite State Machines, Modeling and Simulation, Problem Solving.

* Define Regular Expressions for Finite Automata
  * Justificativa: A Task201 menciona a criação de uma expressão matemática (regular expression) representando o comportamento do sistema.

  * Conhecimentos: Regular Expressions, Finite State Machines, Analytical Thinking.

* Write a technical report
  * Justificativa: O produto inclui um relatório técnico no formato da SBC. Esta competência cobre todas as habilidades envolvidas.

  * Conhecimentos: Written Communication.

