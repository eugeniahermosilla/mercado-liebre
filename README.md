# tarea-mercado-liebre

MICRO DESAFIO 1

Hice el archivo git.ignore para que ignore la carpeta node mudules que se genera automaticamente cada vez que alguien se desarga el proyecto.

Instale npm `install --save-dev nodemon` para que cada vez que realice un cambio se actulice el servidor. Antes instale nodemon de manera global `npm install -g nodemon``

Agregué un comando a la sección de scripts `npm start` para evitar tener que correr siempre `nodemon app.js`.

Instale el modulo de express para poder correr el servidor. Requeri el modulo path para poder mandar HTML al cliente.

MICRO DESAFIO PARTE 2
En esta parte tuve que declarar una carpeta de archivos estaticos de express, para asi poder servir imagenes al sitio web.
const staticFolder = path.resolve(\_\_dirname, "./public"); En esta parte estamos guardando en la variable la ruta de la carpeta de archivos estaticos

app.use(express.static(staticFolder)); Aca uso el metodo app.use que recibe express.static al cual le pasamos la ruta almacenada en el paso anterior.

MICRODESAFIO PARTE 3

Lo primero que hago es agregar un archivo css reset para eliminar cualquier estilo que le pueda dar el navegador por default.

Agrege variables de colores para poder unificar los codigos de colores y no tener que cambiarlos en todos los lugares (en caso de que cambiasen)

Con el \* {} selecionamos todos los elementos HTML y le aplicamos el estilo Roboto.

Para usar los iconos en el documento HTML importamos los iconos.

Cree clases generales, para poder aplicarle el estilo de esa clase a las etiquetas que la implementen.
