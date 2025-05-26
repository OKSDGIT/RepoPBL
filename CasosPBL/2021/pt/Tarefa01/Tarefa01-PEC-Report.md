# Relatório de Especificação de Competências: Tarefa1 - A Máquina de Vendas para Refrigerantes e Lanches

## Introdução

Baseando-se na estrutura geral definida na metodologia CSP, este relatório apresenta a aplicação do **Processo de Especificação de Competências** à **Tarefa1 – A Máquina de Vendas para Refrigerantes e Lanches**, um cenário de Aprendizagem Baseada em Problemas (PBL) que explora o uso de **autômatos finitos e expressões regulares** no desenvolvimento de soluções de hardware e software para máquinas de vendas.

## 1. Análise da Descrição da Tarefa

A tarefa PBL intitulada **"A Máquina de Vendas para Refrigerantes e Lanches"** aborda um problema relacionado ao **cálculo de troco em transações de máquinas de vendas**, onde os pagamentos são feitos com moedas e cédulas. A tarefa exige que os estudantes projetem uma solução que permita à máquina de vendas aceitar pagamentos, dispensar troco com precisão e operar de acordo com requisitos funcionais pré-definidos.

Para resolver esse problema com sucesso, os estudantes devem demonstrar sua capacidade de:
- **Aplicar conceitos de autômatos finitos** para modelar o comportamento da máquina de vendas.
- **Simular e validar** a funcionalidade do autômato usando ferramentas computacionais.
- **Documentar o processo de desenvolvimento** de forma estruturada e técnica.

Esta tarefa não apenas avalia o entendimento dos estudantes sobre **teoria de autômatos**, mas também sua capacidade de:
1. **Analisar restrições do mundo real** e traduzi-las em um modelo computacional formal.
2. **Projetar e implementar** um autômato que atenda aos requisitos funcionais.
3. **Justificar e explicar** decisões de projeto por meio de um relatório técnico bem estruturado.

Além disso, a tarefa inclui um desafio opcional: implementar um **recurso de troco bônus aleatório**, onde a máquina de vendas ocasionalmente fornece um R$1,00 extra quando o valor exato do produto é pago. Isso adiciona um **elemento estocástico** ao sistema, incentivando os estudantes a considerar **comportamentos probabilísticos** em seu projeto de autômato.

Por meio desse cenário estruturado de **Aprendizagem Baseada em Problemas (PBL)**, os estudantes engajam-se com um **problema do mundo real**, conectando conhecimento teórico com **modelagem computacional prática**, simulação e documentação técnica.

## 2. Enumeração de Conhecimento

Para enumerar sistematicamente o conhecimento computacional necessário para esta tarefa, utilizou-se o **Sistema de Classificação da Computação da ACM (2012)** como vocabulário controlado. Esse sistema é amplamente reconhecido e adotado globalmente, garantindo padronização e consistência na categorização do conhecimento computacional.

Para o **conhecimento profissional (FPK)**, referenciamos o **Currículo de Computação da ACM (CC) 2020**, que fornece um framework estruturado para competências profissionais essenciais.

Com base na **descrição da tarefa**, identificou-se o seguinte conjunto de componentes de conhecimento necessários:

### **Conhecimento Computacional**  
- **Autômatos sobre Objetos Infinitos (Autômatos Finitos Determinísticos - AFD)**  
  - Envolve o estudo e a aplicação de modelos matemáticos que descrevem sistemas computacionais usando **estados e transições**.  
  - Essencial para projetar a **lógica baseada em estados** da máquina de vendas.  

- **Linguagens Regulares (Expressões Regulares - ER)**  
  - Exige compreensão e aplicação de **técnicas formais** para representar e manipular conjuntos de strings.  
  - Usado principalmente em **processamento de texto, análise léxica e correspondência de padrões** na lógica operacional da máquina de vendas.  

