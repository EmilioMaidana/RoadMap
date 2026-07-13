# 🎓 UTN FRBA — Ing. en Sistemas de Información

Dos herramientas interactivas para trackear la carrera:

[![Ver sitio](https://img.shields.io/badge/Sitio-Abrir-5fb3ff?style=for-the-badge)](https://emiliomaidana.github.io/RoadMap/)

> Reemplazá `TUUSUARIO` y `TUREPO` por tu usuario y nombre de repo reales una vez que lo subas.

## 🗺️ `roadmap.html` — Roadmap de correlativas

Roadmap con las 36 materias del plan 2023, agrupadas por nivel, con lógica de correlativas (bloqueo/desbloqueo automático según lo cursado/aprobado).

- Cada materia se marca como **Cursando** o **Aprobada**.
- No deja marcar una materia si no cumplís los requisitos de las que la preceden.
- Barra de progreso general y contadores.
- Progreso guardado en `localStorage`.

## 🗓️ `planificador.html` — Planificador de cursada (2° cuatrimestre 2026)

Combina la oferta de horarios de **Ingeniería en Sistemas** (extraída de la planilla de la Secretaría) con la currícula de la **Tecnicatura en Ciencia de Datos e IA**, para poder visualizar superposiciones y armar la inscripción.

- Catálogo de comisiones de Ingeniería con día/turno/módulo — tildás las que te interesan y marcás cuál priorizás si se superponen.
- Currícula completa de la Tecnicatura por cuatrimestre, con checkbox de aprobadas y carga manual de horario para las materias del 5° cuatrimestre (todavía sin oferta publicada).
- Grilla semanal que combina ambas, con colores distintos por carrera y resaltado de prioridad.
- ⚠️ Los horarios de Ingeniería son una **aproximación**: la planilla original solo trae número de módulo, no el horario de reloj, así que se estimó 1 módulo ≈ 1 hora según el turno. Confirmá el horario real en Autogestión antes de inscribirte.
- Todo el estado (selección, prioridades, progreso, horarios manuales) se guarda en `localStorage`.

## `index.html` — landing

Página simple que enlaza a las dos herramientas de arriba.

## Cómo correrlo local

Abrí cualquiera de los `.html` directamente en el navegador, no necesitan build ni dependencias.

## Deploy

Este repo está pensado para servirse con **GitHub Pages**:

1. `Settings → Pages → Source: main / (root)`
2. Guardar. Queda disponible en `https://TUUSUARIO.github.io/TUREPO/`
