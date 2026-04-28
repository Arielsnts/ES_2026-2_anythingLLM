## Controle de Qualidade
 
Governanca baseada em CONTRIBUTING.md com exigencia de issue preexistente, conventional commits, checklist de self-review e aprovacao por pares. ESLint e Prettier no CI cobrem os tres subprojetos. Lacuna: comando de lint nao usa `--max-warnings 0`, ou seja, warnings nao bloqueiam o merge. Ausencia de Code Coverage (Codecov). Divida tecnica gerenciada de forma reativa e transparente via labels e FIXME no codigo.
 
**MPS.BR**
- GQA 1 a 5: atendidos satisfatoriamente para contexto open source
- GQA 6: parcialmente — sem fluxo de escalonamento formal para nao-conformidades internas
- GQA 7: nao atende — sem Plano de GQA nem relatorios periodicos de metricas de qualidade
**CMMI**
- PPQA atendido em avaliacao objetiva via pipeline automatizado
- Registro e comunicacao de nao-conformidades internas apenas parcial (ex: FIXME silenciado no codigo sem registro formal)
- Nivel gerenciado, mas nao plenamente institucionalizado
**Sugestao de Melhoria**
- Promover regras criticas de warn para error no ESLint e adicionar `--max-warnings 0`
- Avaliar migracao incremental para TypeScript
- Associar issues de divida tecnica a milestones com prazos definidos
- Incluir relatorios simplificados de metricas de qualidade nos ciclos de release
