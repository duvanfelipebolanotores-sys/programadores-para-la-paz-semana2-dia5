# Programadores para la Paz – Semana 2 Día 5

## Overview
Static educational project containing a community participation form ("Formulario Participa") built with plain HTML and CSS. The activity is part of a programming course (Programadores para la Paz, Semana 2 Día 5) focused on accessibility, clear language, data minimization, and responsible information verification.

## Project structure
- `semana2/` – Files students must complete:
  - `index.html` – Participation form
  - `styles.css` – Form styling
  - `checklist-accesibilidad.txt` – Accessibility checklist
  - `reflexion-verificacion.txt` – Reflection on responsible verification
- `instrucciones/guia-practica-semana2-dia5.txt` – Practice guide
- `README.md` – Activity instructions and required Git workflow

## Replit environment setup
- Language runtime: Python 3.11 (used only to serve static files in development)
- Workflow `Start application`: serves the `semana2` directory as a static site on port 5000 using Python's built-in HTTP server, bound to `0.0.0.0` so the Replit preview proxy can reach it.
  - Command: `python -m http.server 5000 --bind 0.0.0.0 --directory semana2`
- Deployment: configured as a `static` deployment with `publicDir = semana2`.

## Notes
- This is a pure static site; no backend, database, or build step is required.
- The README instructs students to work on personal Git branches (`nombres_apellidos`) and never on `main`.
