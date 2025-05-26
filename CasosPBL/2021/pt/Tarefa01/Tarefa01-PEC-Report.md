
5.000 / 5.000
# Relatório de Especificação de Competências: Tarefa 1 - A Máquina de Vendas de Refrigerantes e Salgadinhos

## Introdução

Com base na estrutura geral definida na metodologia CSP, este relatório apresenta a aplicação do **Processo de Especificação de Competências** à **Tarefa 1 – A Máquina de Vendas de Refrigerantes e Salgadinhos**, um cenário de Aprendizagem Baseada em Problemas (ABP) que explora o uso de **autômatos finitos e expressões regulares** no projeto de soluções de software e hardware para máquinas de venda automática.

## 1. Análise da Descrição da Tarefa

A tarefa ABP intitulada **"A Máquina de Vendas de Refrigerantes e Salgadinhos"** apresenta um problema relacionado ao **cálculo de troco em transações em máquinas de venda automática**, onde os pagamentos são feitos com moedas e notas. A tarefa exige que os alunos projetem uma solução que permita à máquina de venda automática aceitar pagamentos, dispensar o troco com precisão e operar de acordo com requisitos funcionais predefinidos.

Para abordar este problema com sucesso, os alunos devem demonstrar sua capacidade de:
- **Aplicar conceitos de autômatos finitos** para modelar o comportamento da máquina de venda automática.

- **Simular e validar** a funcionalidade do autômato utilizando ferramentas computacionais.
- **Documentar o processo de desenvolvimento** de forma estruturada e técnica.

Esta tarefa não apenas avalia a compreensão dos alunos sobre a **teoria dos autômatos**, mas também avalia sua capacidade de:
1. **Analisar restrições do mundo real** e traduzi-las em um modelo computacional formal.
2. **Projetar e implementar** um autômato que atenda aos requisitos funcionais.
3. **Justificar e explicar** as decisões de projeto por meio de um relatório técnico bem estruturado.

Além disso, a tarefa apresenta um desafio opcional: implementar um **recurso de troco bônus aleatório**, em que a máquina de venda automática ocasionalmente oferece um adicional de R$ 1,00 quando o preço exato do produto é pago. Isso adiciona um **elemento estocástico** ao sistema, incentivando os alunos a considerarem **comportamentos probabilísticos** no projeto do autômato.

Por meio deste cenário estruturado de Aprendizagem Baseada em Problemas (ABP), os alunos se envolvem com um problema do mundo real, conectando conhecimento teórico com modelagem computacional prática, simulação e documentação técnica.

## 2. Enumeração de Conhecimento

Para enumerar sistematicamente o conhecimento de computação necessário para esta tarefa, o Sistema de Classificação de Computação da ACM (2012) foi utilizado como vocabulário controlado. Este sistema de classificação é amplamente reconhecido e adotado globalmente, garantindo padronização e consistência na categorização do conhecimento de computação.

Para o conhecimento profissional (FPK), utilizamos como referência o Currículo de Computação da ACM (CC) 2020, que fornece uma estrutura para competências profissionais essenciais.

Com base na **descrição da tarefa**, o seguinte conjunto de componentes de conhecimento necessários foi identificado:

### **Conhecimento em Computação**
- **Autômatos sobre Objetos Infinitos (Autômatos Finitos Determinísticos - AFD)**
- Envolve o estudo e a aplicação de modelos matemáticos que descrevem sistemas computacionais usando **estados e transições**.
- Essencial para o projeto de **lógica de máquinas de venda automática baseada em estados**.

- **Linguagens Regulares (Expressões Regulares - ER)**
- Requer a compreensão e a aplicação de **técnicas formais** para representar e manipular conjuntos de strings.
- Usado principalmente em **processamento de texto, análise lexical e correspondência de padrões** dentro da lógica operacional da máquina de venda automática.

- **Análise de Requisitos (Engenharia de Requisitos de Software)**
- Um processo sistemático para **coletar, analisar e especificar requisitos de sistema**.
- Garante que as **necessidades do usuário e as expectativas do sistema** sejam claramente compreendidas e documentadas.

