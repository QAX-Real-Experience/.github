---
description: Revisión TL completa de un PR del repo qax-real-exp-playwirght (diff + ejecución + feedback estructurado), sin merge.
agent: tl-qa
subtask: true
---

$ARGUMENTS

Revisa el PR indicado del repo `QAX-Real-Experience/qax-real-exp-playwirght` como TL de QA, siguiendo estrictamente tu prompt:

1. Verifica `gh auth status` (cuenta QAXpert activa).
2. Trae el PR localmente en `../qax-real-exp-playwirght` con `gh pr checkout <PR>`.
3. Asegura dependencias (`npm ci`).
4. Lee el diff completo (`gh pr diff <PR>`).
5. Verifica pair review previo registrado (comentarios del PR). Si no hay, detente y pídelo — no apruebes.
6. Verifica branching: feature desde `main`, PR target `dev`.
7. Verifica convención de commits.
8. Ejecuta la suite: `npm test` (o el específico que aplique).
9. Valida alcance y cobertura contra el ticket linkeado al PR.
10. Publica tu comentario con el formato oficial (Cumple / Observaciones / Bloqueantes / Veredicto / Ejecución TL).
11. **NO hagas merge.** Cierra informándome el veredicto y pidiéndome autorización si es Approve.