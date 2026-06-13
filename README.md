

# PracticaBootstrap — Proyección Personal

Este repositorio contiene la práctica de Bootstrap 5 enfocada en la proyección personal, académica y profesional. Es una versión independiente de prácticas previas (HTML y CSS) y demuestra la aplicación de componentes de Bootstrap, combinaciones de componentes y personalizaciones mediante un archivo CSS propio.

## Archivos principales
- `pages/proyeccion.html` — página de proyección (principal de esta práctica).
- `css/proyeccion.css` — estilos personalizados que complementan Bootstrap.
- `index.html` — (portafolio previo) mantiene el enlace hacia `pages/proyeccion.html`.

## Descripción breve
La página presenta:
- Secciones semánticas: `header`, `nav`, `main`, `section`, `aside`, `footer`.
- Componentes Bootstrap organizados: navbar, grid, cards, accordion, carousel, modal con formulario, tabla responsiva con progress bars, list groups, badges y más.
- Personalización visual mediante variables CSS y reglas específicas en `css/proyeccion.css`.

## Estructura de carpetas
![alt text](/img/image.png)

## Cómo ver el sitio (recomendado)
1. Abrir una terminal en la carpeta `PracticaBootstrap`.
2. Iniciar un servidor local (recomendado para que rutas y componentes funcionen correctamente):

```bash
python -m http.server 8000
```

3. Abrir en el navegador:
- `http://localhost:8000/pages/proyeccion.html` (página de proyección)
- `http://localhost:8000/index.html` (portafolio previo)

## Componentes Bootstrap usados
- Navbar
- Container
- Grid (row / col)
- Cards
- Buttons
- Alerts
- Badges
- Carousel (dentro de Accordion)
- Accordion
- Modal (formulario dentro)
- Progress bars (dentro de tabla)
- List groups
- Table (responsive)
- Forms (validación cliente)
- Utilities: spacing, display, typography

## Combinaciones y ejemplos implementados
- Accordion que contiene el Carousel — combinación de componentes.
- Modal con formulario validado en cliente — ejemplo de Forms dentro de Modal.
- Tabla responsiva que muestra metas con barras de progreso.

## Personalizaciones en `css/proyeccion.css`
- Variables de color para fácil ajuste.
- Ajustes de `carousel` (alto fijo y `object-fit: cover`).
- Sombras suaves en `navbar` y tarjetas.
- Estilos de tabla responsiva y focus en inputs del modal.

## Mobile First y accesibilidad
- La página se construyó pensando primero en móvil usando clases responsivas de Bootstrap.
- Se usan etiquetas semánticas y atributos ARIA proporcionados por componentes de Bootstrap.
- Recomendación: ejecutar Lighthouse o WAVE para auditoría de accesibilidad y rendimiento.

## Entrega y repositorio GitHub
1. Crear un nuevo repositorio público en GitHub llamado, por ejemplo, `PracticaBootstrap`.
2. Subir todo el contenido de esta carpeta.
3. Añadir en la portada del repo un enlace hacia `pages/proyeccion.html` como ejemplo de la práctica.

## Autor
- Daniel Gustavo Barragan Montero
- Contacto: dgbarragan@espe.edu.ec

---

Si quieres, puedo:
- añadir capturas de pantalla automáticamente (dime nombres de archivos en `img/`),
- preparar un archivo `LICENSE` y plantilla `CONTRIBUTING.md`,
- o crear una breve guía para la evaluación (ej.: lista de verificación de criterios).


