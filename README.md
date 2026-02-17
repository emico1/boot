# Bootstrap Landing Page

Landing page moderna y responsiva creada con Bootstrap 5, ideal para empresas de tecnología y desarrollo de software.

## Descripción

Página web profesional de una sola página (Single Page Application) que incluye:

- Hero section con animación de fondo
- Sección de estadísticas
- Showcase de servicios
- Características principales
- Planes y precios
- Formulario de contacto
- Footer completo con newsletter

## Características

- Diseño 100% responsivo
- Animaciones CSS suaves
- Sistema de grid de Bootstrap 5
- Iconos de Bootstrap Icons
- Navbar fijo con scroll suave
- Cards con efectos hover
- Formularios estilizados
- Gradientes modernos
- Compatible con todos los navegadores modernos

## Tecnologías Utilizadas

- HTML5
- CSS3
- Bootstrap 5.3.2
- Bootstrap Icons 1.11.1
- JavaScript (Bootstrap Bundle)

## Estructura del Proyecto

```
.
├── bootstrap-landing.html    # Archivo principal
├── test-bootstrap.html        # Archivo de prueba
└── README.md                  # Documentación
```

## Instalación

### Opción 1: Uso directo

1. Descarga el archivo `bootstrap-landing.html`
2. Abre el archivo en tu navegador web
3. Listo, no requiere instalación adicional

### Opción 2: Con Live Server (VSCode)

1. Abre el proyecto en Visual Studio Code
2. Instala la extensión "Live Server"
3. Click derecho en `bootstrap-landing.html`
4. Selecciona "Open with Live Server"

### Opción 3: Con servidor local

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js (con http-server)
npx http-server
```

Luego abre: `http://localhost:8000/bootstrap-landing.html`

## Secciones de la Página

### Navbar
Barra de navegación fija con enlaces a todas las secciones y botón de llamada a la acción.

### Hero Section
Sección principal con título, descripción y botones de acción. Incluye animación de fondo con patrón de puntos.

### Stats Section
Estadísticas destacadas con números grandes y descripciones.

### Services Section
Tarjetas de servicios con iconos, descripciones y listas de características.

### Features Section
Características principales del servicio organizadas en grid de 4 columnas.

### Pricing Section
Tres planes de precios con el plan profesional destacado en el centro.

### Contact Section
Formulario de contacto completo con información de contacto al lado.

### Footer
Pie de página con información de la empresa, enlaces, redes sociales y newsletter.

## Personalización

### Cambiar Colores

Modifica las variables CSS en la sección `<style>`:

```css
:root {
    --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    --secondary-gradient: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
}
```

### Cambiar Textos

Busca y reemplaza los textos directamente en el HTML:
- Nombre de la empresa: "TechSolutions"
- Títulos de secciones
- Descripciones de servicios
- Información de contacto

### Agregar/Quitar Secciones

Cada sección está envuelta en un tag `<section>`. Simplemente elimina o duplica las secciones que necesites.

## Clases de Bootstrap Utilizadas

### Layout
- `container`: Contenedor responsivo
- `row`: Fila del grid
- `col-md-*`: Columnas responsivas

### Componentes
- `navbar`: Barra de navegación
- `card`: Tarjetas de contenido
- `btn`: Botones
- `form-control`: Inputs de formulario
- `badge`: Etiquetas pequeñas

### Utilidades
- `mb-*`, `mt-*`, `py-*`, `px-*`: Márgenes y padding
- `text-center`: Texto centrado
- `d-flex`: Display flex
- `shadow-*`: Sombras
- `bg-*`: Colores de fondo

## Compatibilidad

### Navegadores Soportados
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

### Dispositivos
- Desktop (1920px+)
- Laptop (1024px - 1919px)
- Tablet (768px - 1023px)
- Mobile (320px - 767px)

## CDN Utilizados

```html
<!-- Bootstrap CSS -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

<!-- Bootstrap Icons -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.1/font/bootstrap-icons.css">

<!-- Bootstrap JS -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
```

## Solución de Problemas

### La página se ve en blanco

1. Verifica tu conexión a internet (los CDN requieren conexión)
2. Abre la consola del navegador (F12) y busca errores
3. Verifica que los CDN de Bootstrap carguen correctamente
4. Prueba con el archivo `test-bootstrap.html` incluido

### Los estilos no se aplican correctamente

1. Limpia el cache del navegador (Ctrl + F5)
2. Verifica que el archivo CSS de Bootstrap cargue
3. Revisa la consola por errores de CORS

### El menú móvil no funciona

1. Verifica que Bootstrap JS esté cargando
2. Asegúrate de que no haya errores en la consola
3. Prueba en modo incógnito

## Mejoras Futuras

- Integración con backend para el formulario de contacto
- Animaciones adicionales con AOS (Animate On Scroll)
- Sistema de templates con variables
- Versión multiidioma
- Optimización de imágenes
- Implementación de lazy loading

## Licencia

Este proyecto es de código abierto y está disponible bajo la licencia MIT.

## Autor

Desarrollado por EcoDevLabs

## Contacto

- Email: contacto@techsolutions.com
- Teléfono: +52 (81) 1234-5678

## Recursos Adicionales

- [Documentación de Bootstrap 5](https://getbootstrap.com/docs/5.3/)
- [Bootstrap Icons](https://icons.getbootstrap.com/)
- [CDN de jsDelivr](https://www.jsdelivr.com/)

## Changelog

### Version 1.0.0 (2024-02-16)
- Lanzamiento inicial
- Implementación de todas las secciones principales
- Diseño responsivo completo
- Integración de Bootstrap 5.3.2
