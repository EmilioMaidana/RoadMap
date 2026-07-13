# 🎓 Roadmap — Ing. en Sistemas de Información (UTN FRBA)

Roadmap interactivo para trackear mi progreso en la carrera, plan 2023, con lógica de correlativas incluida (bloqueo/desbloqueo automático de materias según lo que tengo cursado y aprobado).

[![Ver Roadmap](https://img.shields.io/badge/Roadmap-Ver%20progreso-5fb3ff?style=for-the-badge)](https://emiliomaidana.github.io/roadmap/)

> Reemplazá `TUUSUARIO` y `TUREPO` por tu usuario y nombre de repo reales una vez que lo subas.

## ¿Qué hace?

- Muestra las 36 materias del plan agrupadas por nivel.
- Cada materia se puede marcar como **Cursando** o **Aprobada**.
- Respeta las correlativas: no te deja marcar una materia si no cumplís los requisitos de cursada/aprobada de las que la preceden.
- Barra de progreso general y contadores (aprobadas, cursando, disponibles, bloqueadas).
- El progreso se guarda en el `localStorage` del navegador.

## Cómo correrlo local

Simplemente abrí `index.html` en el navegador, no necesita build ni dependencias.

## Deploy

Este repo está pensado para servirse con **GitHub Pages**:

1. `Settings → Pages → Source: main / (root)`
2. Guardar. Queda disponible en `https://TUUSUARIO.github.io/TUREPO/`
