# Relatório de Especificação de Competências: Tarefa 02 - Controle de Tráfego

## Introdução

Este relatório aplica o **Processo de Especificação de Competências (PEC)** ao cenário de Aprendizagem Baseada em Problemas (ABP) intitulado **"Controle de Tráfego"**, que envolve os alunos no desenvolvimento de uma solução computacional utilizando **Máquinas de Turing** para monitoramento e classificação de veículos em rodovias. A tarefa integra métodos formais e pensamento sistêmico para modelar um problema real identificado pelo Departamento de Infraestrutura de Transportes da Bahia (DERBA).

Através da metodologia PEC, as competências são extraídas e estruturadas com base na análise da descrição da tarefa, domínios de conhecimento relevantes, objetivos de aprendizagem e disposições comportamentais. O objetivo é definir um framework robusto de competências alinhado tanto com o **desenvolvimento de habilidades técnicas** quanto com a **resolução colaborativa de problemas**.

## 1. Análise da Descrição da Tarefa

A tarefa *Controle de Tráfego* desafia os alunos a desenvolver uma solução computacional formal que aborda um problema real identificado pelo **Departamento de Infraestrutura de Transportes da Bahia (DERBA)**: a deterioração de rodovias devido à pressão excessiva do tráfego noturno de veículos pesados.

Para apoiar os esforços de prevenção de desgaste do pavimento, os alunos devem projetar um sistema capaz de:

* **Processar dados de sensores** coletados nas entradas e saídas de veículos na rodovia Aratu;
* **Classificar veículos** em três categorias de peso (leve, pesado e muito pesado);
* **Contar ocorrências** para cada categoria durante a noite anterior; e
* **Identificar a categoria mais frequente**, permitindo que o DERBA priorize intervenções.

O sistema deve ser modelado usando **Máquinas de Turing**, refletindo um modelo teórico porém expressivo de computação. Os entregáveis incluem um ou mais **arquivos de Máquina de Turing baseados no JFLAP** e um **relatório técnico** em conformidade com os padrões de formatação da SBC, explicando claramente a lógica de classificação, racional de design e processo de simulação.

Esta tarefa requer que os alunos:

* **Traduzam objetivos definidos pelo usuário** em especificações formais de sistema baseadas na teoria da computabilidade;
* **Modelem restrições do mundo real** (ex: estrutura de entrada dos sensores, lógica de classificação por peso) usando Máquinas de Turing;
* **Avaliem o uso de variantes de Máquinas de Turing** (ex: multifita, não-determinísticas) quando modelos padrão forem insuficientes;
* **Simulem e testem** o modelo usando ferramentas apropriadas para garantir correção funcional;
* **Colaborem efetivamente** durante o processo de resolução de problemas, documentando todas as etapas e decisões de forma estruturada e reflexiva.

Através deste cenário de aprendizagem baseada em problemas, espera-se que os alunos integrem **conhecimento teórico de computação** com **modelagem prática e simulação**, produzindo uma solução que seja tanto academicamente rigorosa quanto socialmente relevante.

## 2. Enumeração de Conhecimentos

Para completar com sucesso a tarefa *Controle de Tráfego*, os alunos devem mobilizar um conjunto inter-relacionado de domínios de conhecimento teórico e profissional. Estes domínios estão alinhados com taxonomias reconhecidas: o **ACM Computing Classification System (2012)** para conhecimentos de computação e o **ACM/IEEE CC2020** para competências profissionais.

Esta base de conhecimento garante que o problema seja abordado não apenas de uma perspectiva técnica, mas também através de raciocínio analítico, especificação formal e comunicação efetiva.

### Conhecimentos de Computação

* **Máquinas de Turing**
  * Fundamentais para representar o processo computacional necessário para classificar veículos e calcular estatísticas de frequência. Os alunos devem entender a estrutura, comportamento e poder expressivo das Máquinas de Turing para codificar operações do mundo real em um modelo formal.

* **Variantes de Máquinas de Turing**
  * O conhecimento de Máquinas de Turing multifita ou não-determinísticas é essencial quando modelos padrão são insuficientes para desempenho ou expressividade. Variantes permitem manipulação mais eficiente de dados e simulação do sistema sob restrições complexas.

* **Tese de Church-Turing**
  * Fornece a base teórica para a tarefa, reforçando a equivalência entre raciocínio algorítmico e funções Turing-computáveis. Espera-se que os alunos fundamentem suas soluções neste conceito fundamental.

* **Engenharia de Requisitos**
  * Permite a identificação, análise e formalização das necessidades do usuário (ex: demanda do DERBA por classificação de tráfego noturno) em requisitos computacionais que guiam o design do sistema.

* **Modelagem e Simulação**
  * Envolve abstrair comportamentos do sistema em representações formais e validá-los através de ferramentas como o **JFLAP**. Esta área de conhecimento suporta refinamento iterativo e verificação da solução proposta.

### Conhecimentos Profissionais (FPK)

