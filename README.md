# Where in Rome — Página de una banda con HTML, CSS y Bootstrap

Sitio web de una sola página dedicado a la banda *When in Rome*, hecho como taller de **HTML, CSS y Bootstrap 5**. Incluye una barra de navegación, una sección de bienvenida, la historia de la banda, la discografía, una galería de imágenes y un formulario de suscripción con validación.

## Secciones

| Sección | Contenido |
| --- | --- |
| Inicio | Portada con la canción destacada |
| Historia | Reseña de la banda |
| Discografía | Álbum y sencillos en tarjetas |
| Galería | Imágenes en cuadrícula |
| Contacto | Formulario de suscripción (nombre, apellido, correo, país y aceptación de términos) |

## Qué demuestra

- Maquetación responsive con la cuadrícula y los componentes de Bootstrap 5 (navbar colapsable, tarjetas, formulario).
- Estilos propios en `css/styles.css` que personalizan la base de Bootstrap.
- Estructura semántica con secciones ancladas desde el menú.

## Cómo verlo

No necesita compilación. Abre `index.html` en el navegador, o sírvelo localmente:

```bash
git clone https://github.com/Alejob12/Taller-HTML-CSS-y-Bootstrap.git
cd Taller-HTML-CSS-y-Bootstrap
python3 -m http.server 8000     # http://localhost:8000
```

Bootstrap se carga desde un CDN, así que se necesita conexión a internet.

## Estructura

```
index.html        Página completa
css/styles.css    Estilos personalizados
assets/img/       Imágenes de la galería
```

## Autor

**Alejandro Bernal** — Ingeniería de Sistemas e Industrial, Universidad de los Andes.
