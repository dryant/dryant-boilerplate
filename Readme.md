Dryant Boilerplate

# Dryant Boilerplate

license - CC BY 4.0

Un Boilerplate es un conjunto de archivos y carpetas que se utilizan como punto de partida para un nuevo proyecto. Puede contener además de archivos de código, configuraciones, dependencias, entre otros. El objetivo de un Boilerplate es evitar tener que empezar desde cero cada vez que se inicia un nuevo proyecto.

Dryant-boilerplate es un boilerplate para iniciar rápidamente proyectos de desarrollo web HTML y CSS con Sass, Parcel y herramientas de postprocesamiento como PostCSS y PostHTML. Este boilerplate incluye una estructura de archivos bien organizada y configurada con las dependencias necesarias para comenzar a desarrollar de inmediato y de una forma mas rápida y eficiente.

## Descripción

Dryant-boilerplate proporciona una base sólida para comenzar a desarrollar proyectos web HTML y CSS de manera eficiente.

### Vetajas:

#### Cambios en tiempo real

Permite escribir código a la vez que visualizas en tiempo real los cambios en el navegador, gracias a Parcel, un empaquetador de módulos rápido y zero-configuration.

#### Variables en CSS

Puedes utilizar características avanzadas de CSS como variables, anidamiento y mixins, lo que facilita la escritura y el mantenimiento de estilos, gracias a Sass.

#### Compatibilidad con navegadores

Añade automáticamente los prefijos de los navegadores a tus estilos CSS, lo que ayuda a garantizar una mejor compatibilidad entre navegadores, gracias a Autoprefixer.

#### Reutilización de código HTML

Permite incluir archivos HTML dentro de otros, gracias a PostHTML, con lo que puedes reutilizar código HTML.

#### Formateo automático de código

Formatea automáticamente los archivos HTML y CSS utilizando Prettier para mantener un código limpio y legible.

#### Eliminación de archivos innecearios

Limpia la carpeta dist y otros directorios temporales generados durante el desarrollo, gracias a npm run clean.

### Requisitos

Para utilizar este boilerplate, necesitas tener instalado Node.js en tu sistema. Recomendamos utilizar la versión 14 o superior.

## Dependencias

Las dependencias que usa este boilerplate para conseguir las ventajas nombradas anteriormente son las siguientes:

**Sass**: Permite utilizar características avanzadas de CSS como variables, anidamiento y mixins, lo que facilita la escritura y el mantenimiento de estilos.

**Parcel**: Es un empaquetador de módulos rápido, zero-configuration, que se encarga de compilar y servir tu proyecto automáticamente.

**PostCSS**: Un procesador de CSS que te permite transformar tus estilos con plugins, como autoprefixer, para mejorar la compatibilidad con los navegadores.

**PostHTML**: Un procesador HTML que te permite utilizar plugins como PostHTML Include para incluir archivos HTML dentro de otros.

**Autoprefixer**: Un plugin de PostCSS que añade automáticamente los prefijos de los navegadores a tus estilos CSS, lo que ayuda a garantizar una mejor compatibilidad entre navegadores.

## Instalación

Para poder usar el boilerplate, lo único que tendremos que hacer es clonar el repositorio y una vez dentro de la carpeta del proyecto ejecutar un npm install para instalar todas las dependencia:

        ` // Clonar el repositorio

        git clone https://github.com/dryant/dryant-boilerplate.git

        // Entrar en la carpeta del proyecto

        cd dryant-boilerplate

        // Instalar las dependencias npm install
        `

## Uso

Una vez clonado el repositorio e instalado las dependencias, si lanzamos el comando _**npm run parcel:serve**_ automáticamente se abrirá el navegador con la página por defecto del boilerplate. Cada vez que modifiques cualquier archivo y guardes los cambios automáticamente se actualizará la página para ver los cambios efectuados.

## Scripts

A continuación se muestran los scripts que puedes utilizar con el boilerplate:

| Script                 | Descripción                                                                                                                            |
| ---------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| `npm run parcel:serve` | Inicia un servidor de desarrollo con Parcel para la página `index.html`, observando cambios y recargando automáticamente el navegador. |
| `npm run parcel:build` | Compila el proyecto para producción con Parcel, optimizando los recursos y preparándolos para despliegue.                              |
| `npm run format`       | Formatea automáticamente los archivos HTML y CSS utilizando Prettier.                                                                  |
| `npm run clean`        | Limpia la carpeta `dist` y otros directorios temporales generados durante el desarrollo.                                               |
| `npm run dev`          | Inicia un servidor de desarrollo con Parcel y abre el proyecto en el navegador.                                                        |
| `npm run build`        | Compila el proyecto para producción, optimizando y minificando los archivos para su despliegue.                                        |
| `npm start`            | Inicia un servidor de desarrollo de Parcel para la página `index.html`.                                                                |
| `npm test`             | Ejecuta pruebas (actualmente no hay pruebas especificadas).                                                                            |

## Licencia

**Licencia Creative Commons Atribución 4.0 Internacional (CC BY 4.0)**

Puedes:

- **Compartir:** copiar y redistribuir el material en cualquier medio o formato.
- **Adaptar:** remezclar, transformar y construir sobre el material para cualquier propósito, incluso comercialmente.

Bajo las siguientes condiciones:

- **Atribución:** debes dar el crédito adecuado, proporcionar un enlace a la licencia e indicar si se realizaron cambios. Puedes hacerlo de cualquier manera razonable, pero no de una manera que sugiera que el licenciante te respalda a ti o al uso que hagas del material.