* **Pensamento Analítico e Crítico**
  * Necessário para desconstruir o contexto do problema (ex: monitoramento e classificação de tráfego) em componentes acionáveis, e para formular modelos lógicos que atendam às expectativas das partes interessadas.

* **Resolução de Problemas e Solução de Problemas**
  * Essencial para abordar questões de implementação, como lidar com formatos de entrada não padronizados, otimizar o uso de fitas ou depurar simulações de Máquinas de Turing.

* **Comunicação Escrita**
  * Necessária para produzir um relatório bem estruturado e tecnicamente sólido que documente o racional de design, decisões de implementação e estratégias de validação. Isso garante que os resultados sejam comunicados efetivamente para públicos técnicos e não técnicos, como o DERBA.

## 3. Identificação de Objetivos de Aprendizagem

### Objetivo Geral

Desenvolver e validar soluções computacionais formais para problemas do mundo real aplicando conhecimento de **Máquinas de Turing**, com foco em modelagem, classificação e análise de dados de tráfego baseados em entrada de sensores.

Este objetivo destaca a aplicação prática de conceitos teóricos da ciência da computação, reforçando a capacidade de projetar soluções algorítmicas fundamentadas em modelos formais.

### Objetivos Específicos

Para alcançar o objetivo geral, espera-se que os alunos:

1. **Identifiquem** requisitos e restrições do sistema com base no input das partes interessadas, particularmente as necessidades expressas pelo DERBA para análise e classificação de dados de tráfego.
2. **Traduzam e alinhem** estes requisitos com as capacidades e limitações computacionais das Máquinas de Turing, garantindo um design de sistema fiel e executável.
3. **Avaliem** a adequação das Máquinas de Turing padrão e determinem quando o uso de **variantes de máquina** (ex: multifita, não-determinísticas) é necessário para melhorar expressividade ou desempenho.
4. **Apliquem** a **Tese de Church-Turing** para justificar a viabilidade do sistema proposto, conectando modelos formais de computação com o conceito intuitivo de resolução algorítmica de problemas.
5. **Forneçam** simulações de **Máquina de Turing** em formato JFLAP que demonstrem uma solução funcional para o problema.

### Importância Destes Objetivos

Estes objetivos de aprendizagem estabelecem um **caminho estruturado e progressivo** para o desenvolvimento de competências ao integrar:

* **Compreensão teórica** de modelos formais de computação;
* **Análise contextual** de problemas do mundo real;
* **Habilidades de modelagem e simulação** para implementação e validação de sistemas;
* **Reflexão crítica** sobre adequação computacional e decisões de design.

Juntos, eles garantem que os aprendizes estejam equipados para preencher a lacuna entre **conceitos teóricos abstratos** e **resolução prática de problemas**, promovendo uma experiência de aprendizagem baseada em competências que é tanto rigorosa quanto relevante para contextos profissionais em computação.

## 4. Definições de Competências

As competências são especificadas com base nos **Objetivos de Aprendizagem (OAs)** identificados na análise da tarefa.

### Reúso de Competências

Para cumprir o objetivo de "fornecer simulações de **Máquina de Turing** em formato JFLAP que demonstrem uma solução funcional para o problema", reutilizamos a competência:

> **Testar Autômatos Usando Simuladores**

definida anteriormente na *Tarefa01 – A Máquina de Vendas de Refrigerantes e Lanches*:

Esta competência permanece totalmente relevante na tarefa atual, onde espera-se que os alunos validem seus modelos de autômatos através de ferramentas formais de simulação como o JFLAP. Os resultados de aprendizagem incluem a capacidade de executar, observar e analisar o comportamento de autômatos em um ambiente simulado, garantindo correção funcional e alinhamento com as especificações do sistema.

Além disso, como um dos entregáveis desta tarefa é um **relatório técnico** formatado de acordo com os padrões acadêmicos da **Sociedade Brasileira de Computação (SBC)**, também reutilizamos a competência definida anteriormente na *Tarefa01*:

> **Escreva, em grupo, um Relatório Técnico**

Esta competência envolve planejar, estruturar e compor um documento abrangente que comunique claramente o processo de resolução de problemas, decisões tomadas e justificativas para o modelo implementado. Ela reforça habilidades essenciais em redação técnica, colaboração em equipe e documentação.

O reúso destas competências apoia os seguintes princípios:

* **Consistência pedagógica** no desenvolvimento de competências através de diferentes tarefas de aprendizagem.
* **Reconhecimento e reforço de habilidades transversais**, como documentação e validação baseada em ferramentas.
* **Evitação de redundância** através de rastreabilidade estruturada de competências.
* **Alinhamento com educação baseada em competências**, onde um resultado de aprendizagem bem definido pode ser demonstrado em múltiplos contextos instrucionais.

Ao **reutilizar competências validadas**, garantimos que os alunos construam sobre habilidades previamente adquiridas, promovemos aprendizagem cumulativa e facilitamos práticas de avaliação baseadas em indicadores de desempenho observáveis e transferíveis.