- **Análise de Requisitos (Engenharia de Requisitos de Software)**  
  - Um processo sistemático para **coletar, analisar e especificar requisitos do sistema**.  
  - Garante que **necessidades do usuário e expectativas do sistema** sejam claramente compreendidas e documentadas.  

- **Ferramentas de Simulação**  
  - Envolve o uso de **ferramentas de simulação de autômatos** (como JFLAP) para validar e analisar **soluções propostas**.  
  - Permite **testar, depurar e refinar** o autômato da máquina de vendas antes da implementação.  

### **Conhecimento Profissional (FPK)**  
- **Pensamento Analítico e Crítico**  
  - A capacidade de **decompor problemas complexos em componentes fundamentais**, avaliar resultados e tomar decisões bem fundamentadas com base em análise rigorosa.  

- **Resolução de Problemas e Depuração**  
  - Exige identificar, analisar e resolver **desafios específicos da tarefa** usando **estratégias eficazes e métodos computacionais** para desenvolver soluções ótimas.  

- **Comunicação Escrita**  
  - A capacidade de **elaborar relatórios técnicos claros e estruturados**, detalhando o processo de projeto, implementação e validação.  
  - Garante que descobertas e decisões sejam comunicadas de forma eficaz às partes interessadas.  

Esta **enumeração de conhecimento** serve como base para a especificação de competências, garantindo que os estudantes adquiram tanto **expertise teórica quanto prática** necessária para concluir a tarefa com sucesso.

## 3. Identificação de Objetivos de Aprendizagem

O **objetivo geral** desta tarefa é desenvolver **autômatos finitos e expressões regulares** para resolver **problemas do mundo real**, modelando um sistema de máquina de vendas. Esse objetivo enfatiza a aplicação prática da **teoria de autômatos** na resolução computacional de problemas.

### **Objetivos Específicos de Aprendizagem**
Para alcançar esse objetivo geral, os estudantes devem demonstrar a capacidade de:

1. **Identificar funcionalidades do sistema**  
   - Analisar o modelo conceitual do usuário para a máquina de vendas e definir seus comportamentos esperados.

2. **Alinhar requisitos do usuário com funcionalidades do autômato**  
   - Conciliar as funcionalidades desejadas da máquina de vendas com as restrições e capacidades do autômato em desenvolvimento.

3. **Avaliar o papel do não-determinismo em autômatos finitos**  
   - Analisar quando e como **autômatos finitos não-determinísticos (AFN)** podem ser usados efetivamente no projeto do sistema.

4. **Compreender equivalências entre autômatos determinísticos e não-determinísticos**  
   - Demonstrar compreensão da equivalência entre **Autômatos Finitos Determinísticos (AFD)** e **Autômatos Finitos Não-Determinísticos (AFN)**, destacando cenários onde um pode ser preferível ao outro.

5. **Compreender a equivalência entre Autômatos Finitos (AF) e Expressões Regulares (ER)**  
   - Estabelecer conexões entre **representações de autômatos finitos** e **expressões regulares**, reforçando sua intercambialidade teórica e prática.

6. **Aplicar a equivalência AF-ER no desenvolvimento de expressões regulares**  
   - Utilizar autômatos finitos existentes para derivar **expressões regulares correspondentes**, aplicando métodos formais para converter autômatos em padrões regex equivalentes.

7. **Associar opções da máquina de vendas, moedas e cédulas a símbolos do alfabeto**  
   - Mapear elementos do mundo real da máquina de vendas (como seleções de produtos e métodos de pagamento) para o **alfabeto formal** usado no projeto do autômato.

8. **Desenvolver relatórios técnicos**  
   - Documentar o **projeto, implementação e validação** do autômato, garantindo clareza e precisão na escrita técnica.

9. **Usar ferramentas de simulação de autômatos finitos**  
   - Aplicar ferramentas como **JFLAP** para simular, analisar e verificar a funcionalidade do autômato projetado.

