# Instrucciones para GitHub Copilot en Lab-contenido

Copilot lee este archivo automáticamente en este repositorio.
Las reglas completas del proyecto están en `CLAUDE.md` (las usa Claude Code);
este archivo resume las mismas reglas para que ambos asistentes trabajen igual.

## Sobre quién trabaja aquí

- Persona **principiante** en GitHub, git y programación. Trabaja en laptop y en el móvil.
- Responder siempre en **español**, con lenguaje sencillo y **paso a paso**.
- La primera vez que uses un término técnico (commit, rama, pull request, merge…),
  explícalo en una frase.
- Antes de proponer un cambio grande, explica qué vas a cambiar y por qué.

## Reglas de seguridad

- Nunca sugieras guardar contraseñas, claves de API, tokens ni datos de clientes
  o pacientes en el código. Si ves uno, avisa.
- No propongas borrar archivos ni ramas sin explicar el riesgo.

## Convenciones del proyecto

- Trabajar en una rama por tarea, nunca directo en `main`.
- Nombres de rama: `tipo/descripcion-corta` (ej.: `juego/piso-de-lava-sonido`).
- Mensajes de commit en español, en imperativo y cortos (ej.: `Añade sonido al derrape`).
- Carpetas: `juego/` (un archivo HTML por juego), `docs/` (guías).

## Sobre el código de los juegos

- Son páginas HTML de un solo archivo, con CSS y JavaScript dentro.
- `juego/piso-de-lava.html` usa Three.js r128 desde cdnjs (con verificación `integrity`).
  No cambies la versión sin actualizar el hash `integrity`.
- Mantén los textos visibles para el jugador en español.
- Respeta el diseño existente: colores definidos como variables CSS en `:root`.

## Reparto de trabajo con Claude Code

- **Copilot**: autocompletar mientras se escribe, explicar código seleccionado,
  arreglos pequeños, sugerir mensajes de commit y revisar pull requests.
- **Claude Code**: tareas grandes de varios archivos, probar los juegos en el navegador,
  publicar y gestionar issues y pull requests.
- Las tareas pendientes se anotan como **issues** en GitHub, para que ambos las vean.
