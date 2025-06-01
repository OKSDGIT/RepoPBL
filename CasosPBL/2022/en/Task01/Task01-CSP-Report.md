# **Surveillance Drone Prototype: Competency-Oriented Report**

**Team Members**: Lais Salvador, Edeyson A. Gomes, Luiz Gavaza
**Date**: March 21, 2022

---

## 1. Task Description Analysis

The problem scenario presented by SOS Florestal involves the development of a prototype surveillance module for a drone used in forest monitoring. The module must be capable of detecting and reporting deforestation, river siltation, and forest fires using optical, thermal, and positional data. The real-time transmission of photos and videos, enriched with GPS coordinates and sensor readings, enables the system to identify critical events and respond accordingly.

Given the functional requirements and limited budget, students proposed modeling the system behavior using a **Finite State Machine (FSM)**. This approach allows for representing the system's states and transitions triggered by input events, ensuring a deterministic and transparent operation model. The use of FSM also aligns with the learning objectives of the course, enabling students to apply theoretical concepts to a practical, real-world problem.

---

## 2. Knowledge Specification

To solve the problem effectively, the following core knowledge areas are required:

* **Finite State Machines**: Understanding states, transitions, determinism, and simulation in tools like JFLAP.
* **Regular Languages**: Grasping the class of languages recognizable by FSMs.
* **Regular Expressions**: Using concise notation to describe language patterns that can be accepted by FSMs.
* **Chomsky Hierarchy**: Positioning FSMs and regular languages in the broader hierarchy of language classes.

This knowledge will be mobilized to model the system's behavior, validate it using simulation tools, and evaluate the feasibility of minimizing the number of states and transitions based on the number of monitored events.

---

## 3. Learning Objectives and Expected Outcomes

### General Objective

Develop and consolidate the ability to model, implement, and document computational systems grounded in formal language theory—particularly Finite State Machines—through the resolution of real-world problems.

### Specific Learning Objectives

* Master the conceptual and operational foundations of FSMs and their connections to regular languages and regular expressions.
* Translate the requirements of a surveillance drone into a finite state representation that reflects its operational logic.
* Apply regular expressions to capture and simulate expected input behaviors and sensor triggers.
* Experiment with FSM minimization strategies to optimize system design for cost and complexity.
* Validate the FSM using JFLAP simulations, including at least two illustrative scenarios.
* Relate FSM design to the practical constraints and informational needs of a real company.
* Collaboratively document the rationale, design, and implementation details in a technical report following SBC formatting standards.


## 4. Competency Definition


### Reusability Note 

The competency **"Document formal solutions using SBC technical report standards"** was **reused** from previous tasks, as it is a **cross-cutting academic skill** required across multiple projects in the course.

Its continued application reinforces the importance of academic communication, particularly in documenting formal models and solutions using the SBC format. By reusing this competency, students deepen their proficiency in producing high-quality, technically accurate, and standards-compliant reports.

The reuse also aligns with the course’s broader educational goals of developing transferable skills applicable across various computational modeling contexts.




### 4.1 Competency A Specification

### A.1 Competency Title

    Develop problem-solving systems using finite state machines


### A.2 Textual Description

Design and implement formal models using Finite State Machines (FSM) to represent and simulate systems that respond to sequences of inputs and environmental conditions.

### A.3 Knowledge Specification

The following knowledge areas are critical for this competency:

* Finite State Machines (FSMs)
* Regular Languages
* Requirements Analysis
* Analytical and Critical Thinking (FPK)

### A.4 Disposition Specification

A análise da tarefa revelou a necessidade de posturas voltadas à colaboração, responsabilidade e raciocínio analítico aplicado à modelagem formal de sistemas computacionais.
As principais disposições incluem: Collaborative, Responsible, Proactive, Analytical, Systematic.

### A.5 Knowledge-Skill Pairing

This step maps **knowledge areas to the corresponding skills** required to successfully demonstrate competency in this task.

**A.5.1 Mapping Knowledge to Skills**
Para demonstrar essa competência, o aluno deve mostrar a capacidade de:

* Aplicar conhecimentos sobre Finite State Machines (FSMs) (simulate, test, validate)
* Compreender Regular Languages (classify, define)
* Aplicar Requirements Analysis (analyze, formalize)
* Aplicar Analytical and Critical Thinking (FPK) (evaluate, troubleshoot)

**A.5.2 Bloom’s Taxonomy Alignment**
O nível Aplicar é utilizado para simular transições de estado, testar configurações do autômato e validar a correção em relação ao comportamento do sistema.
O nível Compreender é empregado para classificar e explicar padrões de linguagem regular e como se relacionam com a funcionalidade do sistema.

**A.5.3 Verb Annotation**
To provide clarity on competency expectations, the following verb annotations define the required actions:

* simulate
* test
* validate
* classify
* define
* analyze
* evaluate
* troubleshoot

### A.6 Summary Table for Competency A

