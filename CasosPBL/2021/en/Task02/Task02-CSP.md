# Competency Specification Report: Task2 - Traffic Control

## Introduction

This report presents the application of the **Competency Specification Process** to the **Task2 - Traffic Control**, a Problem-Based Learning (PBL) scenario that explores the use of **Turing machines** in the design of a traffic control solution.

The **Competency Specification Process** is a structured methodology designed to **identify, classify, and document competencies** embedded within an educational task. By analyzing the task description, required knowledge, learning objectives, and behavioral dispositions, this process enables educators to define a competency framework that aligns with **real-world problem-solving and educational objectives**.

### **Objective of this Report**
The primary goal of this report is to demonstrate how the **Competency Specification Process** is applied to **Task2** by systematically identifying:
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


Especificação de Competências

Anotação de Competências da Tarefa: “O Retorno do robô fazendeiro”


1. Learning Task Statement Analysis
A tarefa do caso PBL intitulada “Controle de Tráfego na Estrada de Aratu” apresenta um problema relacionado à análise do fluxo de veículos em uma rodovia com alto índice de deterioração devido ao tráfego intenso, especialmente de veículos pesados durante o período noturno. Para resolver esse problema, os alunos devem demonstrar conhecimento sobre Máquinas de Turing, aplicando esse conceito para modelar a solução computacional. 


2. Knowledge Enumeration
Para a identificação e organização dos conhecimentos necessários à resolução da tarefa, adotou-se como referência o ACM Computing Classification System 2012 (ACM CCS 2012), garantindo um vocabulário controlado amplamente reconhecido para a categorização dos conteúdos computacionais. Já para os conhecimentos profissionais (FPK), utilizou-se a classificação do relatório ACM CC 2020, assegurando alinhamento com as diretrizes atuais de competências para a área de computação. O conjunto de conhecimentos requeridos especificado na tarefa foi identificado como: 

Máquinas de Turing - nmT: envolve o estudo de um modelo abstrato de computação capaz de simular qualquer algoritmo computável. No contexto do problema, as Máquinas de Turing são utilizadas para modelar a solução de categorização dos veículos, processando a entrada fornecida pelos sensores e determinando o número de veículos por categoria.

Variações de Máquinas de Turing - nmT: requer o entendimento de diferentes versões das Máquinas de Turing, como Máquinas de Turing com múltiplas fitas, não determinísticas e variantes com saída específica. Essas variações podem ser aplicadas para otimizar o processamento dos dados de tráfego, permitindo maior eficiência na análise e classificação dos veículos.

Tese de Church-Turing - nmT: envolve a compreensão do princípio fundamental da computabilidade, que estabelece que qualquer função computável pode ser realizada por uma Máquina de Turing. No problema do controle de tráfego, essa tese auxilia na justificativa teórica de que a abordagem computacional escolhida pode efetivamente resolver a tarefa de categorização e análise dos veículos, garantindo que o modelo adotado seja viável e adequado.

Engenharia de Requisitos: que requer um processo de coleta e identificação de requisitos do sistema.

Pensamento analítico e crítico (FPK), que requer um processo mental de simplificar informações complexas em partes básicas e avaliar resultados para tomar decisões adequadas.

Resolução de problemas e Soluções de Problemas (FPK): requer que o aluno identifique, analise e solucione problemas especificados.

Modelagem e Simulação: requer o envolvimento na criação de representações de sistemas que simule e execute os processos do mundo real.

Comunicação Escrita (FPK): para elaborar o relatório, os alunos precisam transmitir informações por meio de texto, de forma clara e objetiva o passo a passo da construção da solução da tarefa.



3. Learning Objectives Identification:
O objetivo geral desta tarefa é desenvolver uma solução que utilize os sensores já instalados na estrada para identificar e categorizar os veículos que trafegam à noite, gerando um relatório diário com a quantidade de veículos por categoria (leves, pesados e muito pesados) e apontando qual categoria foi predominante no período analisado. Os objetivos específicos são:

