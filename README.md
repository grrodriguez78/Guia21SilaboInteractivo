# Sitio del curso · Fundamentos de Tecnologías de la Información (UTPL)

Guía 21 · Sitio del curso o sílabo interactivo · Curso Vibe Coding CEDIA 2026.
Primera versión: semanas 1 a 4 del plan docente ABR/2026 - AGO/2026.

## Archivos
- `index.html`: el sitio completo (HTML, CSS y JavaScript mínimo, sin bibliotecas). Se abre con doble clic en cualquier navegador.
- `revision_silabo.md`: comparación con el plan docente y discrepancias abiertas.
- `pruebas.md`: resultados de las pruebas de teléfono, teclado, texto ampliado y enlaces.

## Cómo actualizar el contenido
Todo el contenido está en el bloque `const SILABO = { … }` al inicio del `<script>` de `index.html`.
Para cambiar una fecha, lectura o enlace edite solo ese bloque; no toque el diseño.
Para agregar la semana 5, copie un objeto de `semanas` y cambie `n`, fechas, temas y actividades.

## Publicar en GitHub Pages (paso 5)
1. Cree un repositorio **público** en GitHub, por ejemplo `fti-utpl-2026`. Todo lo que suba será público: no incluya datos de estudiantes.
2. Suba `index.html` (y, si quiere, los dos .md) a la raíz del repositorio con «Add file → Upload files».
3. Vaya a Settings → Pages. En «Build and deployment», elija «Deploy from a branch», rama `main`, carpeta `/ (root)` y guarde.
4. Tras uno o dos minutos aparecerá la dirección `https://<su-usuario>.github.io/fti-utpl-2026/`.
5. Ábrala desde otro dispositivo (un teléfono con datos móviles), compruebe enlaces y guarde una captura como evidencia.
6. En el EVA, agregue esa dirección como recurso URL de la semana 1. Las entregas siguen en el EVA.
