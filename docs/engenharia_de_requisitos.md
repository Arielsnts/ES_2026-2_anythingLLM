## Engenharia de Requisitos
 
Sem documento formal de requisitos. Issues funcionam como substituto informal de RFC. O CONTRIBUTING.md exige que todo PR tenha uma issue associada. Rastreabilidade parcial via GitHub (Issue > PR > Commit > Release). Foram identificados casos de violacao da propria regra de vinculacao (PR #3077, PR #4819).
 

---

## MPS.BR
- REQ 1: atende parcialmente — qualidade varia conforme o contribuidor
- REQ 2: nao atende — sem backlog estruturado nem criterios de aceitacao
- REQ 3: atende parcialmente — regra existente, mas aplicacao inconsistente
- REQ 4: atende parcialmente — rastreabilidade direta existe, rastreabilidade inversa nao e garantida
- REQ 5: nao atende — sem revisao formal de consistencia entre o que foi solicitado e o que foi entregue

---

## CMMI
- Processo de mudancas funcional na pratica, mas informal e sem CCB
- Todas as decisoes concentradas em um unico mantenedor
- Analise de impacto inexistente antes do inicio do desenvolvimento

---

## Sugestao de Melhoria
- Criar template RFC formal com analise de impacto, alternativas e aprovacao por pelo menos dois mantenedores
- Implementar pipeline automatizado para monitorar breaking changes de APIs externas
- Aplicar tecnicamente a regra de vinculacao de issues via GitHub Actions (bloqueio automatico)
- Exigir issue de follow-up para entregas parciais antes do merge

---

Verifique as [evidências](/evidencias/engenharia_de_requisitos/)