### **Importância desses Objetivos**
Esses objetivos de aprendizagem fornecem um **caminho estruturado** para o desenvolvimento de competências, garantindo que os estudantes adquiram:
- **Uma base teórica sólida** em autômatos e linguagens formais.
- **A capacidade de conectar teoria e prática**, aplicando métodos formais para resolver problemas computacionais.
- **Experiência prática com ferramentas de simulação**, reforçando habilidades de resolução de problemas.
- **Habilidades de comunicação técnica**, essenciais para transmitir soluções em contextos profissionais e acadêmicos.

Ao alcançar esses objetivos, os estudantes estarão equipados com as **habilidades computacionais e analíticas** necessárias para modelar sistemas do mundo real usando **autômatos finitos e expressões regulares**.

## 4. Definição de Competências

As competências são especificadas com base nos **Objetivos de Aprendizagem (OAs)** identificados na análise da tarefa.

### 4.1 Especificação da Competência A  

### A.1 Título da Competência
    Projetando Soluções Eficientes com Autômatos

### A.2 Descrição Textual  
Esta competência foca na capacidade de projetar e implementar **soluções eficazes e otimizadas** usando **autômatos finitos**. Exige um **profundo entendimento da teoria de autômatos**, incluindo a identificação de requisitos funcionais, sua tradução em **implementações técnicas viáveis** e a garantia de que o **autômato final seja eficiente, confiável e atenda às expectativas do usuário**.

Os estudantes devem **equilibrar necessidades definidas pelo usuário com restrições de autômatos**, garantindo que o sistema da máquina de vendas funcione corretamente sob diferentes condições. Essa competência também enfatiza a **importância da validação**, exigindo que os estudantes **simulem, testem e refinem seus modelos** para garantir precisão e desempenho em **aplicações do mundo real**.

Além disso, a competência inclui a **capacidade de lidar com restrições adicionais**, como implementar o **mecanismo de troco bônus** introduzido como um desafio extra pelo técnico de TI.

### A.3 Especificação de Conhecimento
As seguintes áreas de conhecimento são críticas para esta competência:  

- **Autômatos sobre Objetos Infinitos**  
  - Fundamental para modelar a lógica operacional da máquina de vendas.  
  - Envolve projetar estados e transições para representar funcionalidades do sistema.  

- **Análise de Requisitos**  
  - Garante uma **identificação e documentação precisas dos requisitos do sistema**.  
  - Conecta necessidades do usuário com as capacidades técnicas de autômatos finitos.  

- **Pensamento Analítico e Crítico (FPK)**  
  - Necessário para **decomposição de problemas e planejamento estratégico**.  
  - Auxilia no alinhamento de requisitos do usuário com viabilidade técnica, otimizando recursos computacionais.  

### A.4 Especificação de Disposição
A tarefa **"A Máquina de Vendas para Refrigerantes e Lanches"** destaca atributos comportamentais essenciais para resolução de problemas e colaboração em equipe. Esses incluem:  

 **Colaboração**  
- A tarefa segue a **metodologia de Aprendizagem Baseada em Problemas (PBL)**, exigindo interação contínua da equipe.  
- Essencial para desenvolver soluções colaborativamente por meio de **sessões PBL em quadro branco**, manter o **logbook** e **documentar cada fase do projeto**.  
- Incentiva **compartilhamento de conhecimento** e melhorias iterativas.  

 **Responsabilidade**  
- Garante o cumprimento de **prazos do projeto**, **documentação precisa** e um **projeto de autômato funcional**.  
- Exige responsabilidade individual pelas contribuições, assegurando que o **produto final atenda às expectativas do usuário** e aos padrões do projeto.  

 **Proatividade**  
- Incentiva a antecipação de desafios, como o **recurso de troco bônus aleatório (R$1,00 extra)**, que exige **pesquisa adicional e ajustes técnicos**.  
- Envolve buscar ativamente conhecimento, incluindo a **relação entre expressões regulares e autômatos finitos**.  
- Apoia uma abordagem proativa para depuração, refinamento e melhoria do sistema.  

 **Criatividade**  
