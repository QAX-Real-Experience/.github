---
description: Descompone una base de historia de usuario en tickets Ready (DoR) en el tablero Campus QAX. Requiere autorización para crear.
agent: tl-qa
subtask: true
---

$ARGUMENTS

Toma esta **base de historia de usuario** y organiza tickets para el tablero QAX Real Experience:

1. Descompón en tareas atómicas, accionables por un aprendiz, cumpliendo el Definition of Ready (identificación, contexto, alcance, nivel APIs/Web, repositorio/framework, criterio de salida).
2. Muéstrame el **plan de tickets** redactados (sin crear nada todavía) para aprobación.
3. Cuando yo diga "sí":
   - Crea los issues con `gh issue create` en el repo correspondiente (por defecto `QAX-Real-Experience/qax-real-exp-playwirght`).
   - Usa el template de cuerpo del agente (Contexto / Alcance / Nivel / Repositorio / Criterio de salida / Flujo).
   - Linkea cada issue al tablero `orgs/QAX-Real-Experience/projects/1` y mueve la tarjeta a `Ready`.
4. Reporta los IDs creados y cómo quedó el tablero.