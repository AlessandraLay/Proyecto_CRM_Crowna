# Crowna CRM

Crowna CRM es una plataforma de gestión de relaciones con clientes diseñada para ayudar a las empresas a organizar, automatizar y mejorar la gestión de sus clientes.

## Tecnologías utilizadas

- HTML5
- CSS3
- SCSS (Sass)
- Bootstrap 5
- JavaScript
- AOS (Animate On Scroll)
- Git y GitHub
- GitHub Pages

## Características del proyecto

- Diseño responsive adaptable a dispositivos móviles, tablets y escritorio.
- Arquitectura SCSS modular para facilitar el mantenimiento y la reutilización de estilos.
- Componentes reutilizables, como botones y tarjetas.
- Transiciones CSS para mejorar la interacción con los botones.
- Animaciones al desplazarse por la página mediante la librería AOS.
- Navegación entre seis páginas: Inicio, Productos, Planes, Recursos, Empresa y Contacto.

## Arquitectura SCSS

El proyecto utiliza una arquitectura modular para organizar los estilos y facilitar su mantenimiento y reutilización.

```text
scss/
├── main.scss
├── utilities/
│   ├── _variables.scss
│   ├── _mixins.scss
│   └── _extend.scss
├── base/
│   ├── _tipografia.scss
│   └── _base.scss
├── layout/
│   ├── _header.scss
│   ├── _footer.scss
│   └── _nav.scss
├── components/
│   ├── _buttons.scss
│   └── _cards.scss
└── pages/
    ├── _home.scss
    ├── _productos.scss
    ├── _planes.scss
    ├── _recursos.scss
    ├── _empresa.scss
    └── _contacto.scss
```

### Organización de los estilos

- **utilities:** variables, mixins y extensiones reutilizables.
- **base:** estilos generales y tipografía.
- **layout:** encabezado, navegación y pie de página.
- **components:** botones y tarjetas reutilizables.
- **pages:** estilos específicos de cada página.
- **main.scss:** punto de entrada que importa los archivos parciales mediante `@use`.

## SEO On-page y accesibilidad

- Se incorporaron meta descriptions específicas para cada página.
- Se definieron palabras clave relacionadas con el contenido de cada página.
- Se optimizaron los atributos alt de las imágenes.
- Se revisaron los títulos y encabezados para mejorar el SEO.


## Compilación de SCSS

El archivo `scss/main.scss` se compila para generar `css/style.css`, utilizado por las páginas HTML.

Para compilar una vez:

```bash
sass scss/main.scss css/style.css
```

Para compilar automáticamente cada vez que se guarden cambios:

```bash
sass --watch scss/main.scss css/style.css
```

## Sitio web

[Visitar Crowna CRM](https://alessandralay.github.io/Proyecto_CRM_Crowna/)

## Repositorio

[Ver código fuente en GitHub](https://github.com/AlessandraLay/Proyecto_CRM_Crowna)