- Necessária para adaptar **funcionalidades de autômatos a requisitos específicos do usuário**.  
- Incentiva a exploração de **implementações alternativas**, como a incorporação de **elementos aleatórios** no comportamento do autômato.  
- Melhora a **documentação técnica**, tornando as operações do sistema visual e conceitualmente envolventes.  

### A.5 Pareamento Conhecimento-Habilidade

Esta etapa mapeia **áreas de conhecimento às habilidades correspondentes** necessárias para demonstrar competência nesta tarefa.  

**A.5.1 Mapeamento de Conhecimento para Habilidades**  
Para alcançar esta competência, os estudantes devem demonstrar a capacidade de:  

- **Aplicar** Pensamento Analítico e Crítico junto com conhecimento de **Autômatos sobre Objetos Infinitos** para **resolver o problema de cálculo de troco da máquina de vendas**.  
- **Identificar e interpretar** requisitos do sistema, demonstrando proficiência em **Análise de Requisitos**.  

**A.5.2 Alinhamento com a Taxonomia de Bloom**  
Para garantir uma abordagem de aprendizagem estruturada e progressiva, cada componente de conhecimento é alinhado com a Taxonomia Revisada de Bloom, fornecendo um framework claro para avaliação de competências.

- **Pensamento Analítico e Crítico (FPK) – Aplicar**  
  - Avalia a capacidade do estudante de **decompor problemas complexos** em componentes fundamentais.  
  - Examina a habilidade de **analisar relações, identificar padrões e formular estratégias lógicas** para resolução de problemas.  
  - Garante que os estudantes possam efetivamente **conectar conhecimento teórico com implementação prática**.  

- **Autômatos sobre Objetos Infinitos – Criar**  
  - Mede a capacidade do estudante de **projetar e implementar soluções baseadas em autômatos** para um problema definido.  
  - Avalia a habilidade de **traduzir restrições do sistema do mundo real em modelos de autômatos** usando estados e transições.  
  - Garante que os estudantes possam efetivamente **aplicar técnicas de modelagem computacional** para resolver problemas de transação em máquinas de vendas.  

- **Análise de Requisitos – Aplicar**  
  - Avalia a capacidade do estudante de interpretar e traduzir restrições do sistema e requisitos do usuário em especificações formais.
  - Examina a capacidade de aplicar técnicas de análise estruturada para identificar requisitos funcionais e não funcionais.
  - Garante que os estudantes possam organizar e integrar logicamente requisitos em um modelo computacional coerente.

**A.5.3 Anotação de Verbos**  
Para esclarecer as expectativas da competência, as seguintes anotações de verbos definem as ações necessárias:  

- **Criar** → Autômatos sobre Objetos Infinitos → **Construir, Desenvolver, Projetar** um autômato funcional que atenda às restrições computacionais.
- **Aplicar** → Análise de Requisitos → **Interpretar, Implementar, Organizar** requisitos estruturados do sistema em um framework computacional. 

### A.6 Tabela Resumo para Competência A

| **Competência** | **Disposições** | **Conhecimento** | **Habilidade** |
|------------|-----------|------------|----|
|  |   | Autômatos sobre Objetos Infinitos | **Criar (Construir, Desenvolver, Projetar)** |
| **Desenvolver soluções de problemas usando Autômatos** | **Colaborativa, Responsável, Proativa, Criativa** | Análise de Requisitos | **Aplicar (Interpretar, Implementar, Organizar)** |
| | | Pensamento Analítico e Crítico (FPK) | **Aplicar** |

### **4.2 Especificação da Competência B**

### B.1 Título da Competência  
    Determinando Quando Usar Autômatos Finitos Determinísticos (AFD)  

### B.2 Descrição da Competência  
Esta competência foca no **entendimento do determinismo em autômatos finitos** e na **determinação de quando aplicar não-determinismo**. Os estudantes devem analisar restrições do sistema e **decidir se um autômato determinístico ou não-determinístico** é a escolha ideal para resolver um problema específico.

