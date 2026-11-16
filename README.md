# Seguimiento · Microsoft Elevate for Educators

Panel compartido para el seguimiento del proyecto Microsoft Elevate for Educators (Letcraft Educación). Recoge cuatro bloques de trabajo:

- Webinars para la comunidad
- Dinamización del grupo de LinkedIn
- Formaciones MOOC de Microsoft 365 para consejerías
- Difusión y comunicación (paid media)

Cada bloque y cada tarea tiene owner (Andrea, Jero o Esther), prioridad (alta, media o baja), estado e hitos con fecha. Además hay notas de reunión, que se pueden convertir en tareas o hitos, y un historial de versiones.

## Cómo funciona

- La web es index.html y se publica con GitHub Pages.
- Los datos están en data.json. Cada vez que alguien pulsa **Guardar**, se crea un commit en este repositorio, así que cada guardado queda como una versión con autor y fecha.
- En la pestaña **Historial de versiones** se ve qué cambió en cada guardado, y se puede restaurar cualquier versión anterior.
- Si dos personas editan a la vez, el panel combina los cambios de las dos al guardar. También se actualiza solo cada 40 segundos con lo que guarden los demás.

## Para editar (solo la primera vez, en cada navegador)

1. Necesitas una cuenta de GitHub con acceso a este repositorio. Jero te invita desde **Settings → Collaborators**.
2. Crea un token: <https://github.com/settings/tokens/new?scopes=repo&description=Seguimiento%20Elevate>. Deja marcada la casilla repo y pulsa **Generate token**.
3. En el panel, pulsa el engranaje ⚙, elige quién eres y pega el token. El token solo se guarda en tu navegador.

Quien solo quiera consultar el panel no necesita nada: basta con abrir el enlace.

> Aviso: en el plan gratuito de GitHub, la web y el repositorio son públicos. Cualquiera que tenga el enlace puede leer el contenido. No pongáis datos personales ni nada confidencial.
