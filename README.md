# Crowna CRM

Crowna CRM es una plataforma de gestión de relaciones con clientes diseñada para ayudar a las empresas a organizar, automatizar y mejorar la gestión de sus clientes.

# Tecnologías utilizadas

HTML5

CSS3

SCSS (Sass)

Bootstrap 5

JavaScript

AOS (Animate On Scroll)

CSS Animations (@keyframes)

Git y GitHub

Netlify

# Características del proyecto

Diseño responsive adaptable a dispositivos móviles, tablets y escritorio.

Navegación entre seis páginas: Inicio, Productos, Planes, Recursos, Empresa y Contacto.

Arquitectura SCSS modular para facilitar el mantenimiento y la reutilización de estilos.

Componentes reutilizables, como botones y tarjetas.

Transiciones CSS para mejorar la interacción con los botones.

Animaciones CSS mediante @keyframes.

Animaciones al desplazarse por la página mediante AOS, donde está implementada.

Componentes de Bootstrap 5 para facilitar el desarrollo de la interfaz.

Optimización básica de SEO on-page y accesibilidad.

# Estructura del proyecto

```text
Proyecto_CRM_Crowna/
├── index.html
├── pages/
│   ├── contacto.html
│   ├── empresa.html
│   ├── planes.html
│   ├── productos.html
│   └── recursos.html
├── css/
│   ├── style.css
│   └── style.css.map
├── scss/
│   ├── base/
│   │   ├── _base.scss
│   │   └── _tipografia.scss
│   ├── components/
│   │   ├── _buttons.scss
│   │   └── _cards.scss
│   ├── layout/
│   │   ├── _header.scss
│   │   ├── _footer.scss
│   │   └── _nav.scss
│   ├── pages/
│   │   ├── _home.scss
│   │   ├── _productos.scss
│   │   ├── _planes.scss
│   │   ├── _recursos.scss
│   │   ├── _empresa.scss
│   │   └── _contacto.scss
│   ├── utilities/
│   │   ├── _variables.scss
│   │   ├── _mixins.scss
│   │   └── _extend.scss
│   └── main.scss
├── crowna_assets_png/
├── package.json
└── README.md
```


# Arquitectura SCSS

El proyecto utiliza una arquitectura modular para organizar los estilos y facilitar su mantenimiento y reutilización.

# Organización de los estilos

utilities: variables, mixins y extensiones reutilizables.

base: estilos generales y tipografía.

layout: encabezado, navegación y pie de página.

components: botones y tarjetas reutilizables.

pages: estilos específicos de cada página.

main.scss: punto de entrada que importa los archivos parciales mediante @use.

# Animaciones y transiciones

El proyecto incorpora efectos visuales para mejorar la experiencia de navegación:

Transiciones CSS: suavizan los cambios visuales de los elementos interactivos, como los botones.

@keyframes: permite definir animaciones personalizadas mediante estados iniciales y finales.

AOS (Animate On Scroll): permite animar elementos al desplazarse por la página, en las secciones donde se encuentra implementado.

# SEO on-page y accesibilidad

Meta descriptions específicas para las páginas.

Palabras clave relacionadas con el contenido de cada página.

Atributos alt en las imágenes.

Títulos y encabezados organizados para facilitar la comprensión del contenido.

# Compilación de SCSS

El archivo scss/main.scss se compila para generar css/style.css, utilizado por las páginas HTML.

# Compilar una vez

sass scss/main.scss css/style.css

# Compilar automáticamente al guardar cambios

sass --watch scss/main.scss css/style.css

Para detener la compilación automática, pulsa Ctrl + C en la terminal

# Sitio web publicado

[Visitar Crowna CRM](https://crownacrm.netlify.app/)

# Repositorio

[Ver código fuente en GitHub](https://github.com/AlessandraLay/Proyecto_CRM_Crowna)
