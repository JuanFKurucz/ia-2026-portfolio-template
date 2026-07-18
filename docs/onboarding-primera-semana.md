---
title: "Empezar el portafolio"
date: 2026-07-13
---

# Empezar el portafolio

Esta guía corresponde a tu repositorio editable. El sitio de tareas se lee; acá publicás dos casos grupales y tus evidencias individuales de continuidad.

## Primeros 30 minutos

1. Ajustá los datos mínimos de [Acerca de mí](acerca.md).
2. Confirmá que el [mapa de evidencias](portfolio/mapa-evidencias.md) contiene las 14 clases y los dos casos.
3. Abrí la [plantilla de evidencia](portfolio/plantilla-evidencia.md) y la [plantilla de caso](portfolio/plantilla.md); ubicá dónde irán `clase-02.md` y `caso-1.md`.
4. Probá el sitio localmente y ejecutá el smoke de publicación de tres pasos de esta página.
5. Leé la [política AI-safe](politica-uso-ia.md) antes de usar IA.

## Resultado de la primera semana

- El repositorio abre y el mapa se puede editar mediante commits.
- Sabés dónde vive la consigna, el artefacto compartido y la entrega formal.
- La fila Caso 1 permanece `Pendiente` hasta que exista un resultado probado.
- No publicaste secretos, PII ni material reservado.

## Flujo por clase

1. Leé la práctica y resolvé su único ejercicio `Para casa`.
2. Copiá [plantilla-evidencia.md](portfolio/plantilla-evidencia.md) usando el archivo indicado en el mapa.
3. Conservá configuración, run o comprobación, resultado comparado, decisión y límite.
4. Marcá el estado mediante un commit cuando la entrada exista y pase el validador.

## Flujo por bloque

1. Acordá con tu equipo de 2–3 una pregunta sobre el dataset o corpus común indicado en el brief del caso.
2. Usá las prácticas de la unidad como herramientas, no como una receta para copiar.
3. Conservá un resultado observable y un artefacto compartido.
4. Creá o actualizá `portfolio/caso-1.md` o `portfolio/caso-2.md` y declará tu contribución.
5. Cambiá el estado cuando puedas reproducir y defender la evidencia.
6. Entregá en WebAsignatura solo el enlace o archivo pedido.

## Contrato mínimo de evidencia individual

```markdown
## Objetivo
## Configuración
## Run o traza
## Resultado y comparación
## Evidencia
## Reproducibilidad
## Decisión y límite
## Siguiente experimento
## Uso de IA
## Microdefensa
```

## Contrato mínimo de caso

```markdown
## Objetivo
## Dataset, corpus o fixtures
## Sistema, datos, modelo y evaluación
## Resultado probado
## Evidencia
## Reproducibilidad
## Decisiones y límites
## Uso de IA
## Autoría compartida
## Microdefensa
```

## Trabajo en equipo

La evidencia técnica se mantiene una sola vez. Cada integrante del equipo de 2–3 la enlaza desde su portafolio y registra una contribución o decisión que pueda explicar. Las identidades formales quedan en WebAsignatura; no hace falta publicar nombres reales.

## Crear y publicar el repositorio

1. Abrí [ia-2026-portfolio-template](https://github.com/JuanFKurucz/ia-2026-portfolio-template) y elegí **Use this template**.
2. Nombralo `ia-2026-portafolio-<alias>` sin tu nombre completo, cédula ni identificadores de terceros. Conservá `main` como rama canónica.
3. En **Settings → Pages**, seleccioná **GitHub Actions**. No hace falta crear otra rama ni agregar tokens.

### Smoke de publicación

1. En local, ejecutá `python scripts/validate_portfolio.py` y `mkdocs build --strict`.
2. Hacé un commit pequeño en `main` y confirmá que **Calidad del portafolio** y **Publicar portafolio en GitHub Pages** terminan correctamente.
3. Abrí la URL de Pages en una ventana privada y comprobá portada, mapa y una entrada. Si Actions no está disponible, entregá el build local, el SHA del commit y la captura del resultado a través de WebAsignatura.

Antes de publicar, buscá `.env`, tokens, nombres completos, cédulas, correos, URLs privadas y datos de terceros. El validador detecta secretos comunes, pero la revisión de PII sigue siendo humana.

## Si algo falla

- Si Pages no publica, conservá la evidencia local y el comando o error observado.
- Si falta una dependencia o servicio, documentá una alternativa local, congelada o simulada.
- Si usaste IA para resolver un problema, registrá qué sugerencia aceptaste y cómo la verificaste.
- Un resultado negativo puede ser `Mínimo` o `Defendible` si está medido e interpretado.