Esta competência exige a capacidade de:  
- **Diferenciar autômatos determinísticos e não-determinísticos** com base em suas propriedades e aplicações práticas.  
- **Avaliar requisitos do problema** para determinar o modelo de autômato mais eficiente.  
- **Justificar a escolha** do tipo de autômato com raciocínio lógico e restrições computacionais.

### B.3 Especificação de Conhecimento  
As seguintes áreas de conhecimento são essenciais para esta competência:  

- **Autômatos sobre Objetos Infinitos**  
  - Compreender as características, limitações e aplicações de **modelos determinísticos vs. não-determinísticos**.  
  - Identificar cenários onde um modelo pode ser mais vantajoso que o outro.  

- **Pensamento Analítico e Crítico (FPK)**  
  - Necessário para **avaliar restrições do sistema e tomar decisões informadas**.  
  - Permite que os estudantes desenvolvam **raciocínio estratégico** ao escolher entre modelos AFD e AFN.  

### B.4 Especificação de Disposição  
Semelhante à **Competência A**, esta competência exige que os estudantes demonstrem **atributos comportamentais** essenciais que facilitam a resolução de problemas e a tomada de decisões:  

- **Pensamento Investigativo** – Incentiva curiosidade e **análise crítica** das propriedades de autômatos e suas aplicações.  
- **Colaboração** – Apoia o trabalho em equipe ao discutir e justificar escolhas entre AFD e AFN.  
- **Responsabilidade** – Garante consistência lógica e precisão na tomada de decisões.  
- **Proatividade** – Promove pesquisa independente e exploração de aplicações de autômatos.  
- **Criatividade** – Encoraja abordagens inovadoras para resolver problemas com restrições complexas.  

### B.5 Pareamento Conhecimento-Habilidade  
Esta etapa associa **áreas de conhecimento às habilidades correspondentes** necessárias para demonstrar competência.

 **B.5.1 Mapeamento de Conhecimento para Habilidades**  
Para alcançar esta competência, os estudantes devem demonstrar a capacidade de:  
- **Aplicar** Pensamento Analítico e Crítico para **diferenciar autômatos determinísticos e não-determinísticos**.  
- **Compreender** Autômatos sobre Objetos Infinitos para **identificar corretamente cenários onde um autômato determinístico ou não-determinístico é mais apropriado**.  

**B.5.2 Alinhamento com a Taxonomia de Bloom**  

Para avaliar com precisão as habilidades necessárias para esta competência, cada componente de conhecimento é alinhado com a **Taxonomia Revisada de Bloom**, garantindo uma progressão de aprendizagem estruturada e desafio cognitivo apropriado.  

- **Pensamento Analítico e Crítico (FPK) – Aplicar**  
  - Avalia a capacidade do estudante de **avaliar restrições do problema e justificar a escolha** entre **Autômatos Finitos Determinísticos (AFD) e Autômatos Finitos Não-Determinísticos (AFN)**.  
  - Exige a habilidade de **analisar as diferenças entre AFD e AFN** e determinar qual modelo é **mais adequado para um cenário de problema específico**.  
  - Garante que os estudantes possam **argumentar logicamente suas decisões** com base em **eficiência computacional, complexidade de implementação e restrições do sistema**.  

- **Autômatos sobre Objetos Infinitos (AFD/AFN) – Compreender**  
  - Avalia a capacidade do estudante de **diferenciar e classificar** autômatos determinísticos e não-determinísticos com base em suas propriedades.  
  - Exige a habilidade de **identificar corretamente quando cada tipo de autômato deve ser usado**, reconhecendo suas vantagens e limitações.  
  - Garante que os estudantes desenvolvam **uma compreensão conceitual da relação entre AFD, AFN e restrições do problema**, formando uma base sólida para a tomada de decisões.  

 **B.5.3 Anotação de Verbos**  