- **Ferramentas de Simulação**
- Envolve o uso de **ferramentas de simulação de autômatos** (como JFLAP) para validar e analisar **soluções propostas**.
- Permite **testar, depurar e refinar** o autômato da máquina de venda automática antes da implementação.

### **Conhecimento Profissional (FPK)**
- **Pensamento Analítico e Crítico**
- Capacidade de **decompor problemas complexos em componentes fundamentais**, avaliar resultados e tomar decisões bem fundamentadas com base em análises rigorosas.

- **Resolução e Solução de Problemas**
- Requer a identificação, análise e resolução de **desafios específicos da tarefa** usando **estratégias e métodos computacionais eficazes** para desenvolver soluções ideais.

- **Comunicação Escrita**
- Capacidade de **elaborar relatórios técnicos claros e estruturados** detalhando os processos de design, implementação e validação.
- Garante que as descobertas e decisões sejam comunicadas de forma eficaz às partes interessadas.

Esta **enumeração de conhecimentos** serve como base para a especificação de competências, garantindo que os alunos adquiram tanto a **experiência teórica quanto a prática** necessárias para concluir a tarefa com sucesso.


## 3. Identificação dos Objetivos de Aprendizagem

O **objetivo geral** desta tarefa é desenvolver **autômatos finitos e expressões regulares** para resolver **problemas do mundo real** por meio da modelagem de um sistema de máquina de venda automática. Este objetivo enfatiza a aplicação prática da **teoria dos autômatos** na resolução de problemas computacionais.

### **Objetivos Específicos de Aprendizagem**
Para atingir este objetivo geral, os alunos devem demonstrar a capacidade de:

1. **Identificar as funcionalidades do sistema**
- Analisar o modelo conceitual da máquina de venda automática apresentado pelo usuário e definir seus comportamentos esperados.

2. **Alinhar os requisitos do usuário com as funcionalidades do autômato**
- Conciliar as funcionalidades desejadas da máquina de venda automática com as restrições e capacidades do autômato em desenvolvimento.

3. **Avaliar o papel do não determinismo em autômatos finitos**
- Avaliar quando e como **autômatos finitos não determinísticos (ANF)** podem ser usados ​​efetivamente no projeto do sistema.

4. **Compreender as equivalências entre autômatos determinísticos e não determinísticos**
- Demonstrar compreensão da equivalência entre **Autômatos Finitos Determinísticos (AFD)** e **Autômatos Finitos Não Determinísticos (ANF)**, destacando cenários em que um pode ser preferível ao outro.

5. **Compreender a equivalência entre Autômatos Finitos (AF) e Expressões Regulares (RE)**
- Estabelecer conexões entre **representações de autômatos finitos** e **expressões regulares**, reforçando sua intercambialidade teórica e prática.

6. **Aplicar a equivalência de AF para RE no desenvolvimento de expressões regulares**
- Utilizar autômatos finitos existentes para derivar **expressões regulares correspondentes**, aplicando métodos formais para converter autômatos em padrões de expressões regulares equivalentes.

7. **Associar opções de máquinas de venda automática, moedas e notas com símbolos alfabéticos**
- Mapear elementos do mundo real da máquina de venda automática (como seleções de produtos e métodos de pagamento) no **alfabeto formal** usado no projeto do autômato.

8. **Desenvolver relatórios técnicos**
- Documentar o **projeto, a implementação e a validação** do autômato, garantindo clareza e precisão na redação técnica.

9. **Utilizar ferramentas de simulação de autômatos finitos**
- Aplicar ferramentas como o **JFLAP** para simular, analisar e verificar a funcionalidade do autômato projetado.

### **Importância destes Objetivos**
Estes objetivos de aprendizagem fornecem um **caminho estruturado** para o desenvolvimento de competências, garantindo que os alunos adquiram:
- **Uma sólida base teórica** em autômatos e linguagens formais.
- **A capacidade de conectar teoria e prática**, aplicando métodos formais para resolver problemas computacionais.
- **Experiência prática com ferramentas de simulação**, reforçando habilidades práticas de resolução de problemas.

- **Habilidades de comunicação técnica**, essenciais para a transmissão de soluções em contextos profissionais e acadêmicos.

