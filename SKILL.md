---
name: chrono-ward
description: "Detección de drift temporal."
metadata:
  {
    "openclaw": {
      "emoji": "⏳",
      "version": "0.1.0",
      "author": "smouj"
    }
  }
---

# Chrono Ward

## Purpose
Detector de drift temporal en tareas recurrentes para forzar re-planificación proactiva cuando cambian condiciones, datos o supuestos.

## Scope
- Execute this skill when tasks match this domain.
- Keep actions measurable and reversible.
- Prefer local-first execution and minimal permissions.

## Inputs expected
- Goal/intention in plain language
- Optional constraints (time/cost/privacy)
- Optional files/URLs needed for context

## Outputs
- Brief execution plan
- Step-by-step actions performed
- Verification checks
- Rollback/recovery notes

## Standard workflow
1. Validate scope and constraints.
2. Build a minimal execution plan.
3. Execute in small safe steps.
4. Verify results with explicit checks.
5. Summarize outcome + next steps.

## Commands (reference)
```bash
# validation stub
printf "running chrono-ward checks...
"

# add project-specific command here
# ./scripts/chrono-ward.sh
```

## Guardrails
- Never expose secrets in logs or outputs.
- Avoid destructive actions without explicit confirmation.
- Fail safely and report actionable diagnostics.

## Installation notes
- No external dependency is required for the documentation skeleton.
- Add dependencies in this section when implementation starts.

## Test checklist
- [ ] Happy path validated
- [ ] Error path validated
- [ ] Idempotency checked
- [ ] Security constraints verified

## Changelog
- 0.1.0: Initial structure, purpose, workflow and guardrails.