Identificar as funcionalidades do sistema idealizado pelo usuário.
Conciliar as funcionalidades desejadas pelo usuário com as funcionalidades da máquina de Turing a ser desenvolvida.
Avaliar a necessidade de se usar extensões na máquina de Turing a ser desenvolvida.
Aplicar a tese de Church-Turing ao associar o conceito formal de máquina de Turing com a noção intuitiva de algoritmo.



4. Competency Definition
As competências serão especificadas com base nos learning objectives (LO) identificados.

Competency 1


4.1 Competency Title: 
Desenvolver soluções de problemas usando a máquina de Turing

4.2 Textual Description: 
Com base nos objetivos de aprendizagem (LO1 e LO2), especificou-se a competência "Desenvolver soluções de problemas usando a Máquina de Turing". Essa competência se concentra na capacidade do aluno de projetar e implementar soluções computacionais para o problema de controle de tráfego, utilizando o conceito de Máquinas de Turing. O aluno deve demonstrar compreensão dos princípios fundamentais desse modelo computacional, aplicá-lo para processar e classificar os dados dos sensores da estrada e, a partir disso, gerar uma análise detalhada da circulação de veículos. Além disso, espera-se que ele seja capaz de validar a solução proposta, garantindo precisão, confiabilidade e desempenho na categorização do tráfego e na identificação de padrões relevantes para a gestão da infraestrutura rodoviária.

4.3 Knowledge Specification
Os conhecimentos necessários para essa competência incluem:
Máquinas de Turing (nmT): Essencial para atingir o objetivo geral, esse conhecimento envolve compreender e aplicar os princípios das Máquinas de Turing para modelar a solução do problema de categorização e análise do tráfego.
Variações de Máquinas de Turing: Fundamentais para aprimorar a eficiência da solução, permitindo que diferentes modelos, como máquinas de múltiplas fitas ou não determinísticas, sejam considerados para otimizar o processamento dos dados coletados pelos sensores.
Tese de Church-Turing: Importante para justificar teoricamente a viabilidade computacional da solução, garantindo que a abordagem adotada é capaz de resolver o problema de forma eficaz.
Engenharia de Requisitos: Necessária para identificar e formalizar corretamente as necessidades dos técnicos do DERBA, assegurando que os requisitos do sistema sejam bem compreendidos e implementados adequadamente.
Pensamento Analítico e Crítico (FPK): Essencial para planejar e desenvolver a solução, permitindo que o aluno analise as informações disponíveis, avalie diferentes estratégias e proponha abordagens que equilibrem precisão e eficiência.

4.4 Attitude Specification
A análise da tarefa "Controle de Tráfego na Estrada de Aratu" destaca atitudes comportamentais essenciais para a resolução do problema e a entrega de uma solução eficaz. As principais atitudes incluem:
Colaborativo: Trabalhar de forma integrada com os colegas para estruturar a solução, compartilhar descobertas e garantir que todas as partes do sistema operem de maneira coesa.
Responsável: Assumir compromisso com a qualidade da solução, respeitando prazos e garantindo que os requisitos estabelecidos pelos técnicos do DERBA sejam atendidos corretamente.
Proativo: Antecipar possíveis dificuldades na implementação da solução computacional, propor melhorias e adaptar o modelo conforme necessário para maior precisão na categorização dos veículos.
Investigativo: Explorar diferentes variações da Máquina de Turing e suas aplicações no contexto do controle de tráfego, analisando a melhor forma de processar os dados capturados pelos sensores da rodovia.
Criativo: Desenvolver soluções inovadoras para aprimorar a análise dos dados do tráfego noturno, permitindo que o sistema seja mais eficiente e adaptável às demandas dos técnicos de infraestrutura.
4.5 Knowledge/Skill Pairing
Esta etapa envolve alinhar os componentes de conhecimento com as habilidades correspondentes necessárias para aplicá-los de forma eficaz no contexto da tarefa.
4.5.1 Mapping Knowledge to Skills
Para demonstrar essa competência, o aluno deve mostrar a capacidade de:
Aplicar o Pensamento Analítico e Crítico juntamente com o conhecimento sobre Máquinas de Turing para desenvolver uma solução computacional que processe e classifique os dados de tráfego. Isso envolve modelar o funcionamento dos sensores e a categorização dos veículos dentro da estrutura formal de uma Máquina de Turing.
Utilizar Máquinas de Turing para representar e simular a lógica da contagem e categorização dos veículos, garantindo que o modelo seja capaz de processar as informações corretamente e oferecer uma solução eficiente para o problema proposto.
Identificar e especificar corretamente os requisitos essenciais do sistema, demonstrando uma compreensão clara da Engenharia de Requisitos. O aluno deve ser capaz de levantar as necessidades dos técnicos do DERBA, interpretar as informações dos sensores e definir os critérios para análise dos dados.
Relacionar os requisitos com a modelagem computacional, garantindo que as necessidades dos usuários sejam traduzidas em funcionalidades práticas dentro da solução desenvolvida.
4.5.2 Bloom’s Taxonomy Alignment

