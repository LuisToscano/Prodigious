# Prodigious
Prueba de desarrollo móvil presentada para Prodiguous.

***************************** Enunciado ************************************

Create an app that will show a list of posts, which you can save and view their details. You will consume a webservice (either using your own webservice or a sample one like https://jsonplaceholder.typicode.com/)) The app should be able to:

1. Download and cache the list of posts.
2. Show list of post titles which you can tap.
3. Show post details including user and post details.
4. Add a post to favorite posts, which should be saved locally
5. Show list of favorite posts
6. Show favorite post details (like 3)
7. Handle offline mode that will show the user is online but continue working.
8. Handle data refresh with table dragging

************************* Herramientas Utilizadas **************************

AngularJS
Ionic Framework
Gulp JS (SASS y minificado JS)
JSON Server

******************************* Requisitos *******************************

1. NodeJS (https://nodejs.org/en/)
2. npm (https://www.npmjs.com/)
3. Cordova/Ionic (http://ionicframework.com/docs/guide/installation.html)

******************************* A tener en cuenta *******************************

1. Se debe configurar la url para acceder al archivo posts.JSON, esto debe realizarse en el archivo:
 
'Prodiguous\app\constants\constants.provider.js' modificando el valor 'providers.posts.url'

Para casos de prueba se utilizó JSON Server, y la ruta 'http://localhost:3000/posts'

****************************** Instalación ********************************

1. Descargar y descomprimir el documento adjunto Prodigious Prueba.zip
2. Ingresar al directorio contenido usando la linea de comandos.
3. Ejecutar el comando npm install.

o

1. Descargar y descomprimir el documento adjunto ProdigiousFull.zip

***************************** Visualización ********************************

1. Navegador web:
Ejecutar el comando
ionic serve 

2. Android/iOS
Ejecutar los comandos:

ionic build android/ios
ionic run android/ios

