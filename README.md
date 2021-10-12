# graphql-platzi-frontend
Platzi - Curso Básico de GraphQL (Frontend)

> Para visualizar el proyecto Backend (que construye las queries en GraphQL) dar clic [acá](https://github.com/cesardramirez/graphql-platzi-backend).

## Dependencias

> *dependencies*:
> <br>**graphl-request**: Cliente que se va a usar para hacer los llamados al backend.
> <br>**handlebars**: Motor de plantillas.

> *devDependencies*:
> <br>**browserify** y **uglifyify**: Compactar js con todas las dependencias y construir un bundle.

### Listado de comandos

`npm install`  _Generar la carpeta node_modules (necesario para ejecutar el proyecto)._
<br>`npm run bundle`  _Generar el archivo bundle.js que será llamado al iniciar el index.html en el navegador._

## Ejecución del proyecto.

Cuando el *bundle.js* ya se haya generado, se abre desde el navegador el archivo *index.html*. Se debe tener arriba el servidor de GraphQL a nivel de Backend [http://localhost:3000/graphql](http://localhost:3000/graphql) para que, cuando se ingrese texto genere los resultados de la búsqueda.

<br>![](/docs/img/01_Front_Result.png)
<br>![](/docs/img/02_Front_Result.png)
<br>![](/docs/img/03_Front_Result.png)