Máquinas de Turing: O nível Aplicar é utilizado para avaliar a capacidade do aluno de empregar o conceito de Máquinas de Turing na modelagem e solução do problema de controle de tráfego.
Engenharia de Requisitos: O nível Compreender é empregado para verificar se o aluno consegue interpretar e estruturar corretamente os requisitos do sistema com base nas necessidades do problema.
Pensamento Analítico e Crítico (FPK): O nível Aplicar é escolhido para avaliar a habilidade do aluno de decompor o problema em partes menores e desenvolver estratégias eficazes para sua solução.

4.5.3 Verb Annotation


Tabela resumo da Competência 1



Anotação de Competências da Tarefa “Controle de Tráfego”

Como resultado do passo 1, tem-se que a A Tarefa “Controle de Tráfego” descreve uma solução para os problemas identificados pelos técnicos do Departamento de Infraestrutura de Transportes da Bahia (DERBA) e solicita a implementação da solução em um simulador e um relatório de execução. 

Para cumprir o passo 2, extraiu-se o conjunto de conhecimentos requeridos, especificado na tarefa: {Máquinas de Turing (nmT), Variações de mT, Tese de Church-Turing}

Para fazer a adequação da descrição desses conhecimentos com um vocabulário controlado, resultou-se no uso de “Máquinas de Turing” para os conhecimentos da tarefa originalmente descritos como “Máquinas de Turing (nmT)” e “Variações de mT}”. Como o vocabulário não contempla “Tese de Church-Turing”, a descrição desse conhecimento foi mantido.

Para a execução da tarefa, inferiu-se que mais conhecimentos são necessários e adicionaram-se os seguintes:

Engenharia de Requisitos: que requer um processo de coleta e identificação de requisitos do sistema.

Pensamento analítico e crítico (FPK), que requer um processo mental de simplificar informações complexas em partes básicas e avaliar resultados para tomar decisões adequadas.

Resolução de problemas e Soluções de Problemas (FPK): requer que o aluno identifique, analise e solucione problemas especificados.

Modelagem e Simulação: requer o envolvimento na criação de representações de sistemas que simule e execute os processos do mundo real.

Comunicação Escrita (FPK): para elaborar o relatório, os alunos precisam transmitir informações por meio de texto, de forma clara e objetiva o passo a passo da construção da solução da tarefa.

No passo 3, inicialmente pensou-se em transformar cada objetivo de aprendizagem numa especificação de competência. Assim, as descrições de competências seriam:

