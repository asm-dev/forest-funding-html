# Reforestación en Galicia - Estructura HTML

&nbsp;

## Descripción del proyecto

Este proyecto contiene el HTML de una página web diseñada para promover la reforestación en Galicia, una región afectada gravemente por incendios forestales. Es una página de micromecenazgo cuyo fin principal es generar conciencia sobre la importancia de la recuperación ambiental mediante la recaudación de donativos que permitan la reforestación de montes gallegos incendiados.

> **Nota**: Este proyecto no incluye datos ni proyectos reales. Es una maqueta educativa con fines demostrativos

&nbsp;

La creación de esta web forma parte del programa de actividades del MS en Desarrollo Web de la UEM. Este repositorio únicamente contiene la estructura HTML del sitio, pero se itera sobre la misma agregando estilos e interactividad con CSS y JS en otros dos repositorios:

1. [Ponemos la web bonita](https://github.com/asm-dev/forest-funding-css)
2. La volvemos interactiva

&nbsp;

## Objetivos de la web

- **Informar**. Difundir información sobre la problemática de los incendios forestales en Galicia y la necesidad de reforestar.
- **Concienciar**. Educar a la comunidad sobre la importancia de la sostenibilidad y la preservación de la biodiversidad.
- **Facilitar la acción**. Crear una herramienta online de fácil utilización para simplificar el proceso de donaciones colectivas.

&nbsp;

## Mapa del sitio

1. **Inicio**:
   - Introducción al problema de los incendios.
   - Llamada a la acción mediante el uso de una imagen de un bosque reforestado.

2. **Sobre Nosotros**:
   - Se detallan la misión y objetivos.
   - Recoge información sobre el equipo responsable del proyecto.

3. **Proyectos**:
   - Descripción de iniciativas clave como la reforestación en As Fragas do Eume.
   - Descripción de acciones de concienciación como talleres de educación ambiental en colegios gallegos.

4. **Donar**:
   - Formulario para realizar contribuciones.
   - Información sobre cómo se utilizan las donaciones (política de transparencia).

5. **Contacto**:
   - Información de contacto y ubicación de la oficina.
   - Enlace a Google Maps para simplificar el acceso.

&nbsp;

## Diseño técnico

Se ha utilizado HTML semántico para garantizar la accesibilidad y una estructura clara:

- **Navegación sencilla**. El usuario puede acceder a todas las secciones mediante el _scroll_ o el uso del navegador principal del sitio.
- **Etiquetas semánticas**. Se emplean tags como `<header>`, `<main>`, `<section>`, `<article>` y `<footer>`, en lugar de `<div>` dado que este último no aporta mayor significado. Esto contribuye a la legibilidad del código, pero además optimiza el SEO y la UX con lectores de pantalla.
- **Accesibilidad**. Todas las imágenes incluyen atributos `alt` descriptivos para personas con discapacidad visual. Además, el formulario emplea etiquetas claras y campos requeridos.
- **Eficiencia de carga**. Las imágenes han sido optimizadas para reducir su peso sin comprometer la calidad visual. Con ello conseguimos asegurar un mínimo consumo.

&nbsp;

## Futuras Implementaciones

Aunque este proyecto es un mock, tiene potencial para evolucionar y convertirse en una plataforma real que incluya:

- Proyectos verificados y actualizados en tiempo real.
- Funcionalidades avanzadas como un mapa interactivo de zonas reforestadas.
- Colaboración con entidades gubernamentales y ONGs.
