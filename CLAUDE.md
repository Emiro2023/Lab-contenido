# Instrucciones de trabajo para Lab-contenido

Este archivo lo lee Claude Code al empezar cada sesión en este repositorio.
También sirve como guía para la persona dueña del repo.

## Sobre quién trabaja aquí

- Es **principiante** en GitHub, git, Claude Code y en las herramientas conectadas
  (Google Drive, Docs, Sheets, Gmail, Calendar, Google One / Gemini, Notion, Canva,
  Adobe, Vercel, WordPress y demás conectores).
- Trabaja **desde el móvil y desde su laptop (Windows)**.
- Tiene: Claude Code, GitHub Copilot Student, **Google Antigravity** (con plan Pro de Google)
  y VS Code. Editor principal recomendado en la laptop: **Antigravity**.
- Idioma: **español**.

## Cómo explicar y trabajar con esta persona

1. Explicar **paso a paso**, en lenguaje sencillo, sin dar por sabida la jerga.
   La primera vez que aparezca un término técnico (commit, rama, pull request, merge…),
   explicarlo en una frase.
2. Antes de hacer algo, decir **qué se va a hacer y por qué**. Después, decir **qué se hizo**
   y cómo comprobarlo.
3. Dar instrucciones para el móvil cuando haya que tocar algo en una web
   (qué botón, en qué sección). Si una pantalla puede ser distinta, pedir captura.
4. Ir de a poco: una tarea a la vez, y preguntar antes de pasar a la siguiente
   cuando el trabajo sea largo.
5. Recomendar siempre la opción más segura y simple, y explicar los riesgos
   (pagos, privacidad, borrar cosas).

## Reglas de seguridad (siempre)

- **Pedir confirmación antes de** cualquier acción difícil de deshacer o que salga hacia fuera:
  borrar archivos o ramas, hacer merge a `main`, publicar una web, enviar correos,
  crear eventos, compartir documentos, gastar dinero o créditos.
- **Nunca** subir al repo contraseñas, claves de API, tokens ni datos personales
  de clientes o pacientes. Si aparece uno, avisar y no subirlo.
- Si una web pide **tarjeta o pago** inesperado, detenerse y avisar.
- Configuración de privacidad recomendada en Copilot: sugerencias de código público
  **bloqueadas** y uso de datos para entrenar IA **desactivado** (ya aplicado).

## Cómo organizar el trabajo en GitHub

### Flujo de trabajo (de idea a publicado)

1. **Issue**: anotar la idea, tarea o error en la pestaña *Issues* del repo.
2. **Rama**: crear una rama para esa tarea; nunca trabajar directo sobre `main`.
3. **Commits**: guardar cambios pequeños y frecuentes, cada uno con un mensaje claro.
4. **Pull request (PR)**: proponer unir la rama a `main`; revisar los cambios antes.
5. **Merge**: unir cuando todo esté bien. Luego se puede borrar la rama.
6. **Publicar** (GitHub Pages u otro servicio) solo desde `main`.

### Nombres y mensajes

- Ramas: `tipo/descripcion-corta`, por ejemplo `juego/piso-de-lava-sonido`,
  `docs/guia-inicio`, `arreglo/menu-movil`.
- Mensajes de commit en español, en imperativo y cortos:
  `Añade sonido al derrape`, `Corrige el menú en el móvil`.
- Issues con título claro y una lista de qué debe quedar hecho.

### Estructura de carpetas del repo

- `juego/`: juegos (cada juego en su propio archivo HTML).
- `docs/`: guías y documentación (crear cuando haga falta).
- `CLAUDE.md`: estas instrucciones.
- Un `README.md` explica qué hay en el repo (pendiente de crear).

### Estado actual del repo

- La rama principal `main` **todavía no existe**. El trabajo está en la rama
  `ccr-f1ec6aff-wa7nxl`. Próximo paso sugerido: crear `main` con un pull request,
  como práctica guiada.
- La cuenta tiene **GitHub Student Developer Pack** (con GitHub Pro) y
  **GitHub Copilot Student** activos.

## Claude Code + Antigravity + Copilot: cómo trabajan juntos

Copilot lee `.github/copilot-instructions.md`; Claude Code lee este archivo.
En Antigravity, añadir una regla que diga que siga `CLAUDE.md`.
Si cambia una regla importante, actualizar estos archivos.

### Un papel para cada herramienta (para no confundirse)

1. **Laptop → Antigravity** (editor + agentes de Gemini). Un solo editor:
   no usar VS Code y Antigravity a la vez.
2. **Tareas grandes, en la nube o desde el móvil → Claude Code.**
3. **GitHub.com y app GitHub → Copilot**: revisar pull requests, preguntas rápidas.
4. **GitHub es el centro**: todo se guarda allí, se trabaje con la herramienta que sea.

La tabla de abajo nombra VS Code; en la laptop, lo mismo aplica a Antigravity
(autocompletar, explicar código, arreglos pequeños) usando su agente de Gemini.

### Qué hace cada uno

| Tarea | Herramienta |
|---|---|
| Autocompletar código mientras se escribe | Copilot (VS Code) |
| "¿Qué hace este código?" (seleccionar → Explicar) | Copilot Chat (VS Code) |
| Arreglo pequeño en un archivo abierto | Copilot (VS Code) |
| Mensaje de commit sugerido | Copilot (botón ✨ en el panel de git de VS Code) |
| Resumen y revisión de un pull request | Copilot en GitHub.com |
| Preguntas rápidas sobre el repo desde el móvil | Copilot en GitHub.com o en la app GitHub |
| Crear o cambiar varias cosas a la vez, un juego nuevo, una web | Claude Code |
| Probar en el navegador, sacar capturas, revisar que funcione | Claude Code |
| Crear issues, ramas y pull requests; publicar | Claude Code |
| Planear un proyecto y explicar paso a paso | Claude Code |

### Reglas para no pisarse

1. **Issues como lista común**: toda tarea se anota como issue; así ambos la ven.
2. **Una herramienta por rama a la vez**: si Claude Code trabaja en una rama,
   no editar esa misma rama en Antigravity o VS Code al mismo tiempo (y al revés).
3. **Antes de empezar en la laptop**: en el editor, hacer *Sync / Pull*
   (traer los últimos cambios de GitHub). **Al terminar**: *Commit* y *Push*.
4. **Doble revisión**: lo que hace uno, lo puede revisar el otro.
   Ejemplo: Claude Code abre un pull request → se pide revisión de Copilot en GitHub.
5. **Copilot como agente** (opcional, más adelante): en GitHub se puede asignar un issue
   a Copilot y él abre un pull request solo. Usarlo solo con tareas pequeñas y claras,
   y revisar siempre su pull request antes de unirlo.

## Cómo organizar las demás herramientas

- **Un lugar para cada cosa**:
  - Código y páginas web → GitHub.
  - Documentos para leer y editar en equipo → Google Docs o Notion.
  - Tablas y números → Google Sheets.
  - Diseños y piezas gráficas → Canva o Adobe Express.
  - Fechas y reuniones → Google Calendar.
- **Nombres consistentes** en todas las herramientas: `Cliente - Proyecto - Tipo`,
  por ejemplo `Lab - Piso de Lava - Ideas`.
- **Carpetas por cliente o proyecto** en Google Drive, con la misma estructura siempre.
- Al usar un conector (Gmail, Drive, Calendar, Notion…), Claude explica qué va a
  leer o cambiar y pide confirmación antes de escribir, enviar o compartir.
- Revisar periódicamente qué conectores están activos y desconectar los que no se usen.