| **Competency**                                              | **Dispositions**                                              | **Knowledge**                          | **Skill**                            |
| ----------------------------------------------------------- | ------------------------------------------------------------- | -------------------------------------- | ------------------------------------ |
| Develop problem-solving systems using finite state machines | Collaborative, Responsible, Proactive, Analytical, Systematic | Finite State Machines (FSMs)           | **Apply (simulate, test, validate)** |
|                                                             |                                                               | Regular Languages                      | **Understand (classify, define)**    |
|                                                             |                                                               | Requirements Analysis                  | **Apply (analyze, formalize)**       |
|                                                             |                                                               | Analytical and Critical Thinking (FPK) | **Apply (evaluate, troubleshoot)**   |


A seguir, está a **especificação de competências não reutilizadas** anteriormente e que emergem de maneira específica na Tarefa 1 — *Drone Monitoring*, com base nas características singulares da tarefa: análise de requisitos para protótipos funcionais, estimativa de estados e transições, e integração de expressões regulares em sistemas formais.

---

## 4.2 Competency B Specification

### B.1 Competency Title

```
Specify formal requirements for reactive systems modeled by finite automata  
```

### B.2 Textual Description

Analyze functional and behavioral requirements of reactive systems and translate them into formal specifications suitable for implementation using finite automata.

### B.3 Knowledge Specification

The following knowledge areas are critical for this competency:

* Requirements Engineering
* Finite Automata Design
* Chomsky Hierarchy
* Functional Specification Techniques

### B.4 Disposition Specification

A atividade demandou uma abordagem crítica e detalhada da especificação de comportamentos esperados e exceções. As principais disposições envolvidas são:
Analytical, Detail-Oriented, Precise, Responsible.

### B.5 Knowledge-Skill Pairing

**B.5.1 Mapping Knowledge to Skills**
Para demonstrar essa competência, o aluno deve mostrar a capacidade de:

* Analisar requisitos funcionais e comportamentais do sistema (Requirements Engineering)
* Traduzir especificações de alto nível em autômatos formais (Finite Automata Design)
* Compreender a posição e os limites do sistema dentro da Hierarquia de Chomsky
* Documentar o comportamento esperado de forma clara e formal (Specification Techniques)

**B.5.2 Bloom’s Taxonomy Alignment**
O nível Analisar é usado para decompôr requisitos funcionais.
O nível Aplicar é empregado para formalizar comportamentos usando autômatos.

**B.5.3 Verb Annotation**

* analyze
* interpret
* formalize
* specify

### B.6 Summary Table for Competency B

| **Competency**                                                              | **Dispositions**                                  | **Knowledge**            | **Skill**                          |
| --------------------------------------------------------------------------- | ------------------------------------------------- | ------------------------ | ---------------------------------- |
| Specify formal requirements for reactive systems modeled by finite automata | Analytical, Detail-Oriented, Precise, Responsible | Requirements Engineering | **Analyze (decompose, interpret)** |
|                                                                             |                                                   | Finite Automata Design   | **Apply (formalize)**              |
|                                                                             |                                                   | Chomsky Hierarchy        | **Understand (classify)**          |
|                                                                             |                                                   | Specification Techniques | **Apply (structure, document)**    |

---

## 4.3 Competency C Specification

### C.1 Competency Title

```
Estimate formal resource needs based on state complexity  
```

### C.2 Textual Description

Estimate the number of states and transitions required to implement formal models of system behavior using finite automata, supporting feasibility analysis and resource planning.

### C.3 Knowledge Specification

The following knowledge areas are critical for this competency:

* State Complexity Analysis
* Finite State Machines
* Cost Estimation Techniques
* Requirements-Driven Modeling

### C.4 Disposition Specification

Esta competência exige uma mentalidade investigativa, voltada à previsão de recursos e à tomada de decisões fundamentadas. Disposições envolvidas:
Foresighted, Logical, Systematic, Strategic.

### C.5 Knowledge-Skill Pairing

**C.5.1 Mapping Knowledge to Skills**
Para demonstrar essa competência, o aluno deve mostrar a capacidade de:

* Estimar quantitativamente os elementos do modelo (número de estados e transições)
* Relacionar requisitos a complexidade formal do autômato
* Utilizar estimativas para informar orçamentos e decisões de viabilidade técnica

**C.5.2 Bloom’s Taxonomy Alignment**
O nível Aplicar é utilizado para operar estimativas com base em requisitos.
O nível Avaliar é utilizado para julgar a viabilidade com base nas estimativas.

**C.5.3 Verb Annotation**

* estimate
* justify
* relate
* evaluate

### C.6 Summary Table for Competency C

| **Competency**                                           | **Dispositions**                            | **Knowledge**                | **Skill**                              |
| -------------------------------------------------------- | ------------------------------------------- | ---------------------------- | -------------------------------------- |
| Estimate formal resource needs based on state complexity | Foresighted, Logical, Systematic, Strategic | State Complexity Analysis    | **Apply (estimate, quantify)**         |
|                                                          |                                             | Finite State Machines        | **Apply (map states and transitions)** |
|                                                          |                                             | Requirements-Driven Modeling | **Evaluate (justify feasibility)**     |


