# Nexora Cloud — Landing Page

## Descripción

Este proyecto consiste en una landing page corporativa desarrollada con **HTML5 y CSS3**.

La página presenta una empresa ficticia llamada **Nexora Cloud**, dedicada a ofrecer soluciones de infraestructura tecnológica y cloud.

El objetivo es practicar la creación de una página web estructurada, semántica y responsive utilizando únicamente HTML y CSS.

## Estructura del proyecto

```text
nginx-static-poc/
└── html/
    ├── index.html
    └── css/
        └── style.css
```

## Tecnologías utilizadas

- HTML5
- CSS3
- Diseño responsive mediante media queries
- CSS Grid
- Flexbox

No se utilizan JavaScript ni frameworks externos.

## Contenido de la página

La landing page está dividida en varias secciones:

1. **Cabecera y navegación**
   - Logo de Nexora Cloud.
   - Enlaces internos a las diferentes secciones.
   - Botón de contacto.

2. **Presentación principal**
   - Título principal.
   - Descripción de la empresa.
   - Botones de navegación.
   - Ilustración visual de los servicios.

3. **Servicios**
   - Infraestructura cloud.
   - Despliegue de aplicaciones.
   - Seguridad y monitorización.

4. **Infraestructura**
   - Explicación de la arquitectura.
   - Diagrama visual del flujo:
     `Usuarios → Balanceador → Clúster de servidores → Base de datos`
   - Características de seguridad, rendimiento y escalabilidad.

5. **Contacto**
   - Llamada a la acción.
   - Enlace de correo electrónico.

6. **Pie de página**
   - Enlaces de navegación.
   - Información de la empresa.

## HTML

El archivo `index.html` utiliza etiquetas semánticas como:

- `<header>`
- `<nav>`
- `<main>`
- `<section>`
- `<article>`
- `<footer>`

También incluye:

- `meta charset`
- `meta viewport`
- descripción mediante `meta description`
- título de la página
- enlace a la hoja de estilos externa

La hoja CSS se carga mediante:

```html
<link rel="stylesheet" href="css/style.css">
```

## CSS

Los estilos se encuentran en:

```text
html/css/style.css
```

Se utilizan:

- Variables CSS para los colores principales.
- Flexbox para diferentes elementos de la interfaz.
- CSS Grid para las rejillas de servicios, características y footer.
- Media queries para adaptar la página a pantallas pequeñas.
- Estados y estilos diferenciados para botones y enlaces.

## Diseño responsive

La página incorpora una media query para pantallas de hasta `650px`.

En dispositivos pequeños:

- Las columnas pasan a una sola columna.
- Los botones se reorganizan verticalmente.
- El menú puede ocupar varias líneas.
- El diagrama de arquitectura cambia a orientación vertical.
- Los contenidos se adaptan al ancho disponible.

## Cómo visualizar el proyecto

No necesita instalación ni servidor para esta fase.

Se puede abrir directamente:

```text
html/index.html
```

con cualquier navegador web moderno.

También se puede utilizar la extensión **Live Server** de Visual Studio Code para visualizar los cambios mientras se desarrolla.

## Objetivo de la práctica

El objetivo de esta primera fase es trabajar la estructura y presentación de una aplicación web mediante HTML y CSS.

Las configuraciones de servidor, Docker, Nginx y despliegue se incorporarán en fases posteriores cuando formen parte del contenido trabajado en clase.
