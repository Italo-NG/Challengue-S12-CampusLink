# CampusLink

CampusLink es una landing page estatica para presentar una solucion de reporte, ubicacion y seguimiento de incidencias dentro de un campus.

## Autores

- Italo Gabriel Ninahuanca Garcia
- Diego Yahir Chilingano Salas

## Segmentos objetivo

- Estudiantes que necesitan reportar incidencias del campus de forma rapida.
- Docentes que requieren comunicar problemas de infraestructura, bienestar o seguridad.
- Personal de soporte y operaciones que atiende, prioriza y da seguimiento a reportes.

## Caracteristicas principales

- Presentacion de la propuesta de valor de CampusLink.
- Secciones informativas sobre problema, solucion, beneficios y usuarios objetivo.
- Explicacion del flujo de reporte y seguimiento de incidencias.
- Vista demostrativa de la experiencia mobile.
- Formulario de contacto institucional.
- Pantalla basica de inicio de sesion.

## Tecnologias usadas

- HTML5
- CSS3
- JavaScript
- Cucumber para escenarios de aceptacion

## Estructura del proyecto

```text
public/
  index.html
  favicon.ico
  login.html
  assets/
    styles/
      styles.css
      base.css
      layout.css
      components.css
      pages.css
      responsive.css
      login.css
      vista-app/
    images/
      logo/
      imagenes/
    scripts/
      main.js
      login.js
      modulos/
features/
  landing/
  mobile-core/
  step_definitions/
README.md
package.json
```

## Flujo GitFlow usado

- `main`: rama principal estable del proyecto.
- `develop`: rama de integracion creada desde `main`.
- `feature/landing-work-in-progress`: rama de trabajo creada desde `develop` para la estructura y avance funcional de la landing page.

Los cambios se trabajan primero en ramas `feature/*`, luego se integran mediante Pull Request hacia `develop` y, si corresponde, desde `develop` hacia `main`.

## Como ejecutar

El proyecto usa modulos de JavaScript, por lo que se recomienda abrir `public/index.html` con WebStorm usando un servidor local o Live Server.

## Pruebas

```bash
npm run test:acceptance
```
