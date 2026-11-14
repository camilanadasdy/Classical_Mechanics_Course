# Página del curso: Mecánica Clásica

Sitio estático preparado para publicar con GitHub Pages. No requiere dominio propio, frameworks ni procesos de compilación.

## Publicar en GitHub Pages

1. Crea o inicia sesión en https://github.com/.
2. Crea un repositorio nuevo, por ejemplo `mecanica-clasica`. Para GitHub Free, déjalo **Public**.
3. Descomprime este paquete y sube al repositorio los archivos y carpetas que contiene. `index.html` debe quedar en la raíz.
4. En el repositorio, abre **Settings → Pages**.
5. En **Build and deployment**, elige **Deploy from a branch**.
6. Selecciona la rama `main` y la carpeta `/(root)`, y pulsa **Save**.
7. Espera a que GitHub publique el sitio. La dirección tendrá el formato `https://TU-USUARIO.github.io/mecanica-clasica/`.

## Personalizar antes de compartir

- En `index.html`, reemplaza `[Nombre del docente]` y `[Institución]`.
- Revisa la distribución horaria, el temario, la evaluación y la bibliografía. El contenido actual es una propuesta inicial, no un programa aprobado.
- En cada semana, añade enlaces a tus archivos PDF, diapositivas, lecturas y talleres. Puedes crear subcarpetas dentro de `materials/semana-XX/` y enlazar los archivos desde la semana correspondiente.
- Si cambias el número de semanas o las horas, actualiza también los indicadores de la portada.

## Estructura

- `index.html`: contenido del sitio.
- `styles.css`: diseño adaptable a móvil y escritorio.
- `script.js`: interacción de los apartados semanales y menú móvil.
- `materials/`: carpetas de ejemplo para recursos de cada semana.

La página es pública: no subas datos personales de estudiantes, calificaciones ni documentos privados.
