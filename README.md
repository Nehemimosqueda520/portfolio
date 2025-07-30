# Nehemías Mosqueda Portfolio

Este repositorio contiene el código fuente para el sitio web del portafolio de Nehemías Mosqueda. El sitio está diseñado para mostrar información sobre habilidades, servicios, proyectos y cómo contactar a Nehemías.

## Estructura del Código

- **index.html**: Archivo principal que define la estructura del sitio web con diferentes secciones como "inicio", "sobre mí", "servicios", "portfolio" y "contacto".
- **css/style.css**: Archivo CSS personalizado para estilos específicos del sitio web.
- **js/script.js**: Archivo JavaScript que proporciona funcionalidades adicionales al sitio web.
- **images**: Carpeta con imágenes utilizadas en el sitio web.
- **documents**: Contiene archivos descargables como currículum y carta de presentación en formato PDF.

## Secciones del Sitio Web

- **Inicio (Home)**: Presentación de Nehemías Mosqueda con información sobre habilidades y estudios. Enlaces a perfiles de correo electrónico y GitHub. Botón de descarga de currículum.
- **Sobre Mí (About)**: Breve información personal, actitud hacia el aprendizaje y objetivo profesional.
- **Servicios (Services)**: Enumeración de servicios ofrecidos con descripciones breves.
- **Portfolio**: Muestra proyectos con imágenes, títulos y descripciones.
- **Contacto**: Formulario de contacto con campos para nombre, correo, teléfono, empresa y mensaje.
- **Contacto**: Formulario de contacto que envía los datos de manera segura a través de HTTPS utilizando el servicio [Formspree](https://formspree.io/).
- **Footer**: Información de derechos de autor y botón de regreso al inicio.

## Recursos Externos Utilizados

- **Swiper**: Librería JavaScript para crear sliders/carousels.
- **Boxicons**: Conjunto de iconos utilizados para redes sociales y servicios.

## Optimización para Motores de Búsqueda (SEO)

El sitio incorpora metadatos descriptivos y etiquetas Open Graph para mejorar la visibilidad en buscadores y redes sociales. Todas las imágenes incluyen atributos `alt` descriptivos para favorecer la accesibilidad y el posicionamiento.

## Uso y Contribución

El código es público y puede ser utilizado o modificado. Para contribuir, hacer un fork, realizar cambios y enviar un pull request.

*Nota: Se recomienda mantener actualizados los recursos externos utilizados en el código.*

Para más detalles o mejoras en la documentación, contactar a Nehemías Mosqueda a través de los enlaces proporcionados en el sitio web.

### Configurar el formulario de contacto

El formulario utiliza Formspree para enviar los mensajes de forma segura. Si deseas recibir los correos en tu propia cuenta, registra un formulario en Formspree y actualiza el atributo `action` en `index.html` con el enlace proporcionado por el servicio.

Se ha incorporado Google reCAPTCHA para prevenir el spam. Registra tu dominio y reemplaza el valor de `data-sitekey` en `index.html` por tu clave de sitio.