- **Compreender** → Autômatos sobre Objetos Infinitos → **Comparar** conceitos de AFD e AFN.  
- **Aplicar** → Pensamento Analítico e Crítico → **Avaliar e decidir** sobre o modelo de autômato apropriado.  

### B.6 Tabela Resumo para Competência B  

| **Competência** | **Disposições** | **Conhecimento** | **Habilidade** |
|---------------|-----------------|--------------|-----------|
| **Determinar quando usar um AFD ou AFN** | **Investigativa, Colaborativa, Responsável, Proativa, Criativa** | **Autômatos sobre Objetos Infinitos** | **Compreender (Comparar)** |
| | | **Pensamento Analítico e Crítico (FPK)** | **Aplicar (Avaliar & Decidir)** |

### **4.3 Especificação da Competência C**

### C.1 Título da Competência  
    Testando Autômatos Usando Simuladores

### C.2 Descrição da Competência
Esta competência foca na capacidade de **testar autômatos finitos usando ferramentas de simulação**. Os estudantes devem desenvolver proficiência no uso de **simuladores de autômatos** para verificar a correção de seus modelos, diagnosticar erros e refinar suas soluções por meio de testes iterativos.  

Esta competência exige a capacidade de:  
- **Usar ferramentas de simulação para validar a funcionalidade de autômatos**.  
- **Analisar o comportamento do autômato** e compará-lo com resultados esperados.  
- **Identificar e corrigir erros no projeto do autômato** por meio de solução de problemas sistemática.  
- **Aplicar estratégias estruturadas de resolução de problemas** para melhorar o desempenho do autômato.  

### C.3 Especificação de Conhecimento  
As seguintes áreas de conhecimento são essenciais para esta competência:  

- **Autômatos sobre Objetos Infinitos**  
  - Compreender o comportamento de autômatos em ambientes simulados.  
  - Usar ferramentas computacionais para testar propriedades de autômatos e validar sua execução.  

- **Resolução de Problemas e Depuração (FPK)**  
  - Necessário para **diagnosticar e resolver erros** em simulações de autômatos.  
  - Permite que os estudantes refinem modelos iterativamente, garantindo precisão e robustez.  

### C.4 Especificação de Disposição  
Semelhante às **competências anteriores**, esta competência exige que os estudantes demonstrem **atributos comportamentais** essenciais que facilitam testes, depuração e melhoria de autômatos:  

- **Colaboração** – Incentiva o trabalho em equipe na análise do comportamento do autômato e na discussão de estratégias de depuração.  
- **Responsabilidade** – Garante **testes metódicos**, documentação de problemas e refinamento dos projetos de autômatos.  
- **Proatividade** – Promove iniciativa na identificação de fraquezas nos modelos de autômatos e na aplicação de correções.  
- **Criatividade** – Apoia inovação em **técnicas de solução de problemas** e **experimentação com diferentes abordagens de simulação**.  

### C.5 Pareamento Conhecimento-Habilidade  
Esta etapa mapeia **áreas de conhecimento às habilidades correspondentes** necessárias para demonstrar competência.

 **C.5.1 Mapeamento de Conhecimento para Habilidades**  
Para alcançar esta competência, os estudantes devem demonstrar a capacidade de:  
- **Aplicar** Autômatos sobre Objetos Infinitos para **simular e validar o autômato projetado**.  
- **Aplicar** Resolução de Problemas e Depuração (FPK) para **identificar e resolver erros durante a simulação**.  

**C.5.2 Alinhamento com a Taxonomia de Bloom**  

As **áreas de conhecimento** necessárias para esta competência estão alinhadas com a **Taxonomia Revisada de Bloom**, garantindo um processo de aprendizagem estruturado que progride da compreensão de conceitos para sua aplicação em cenários práticos.  