Ao atingir esses objetivos, os alunos estarão equipados com as **habilidades computacionais e analíticas** necessárias para modelar sistemas do mundo real usando **autômatos finitos e expressões regulares**.

## 4. Definição de Competência

As competências são especificadas com base nos **Objetivos de Aprendizagem (OAs)** identificados na análise da tarefa.

### 4.1 Especificação da Competência A

### A.1 Título da Competência
Projetando Soluções Eficientes com Autômatos

### A.2 Descrição Textual
Esta competência concentra-se na capacidade de projetar e implementar **soluções eficazes e otimizadas** usando **autômatos finitos**. Ela requer um **profundo conhecimento da teoria de autômatos**, incluindo a identificação de requisitos funcionais, sua tradução em **implementações técnicas viáveis** e a garantia de que o **autômato final seja eficiente, confiável e atenda às expectativas do usuário**.

Os alunos devem **equilibrar as necessidades definidas pelo usuário com as restrições dos autômatos**, garantindo que o sistema da máquina de venda automática funcione corretamente em diferentes condições. Esta competência também enfatiza a **importância da validação**, exigindo que os alunos **simulem, testem e refinem seus modelos** para garantir a precisão e o desempenho em **aplicações do mundo real**.

Além disso, a competência inclui a **capacidade de lidar com restrições adicionais**, como a implementação do **mecanismo de troca de bônus** introduzido como um desafio extra pelo técnico de TI.

### A.3 Especificação de Conhecimento
As seguintes áreas de conhecimento são críticas para esta competência:

- **Autômatos sobre Objetos Infinitos**
- Fundamental para modelar a lógica operacional da máquina de venda automática.
- Envolve o projeto de estados e transições para representar as funcionalidades do sistema.

- **Análise de Requisitos**
- Garante uma **identificação e documentação precisas dos requisitos do sistema**.
- Conecta as necessidades do usuário com as capacidades técnicas dos autômatos finitos.

- **Pensamento Analítico e Crítico (FPK)**
- Necessário para **decomposição de problemas e planejamento estratégico**.
- Auxilia no alinhamento dos requisitos do usuário com a viabilidade técnica, otimizando os recursos computacionais.

### A.4 Especificação de Disposição
A tarefa **"Máquina de Venda Automática de Refrigerantes e Salgadinhos"** destaca os principais atributos comportamentais necessários para a resolução de problemas e a colaboração eficaz da equipe. Isso inclui:

**Colaboração**
- A tarefa segue a metodologia de **Aprendizagem Baseada em Problemas (ABP)**, exigindo interação contínua da equipe.
- Essencial para o desenvolvimento colaborativo de soluções por meio de **sessões de quadro branco de ABP**, manutenção do **diário de bordo** e **documentação de cada fase do projeto**.
- Incentiva o **compartilhamento de conhecimento** e melhorias iterativas.

**Responsabilidade**
- Garante o cumprimento dos **prazos do projeto**, **documentação** precisa e um **design de autômato funcional**.
- Exige responsabilidade individual pelas contribuições, garantindo que a **entrega final atenda às expectativas do usuário** e aos padrões do projeto.

**Proatividade**
- Incentiva a antecipação de desafios, como o **recurso de alteração bônus aleatória (R$ 1,00 extra)**, que requer **pesquisa adicional e ajustes técnicos**.
- Envolve a busca ativa de conhecimento, incluindo a **relação entre expressões regulares e autômatos finitos**.

- Oferece suporte a uma abordagem proativa para depuração, refinamento e melhoria do sistema.

**Criatividade**
- Necessária para adaptar as **funcionalidades dos autômatos aos requisitos específicos do usuário**.
- Incentiva a exploração de **implementações alternativas**, como a incorporação de **elementos aleatórios** no comportamento dos autômatos.
- Aprimora a **documentação técnica**, tornando as operações do sistema visual e conceitualmente envolventes.

### A.5 Emparelhamento Conhecimento-Habilidade

Esta etapa mapeia as **áreas de conhecimento às habilidades correspondentes** necessárias para demonstrar com sucesso a competência nesta tarefa.

**A.5.1 Mapeando Conhecimento às Habilidades**
Para atingir esta competência, os alunos devem demonstrar a capacidade de:

- **Aplicar** o Pensamento Analítico e Crítico, juntamente com o conhecimento de **Autômatos sobre Objetos Infinitos**, para **resolver o problema de cálculo de troco da máquina de venda automática**.
- **Identificar e interpretar** os requisitos do sistema, demonstrando proficiência em **Análise de Requisitos**.

**A.5.2 Alinhamento com a Taxonomia de Bloom**
Para garantir uma abordagem de aprendizagem estruturada e progressiva, cada componente de conhecimento está alinhado com a Taxonomia Revisada de Bloom, fornecendo uma estrutura clara para a avaliação de competências.

- **Pensamento Analítico e Crítico (FPK) – Aplicar**
- Avalia a capacidade do aluno de **decompor problemas complexos** em componentes fundamentais.
- Avalia a capacidade de **analisar relacionamentos, identificar padrões e formular estratégias lógicas** para a resolução de problemas.
- Garante que os alunos consigam efetivamente **conectar o conhecimento teórico com a implementação prática**.

- **Autômatos sobre Objetos Infinitos – Criar**
- Mede a capacidade do aluno de **projetar e implementar soluções baseadas em autômatos** para um problema definido.
- Avalia a capacidade de **traduzir restrições de sistemas do mundo real em modelos de autômatos** usando estados e transições.
- Garante que os alunos consigam efetivamente **aplicar técnicas de modelagem computacional** para resolver problemas de transações em máquinas de venda automática.

- **Análise de Requisitos – Aplicar**
- Avalia a capacidade do aluno de interpretar e traduzir restrições do sistema e requisitos do usuário em especificações formais.
- Avalia a capacidade de aplicar técnicas de análise estruturada na identificação de requisitos funcionais e não funcionais.
- Garante que os alunos consigam organizar e integrar logicamente os requisitos em um modelo computacional coerente.


**A.5.3 Anotação Verbal**
Para esclarecer as expectativas de competência, as seguintes anotações verbais definem as ações necessárias:

- **Criar** → Autômatos sobre Objetos Infinitos → **Construir, Desenvolver, Projetar** um autômato funcional que satisfaça restrições computacionais.
- **Aplicar** → Análise de Requisitos → **Interpretar, Implementar, Organizar** requisitos de sistema estruturados em uma estrutura computacional.

### A.6 Tabela Resumo da Competência A

| **Competência** | **Disposições** | **Conhecimento** | **Habilidade** |
|------------|-----------|------------|----|
| | | Autômatos sobre Objetos Infinitos | **Criar (Construir, Desenvolver, Projetar)** |
| **Desenvolver soluções de problemas usando Autômatos** | **Colaborativo, Responsável, Proativo, Criativo** | Análise de Requisitos | **Aplicar (Interpretar, Implementar, Organizar)** |
| | | Pensamento Analítico e Crítico (FPK) | **Aplicar** |

### **4.2 Especificação da Competência B**

### B.1 Título da Competência
Determinando Quando Usar Autômatos Finitos Determinísticos (ADF)

### B.2 Descrição da Competência
Esta competência se concentra em **compreender o determinismo em autômatos finitos** e **determinar quando aplicar o não determinismo**. Os alunos devem analisar as restrições do sistema e **decidir se um autômato determinístico ou não determinístico** é a escolha ideal para resolver um determinado problema.

Esta competência requer a capacidade de:
- **Diferenciar autômatos determinísticos e não determinísticos** com base em suas propriedades e aplicações práticas.
- **Avaliar os requisitos do problema** para determinar o modelo de autômato mais eficiente.
- **Justificar a escolha** do tipo de autômato com raciocínio lógico e restrições computacionais.

### B.3 Especificação de Conhecimento
As seguintes áreas de conhecimento são essenciais para esta competência:

- **Autômatos sobre Objetos Infinitos**
- Compreender as características, limitações e aplicações de **modelos determinísticos vs. não determinísticos**.
- Identificar cenários em que um modelo pode ser mais vantajoso que o outro.

- **Pensamento Analítico e Crítico (FPK)**
- Necessário para **avaliar as restrições do sistema e tomar decisões informadas**.
- Permite que os alunos desenvolvam **raciocínio estratégico** ao escolher entre modelos DFA e NFA
