# Antes de empezar

## Paso 1. Instalar Node.js

[Descargar Node.js](https://nodejs.org/es/)

```node --version

npm --version

npm init
```

## Paso 2. Instalar Gulp

[Descargar Gulpjs](https://gulpjs.com/)

[Tutorial básico](https://frontendlabs.io/1669--gulp-js-en-espanol-tutorial-basico-primeros-pasos-y-ejemplos)

```npm install --save-dev gulp

gulp --version

npm init


npm install --save-dev gulp-concat

npm install --save-dev gulp-uglify

//npm i gulp-sass

//npm i gulp-cssmin
```

>Antes de nada hay que crear el fichero gulpfile.js que será el encargado de convertir y concatenar los ficheros de scss en css. Así como de comprimir y concatenar los fichero javacript. Estos fichero se alojan en la carpeta source/scss y source/js respectivamente.

## Paso 3. Crear un repositorio de archivos Git.

Configuración rápida - si has hecho este tipo de cosas antes:
[axterix25/PlantillasHTML5](https://github.com/axterix25/PlantillasHTML5.git)


…o crear un nuevo repositorio desde la línea de comandos

```echo "# PlantillasHTML5" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/axterix25/PlantillasHTML5.git
git push -u origin master
```

…o subir un repositorio existente desde la línea de comandos

```git remote add origin https://github.com/axterix25/PlantillasHTML5.git
git push -u origin master
```

…o importar código desde otro repositorio.

git-cheatsheet
https://education.github.com/git-cheat-sheet-education.pdf

[Como se organiza sass](https://fontawesome.com/how-to-use/on-the-web/using-with/sass)
