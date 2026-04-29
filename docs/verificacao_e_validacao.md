## Verificacao e Validacao
 
Pipeline de CI/CD robusto via GitHub Actions com lint obrigatorio, testes unitarios (Jest), revisao por pares com Branch Protection Rules e ambiente de QA isolado por PR. Testes de seguranca contra SSRF e validacao de injecao de variaveis no System Prompt para prevencao de alucinacoes. Feedback da comunidade via Issues e Discord integrado ao ciclo de validacao.
 
**MPS.BR**
- VV 1 a VV 5: todos atendidos
- Selecao de artefatos, procedimentos definidos como codigo, criterios binarios de aceite, resultados registrados e comunicados na plataforma
**CMMI**
- Niveis 1, 2 e 3 de VV atendidos
- Procedimentos definidos como infraestrutura de codigo, revisoes por pares obrigatorias, registros centralizados e rastreabilidade completa
**Sugestao de Melhoria**
- Integrar frameworks de avaliacao automatizada de IA (como Ragas ou TruLens) no CI para metricas de fidelidade e relevancia das respostas
- Configurar quality gates de cobertura minima de testes (ex: 80%) via SonarQube
- Bloquear bypass de revisao por pares via "Do not allow bypassing the above settings" no GitHub, incluindo administradores

---

Verifique as [evidências](/evidencias/verificacao_e_validacao/)