Os estudantes devem **aplicar** seu conhecimento de **Autômatos sobre Objetos Infinitos** ao experimentar, relacionar e simular autômatos para validar o comportamento do sistema. Isso garante que possam **executar, testar e analisar simulações de autômatos** com eficácia, verificando sua correção e identificando áreas para melhoria.  

Da mesma forma, espera-se que os estudantes **apliquem** **Resolução de Problemas e Depuração (FPK)** ao diagnosticar e corrigir erros no projeto do autômato durante a simulação. Isso envolve **identificar, depurar e otimizar o comportamento do autômato** com base nos resultados das simulações, garantindo que o sistema funcione conforme o esperado.  

Ao demonstrar proficiência em ambas as áreas, os estudantes desenvolverão habilidades essenciais de resolução de problemas que lhes permitirão refinar modelos computacionais iterativamente.  

**C.5.3 Anotação de Verbos**  

Para esclarecer os resultados de aprendizagem esperados, as seguintes anotações de verbos definem as ações-chave que os estudantes devem demonstrar:  

- **Aplicar** conhecimento de Autômatos sobre Objetos Infinitos para **experimentar, relacionar e simular** autômatos.  
- **Aplicar** Resolução de Problemas e Depuração → Diagnosticar, Depurar, Refinar simulações de autômatos. 

### **C.6 Tabela Resumo para Competência C**  

| **Competência** | **Disposições** | **Conhecimento** | **Habilidade** |
|---------------|-----------------|--------------|-----------|
| **Testando Autômatos Usando Simuladores** | **Colaborativa, Responsável, Proativa, Criativa** | **Autômatos sobre Objetos Infinitos** | **Aplicar (Experimentar, Relacionar, Simular)** |
| | | **Resolução de Problemas e Depuração (FPK)** | **Aplicar (Diagnosticar, Depurar, Refinar)** |

### **4.4 Especificação da Competência D**  

### D.1 Título da Competência
    Determinando Expressões Regulares que Representam Autômatos

### D.2 Descrição da Competência
Esta competência foca na capacidade de **representar autômatos finitos usando expressões regulares**. Os estudantes devem demonstrar proficiência em traduzir **modelos computacionais baseados em estados** em **representações formais de linguagem equivalentes**, garantindo que as expressões regulares geradas descrevam com precisão o comportamento do autômato.  

Para alcançar isso, os estudantes:  
- **Compreenderão a relação entre autômatos finitos e expressões regulares**, garantindo a transformação correta entre modelos.  
- **Aplicarão conceitos de linguagem formal** para construir expressões regulares apropriadas.  
- **Testarão e refinarão** expressões regulares para verificar sua correção.  

### D.3 Especificação de Conhecimento
As seguintes áreas de conhecimento são essenciais para esta competência:  

- **Autômatos sobre Objetos Infinitos** - Fornece conhecimento fundamental sobre a estrutura e o comportamento de autômatos, servindo como pré-requisito para expressar autômatos por meio de linguagens regulares.  
- **Linguagens Regulares** - Abrange métodos formais para definir e manipular conjuntos de strings usando **expressões regulares**, garantindo que os estudantes possam construir **representações precisas** de autômatos.  
- **Resolução de Problemas e Depuração (FPK)** - Desenvolve a capacidade de **identificar, analisar e corrigir erros** no **processo de transformação de autômatos em expressões regulares**.  

### D.4 Especificação de Disposição  
Como nas competências anteriores, **atributos comportamentais** desempenham um papel crucial na conclusão bem-sucedida desta tarefa:  

- **Pensamento Investigativo** – Incentiva a exploração de abordagens alternativas para definir **expressões regulares equivalentes** para autômatos.  
- **Colaboração** - Apoia o trabalho em equipe no teste e validação de expressões regulares por meio de revisão por pares.  
- **Responsabilidade** - Garante precisão nas representações formais e adesão a princípios teóricos.  
- **Proatividade** - Promove iniciativa no refinamento e otimização de expressões regulares para eficiência.  
- **Criatividade** - Encoraja técnicas inovadoras para minimizar e reestruturar expressões regulares mantendo a correção.  

