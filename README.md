# Reforestación en Galicia - Estructura HTML

Este proyecto contiene el HTML de una página web diseñada para promover la reforestación en Galicia, una región afectada gravemente por incendios forestales. Es una página de micromecenazgo cuyo fin principal es generar conciencia sobre la importancia de la recuperación ambiental mediante la recaudación de donativos que permitan la reforestación de montes gallegos incendiados.

> La web no incluye datos ni proyectos reales. Es una maqueta educativa con fines demostrativos

La creación de esta web forma parte del programa de actividades del MS en Desarrollo Web de la UEM. Este repositorio únicamente contiene la estructura HTML del sitio, pero se itera sobre la misma agregando estilos e interactividad aquí:

1. [CSS](https://github.com/asm-dev/forest-funding-css)
2. [JS](https://github.com/asm-dev/forest-funding-js)

&nbsp;

## Objetivos

- **Informar**. Difundir información sobre la problemática de los incendios forestales en Galicia y la necesidad de reforestar.
- **Concienciar**. Educar a la comunidad sobre la importancia de la sostenibilidad y la preservación de la biodiversidad.
- **Facilitar la acción**. Crear una herramienta online de fácil utilización para simplificar el proceso de donaciones colectivas.

&nbsp;

## Mapa del sitio

Se trata de una única página o Home compuesta de los siguientes elementos:

1. **Inicio**:

   - Introducción al problema de los incendios.
   - Llamada a la acción mediante el uso de una imagen de un bosque reforestado.

2. **Sobre Nosotros**:

   - Se detallan la misión y objetivos.
   - Recoge información sobre el equipo responsable del proyecto.

3. **Proyectos**:

   - Descripción de iniciativas clave como la reforestación en As Fragas do Eume.
   - Descripción de acciones de concienciación como talleres de educación ambiental en colegios gallegos.

4. **Llamada a la acción**:

   - Petición de recaudación para una acción de reforestación en curso.
   - Carrusel de imágenes para incentivar los donativos y trasladar la realidad del incendio.
   - Marcador de progreso en forma de contador y porcentaje de recaudación con respecto al objetivo marcado.

5. **Donar**:

   - Formulario para realizar contribuciones.
   - Información sobre cómo se utilizan las donaciones (política de transparencia).

6. **Contacto**:
   - Información de contacto y ubicación de la oficina.
   - Enlace a Google Maps para simplificar el acceso.

![image](https://github.com/user-attachments/assets/c9b7986f-7f6c-4a13-ae53-d5065c7ac0aa)


&nbsp;

## Diseño técnico

Se ha utilizado HTML semántico para garantizar la accesibilidad y una estructura clara:

- **Navegación sencilla**. El usuario puede acceder a todas las secciones mediante el _scroll_ o el uso del navegador principal del sitio.
- **Etiquetas semánticas**. Se emplean tags como `<header>`, `<main>`, `<section>`, `<article>` y `<footer>`, en lugar de `<div>` dado que este último no aporta mayor significado. Esto contribuye a la legibilidad del código, pero además optimiza el SEO y la UX con lectores de pantalla.
- **Accesibilidad**. Todas las imágenes incluyen atributos `alt` descriptivos para personas con discapacidad visual. Además, el formulario emplea etiquetas claras y campos requeridos.
- **Eficiencia de carga**. Las imágenes han sido optimizadas para reducir su peso sin comprometer la calidad visual. Con ello conseguimos asegurar un mínimo consumo.
