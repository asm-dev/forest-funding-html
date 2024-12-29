# Reforestación en Galicia - Estructura HTML

## Descripción del proyecto

Este proyecto es un mock de una página web diseñada para promover la reforestación en Galicia, una región afectada gravemente por incendios forestales. Se trata de una página de micromecenazgo cuyo fin principal es generar conciencia sobre la importancia de la recuperación ambiental, generando mediante donativos la capacidad de recuperar bosques gallegos afectados por incendios.

El proyecto se incluye en el programa de actividades del MS en Desarrollo Web de la UEM. Contiene meramente la estructura HTML del sitio, pero se itera sobre la misma agregando estilos e interactividad con CSS y JS en estos dos repositorios:

- Repositorio donde ponemos la web bonita
- Repositorio donde la volvemos interactiva

> **Nota**: Este proyecto no incluye datos ni proyectos reales. Es una maqueta educativa con fines demostrativos, nos obstante me encantaría implementarla con proyectos reales en un futuro.

## Objetivos de la web

- **Informar**: Difundir información sobre la problemática de los incendios forestales en Galicia y la necesidad de reforestar.
- **Concienciar**: Educar a la comunidad sobre la importancia de la sostenibilidad y la preservación de la biodiversidad.
- **Facilitar la acción**: Crear una herramienta online de fácil utilización para simplificar el proceso de donaciones ciudadanas.

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

El usuario puede acceder a todas las secciones mediante el scroll o el uso del navegador principal del sitio.

## Diseño técnico

Se ha utilizado HTML semántico para garantizar la accesibilidad y una estructura clara:

- **Etiquetas semánticas**: se emplean tags como `<header>`, `<main>`, `<section>`, `<article>` y `<footer>`, en lugar de `<div>` dado que este último no aporta mayor significado. Esto contribuye a la legibilidad del código, pero además optimiza el SEO y la UX con lectores de pantalla.
- **Accesibilidad**:
  - Todas las imágenes incluyen atributos `alt` descriptivos para personas con discapacidad visual.
  - El formulario emplea etiquetas claras y campos requeridos.
- **Eficiencia de carga**:
  - Las imágenes han sido optimizadas para reducir su peso sin comprometer la calidad visual. Con ello conseguimos asegurar un mínimo consumo para la carga del sitio.

## Futuras Implementaciones

Aunque este proyecto es un mock o MVP, tiene potencial para evolucionar y convertirse en una plataforma real que incluya:

- Proyectos verificados y actualizados en tiempo real.
- Funcionalidades avanzadas como un mapa interactivo de zonas reforestadas.
- Colaboración con entidades gubernamentales y ONGs.
