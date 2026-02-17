### Plano de Estudo para CPSA-F (3 meses, 7-8 horas semanais)

Com base no seu perfil e nos materiais disponíveis, o plano de estudo será estruturado em **12 semanas**, com foco em:

1. **Cobrir o currículo oficial do CPSA-F**.
2. **Desenvolver habilidades práticas** por meio de exercícios e simulações.
3. **Familiarizar-se com o arc42** e os conceitos fundamentais de arquitetura.
4. **Aprofundar-se nos materiais recomendados** para consolidar o conhecimento.

---

## **Estrutura Geral do Plano**
- **Semanas 1-4**: Fundamentos e conceitos básicos.
- **Semanas 5-8**: Atributos de qualidade, trade-offs e estilos arquiteturais.
- **Semanas 9-12**: Documentação, arc42 e preparação para a prova.

Cada semana será dividida em **3 blocos de estudo** de aproximadamente 2-3 horas cada, totalizando 7-8 horas semanais.

---

## **Semana 1-4: Fundamentos e Conceitos Básicos**

### **Semana 1: Introdução ao CPSA-F e Fundamentos de Arquitetura**
**Objetivo**: Compreender o papel da arquitetura de software, o papel do arquiteto e os conceitos fundamentais.

- **Leitura**:
  - Glossário Oficial iSAQB (Seções: \"Arquitetura de Software\", \"Stakeholders\", \"Atributos de Qualidade\").
  - *Software Architecture in Practice* (Capítulos 1-3).
  - *97 Things Every Software Architect Should Know* (Leitura de 10-15 tópicos iniciais).
- **Exercícios**:
  - Identifique os stakeholders de um sistema em que você trabalha atualmente.
  - Liste 3 decisões arquiteturais que você tomou recentemente e analise se foram decisões arquiteturais ou técnicas.
- **Tarefas**:
  - Pesquisar e anotar exemplos reais de decisões arquiteturais em sistemas monolíticos e microservices.

---

### **Semana 2: Stakeholders e Comunicação Arquitetural**
**Objetivo**: Identificar stakeholders e adaptar a comunicação para diferentes públicos.

- **Leitura**:
  - Glossário Oficial iSAQB (Seção: \"Stakeholders\").
  - *Software Systems Architecture* (Capítulo 2: \"Communicating with Stakeholders\").
  - *97 Things Every Software Architect Should Know* (Leitura de mais 10-15 tópicos).
- **Exercícios**:
  - Identifique os stakeholders do sistema monolítico em que você trabalha.
  - Escreva um resumo arquitetural para um stakeholder técnico e outro para um stakeholder executivo.
- **Tarefas**:
  - Pratique explicar decisões arquiteturais complexas de forma simplificada.

---

### **Semana 3: Introdução ao arc42 e Visões Arquiteturais**
**Objetivo**: Familiarizar-se com o arc42 e compreender as visões de contexto e blocos.

- **Leitura**:
  - arc42 (Seções 1 e 2: \"Introdução e Objetivos\" e \"Visão de Contexto\").
  - *Software Architecture in Practice* (Capítulo 5: \"Views and Beyond\").
  - Glossário Oficial iSAQB (Seção: \"Views and Viewpoints\").
- **Exercícios**:
  - Crie uma **Visão de Contexto** para um sistema em que você trabalha.
  - Compare a Visão de Contexto com a **Visão de Blocos Nível 1**.
- **Tarefas**:
  - Identifique os limites do sistema e os sistemas externos que interagem com ele.

---

### **Semana 4: Atributos de Qualidade e Cenários**
**Objetivo**: Entender atributos de qualidade e como priorizá-los.

- **Leitura**:
  - *Software Architecture in Practice* (Capítulo 4: \"Quality Attributes\").
  - *Fundamentals of Software Architecture* (Capítulo 6: \"Quality Attributes\").
  - Glossário Oficial iSAQB (Seção: \"Quality Attributes\").
- **Exercícios**:
  - Liste os atributos de qualidade mais importantes para o sistema monolítico e para os microservices em que você trabalha.
  - Crie cenários de qualidade para **desempenho** e **manutenibilidade**.
- **Tarefas**:
  - Identifique trade-offs entre atributos de qualidade em um sistema que você conhece.

---

## **Semana 5-8: Atributos de Qualidade, Trade-offs e Estilos Arquiteturais**

### **Semana 5: Trade-offs Arquiteturais**
**Objetivo**: Compreender como tomar decisões conscientes de trade-offs.

- **Leitura**:
  - *Fundamentals of Software Architecture* (Capítulo 7: \"Trade-offs\").
  - *Software Architecture: The Hard Parts* (Capítulo 2: \"Trade-off Analysis\").
- **Exercícios**:
  - Analise um trade-off entre **desempenho** e **segurança** em um sistema que você conhece.
  - Liste 3 decisões arquiteturais que envolvem trade-offs e justifique-as.
- **Tarefas**:
  - Identifique decisões irreversíveis em sistemas monolíticos e microservices.

---

### **Semana 6: Estilos Arquiteturais - Parte 1**
**Objetivo**: Explorar estilos arquiteturais clássicos.

- **Leitura**:
  - *Software Architecture in Practice* (Capítulo 6: \"Architectural Styles\").
  - Glossário Oficial iSAQB (Seção: \"Architectural Styles\").
- **Exercícios**:
  - Compare os estilos **Camadas** e **Client-Server**.
  - Identifique o estilo arquitetural predominante no sistema monolítico em que você trabalha.
- **Tarefas**:
  - Liste vantagens e desvantagens de usar **Camadas** em um sistema legado.

---

### **Semana 7: Estilos Arquiteturais - Parte 2**
**Objetivo**: Aprofundar-se em estilos modernos, como microservices e event-driven.

- **Leitura**:
  - *Fundamentals of Software Architecture* (Capítulo 9: \"Microservices\").
  - *Designing Distributed Systems* (Capítulo 1: \"Distributed Systems Patterns\").
- **Exercícios**:
  - Liste os desafios de implementar microservices em um ambiente on-premise.
  - Compare **Microservices** e **Monólito Modular**.
- **Tarefas**:
  - Identifique cenários em que **Event-Driven Architecture** seria mais adequada.

---

### **Semana 8: Cenários de Qualidade e Avaliação**
**Objetivo**: Praticar a criação de cenários de qualidade e avaliação arquitetural.

- **Leitura**:
  - *Evaluating Software Architectures* (Capítulo 3: \"Scenarios\").
  - *Software Architecture in Practice* (Capítulo 7: \"Evaluating Architectures\").
- **Exercícios**:
  - Crie cenários de qualidade para **escalabilidade** e **resiliência**.
  - Avalie os riscos arquiteturais de um sistema que você conhece.
- **Tarefas**:
  - Liste perguntas críticas para avaliar a arquitetura de um sistema.

---

## **Semana 9-12: Documentação, arc42 e Preparação para a Prova**

### **Semana 9: Documentação Arquitetural**
**Objetivo**: Aprender a documentar arquitetura de forma clara e objetiva.

- **Leitura**:
  - arc42 (Seções 3-6: \"Visão de Blocos\", \"Visão de Runtime\", \"Decisões Arquiteturais\").
  - *Documenting Software Architectures* (Capítulo 4: \"Documenting Views\").
- **Exercícios**:
  - Documente uma **Visão de Blocos Nível 1** para um sistema que você conhece.
  - Escreva um ADR (Architectural Decision Record) para uma decisão recente.
- **Tarefas**:
  - Identifique lacunas na documentação de um sistema existente.

---

### **Semana 10: arc42 e Comunicação Avançada**
**Objetivo**: Dominar o arc42 e comunicar arquitetura para diferentes públicos.

- **Leitura**:
  - arc42 (Seções 7-10: \"Visão de Implantação\", \"Visão de Decisões\").
  - *Software Systems Architecture* (Capítulo 7: \"Communicating Architecture\").
- **Exercícios**:
  - Crie uma **Visão de Implantação** para um sistema em cloud.
  - Pratique explicar uma decisão arquitetural para um stakeholder não técnico.
- **Tarefas**:
  - Revise a documentação de um sistema e identifique melhorias.

---

### **Semana 11: Simulação de Prova**
**Objetivo**: Resolver questões estilo CPSA-F.

- **Exercícios**:
  - Resolva 5 questões discursivas baseadas no currículo CPSA-F.
  - Revise suas respostas com base nos critérios de clareza, objetividade e alinhamento ao arc42.
- **Tarefas**:
  - Identifique áreas de dificuldade e revise os materiais correspondentes.

---

### **Semana 12: Revisão Final e Simulação**
**Objetivo**: Consolidar o conhecimento e realizar uma simulação completa.

- **Exercícios**:
  - Resolva uma prova simulada completa (incluindo questões discursivas).
  - Revise os erros e anote os pontos de melhoria.
- **Tarefas**:
  - Releia o Glossário Oficial iSAQB e revise os principais conceitos.

---

## **Dicas Adicionais**
1. **Pratique a escrita discursiva**: Responda questões simuladas com clareza e objetividade.
2. **Reforce o arc42**: Familiarize-se com cada seção do template.
3. **Conecte teoria à prática**: Relacione os conceitos estudados aos sistemas em que você trabalha.

---

### **Plano Detalhado: Semana 1 do Mês 1**

**Objetivo da Semana**:  
Compreender os fundamentos da arquitetura de software, o papel do arquiteto e os conceitos básicos necessários para o CPSA-F. Essa semana é crucial para construir uma base sólida e alinhar o vocabulário arquitetural conforme o glossário oficial do iSAQB.

---

## **Estrutura da Semana 1**

- **Carga Horária Total**: 7-8 horas
- **Divisão do Estudo**:
  - **Bloco 1 (2-3 horas)**: Leitura e compreensão teórica.
  - **Bloco 2 (2-3 horas)**: Exercícios práticos e reflexão.
  - **Bloco 3 (2 horas)**: Revisão, anotações e aplicação prática.

---

### **Bloco 1: Leitura e Compreensão Teórica (2-3 horas)**

#### **Tópicos de Estudo**
1. **O que é Arquitetura de Software?**
   - Definição oficial do iSAQB: \"A arquitetura de software é a estrutura fundamental de um sistema, composta por seus elementos, relações e propriedades.\"
   - Diferenciar arquitetura de design técnico e implementação.

2. **O Papel do Arquiteto de Software**
   - Responsabilidades principais:
     - Tomada de decisões arquiteturais significativas.
     - Comunicação com stakeholders.
     - Garantia de que as decisões atendem aos atributos de qualidade do sistema.
   - Habilidades necessárias:
     - Pensamento crítico.
     - Comunicação clara.
     - Conhecimento técnico e de negócios.

3. **Arquitetura como Conjunto de Decisões**
   - Decisões arquiteturais são aquelas que têm impacto significativo nos atributos de qualidade, custo e viabilidade de um sistema.
   - Exemplos:
     - Escolha de um estilo arquitetural (monólito vs. microservices).
     - Decisão sobre tecnologias ou frameworks.

#### **Materiais de Leitura**
- **Glossário Oficial iSAQB**:
  - Seções: \"Arquitetura de Software\", \"Stakeholders\", \"Decisões Arquiteturais\".
  - Link: [Glossário Oficial iSAQB](https://public.isaqb.org/).
- **Livro: Software Architecture in Practice (4ª edição)**:
  - Capítulos 1-3:
    - Capítulo 1: Introdução à arquitetura de software.
    - Capítulo 2: O papel do arquiteto.
    - Capítulo 3: Arquitetura como conjunto de decisões.
- **Livro: 97 Things Every Software Architect Should Know**:
  - Leia os primeiros 10-15 tópicos (exemplos: \"You’re the Guardian of the Vision\", \"Simplify Essential Complexity\").

#### **Atividades**
- Faça anotações sobre:
  - Definições importantes.
  - Diferenças entre arquitetura e design técnico.
  - Exemplos de decisões arquiteturais no seu trabalho atual.
- Crie um mapa mental com os conceitos principais.

---

### **Bloco 2: Exercícios Práticos e Reflexão (2-3 horas)**

#### **Exercício 1: Identificação de Stakeholders**
- **Tarefa**: Liste os stakeholders do sistema monolítico em que você trabalha atualmente.
  - Perguntas para reflexão:
    - Quem são os usuários finais?
    - Quem financia o sistema?
    - Quem é responsável pela manutenção e operação?
    - Quem define os requisitos?
  - **Resultado esperado**: Uma lista categorizada de stakeholders (ex.: usuários técnicos, executivos, equipe de operações).

#### **Exercício 2: Decisões Arquiteturais**
- **Tarefa**: Identifique 3 decisões arquiteturais que você tomou recentemente.
  - Classifique-as como:
    - **Arquiteturais** (ex.: escolha de estilo arquitetural, divisão de módulos).
    - **Técnicas** (ex.: escolha de uma biblioteca ou framework).
  - **Perguntas para reflexão**:
    - Qual foi o impacto da decisão nos atributos de qualidade?
    - A decisão foi documentada? Se sim, como?
  - **Resultado esperado**: Um pequeno resumo para cada decisão, explicando seu impacto.

#### **Exercício 3: Reflexão sobre o Papel do Arquiteto**
- **Tarefa**: Com base no que você leu, reflita sobre o seu papel como arquiteto nos últimos anos.
  - Perguntas para reflexão:
    - Quais decisões você tomou que tiveram impacto significativo no sistema?
    - Como você comunicou essas decisões aos stakeholders?
    - Quais desafios você enfrentou ao balancear requisitos técnicos e de negócios?
  - **Resultado esperado**: Um parágrafo descrevendo como você enxerga seu papel como arquiteto.

---

### **Bloco 3: Revisão, Anotações e Aplicação Prática (2 horas)**

#### **Revisão**
1. Revise suas anotações das leituras e exercícios.
2. Certifique-se de que você compreendeu:
   - A definição de arquitetura de software.
   - A diferença entre decisões arquiteturais e técnicas.
   - O papel dos stakeholders no processo arquitetural.

#### **Aplicação Prática**
- Escolha um sistema em que você trabalha e responda:
  - **Qual é a estrutura fundamental do sistema?** (ex.: camadas, módulos, serviços).
  - **Quais decisões arquiteturais foram tomadas?**
  - **Quais stakeholders influenciaram essas decisões?**

#### **Simulação de Questões**
1. **Questão 1**: Explique a diferença entre arquitetura de software e design técnico. Dê exemplos.
2. **Questão 2**: Liste 3 stakeholders de um sistema e descreva como suas necessidades influenciam as decisões arquiteturais.
3. **Questão 3**: Cite uma decisão arquitetural que você tomou e explique como ela impactou os atributos de qualidade.

---

### **Resumo da Semana**
Ao final da semana, você deve:
- Ter uma compreensão sólida do que é arquitetura de software e do papel do arquiteto.
- Saber identificar stakeholders e suas influências nas decisões arquiteturais.
- Diferenciar decisões arquiteturais de decisões técnicas.
- Ter aplicado os conceitos ao seu contexto profissional.

---

### **Checklist de Conclusão**
- [ ] Leitura dos capítulos indicados nos materiais.
- [ ] Anotações sobre definições e conceitos principais.
- [ ] Lista de stakeholders do sistema atual.
- [ ] Resumo de 3 decisões arquiteturais recentes.
- [ ] Respostas às questões simuladas.


