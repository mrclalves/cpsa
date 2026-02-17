## 🔵 Mapa Mental — CPSA‑Foundation 

### 🔵 Introdução
- **Objetivo:** linguagem comum, foco em **decisões significativas**, **atributos de qualidade** e **comunicação**.
- **Competências:** arquitetura como decisões; stakeholders; estilos vs. qualidade; **views/viewpoints**; **arc42**.
- **Escopo:** fundamentos, não tecnologia específica; alinhamento **negócio–técnico–operacional**.

---

### 🔵 Conceitos Fundamentais de Arquitetura
- **Arquitetura = elementos + relacionamentos + princípios** (design/evolução).
- **Decisões arquiteturais:** impacto, irreversibilidade relativa, **trade-offs**.
- **Qualidade vs. funcional:** cenários mensuráveis (estímulo, ambiente, medida).
- **Princípios:** **alta coesão**, **baixo acoplamento**, **SoC**, **limites claros**.
- ⚠️ Erros: confundir arquitetura com diagrama; ignorar restrições; não medir qualidade.

---

### 🔵 Stakeholders e Comunicação
- **Perfis:** negócio/produto, usuários, **DevOps/Operações**, **Segurança/Compliance**, suporte, gestão, finanças.
- **Preocupações específicas** por papel; critérios de aceitação claros.
- **Técnicas:** workshops de qualidade, entrevistas, mapeamento de preocupações.
- **Adequação da mensagem** à audiência; evitar jargão indevido.

---

### 🔵 Atributos de Qualidade e Cenários
- Principais: **desempenho**, **disponibilidade**, **segurança**, **modificabilidade**, **escalabilidade**, **testabilidade**, **usabilidade**.
- **Cenários testáveis:** estímulo + ambiente + medida/critério.
- **Táticas por atributo:** cache, redundância, particionamento, isolamento, gateways, etc.
- **Trade-offs:** latência vs. consistência; segurança vs. usabilidade; flexibilidade vs. complexidade.
- ⚠️ Antipadrões: NFRs vagos (“rápido”, “seguro”) sem métrica.

---

### 🔵 Estilos Arquiteturais e Padrões
- **Camadas:** dependências controladas; testabilidade/modificabilidade.
- **Cliente–Servidor:** contratos claros; centralização; impacto de rede/latência.
- **Pipes & Filters:** composição em estágios; reuso; throughput vs. latência.
- **Event‑Driven:** assíncrono; desacoplamento temporal/espacial; observabilidade mais complexa.
- **Microservices:** autonomia; implantação independente; custo operacional.
- **Monólito Modular:** simplicidade operacional; módulos coesos; limites internos fortes.
- **Seleção por drivers:** atributos prioritários + restrições.

---

### 🔵 Documentação (Views, Viewpoints, arc42)
- **View:** representação para preocupações específicas.
- **Viewpoint:** propósito, stakeholders, notação, convenções.
- **Kit mínimo de views:**
  - **Contexto** (fronteiras/sistemas vizinhos)
  - **Lógica/Blocos** (responsabilidades/interações)
  - **Runtime** (comportamento dinâmico/cenários)
  - **Implantação** (nós, redes, zonas de segurança)
- **arc42:** objetivos, restrições, contexto, solução, qualidade, riscos, decisões.
- **Boas práticas:** consistência entre views; rastreabilidade a requisitos/cenários.

---

### 🔵 Decisões Arquiteturais e ADRs
- **Por quê registrar:** rastreabilidade, alinhamento, onboarding, governança.
- **Estrutura ADR:** contexto → problema → alternativas → **decisão** → **trade-offs** → **consequências**.
- **Práticas:** granularidade adequada; ligação a cenários e riscos; versionamento.

---

### 🔵 Requisitos, Restrições e Contexto
- **Funcionais vs. não funcionais**; metas de produto; compliance/regulações.
- **Restrições:** tecnológicas, organizacionais, processo, orçamento/tempo.
- **Contexto do sistema:** integrações, protocolos, contratos, **SLAs externos**; dependências críticas.

---

### 🔵 Avaliação Arquitetural (noções)
- **Motivação:** reduzir riscos cedo; validar qualidade.
- **Técnicas:** peer reviews, “what‑if”, protótipos.
- **ATAM (visão geral):** drivers, cenários críticos, pontos sensíveis, riscos.
- **Resultados:** lista priorizada de riscos e trade‑offs documentados.

---

### 🔵 Segurança, Operação e Sustentabilidade
- **Segurança por design:** mínimo privilégio, defesa em profundidade, fail‑secure.
- **Operabilidade/Observabilidade:** logs estruturados, métricas, tracing, **SLO/SLI**.
- **Sustentabilidade:** evitar débito; evolução incremental; automação (testes/CI/CD).

---

### 🔵 Testabilidade e Qualidade de Implementação
- **Arquitetura–código:** módulos claros, contratos/intefaces estáveis.
- **Níveis de teste:** unidade, contrato, integração, E2E, não funcionais (perf, segurança).
- **Governança leve:** linters, reviews, matrizes de dependência, quality gates.

---

### 🔵 Encerramento e Preparação para CPSA‑F
- **Recapitular vocabulário iSAQB** e conceitos‑chave.
- **Checklist:** cenários por atributo; seleção de estilo por drivers; pacote mínimo de views; 3–5 **ADRs**.
- ⚠️ Armadilhas:
  - Definir “arquitetura” como diagrama (e não decisões).
  - NFRs sem métrica.
  - Escolher microservices por moda, sem drivers.

---

Se quiser, posso adaptar este mapa para uma página de revisão rápida (A4) ou transformar cada tópico em cartões de estudo com perguntas estilo CPSA‑F.