![Adalab](https://beta.adalab.es/resources/images/adalab-logo-155x61-bg-white.png)

# Evaluación final - Modulo 1 

Está es mi evaluación final, del módulo 1 (maquetación) en *Adalab*.

Consiste en maquetar una **página web desde cero**, es una landing page en su versión inicial, para desarrollar la evaluación final me entregarón un diseño a traves del programa Zeplin, ficheros a utilizar y tambien un pdf con todos los requerimientos, consejos y guias para completarla. 

En la evaluación hay 3 tipos de ficheros y carpetas:

- Los ficheros que están sueltos en la raíz del repositorio, como gulpfile.js, package.json... Son la configuración del proyecto y no necesitamos modificarlos.
- La carpeta `src/`: son los ficheros de nuestra página web, como HTML, SASS, en esta carpeta se codeo todos los nuevos ficheros.
- Las carpetas `public/` y `docs/`, que son generadas automáticamente cuando arrancamos el proyecto. El Kit lee los ficheros que hay dentro de `src/`, los procesa y los genera dentro de `public/` y `docs/`.

Es posible la solución de este ejercicio aplicando todo lo visto en el primer módulo del bootcamp, pasando por temas como:  

- HTML y CSS
- Modelo de caja
- Zeplin
- Flexbox
- Posicionanmiento 
- Diseño responsivo 
- Git 
- Gulp (npm)
- SASS 
- CSS Grid
- Animaciones y transiciones CSS
## ¿Qué encontrarás? 

Esta página contiene 4 secciones principales: 

1. Header o Hero: 
    - Contiene un menu con enlace directo a Adalab.es 
    - El titulo de la página con su correspondiente texto 
    - Un boton con acceso a la sección "3 Reasons To Purchase"
2. Sección 1: Looking Through A Window - *llamada about-us* :
    - Es una pequeña introducción al tema principal de la página 
    - Contiene un small
    - Un titulo principal
    - Un pequeño texto introductorio
    - Un boton con enlace directo a Adalab.es
3. Sección 2: 3 Reasons To Purchase:
    - Da tres motivos por los cuales se debe tomar este servicio
    - Contiene un titulo principal 
    - Tres tarjetas, con su respectivo titulo y parrafo
    - Un boton con enlace directo a Adalab.es
4. Footer:
    - Contiene el copy
    - Contiene un menu con enlaces acerca de los productos de Adalab.es
    - Contiene un menu con enlaces a las redes sociales de Adalab.es

### Que tecnologías se uso:

Como se dijo en el primer apartado fue necesario el conocimiento de todo el modulo de maquetación, en el cual se aplico todos los conceptos vistos, *se reforzo y también se aprendio nuevas formas aplicar lo visto.* 

Diviendolo por secciones se utilizo las siguientes tecnologias: 

- En todo el documento se utilizo HTML, SASS(css), metodología BEM(nombrar las clases), Gulp (partials)
- Para hacerlo diseño responsivo se utilizo @media queries de 768px y 1200px
- Para guardar los cambios, tener un historial del proyecto y volver algún punto del pasado se utilizo GIT con complemento de GitHub para tenerlo en la web
- Los botones tienen cambio de estado al pasar el mouse por encima (:hover) y tambien una transición.
- El boton del footer esta posicionado y tiene una animación de crecimiento

1. Header o Hero: Flexbox
2. Sección 1: Looking Through A Window - *llamada about-us* : Flexbox, se decidio utilizar esta técnologia para reforzar lo visto.
3. Sección 2: 3 Reasons To Purchase: Grid
4. Footer: Flexbox, posicionamiento(boton)

#### Donde se puede ver 
Esta página web tiene un enlace en la web, donde se podra visitar las veces que quiera.

**El enlace es el siguiente: [Evaluación Final - Módulo uno](URL "http://beta.adalab.es/modulo-1-evaluacion-final-jnataliaramirez/")**


##### Instalación de Gulp para entrar al código 

###### Guía de inicio rápido

> **NOTA:** Necesitas tener instalado [Node JS](https://nodejs.org/) para trabajar con este Starter Kit:

*Pasos a seguir cada vez que queremos arrancar un proyecto desde cero:*

1. **Clona esta repositorio desde GitHub**.
1. **Abre una terminal** en la carpeta raíz del repositorio.
1. **Instala las dependencias** locales ejecutando en la terminal el comando:

```bash
npm install
```

**Pasos para arrancar el proyecto:**

Una vez hemos instalado las dependencias, vamos a arrancar el proyecto. **El proyecto hay que arrancarlo cada vez desees verlo desde tu computador** Para ello ejecuta el comando:

```bash
npm start
```

Este comando:

- **Abre una ventana de tu navegador y muestra la página web**, al igual que hace el plugin de VS Code Live Server (Go live).
- También **observa** todos los ficheros que hay dentro de la carpeta `src/`, para que cada vez que modifiques un fichero **refresca tu página en el navegador**.
- También **procesa los ficheros** HTML, SASS / CSS y JS y los **genera y guarda en la carpeta `public/`**. Por ejemplo:
   - Convierte los ficheros SASS en CSS.
   - Combina los diferentes ficheros de HTML y los agrupa en uno o varios ficheros HTML.

Si deseas editar mi evaluación después de ejecutar `npm start` ya puedes empezar a editar todos los ficheros que están dentro de la carpeta `src/` y programar cómodamente.

**Para generar mi página para producción ejecute el comando:**

```bash
npm run docs
```
Y a continuación:

1. Subi a mi repositorio la carpeta `docs/` que se te acaba de generar.
1. Entre en la pestaña `settings` de mi repositorio b.
1. Y en el apartado de GitHub Pages activa la opción **master branch /docs folder**.
1. Y ya está

Tal vez quieras cojer el código de esta evaluación entonces estas en libertad de hacer los mismos pasos que hice yo para tu repo. Recuerda que deberias copiarlo (descargarlo como un zip) y no clonarlo si es lo que deseas. 

Además, los comandos:

```bash
npm run push-docs
```
o

```bash
npm run deploy
```

son un atajo que nos genera la versión de producción y hace push de la carpeta `docs/` del tirón. Te recomendamos ver el fichero `package.json` para aprender cómo funciona.

