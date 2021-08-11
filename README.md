# Ocean-Being

Título del proyecto: Ocean Being

Descripción:
Interfaz de una página web para la organización Ocean Being. El sitio incluye el propósito general de la entidad, sus programas, noticias de interés,
y un formulario de contacto.

Lenguajes utilizados:
HTML
CSS - SASS

Frameworks:
Bootstrap

Librerías de animaciones:
https://animate.style/,
https://michalsnik.github.io/aos/

Librerías de íconos:
https://fontawesome.com/

Software:
Visual Studio Code,
Node.js

Requisitos para modificar las hojas de estilo:
- Luego de instalar Node.js, verificar que se tenga instalado npm (comando: npm).
- Inicializar npm en la carpeta del proyecto:
    npm init,
    npm install -D node-sass nodemon
    - Crear los archivos .css y .scss dentro de las carpetas respectivas.
    - En el package.json, adicionar las siguientes líneas, de acuerdo con los nombres de
      los archivos .css y .scss:
      "build-css": "node-sass --include-path scss scss/estiloPrueba.scss css/estiloPrueba.css",
      "watch-css": "nodemon -e scss -x \"npm run build-css\""
    - Ir al símbolo del sistema y ejecutar el comando: npm run watch-css.


Autor:
Maricel Jiménez Gómez
