# Plantilla de portafolio de IA 2026

Este repositorio sí se edita: es la base del portafolio personal para **Inteligencia Artificial / Fundamentos del Aprendizaje Automático**. No es el sitio de tareas ni el syllabus.

La publicación canónica de esta base es [`ia-2026-portfolio-template`](https://github.com/JuanFKurucz/ia-2026-portfolio-template).

## Evaluación 2026

- Parciales A0: **40%**.
- Casos grupales: **20%**.
- Cinco iRAT/tRAT: **20%**.
- Portafolio individual: **20%**.

Las defensas de las clases 7 y 14 validan autoría individual de los casos y habilitan el bonus del leaderboard. WebAsignatura conserva consignas evaluativas, plazos, devoluciones y notas.

## Primeros 30 minutos

1. Abrí `docs/index.md` y seguí el onboarding.
2. Editá `docs/acerca.md` con una presentación breve.
3. Confirmá que `docs/portfolio/mapa-evidencias.md` contiene las 14 evidencias individuales y los dos casos.
4. Revisá `docs/politica-uso-ia.md`.
5. Probá el sitio localmente antes de entregar el link.

## Cómo crear un caso defendible

1. Copiá `docs/portfolio/plantilla.md` como `docs/portfolio/caso-1.md` o `caso-2.md`.
2. Usá el dataset, corpus o fixture común indicado en el brief público del caso; una fuente distinta sólo corresponde si la consigna la autoriza.
3. Incluí objetivo, resultado probado, evidencia, reproducibilidad, decisiones, límites, uso de IA y contribución.
4. Enlazá el artefacto técnico compartido con tu pareja; no dupliques el informe.
5. Entregá en WebAsignatura solo el enlace o archivo pedido.

## Ejecutar localmente

```bash
python -m pip install -r requirements.txt
mkdocs serve
```

## Verificar

```bash
mkdocs build --strict
```

## No subas

- claves reales, `.env`, tokens o credenciales;
- datos privados de estudiantes, clientes o terceros;
- historiales completos de chat con información sensible;
- notebooks de solución ajenos o material de corrección privada.

## Validación formativa

Cada push ejecuta **Calidad del portafolio**:

- valida Caso 1 y Caso 2 y sus estados en el [mapa de casos](docs/portfolio/mapa-evidencias.md);
- comprueba que una fila en `Mínimo`, `Defendible` o `Revisado` tenga su entrada y las secciones esenciales;
- detecta enlaces locales rotos y posibles secretos;
- construye MkDocs en modo estricto.

Los errores bloquean la publicación por seguridad o estructura. Las advertencias orientan mejoras, pero no sustituyen la devolución docente. El workflow no ejecuta notebooks ni código del estudiante. Cuando la calidad pasa en `main`, Pages publica el sitio automáticamente.
