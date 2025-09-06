##
CCS RULE
Selector 
p{
    color:blue;
}
- Selector is the HTML Element to style
#id{

} apply por id attribute in css

.class{

} 
apply for all class attribute

p.classAtribute{

}
for all paragraph in class attribute

#id > h1 {

}
apply for all childen that apply in id attribute

- Set font used in css file font-family
p{
    font-family: "Courier-New", monospace;
    font-size: 12px;
    text-transform:uppercase;
    text-decoration:underline red solid 5px;;
}

- Box Model
Margin
Border
Padding
Content

- Document Flow 
Elements inline and block
- Block element occuped all space with and height of our contents.
And this elements se aplinan unos debajo del otro.
- Block Elements
- div, h1,h2,h3,h4,h5,h6 , form

- Inline Elements
- a,input, img, b, label, i,em,span

if you want change inline to block can use css
display property : value block or inline

- tablas th header td columna
tr indica la fila 
- ul li indica un elemento de la lista
 ol li 

 # GESTOR DE PAQUETES
 NPM NODE PACKAGE MANAGER(NPM) El gestor de paquetes mas comun para de desarrollo de front end y con esto descarga las dependencias correctas que necesita el proyecto 
 # Herramienta de agrupacion 
El objetivo es agruptar las dependencias en un solo archivo llamado bundle
Si es muy largo puedes dividirse en muchos bundles o paquetes
Gulp y Webpack para herramienta de agrupacion
# Responsive Desing o diseño dinamico
Permite que el sitio web respinde en funcion de el dispositivo donde se visualiza
- Cuadriculas Flexibles Flexible Grids
- Image Fluid
- Media Queries 

### Flexible Columns 
Se componen de columnas , medianiles y magenes, espacio entre cada columna se llama medianil
y el espacio entre el contenido y los margenes izquierdo y derecho se llaman margenes
- Breakpoint Es el punto en el que el contenido y el diseño de un sitio web se adaptaran para proporcionar la mejor experiencia posible para el usuario
Fixxed Grids, Fluid Grids, Hibrid Grids

- El diseño dinamico significa que una pagina web puede estirarse o encogerse autimaticamente en funcion a la pantalla en la que se muestre.

- Bootstrap se divide en un conjunto de cuadricula de 12 columnas que puede ser fluido y fijo.
Siempre boostrap tiene un contenedor que es el ele ento raiz ,filas y columnas

# Another Frameworks for Building Interfaces similar to Bootstrap
- Foundations
- Pure CSS
- TailWind CSS
- UIKIT
- MVP CSS

# Diference Between Dinamic and Static content
La difernecia esta en que el contenido estatico se alamcena en el servidor web como imagenes videos , y el contenido dinamico como gestion de contraseñas y validacion de usuarios se gestionan en el servidor de aplicaciones
# Diferencia entre un servidor web y un servidor de aplicaiones 
El servidor web es donde se muestra el contendido de la pagina y verifica si tiene que ir por contenido estatico o dinamico , almacena datos en cache que trae del servidor de aplicaiones como la gestion de contraseñas.
# SPA VS TRADITIONAL WEB APPLICATION
- Single page application
    Permite al usuario interactuar con el sitio web sin que la aplicacion tenga que descargar nuevas paginas web enteras, EN CAMBIO REESCRIBE LA PAGINA WEB ACTUAL A MEDIDA QUE EL USUARIO INTERACTUA CON ELLA.
    - Enfoque de budling que es traer todos los archivos en el inicio
    - Enfoque lazy loading que va cargando los archivos a medida que se van necesitando y carga los archivos minimos para cargar la aplicaion
- Multiapage applications traditional Forms
# QUE ES REACT
- Cual es el objetivo de React
- Como funcionan sus componentes en conjunto.
React es una biblioteca de codigo abierto desde el 2013
React crea SPA aplications y Movile Applications with React native

Cuando desarrolla una aplicacion puede elegir react para desarrollar la interfaz de usuario, la navegacion y la forma en que se solicita los datos del servidor web
React : Permite definir los componentes que puede combinar para crear una aplicaion web
- Un componente es una pequeña pieza de una interfaz de usuario como un reproductor de musica o una galeria de fotos
-React no es un Framework es una libreria 
- React no utiliza templates , utiliza y reutiliza componentes y renderiza vistas, react hace que las vistas sean mas faciles de mantener 
-React utiliza una representacion del DOM llamado Render que es una representacion ligera de la vista.
- Los datos devueltos de  render  no son una cadena ni un nodo DOM: es una descripción liviana de cómo debería verse el DOM.
- React crea un DOM virtual en memoria 
- Se llama en proceso de reconciliacion
1. Se actualiza el DOM Virtual
2. La version actual del DOM Virtual se compara con la version anterior y verifica que elementos han cambiado
3. Los elementos actualizados se comparan en el DOM del navegador
4. La pagina web se actualiza para coincidir con el DOM del navegador
Como actualizar el DOM del navegador puede ser una operación lenta, este proceso ayuda a reducir la cantidad de actualizaciones del DOM del navegador al actualizarlo solo cuando es necesario.
 arquitectura React Fiber

- Otras bibliotecas para complementar REACT
- Lodash Redondeo de numeros
- Luxon Calendarios
- Redux controlar el estado como eliminar el articulo del carrito
- Axios comunicarse con las API por HTTP
-Jest para escribir pruebas automatizadas para el codigo