Identificar as funcionalidades do sistema idealizado pelo usuário.
Conciliar as funcionalidades desejadas pelo usuário com as funcionalidades da máquina de Turing a ser desenvolvida.
Avaliar a necessidade de se usar extensões na máquina de Turing a ser desenvolvida.
Aplicar a tese de Church-Turing ao associar o conceito formal de máquina de Turing com a noção intuitiva de algoritmo.

Todavia, pretende-se criar especificações de competências que sejam reusáveis (e genéricas) e que utilizem a Taxonomia de Bloom para definir as habilidades. Assim, as definições foram refinadas com múltiplas interações.

Com base nos objetivos 1 e 2, especificou-se a competência “Desenvolver soluções de problemas usando a máquina de Turing”. Espera-se que o aluno demonstre que é capaz de aplicar seus conhecimentos sobre a Máquina de Turing para resolver o problema de controle de tráfego. 

O aluno deve compreender Engenharia de Requisitos para conseguir especificar a solução e Pensamento analítico e crítico (FPK) para conseguir traduzir os requisitos num código de programação funcional.

Para a especificação de Atitudes, como a tarefa requer a solução em grupo, selecionaram-se Colaborativo, Responsável, Proativo, Investigativo e Criativo.

Tem-se, então, a declaração textual da competência: “Desenvolver soluções de problemas usando a máquina de Turing”.

Com base no objetivo 3, especificou-se a competência “Avaliar a necessidade de se usar extensões na máquina de Turing a ser desenvolvida”.

Espera-se que o aluno demonstre ter compreendido como a Máquina de Turing varia em termos de capacidades e restrições, propondo soluções para o Controle de Tráfego, “aplicando” Pensamento analítico e crítico (FPK) para “identificar” os requisitos mais adequados para a resolução do problema. O aluno deve, também, demonstrar ter “compreendido” o conceito da Tese de Church-Turing.

Com base na análise deste objetivo, decidiu-se especificar a competência de forma mais genérica, que reflita com clareza a habilidade do aluno em “identificar” as diferentes capacidades das Máquinas de Turing. Assim, sua declaração tornou-se: “Identificar as variações da Máquina de Turing”.

Para a especificação de Atitudes, como a tarefa requer a solução em grupo, selecionaram-se Investigativo, Colaborativo, Responsável e Proativo.



Com base no objetivo 4, “Aplicar a tese de Church-Turing ao associar o conceito formal de máquina de Turing com a noção intuitiva de algoritmo”, especificou-se a competência “Fazer uso das variações da Máquina de Turing”.

Espera-se que o aluno demonstre ter compreendido como a Máquina de Turing varia em termos de capacidades e restrições, propondo soluções para o Controle de Tráfego, “aplicando” Pensamento analítico e crítico (FPK) para “identificar” os requisitos mais adequados para a resolução do problema. O aluno deve, também, demonstrar ter “compreendido” o conceito da Tese de Church-Turing.

Com base na análise deste objetivo, decidiu-se especificar a competência de forma mais genérica, que reflita com clareza a habilidade do aluno em “aplicar” as diferentes capacidades das Máquinas de Turing. Assim, sua declaração tornou-se: “Fazer uso das variações da Máquina de Turing”.



Com base nos arquivos com máquinas de Turing (formato JFLAP) requeridos no projeto, o aluno deverá representar o problema, aplicando o conhecimento “Resolução de problemas e solução de problemas (FPK)” e simular sua execução, aplicando Modelagem e Simulação. Ou seja, o aluno deve demonstrar que é capaz de testar máquinas de Turing usando simuladores.

Assim, declarou-se a competência associada como: “Testar máquina de Turing usando simulador”.

Para a especificação de Atitudes, como a tarefa requer a solução em grupo, foram selecionados Colaborativo, Responsável, Proativo, Investigativo e Criativo. 



 
Como um dos produtos requeridos na solução é um relatório no modelo de artigos da SBC, espera-se que o aluno escreva um relatório técnico e explique o processo de solução do problema. Tem-se então, o reuso da competência “Escrever um relatório técnico”, já definida no Problema 2.
