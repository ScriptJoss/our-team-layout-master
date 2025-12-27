# Our Team Layout

Proyecto responsive que recrea una sección "Meet the Team" usando HTML y CSS.

## Descripción

Este repositorio contiene una maquetación responsiva basada en un reto de diseño. Contiene una grilla CSS para distribuir los perfiles del equipo, imágenes en `resources/` y adaptaciones en diferentes puntos de quiebre.

## Ver localmente

1. Abre el archivo `index.html` en tu navegador (doble clic) o sirve el proyecto con un servidor estático.

Ejemplo rápido con Python:

```bash
# Python 3
python -m http.server 8000
# luego abre http://localhost:8000
```

## Estructura del proyecto

- `index.html` - HTML principal.
- `style.css` - Estilos del proyecto.
- `resources/` - Imágenes y assets.
- `design/` - Referencias de diseño (si aplica).

## Notas

- Layout basado en CSS Grid y contenedores `.container` para cada miembro.
- Media queries para adaptar el diseño en 1100px, 700px y 400px.
- Ajustes de accesibilidad: revisa contraste de colores y atributos `alt` en imágenes.

## Cómo subir a GitHub (rápido)

```bash
git init
git add .
git commit -m "Initial commit - our-team layout"
git branch -M main
git remote add origin <TU_REPOSITORIO_URL>
git push -u origin main
```

Si quieres publicar con GitHub Pages:

```bash
# en la rama main
git push origin main
# configurar GitHub Pages desde la configuración del repo
```

## Créditos

Hecho por ti — ¡listo para subir a GitHub! ✨

## Licencia

MIT
