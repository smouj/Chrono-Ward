# ⏳ Chrono Ward

<p align="center">
  <img src="https://img.shields.io/badge/Skill-Chrono%20Ward-111827?style=for-the-badge&logo=github" alt="Chrono Ward banner" />
</p>

<p align="center">
  <a href="./README.md"><img src="https://img.shields.io/badge/README-English-1f6feb?style=for-the-badge" alt="English"></a>
  <a href="./README.es.md"><img src="https://img.shields.io/badge/README-Español-c92a2a?style=for-the-badge" alt="Español"></a>
</p>

<p align="center"><em>⏳ Detección de drift temporal.</em></p>

---

## Overview
Detector de drift temporal en tareas recurrentes para forzar re-planificación proactiva cuando cambian condiciones, datos o supuestos.

## Architecture of understanding
```mermaid
flowchart LR
  A[Input goal] --> B[Scope check]
  B --> C[Plan minimal steps]
  C --> D[Execute safely]
  D --> E[Verify outcomes]
  E --> F[Report + next steps]
```

## Installation
```bash
git clone https://github.com/smouj/Chrono-Ward.git
cd Chrono-Ward
# read the contract
cat SKILL.md
```

## Quick usage
```bash
# Example placeholder command
printf "running chrono-ward...\n"
```

## Badges
- Status: Initiating
- Difficulty: Media

## Roadmap
- [ ] Implement core logic v0
- [ ] Add integration tests
- [ ] Publish stable tag v1.0.0
