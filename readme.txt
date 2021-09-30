Funcion:
dapp simple y sencilla que trasnfiere ETH de una cuenta a otra
Levanta un servidor con webpack
Inyecta WEb3 en el navegador, usando MetaMask

Pasos:

* Creamos un proyecto de node. Esto nos crea el package.json
    npm init -y

* Instalamos nuevas libreria, webpack, linea de comandos y web server como librerias de desarrollo
  Usamos para el setup webpack, lo que hace que los modulos de js los empaqueta para poderlos servir en una pagina, aqui iria web3
    npm install webpack webpack-cli webpack-dev-server --save-dev    

* Creamos el folder dist, aqui se va a guardar la aplicacion final 

* Creamos el folder src, aqui se va a guardar los archivos base que van a geenrar la aplicacion

* Creamos un archivo git ignore, aqui escribimos node_modules, que es la carpeta con todas las libreria. Esta carpeta no se sube al github

* Creamos dentro de dist/index.hmtl  (hmtl:5  plantilla bascia html)
    le ponemos un llamado a un script: main.js

* Creamos en src un archivo index.js (console.log('Hola Mundo))

* Creamos un archivo de configuración de webpack para que el .js lo convierta a codigo que pueda leer el html
    webpack.config.js

* Instalamos web3 
    npm install web3   

    npm install  

* Ejecutamos el script start del package.json para iniciar el servidor
    npm run start




