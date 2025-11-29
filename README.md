# Visualización rápida del blueprint

Este repo contiene un panel HTML ligero para explorar, de forma dinámica, el blueprint de la herramienta de análisis financiero descrita previamente.

## Cómo verlo en Codex
1. Desde esta carpeta, lanza un servidor estático:
   ```bash
   python -m http.server 8000
   ```
2. Abre la URL que muestra el terminal (por defecto http://localhost:8000) y navega a `index.html`.
3. Usa los desplegables para revisar cada capa (ingesta, KPIs, LLM, datos externos, backend, dashboard, seguridad y evaluación).

> No requiere dependencias adicionales; funciona solo con HTML/CSS.