### D.5 Pareamento Conhecimento-Habilidade
Esta etapa associa **áreas de conhecimento a habilidades correspondentes**, garantindo que os estudantes desenvolvam tanto **compreensão teórica** quanto **aplicação prática**.  

**D.5.1 Mapeamento de Conhecimento para Habilidades**  
Para demonstrar esta competência, os estudantes devem ser capazes de:  
- **Compreender** Autômatos sobre Objetos Infinitos para **decompor** corretamente sistemas baseados em estados em representações formais de linguagem.  
- **Aplicar** conhecimento de Linguagens Regulares para **construir expressões regulares que representem com precisão autômatos finitos**.  
- **Aplicar** Resolução de Problemas e Depuração (FPK) para **testar e refinar expressões regulares**, garantindo correção e completude.  

**D.5.2 Alinhamento com a Taxonomia de Bloom**  
As habilidades necessárias para esta competência estão alinhadas com a **Taxonomia Revisada de Bloom**, garantindo uma abordagem de aprendizagem estruturada:  

- **Compreender Autômatos sobre Objetos Infinitos** é essencial, pois **a compreensão da estrutura do autômato é um pré-requisito** para traduzi-lo corretamente em uma expressão regular.  
- **Aplicar Linguagens Regulares** é necessário porque os estudantes devem **construir expressões regulares que modelem com precisão o comportamento do autômato**, demonstrando proficiência em representação formal de linguagem.  
- **Aplicar Resolução de Problemas e Depuração** garante que os estudantes possam **validar, testar e refinar suas expressões regulares**, identificando e corrigindo erros para assegurar que as expressões representem verdadeiramente os autômatos associados.  

Ao dominar essas habilidades, os estudantes ganham **um entendimento profundo das transformações de linguagem formal**, aprimorando sua capacidade de trabalhar com **modelos computacionais e fundamentos teóricos** de autômatos.  

**D.5.3 Anotação de Verbos**  
Para esclarecer os resultados de aprendizagem esperados, os seguintes verbos de ação definem as atividades-chave dos estudantes:  

- **Compreender** → Autômatos sobre Objetos Infinitos → **Decompor** autômatos em representações de linguagem equivalentes.  
- **Aplicar** → Linguagens Regulares → **Construir, Modelar, Expressar** autômatos usando expressões regulares.  
- **Aplicar** → Resolução de Problemas e Depuração → **Validar, Testar, Refinar** expressões regulares para garantir precisão.  

### D.6 Tabela Resumo para Competência D

| **Competência** | **Disposições** | **Conhecimento** | **Habilidade** |
|---------------|-----------------|--------------|-----------|
|  |  | **Autômatos sobre Objetos Infinitos** | **Compreender** |
| **Determinar Expressões Regulares que Representam Autômatos** | Investigativa, Colaborativa, Responsável, Proativa, Criativa | **Linguagens Regulares** | **Aplicar** |
| | | **Resolução de Problemas e Depuração (FPK)** | **Aplicar** |

### **4.5 Especificação da Competência E**  

### E.1 Título da Competência
    Relacionando Expressões Regulares a Autômatos Finitos

### E.2 Descrição da Competência
Esta competência foca na capacidade de **estabelecer a relação entre autômatos finitos e expressões regulares**.  

Os estudantes devem demonstrar compreensão de como **autômatos finitos podem ser representados usando expressões regulares** e vice-versa, garantindo que possam transitar com precisão entre esses dois modelos formais.  

Para alcançar isso, os estudantes:  
- **Analisarão a equivalência estrutural entre autômatos finitos e expressões regulares**.  
- **Identificarão a expressão regular correspondente para um autômato finito dado**.  
- **Demonstrarão compreensão das propriedades de linguagens regulares** que conectam essas duas representações.  

### E.3 Especificação de Conheccimentos
