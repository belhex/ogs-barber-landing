# OG'S Barber · Landing page

Landing page responsive para una barbería. **Proyecto de demostración**: el negocio, los datos de contacto y las reseñas son ficticios.

🔗 **Demo online:** https://belhex.github.io/ogs-barber-landing/

## Qué incluye

- Header fijo con menú de navegación que se convierte en menú hamburguesa en celulares
- Sección de servicios con precios, galería de cortes y reseñas
- Horarios, ubicación con mapa de Google Maps incrustado y botón de contacto
- Botón flotante de WhatsApp con mensaje precargado
- Scroll suave y efecto de sombra en el header al desplazarse

## Tecnologías

- **HTML5** semántico (`header`, `nav`, `main`, `section`, `article`, `footer`)
- **CSS3**: variables, Flexbox, Grid, media queries y animaciones
- **JavaScript** vanilla: manejo del DOM y eventos
- **Git y GitHub Pages** para versionado y publicación

## Decisiones de diseño

- **Diseño pensado primero para celular**, porque la mayoría de los clientes de una barbería entran desde el teléfono.
- **Grillas responsive sin media queries** usando `repeat(auto-fit, minmax(...))`.
- **Colores centralizados en variables CSS**, para cambiar la identidad visual editando una sola línea.
- **Accesibilidad básica**: textos `alt` en imágenes, atributos `aria` en el menú y el botón de WhatsApp, y jerarquía correcta de títulos.

## Cómo verlo en tu computadora

1. Clonar el repositorio:
```bash
   git clone https://github.com/belhex/ogs-barber-landing.git
```
2. Abrir la carpeta en VS Code.
3. Abrir `index.html` con la extensión Live Server, o directamente en el navegador.

No requiere instalar nada ni usar herramientas de compilación.

## Estructura

```
├── index.html
├── style.css
├── script.js
└── img/
```

## Autora

Belén Rodriguez