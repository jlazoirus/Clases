# Clases: instrucciones para agentes

Repo privado con el contexto de la docencia de Jonathan Lazo (Jona). Lo leen Claude, ChatGPT, Codex y otros asistentes. Es contexto personal-profesional, separado de Acelera (`jlazoirus/ACELERA_CONTEXTO`).

## Cómo leerlo

1. Empieza por [README.md](README.md) y abre solo el archivo del curso o tema que necesites.
2. Cada institución tiene una carpeta (`repensar/`) con:
   - `README.md`: panorama, navegación y etiquetas de confianza.
   - `cronologia.md`: todo en orden de fecha.
   - `cursos/<curso>/`: un curso por carpeta (programa, cohortes, sesiones, materiales).
   - `temas/`: un archivo por tema, transversal a cursos.
   - `pedagogia.md`, `admin/`, `discrepancias.md`, `fuentes/`.
3. Etiquetas: `CONFIRMADO`, `PLANEADO`, `INFERIDO`, `AUTORREPORTE`. Un deck no prueba que se dictó esa versión, una invitación no prueba asistencia y un comprobante no prueba cobro.

## Cómo actualizarlo

- Cohorte o edición nueva: agrega filas en `cohortes.md` o en el README del curso y en `cronologia.md`; no borres filas anteriores.
- Material nuevo: agrégalo a `materiales.md` del curso, al tema que corresponda y a `fuentes/inventario-drive.json`.
- Curso nuevo: crea `cursos/<slug>/README.md` con el mismo encabezado YAML y enlázalo desde el README de la raíz y el de la institución.
- Institución nueva: crea una carpeta hermana de `repensar/` con la misma estructura.
- Al verificar algo `PLANEADO` o `INFERIDO`, cambia la etiqueta y anota la fuente. Las contradicciones van a `discrepancias.md`.
- Commits pequeños y descriptivos; sin force-push.

## Límites

- Honorarios y demás datos económicos de Jona solo en `repensar/admin/comprobantes.md`; no los copies a otros archivos ni a otros repos. Los precios públicos del folleto sí pueden ir en el curso.
- No guardes datos de alumnos (nombres, correos), enlaces de Zoom, códigos de acceso, RUC, tokens ni contraseñas. Los perfiles de participantes van solo como datos agregados.
- Leer este contexto no autoriza a enviar correos, aceptar invitaciones ni comprometer fechas en nombre de Jona.
