<!-- hide -->
# Desplegando un servidor Apache y sitio Wordpress en Debian (LAMP)


> By [@arnaldoperez](https://github.com/arnaldoperez) and [other contributors](https://github.com/breatheco-de/deploying-wordpress-debian/graphs/contributors) at [4Geeks Academy](https://4geeksacademy.co/)

![last commit](https://img.shields.io/github/last-commit/4geeksacademy/installing-kali-linux-on-virtual-machine)
[![build by developers](https://img.shields.io/badge/build_by-Developers-blue)](https://4geeks.com)
[![build by developers](https://img.shields.io/twitter/follow/4geeksacademy?style=social&logo=twitter)](https://twitter.com/4geeksacademy)

*These instructions are [available in english](https://github.com/breatheco-de/deploying-wordpress-debian/blob/main/README.md)*
<!-- endhide -->

## 📝 Instrucciones

En este proyecto:

- Aprenderás a instalar y poner en marcha un servidor Apache, que maneja [el 30% del tráfico de internet de hoy en día](https://w3techs.com/technologies/details/ws-apache) y se encuentra entre los cuatro servidores más utilizados en el mundo.
- Te familiarizarás con el despliegue de un sitio web en WordPress, [que es utilizado por el 42% de los sitios web actuales](https://kinsta.com/wordpress-market-share/#h-wordpress-market-share-is-wp-market-share-of-all-websites).

Esta configuración se llama [LAMP](https://es.wikipedia.org/wiki/LAMP_(software_bundle)), y es el stack más popular en internet hoy en día. Utilizarás esto durante varios otros proyectos de ciberseguridad.

Con este trabajo, comprenderás cómo funciona un servidor web desde el interior y tendrás un servicio en el que podrás realizar monitoreo y pruebas de seguridad para reforzar las habilidades que adquirirás a lo largo del curso.


<!-- hide -->

### Antes de empezar...

> ¡Te necesitamos! Estos ejercicios se crean y mantienen en colaboración con personas como tú. Si encuentras algún error o falta de ortografía, contribuye y/o repórtalo.

<!-- endhide -->

## 🌱 ¿Cómo empezar este proyecto?

### Instalación en un clic (recomendado)

Puedes empezar estos ejercicios en pocos segundos haciendo clic en: [Abrir en Codespaces](https://codespaces.new/?repo=4GeeksAcademy/deploying-wordpress-debian).

> Una vez ya tengas abierto VSCode, los ejercicios de LearnPack deberían empezar automáticamente, si esto no sucede puedes intentar empezar los ejercicios escribiendo este comando en tu terminal: `$ learnpack start`

### Instalación local:

Clona el repositorio en tu ambiente local y sigue los siguientes pasos:

1. Instala LearnPack, el package manager para tutoriales de aprendizaje y el HTML compiler plugin para LearnPack, asegúrate también de tener node.js 14+:

```bash
$ npm i learnpack -g
$ learnpack plugins:install learnpack-html
```

2. Descarga estos ejercicios en particular usando LearnPack y luego `cd` para entrar en la carpeta:

```bash
$ learnpack download html-forms-tutorial-exercises
$ cd html-forms-tutorial-exercises
```

> Nota: Una vez que termines de descargar, encontrarás una carpeta "exercises" que contiene todos los ejercicios.

3. Inicializa el tutorial/ejercicios ejecutando el siguiente comando en el mismo nivel donde se encuentra tu archivo learn.json:

```bash
$ npm i jest@24.8.0 -g
$ learnpack start
```

<!-- hide -->

## Colaboradores

Gracias a estas personas maravillosas ([emoji key](https://github.com/kentcdodds/all-contributors#emoji-key)):

1. [Arnaldo Perez (arnaloperez)](https://github.com/arnaloperez) cotribución: (build-tutorial) ✅, (documentación) 📖
  
2. [Alejandro Sanchez (alesanchezr)](https://github.com/alesanchezr),  contribución: (detector bugs) 🐛

3. [Lorena Gubaira (lorenagubaira)](https://github.com/lorenagubaira), contribution: (detector bugs) 🐛, contribution: (editor), (tranducción) 🌎

Este proyecto sigue la especificación [all-contributors](https://github.com/kentcdodds/all-contributors). ¡Todas las contribuciones son bienvenidas!

Este y otros ejercicios son usados para [aprender a programar](https://4geeksacademy.com/es/aprender-a-programar/aprender-a-programar-desde-cero) por parte de los alumnos de 4Geeks Academy [Coding Bootcamp](https://4geeksacademy.com/us/coding-bootcamp) realizado por [Alejandro Sánchez](https://twitter.com/alesanchezr) y muchos otros contribuyentes. Conoce más sobre nuestros [Cursos de Programación](https://4geeksacademy.com/es/curso-de-programacion-desde-cero?lang=es) para convertirte en [Full Stack Developer](https://4geeksacademy.com/es/coding-bootcamps/desarrollador-full-stack/?lang=es), o nuestro [Data Science Bootcamp](https://4geeksacademy.com/es/coding-bootcamps/curso-datascience-machine-learning).Tambien puedes adentrarte al mundo de ciberseguridad con nuestro [Bootcamp de ciberseguridad](https://4geeksacademy.com/es/coding-bootcamps/curso-ciberseguridad).
<!-- endhide -->
