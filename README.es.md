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

## Resumen
Detector de drift temporal en tareas recurrentes para forzar re-planificación proactiva cuando cambian condiciones, datos o supuestos.

## Arquitectura de entendimiento
```mermaid
flowchart LR
  A[Objetivo de entrada] --> B[Chequeo de alcance]
  B --> C[Plan mínimo de pasos]
  C --> D[Ejecución segura]
  D --> E[Verificación]
  E --> F[Reporte + siguientes pasos]
```

## Instalación
```bash
git clone https://github.com/smouj/Chrono-Ward.git
cd Chrono-Ward
cat SKILL.es.md
```

## Uso rápido
```bash
printf "ejecutando chrono-ward...\n"
```

## Estado
- Status: Iniciando
- Dificultad: Media

## Roadmap
- [ ] Implementar lógica core v0
- [ ] Añadir tests de integración
- [ ] Publicar tag estable v1.0.0
