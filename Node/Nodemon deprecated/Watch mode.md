# Bye Nodemon, new Feature (--watch)
Al ejecutarlo en modo 'ver', node --watchse reinicia el proceso cuando se modifica un archivo importado.
<br>
Podes usarlo en tu package.json para desarrollar una aplicacion en node/express, sin necesidad de instalar el legendario nodemon como dependencia.
``` js
"dev": "node --wacth app.js",
```
+ Esta nueva implementacion viene del relase [Node.js v18.11.0](https://nodejs.org/es/blog/release/v18.11.0)
