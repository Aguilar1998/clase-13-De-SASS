## Install Node

https://nodejs.org/en

# SASS:

- Variables
- Mixins
- Mixins sin y con parametros, Flex, grid o Media
- Crea tu propio Mixin

## 👉🏽 Para descargar este proyecto:

```
 git clone https://github.com/Aguilar1998/Herramientas-De-SASS.git
 cd clase-13-De-SASS
 git i

```

## 👉🏽 Forma de instalar Sass al momento de crear un proyecto desde cero:

```
    npm init
    npm install -D node-sass nodemon
```

### Crear la carpeta scss y css con sus archivos respectivos .

### Incluir los siguientes script dentro de packaje.json

```
    “build-scss: node-sass --include-path scss sass/style.scss css/style.css”,

    “watch-scss: “nodemon -e scss -x \”npm run build-scss\””
```

```
    npm run watch-scss
```

## 👉🏽 Forma corta de instalar Sass al momento de crear un proyecto desde cero:

```
    npm init

    npm install -g sass

    sudo install -g sass (forzar la instalación si no funciona el anterior comando)

    sass --watch scss:css
```

### Live SASS Compiler (extension de visual estudio code)
