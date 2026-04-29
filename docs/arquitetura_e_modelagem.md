## Arquitetura e Modelagem
 
Monorepo com tres componentes principais: Server (orquestrador central), Frontend (React + Vite) e Collector (ingestao de documentos). Modelo arquitetural RAG com centralized orchestration. Sistema de providers com padroes Factory, Strategy e Adapter para isolar dependencias de LLMs e bancos vetoriais.
 
**MPS.BR**
- PCP 1: atende parcialmente — sem rastreabilidade formal entre requisitos e design
- PCP 1+: nao atende — sem criterios explicitos de decisao arquitetural nem registro de alternativas
- PCP 2: atende parcialmente — avaliacoes ocorrem de forma reativa
- PCP 3: atende — implementacao consistente com a arquitetura definida
- PCP 3+: atende parcialmente — evolucao continua mas sem documentacao estruturada
**CMMI**
- Niveis 1 e 2 de TS atendidos (solucao construida e design consistente)
- Nivel 3 limitado pela ausencia de documentacao formal, criterios de decisao e registros de alternativas
**Sugestao de Melhoria**
- Criar documentacao arquitetural com diagramas e ADRs (Architecture Decision Records)
- Formalizar criterios de decisao tecnica com registro de alternativas avaliadas
- Reduzir acoplamento do server por modularizacao adicional, separando responsabilidades em camadas mais independentes

---

Verifique as [evidências](/evidencias/arquitetura_e_modelagem/) e [diagramas](/diagramas/)