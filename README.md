# desafio-portafolio

Este es un proyecto de portafolio personal desarrollado para mostrar mis habilidades como desarrollador frontend. El sitio incluye secciones sobre mis habilidades, proyectos y una forma de contacto.

## Demo
Puedes ver la página en vivo aquí: [Blog Frontend con Sass Landing Page](https://mr-gantiva.github.io/blog-frontend-sass/)

## Tabla de Contenidos

- [desafio-portafolio](#desafio-portafolio)
  - [Demo](#demo)
  - [Tabla de Contenidos](#tabla-de-contenidos)
  - [Instalación](#instalación)
  - [Uso](#uso)
  - [Descripción de Archivos y Directorios](#descripción-de-archivos-y-directorios)
  - [Tecnologías Utilizadas](#tecnologías-utilizadas)
  - [Contribuir](#contribuir)
  - [Haz un fork del repositorio.](#haz-un-fork-del-repositorio)
  - [Licencia](#licencia)

## Instalación

1. Clona este repositorio:
    ```bash
    git clone https://github.com/mr-gantiva/blog-frontend-sass
    ```
2. Navega al directorio del proyecto:
    ```bash
    cd blog-frontend
    ```

## Uso

Abre el archivo `index.html` en tu navegador para ver el proyecto en acción.

```bash
open index.html
blog-frontend/
├── assets/
│   ├── css/
│   │   ├── main.css
│   │   │
│   │   ├── main.css.map
│   ├── images/
│   │   ├── logos/
│   │   │   └── [imágenes de logos]
│   │   ├── posts/
│   │   │   └── [imágenes de posts]
│   ├── js/
│   │   └── script.js
│   ├── sass/
│   │   ├── abstracts/
│   │   │   └── _mixins.scss_
│   │   │   └── _variables.scss_
│   │   │
│   │   ├── base/
│   │   │   └── reset.scss_
│   │   │   └── _typography.scss
│   │   │
│   │   ├── components/
│   │   │   └── _buttons.scss
│   │   │   └── _cards.scss
│   │   │   └── _logo.scss
│   │   │
│   │   ├── layout/
│   │   │   └── _footer.scss
│   │   │   └── _header.scss
│   │   │
│   │   ├── pages/
│   │   │   └── _home.scss
│   │   │
│   │   ├── themes/
│   │   │
│   │   ├── vendors/
│   │   │
│   │   ├── main.scss
│   └── views/
│       └── login-html
│       └── post-bootstrap.html
│       └── registro.html    
├── index.html
└── README.md
```
## Descripción de Archivos y Directorios
- assets/css/style.css: Contiene los estilos CSS del proyecto.
- assets/images/: Contiene las imágenes utilizadas en el proyecto.
- assets/js/script.js: Contiene el JavaScript del proyecto.
- assets/sass/: Contiene todas las particiones del patron 7-1 con SASS en el proyecto.
- index.html: El archivo principal HTML que estructura el contenido del blog.
- README.md: Este archivo de documentación.

## Tecnologías Utilizadas
- HTML5: Para la estructura del contenido.
- CSS3: Para los estilos y diseño responsivo.
- SASS: Para poder modularizar los estilos del proyecto.
- JavaScript: Para la funcionalidad interactiva.
- AOS (Animate on Scroll): Para animaciones de scroll.

## Contribuir
Si deseas contribuir a este proyecto, por favor sigue estos pasos:

## Haz un fork del repositorio.
- Crea una nueva rama (git checkout -b feature/nueva-funcionalidad).
- Realiza los cambios necesarios y haz commit (git commit -am 'Añadir nueva funcionalidad').
- Haz push a la rama (git push origin feature/nueva-funcionalidad).
- Crea un nuevo Pull Request.

## Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.