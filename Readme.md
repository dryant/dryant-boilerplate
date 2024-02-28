# Dryant Boilerplate

![GitHub](https://img.shields.io/github/license/dryant/dryant-boilerplate)

Boilerplate para iniciar rápidamente proyectos de desarrollo web HTML y CSS con Sass, Parcel y herramientas de postprocesamiento como PostCSS y PostHTML. Este boilerplate incluye una estructura de archivos bien organizada y configurada con las dependencias necesarias para comenzar a desarrollar de inmediato.

## Descripción

Este boilerplate proporciona una base sólida para comenzar a desarrollar proyectos web HTML y CSS de manera eficiente. Con una estructura de archivos bien definida y configurada, y un conjunto de dependencias útiles, puedes comenzar a construir tu sitio web sin tener que preocuparte por la configuración inicial.

## Dependencias

- **Sass**: Permite utilizar características avanzadas de CSS como variables, anidamiento y mixins, lo que facilita la escritura y el mantenimiento de estilos.
- **Parcel**: Es un empaquetador de módulos rápido, zero-configuration, que se encarga de compilar y servir tu proyecto automáticamente.
- **PostCSS**: Un procesador de CSS que te permite transformar tus estilos con plugins, como autoprefixer, para mejorar la compatibilidad con los navegadores.
- **PostHTML**: Un procesador HTML que te permite utilizar plugins como PostHTML Include para incluir archivos HTML dentro de otros.
- **Autoprefixer**: Un plugin de PostCSS que añade automáticamente los prefijos de los navegadores a tus estilos CSS, lo que ayuda a garantizar una mejor compatibilidad entre navegadores.

## Instalación

```
// Clonar el repositorio
git clone https://github.com/dryant/dryant-boilerplate.git

// Entrar en el proyecto
cd dryant-boilerplate

// Instalar todas las dependencias
npm install
```

## Uso

Una vez clonado el repositorio e instalado las dependencias, si lanzamos el comando _npm run parcel:serve_ automáticamente se abrirá el navegador con la página por defecto del boilerplate. Cada vez que modifiques cualquier archivo y guardes los cambios automáticamente se actualizará la página para ver los cambios efectuados.

### Requisitos

Para utilizar este boilerplate, necesitas tener instalado Node.js en tu sistema. Recomendamos utilizar la versión 14 o superior.

### Scripts

| Script                 | Descripción                                                                                                                            |
| ---------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| `npm run parcel:serve` | Inicia un servidor de desarrollo con Parcel para la página `index.html`, observando cambios y recargando automáticamente el navegador. |
| `npm run parcel:build` | Compila el proyecto para producción con Parcel, optimizando los recursos y preparándolos para despliegue.                              |
| `npm run format`       | Formatea automáticamente los archivos HTML y CSS utilizando Prettier.                                                                  |
| `npm run clean`        | Limpia la carpeta `dist` y otros directorios temporales generados durante el desarrollo.                                               |
| `npm run dev`          | Inicia un servidor de desarrollo con Parcel y abre el proyecto en el navegador.                                                        |
| `npm run build`        | Compila el proyecto para producción, optimizando y minificando los archivos para su despliegue.                                        |
| `npm start`            | Inicia un servidor de desarrollo de Parcel.                                                                                            |
| `npm test`             | Ejecuta pruebas (actualmente no hay pruebas especificadas).                                                                            |
