# ⏳ Chrono Ward

<p align="center">
  <img src="https://img.shields.io/badge/Skill-Chrono%20Ward-111827?style=for-the-badge&logo=github" alt="Chrono Ward banner" />
</p>

<p align="center">
  <a href="./README.md"><img src="https://img.shields.io/badge/README-English-1f6feb?style=for-the-badge" alt="English"></a>
  <a href="./README.es.md"><img src="https://img.shields.io/badge/README-Español-c92a2a?style=for-the-badge" alt="Español"></a>
</p>

## Overview
Temporal drift guardian for recurring tasks with proactive replanning.

## Purpose
Guardián temporal: detecta drift en tareas repetitivas, fuerza re-planificación proactiva y conserva histórico de cambios.

## Installation
```bash
git clone https://github.com/smouj/Chrono-Ward.git
cd Chrono-Ward
cat SKILL.md
```

## Architecture (understanding)
```mermaid
flowchart LR
  A[Input] --> B[Validate scope]
  B --> C[Plan safe steps]
  C --> D[Execute]
  D --> E[Verify]
  E --> F[Report]
```

## Status
Initiating

## Difficulty
Media
