---
title: "Mapa de evidencias"
date: 2026-07-15
progress_mode: classes_and_cases
expected_classes: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14]
expected_cases: [CASO1, CASO2]
---

# Mapa de evidencias del portafolio

Estas tablas Markdown son la fuente de verdad. Las prácticas son individuales; los casos se construyen en equipos de 2–3, pero el estado y la capacidad de defenderlos son personales.

## Cómo usar este mapa

1. Copiá [plantilla-evidencia.md](plantilla-evidencia.md) después del único ejercicio `Para casa` de cada clase.
2. Copiá [plantilla.md](plantilla.md) al iniciar cada caso.
3. Usá sólo `Pendiente`, `Mínimo`, `Defendible` o `Revisado`.
4. Entregá en WebAsignatura únicamente lo solicitado.
5. No publiques respuestas A0, secretos, feedback ni datos privados.

<div class="ucu-progress-dashboard" data-ucu-progress-dashboard>
El resumen visual aparece con JavaScript. Las tablas siempre conservan el progreso.
</div>

<div class="ucu-progress-source" data-ucu-progress-source markdown="1">

## Evidencias individuales

| Clase | Unidad | Evidencia central | Archivo sugerido | Estado |
|---:|---|---|---|---|
| 1 | Introducción | EDA manual, preguntas y límite | `portfolio/01-primera-entrada.md` | Pendiente |
| 2 | UT1 | Baseline y primer run MLflow | `portfolio/clase-02.md` | Pendiente |
| 3 | UT1 | Comparación de regresión/clasificación | `portfolio/clase-03.md` | Pendiente |
| 4 | UT1 | Clustering/PCA y decisión de pertinencia | `portfolio/clase-04.md` | Pendiente |
| 5 | UT2 | Primer entrenamiento y curva | `portfolio/clase-05.md` | Pendiente |
| 6 | UT2 | Selección contra overfitting | `portfolio/clase-06.md` | Pendiente |
| 7 | Evaluación 1 | Reflexión individual de defensa | `portfolio/clase-07.md` | Pendiente |
| 8 | UT3 | CNN, transfer y augmentation | `portfolio/clase-08.md` | Pendiente |
| 9 | UT3 | Error visual, IoU/Dice o explicabilidad | `portfolio/clase-09.md` | Pendiente |
| 10 | UT4 | Búsqueda semántica evaluada | `portfolio/clase-10.md` | Pendiente |
| 11 | UT4 | RAG, grounding y abstención | `portfolio/clase-11.md` | Pendiente |
| 12 | UT4 | Traza de agente correcta y problemática | `portfolio/clase-12.md` | Pendiente |
| 13 | UT5 | Smoke, release gate y rollback | `portfolio/clase-13.md` | Pendiente |
| 14 | Evaluación 2 | Reflexión individual de defensa | `portfolio/clase-14.md` | Pendiente |

</div>

## Casos grupales

<div class="ucu-progress-source" data-ucu-progress-source markdown="1">

| Caso | Bloque | Evidencia central | Archivo sugerido | Estado |
|---|---|---|---|---|
| CASO1 | UT1–UT2 · ML clásico | Baseline, runs MLflow, comparación, errores, decisión y límite | `portfolio/caso-1.md` | Pendiente |
| CASO2 | UT3–UT5 · NLP, agentes y despliegue | Runs MLflow, traza LangSmith o local, smoke test, release y rollback | `portfolio/caso-2.md` | Pendiente |

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
