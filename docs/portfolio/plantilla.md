---
title: "Plantilla de caso"
date: 2026-07-13
---

# Plantilla de caso

Copiá esta página como `caso-1.md` o `caso-2.md`. La entrada puede ser breve, pero debe sostener una conclusión verificable y autoría individual defendible.

> [Completar] Reemplazá esta línea y las ayudas de cada sección por evidencia del equipo antes de marcar el caso como `Mínimo`.

## Objetivo

- **Unidad y caso:** qué bloque del curso transferís a un contexto nuevo.
- **Pregunta:** qué quieren averiguar o demostrar.
- **Criterio:** qué resultado observable permitiría responderla.

## Dataset, corpus o fixtures

- Fuente, licencia o permiso de uso.
- Versión y checksum del dataset/corpus común indicado en el brief, o autorización explícita para usar otro.
- Calidad, sesgo, privacidad o limitación relevante.

## Sistema, datos, modelo y evaluación

- Sistema estudiado y contrato de entrada/salida.
- Técnica de la unidad y baseline, control o alternativa.
- Métrica, prueba o criterio de evaluación.

## Configuración

Registrá datos y split, baseline, candidato, parámetros relevantes, versión del entorno y presupuesto de cómputo.

## Run o traza

Incluí el identificador o exportación local equivalente. Para agentes, conservá entrada/salida, pasos, llamadas a herramientas, latencia/tokens y un error o denegación.

## Resultado y comparación

Explicá qué ocurrió y sostenelo con una métrica, prueba, comparación, tabla, gráfico, log, traza o caso de falla. Aclará qué permite afirmar y qué no.

## Evidencia

Incluí entre una y tres evidencias concretas: artefacto compartido, notebook, script, commit, tabla, visualización o log. Señalá cuál debería inspeccionarse primero.

- **Run o trace:** identificador de MLflow, LangSmith o exportación local equivalente, cuando corresponda.
- **Export:** `runs.csv` o `runs.json`; no publiques el directorio `mlruns/`.
- **Comparación:** baseline o referencia, candidato y criterio de selección.
- **Release:** smoke test y rollback para el Caso 2.

## Reproducibilidad

Indicá el entorno y la forma mínima de abrir, ejecutar o inspeccionar el resultado. Si depende de credenciales, hardware o un servicio externo, dejá una alternativa local, congelada o simulada.

## Decisión y límite

- **Decisión técnica:** qué eligieron y por qué.
- **Alternativa descartada:** qué no hicieron y por qué.
- **Límite o riesgo:** dónde podría fallar o inducir una conclusión incorrecta.
- **Próxima prueba:** qué evidencia cambiaría o reforzaría la decisión.

## Siguiente experimento

Definí una sola variación y el resultado que confirmaría o refutaría la hipótesis actual.

## Uso de IA

- **Nivel A0–A4 y propósito.**
- **Salida aceptada, modificada o rechazada.**
- **Verificación humana realizada.**
- **Datos que no se compartieron con herramientas externas.**

## Autoría compartida

Enlazá el artefacto único del equipo de 2–3 y describí brevemente tu contribución o una decisión que puedas defender. Las identidades formales permanecen en WebAsignatura; no hace falta duplicar el informe ni publicar nombres reales.

## Microdefensa

Prepará una explicación breve del resultado y una respuesta a una variación de dato, métrica o requisito. Ambos integrantes deben poder justificar el baseline, la evidencia y el límite sin IA.

## Referencias

Listá solo fuentes realmente usadas e indicá qué idea, dato o herramienta aportó cada una.
