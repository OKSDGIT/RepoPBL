**Problem 1 (Task): The vending machine for sodas and snacks**
Authors: Luiz Gavaza  &nbsp;  Lais Salvador  &nbsp;   David Moises &nbsp;    Roberta Oliveira

Contributors: Edeyson Gomes &nbsp;  Jéssica Santana

21 de September de 2020

## **Task: Machine for sodas and snacks**

### **1.  Introduction**

The company machine for sodas and snacks S.A., decided to develop new solutions for your soft drinks and snacks vending machines based on well-structured hardware and software projects, accompanied by accurate and easy-to-use documentation.
The idea came up when a company computer technician was talking to a group of students from the Department of Computer Science at UFBA. They realized that some state machines, called automata, meet the functionalities of vending machines, in addition to using little memory and being simple to configure.
The company's machines must be configured to sell at least three (3) products, receive coins and bills of R$1.00 and R$2.00, and provide change functionality. The company's portfolio offers options for selling soft drinks for 3.00 and 5.00 reais, and savory snacks for R$5.00 and R$7.00.
Students also commented on a JFLAP tool to test/simulate solutions that use these automata. They said that JFLAP presents a graphical interface that can contribute to the documentation of these new solutions for vending machines. Another interesting point is that the computer technician has already worked with regular expressions and heard that regular expressions are related to some of these automatons: he would like to know if this information is true (investigate); If so, he would like to have at least one example of how this would work for a portion of the automaton built for some vending machine. He thinks expressions can also help with documenting these machines and future projects.

**CHALLENGE**: The IT technician promised an additional bonus if they could help promote the new machines by implementing a modification that allows the machines to randomly give a bonus change of R$1.00 if the amount entered by the customer is exactly the price of the selected product.

### **2. Process** 
During the solution construction process, the Problem Based Learning (PBL) teaching and learning methodology will be used, characterized by real-world problems to stimulate the development of critical thinking, teamwork and problem-solving skills, in addition to contributing to the construction of knowledge about a specific topic. The process must be documented through the PBL whiteboard, composed of the QUESTIONS, FACTS, IDEAS/HYPOTHESES and ACTIONS columns.

### **3.  Product** 
You must post in AVA UFBA by 8:20 pm on 13/10/2020, in the appropriate space for this purpose, a file with an automaton that contains a machine for selling soft drinks and snacks so that the technology team of the drinks and Brazilian savory snacks S.A. can test/simulate in JFLAP, as well as a report using the SBC (Brazilian Computer Society) article model that describes in maximum detail the idealization of the functioning of the soft drinks and snacks vending machine system. 

The report must contain the operations carried out by the system to receive payment from the customer and deliver the chosen product, as well as at least two examples of operation. If it is possible to fulfill the technician's request, this report must also contain the regular expression with the automaton section analyzed, in addition to the expression construction method. If this is not possible, present a justification for this impossibility in the report.



### **4 Knowledge/Concepts Involved** 
- Deterministic Finite Automata (DFA)
- Non-Deterministic Finite Automata  (NFA ou NDFA)
- Regular Expressions (RE)


###
### **5. Learning objectives** 

#### **5.1 General objective** 
Develop finite automata and regular expressions to solve “real” problems, as is the case with the machine project of the company machine for sodas and snacks S.A.* 

#### **5.2 Specific objectives** 

1\. **Identify** the functionalities of the system designed by the user.

2\. **Reconcile** the functionalities desired by the user with those functionalities of the automaton to be developed
 
3\. **Evaluate** the use of non-determinism in the developed automaton

4\. **Identify the equivalence** between AFDet and AFNDet

5\. **Identify the equivalence** between AF and ER

6\. **Apply** the equivalence between AF and ER to develop ER 
based on existing AF

7\. **Associate** machine options, coins, and notes with symbols of an
alphabet

8\. **Specify** technical reports

9\. **Use** simulation tools for AF


### </a> References 
This problem is based on the lecture notes of Professor Martin Musicante 2</sup> do DIMAP - UFRN. <sup>2<https://sigaa.ufrn.br/sigaa/public/docente/portal.jsf?siape=12212512></sup>

RAMOS, M. V. M.; JOSE NETO, J.; VEGA, I. S. **Linguagens Formais: Teoria, Modelagem e Implementação**. Editora Bookman, 2009.
MENEZES, Paulo Blauth. **Linguagens formais e autômatos**. 6. ed. Bookman, 2011.
