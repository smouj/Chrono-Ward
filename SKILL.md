---
name: Chrono Ward
description: "⏳ Temporal drift guardian for recurring tasks with proactive replanning."
when: "When a user request matches chrono-ward capabilities or requires this domain-specific workflow."
examples:
  - "Run Chrono Ward for this task"
  - "Apply Chrono Ward to solve this workflow"
metadata:
  openclaw:
    requires: ["fs_read", "fs_write", "shell_exec", "memory_search"]
  safety_level: high
  version: "1.0.0"
  author: "smouj"
  tags: ["chrono-ward", "automation", "openclaw-skill"]
---

# ⏳ Chrono Ward

## Purpose
Guardián temporal: detecta drift en tareas repetitivas, fuerza re-planificación proactiva y conserva histórico de cambios.

## How to Use / Core Instructions
1. Primero piensa en alcance, riesgo y coste.
2. Luego valida inputs y dependencias mínimas.
3. Ejecuta en pasos pequeños y reversibles.
4. Verifica resultado con checks explícitos.
5. Si hay error, falla seguro y reporta causa + próximo paso.

## Security & Safety Guidelines
Nunca ejecutes código sospechoso sin sandbox. Reporta riesgos al usuario. No envíes datos sensibles fuera del entorno local.

## Tools Required
- fs_read
- fs_write
- shell_exec
- memory_search

## Example Flows
- Entrada -> validación -> plan -> ejecución -> verificación -> reporte.
- Reintento controlado con rollback si falla.

## Edge Cases & Error Handling
- Input incompleto: pedir datos mínimos.
- Dependencia ausente: degradar en modo seguro.
- Error persistente: detener, registrar y escalar.
