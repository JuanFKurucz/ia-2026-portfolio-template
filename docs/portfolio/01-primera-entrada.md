---
title: "Entrada 01 - Arranque y primera evidencia"
date: 2026-06-27
---

# Entrada 01 - Arranque y primera evidencia

## Objetivo

- **Clase o práctica:** onboarding de primera semana.
- **Objetivo:** dejar listo el portafolio personal y demostrar que sé dónde va la evidencia del curso.
- **Resultado visible:** sitio local o publicado, primera página editada y captura si GitHub Pages todavía no publica.
- **Estado:** ruta mínima de arranque.

## Configuración

- Plantilla IA 2026 sobre rama `main`.
- Entorno local y versión de Python usados para el build.
- Commit que contiene esta primera entrada.

## Run o traza

No aplica MLflow ni LangSmith. Registrá el SHA del commit y la salida de `mkdocs build --strict` o del workflow de calidad.

## Resultado y comparación

Compará el contrato esperado —build correcto y portada, mapa y entrada accesibles— con lo observado. Si falla, conservá el mensaje y la página afectada.

## Evidencia

- Link al sitio publicado o captura local guardada en `docs/assets/`.
- Commit o cambio donde se vea esta entrada.
- Nota breve indicando qué archivo edité y cómo lo verifiqué.

## Reproducibilidad

Comando local usado:

```bash
mkdocs serve
```

Si el comando falla, registrá el mensaje de error y qué probaste para resolverlo.

## Decisiones y límites

- **Decisión técnica:** usar este repo como portafolio editable, no como sitio de consignas.
- **Alternativa descartada:** entregar evidencia suelta sin contexto.
- **Límite:** publicación pendiente si GitHub Pages todavía no está activo.
- **Riesgo:** subir por error tokens, datasets privados o material de compañeros.

## Siguiente experimento

Abrí la URL publicada en una ventana privada y comprobá portada, mapa y esta entrada. Si Pages no está disponible, repetí el build desde un checkout limpio.

## Uso de IA

- **Nivel usado:** A0 si no usaste IA; A1/A2 si pediste ayuda para entender MkDocs o resolver errores.
- **Qué verifiqué manualmente:** que el sitio abre, que esta entrada existe y que no publiqué secretos.

## Microdefensa

La consigna se lee en el sitio de tareas; mi evidencia se guarda en este portafolio; la entrega formal será el link o archivo que pida WebAsignatura.
