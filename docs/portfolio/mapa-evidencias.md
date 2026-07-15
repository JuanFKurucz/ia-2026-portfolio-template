---
title: "Mapa de casos"
date: 2026-07-15
progress_mode: cases
expected_cases: [CASO1, CASO2]
---

# Mapa de casos del portafolio

Esta tabla Markdown es la fuente de verdad. Los casos se construyen en equipos de 2–3; el estado y la capacidad de defenderlos son personales.

## Cómo usar este mapa

1. Copiá [plantilla.md](plantilla.md) al iniciar cada caso.
2. Enlazá el artefacto compartido y declará tu contribución.
3. Usá sólo `Pendiente`, `Mínimo`, `Defendible` o `Revisado`.
4. Entregá en WebAsignatura únicamente lo solicitado.
5. No publiques respuestas A0, secretos, feedback ni datos privados.

<div class="ucu-progress-dashboard" data-ucu-progress-dashboard>
El resumen visual aparece con JavaScript. Esta tabla siempre conserva el progreso.
</div>

<div class="ucu-progress-source" data-ucu-progress-source markdown="1">

| Caso | Bloque | Evidencia central | Archivo sugerido | Estado |
|---|---|---|---|---|
| CASO1 | UT1–UT2 · ML clásico | Baseline, runs MLflow, comparación, errores, decisión y límite | `portfolio/caso-1.md` | Pendiente |
| CASO2 | UT3–UT5 · NLP, agentes y despliegue | Runs MLflow, traza LangSmith, smoke test, release y rollback | `portfolio/caso-2.md` | Pendiente |

</div>

## Estados

- `Pendiente`: todavía no existe un resultado verificable.
- `Mínimo`: existe artefacto, resultado y forma de inspeccionarlo.
- `Defendible`: podés explicar contribución, decisiones, límites y uso de IA.
- `Revisado`: incorporaste una devolución o mejora comprobada.

## Contrato de evidencia

Cada entrada incluye pregunta, configuración, run o trace, resultado, comparación, decisión, límite y siguiente experimento. No subas `mlruns/`; exportá `runs.csv` o `runs.json` y conservá sólo artefactos seleccionados.

## Defensas en clases 7 y 14

- Clase 7: defensa del Caso 1.
- Clase 14: defensa del Caso 2.
- Cada equipo tiene tres minutos de presentación y dos de preguntas.
- La nota del caso es grupal; la autoría y el acceso al bonus se validan individualmente.
- Con más de 12 equipos se habilitan dos paneles con los mismos criterios.

Los casos valen **20%**, el portafolio individual **20%**, los parciales **40%** y los cinco iRAT/tRAT **20%**.
