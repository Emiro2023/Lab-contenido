# Instrucciones de trabajo para Lab-contenido

Este archivo lo lee Claude Code al empezar cada sesión en este repositorio.
También sirve como guía para la persona dueña del repo.

## Sobre quién trabaja aquí

- Es **principiante** en GitHub, git, Claude Code y en las herramientas conectadas
  (Google Drive, Docs, Sheets, Gmail, Calendar, Google One / Gemini, Notion, Canva,
  Adobe, Vercel, WordPress y demás conectores).
- Trabaja mucho **desde el móvil**.
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
