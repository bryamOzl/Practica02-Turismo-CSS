# Practica02-Turismo-CSS📄
Se pide realiza un sitio web que tenga al menos una página principal (index.html) y cinco páginas que tengan navegabilidad entre todas
las páginas html. Además, se pide utilizar estilos CSS con la finalidad de obtener un diseño

# Desarrollo 🚀

## a. El desarrollo de cada uno de los puntos antes descritos así como las reglas CSS utilizadas para resolver cada punto.⌨️
Codigo de los archivos css en total son 100 estilos diferentes. Y están dentro de :
*	Página styles.css
*	Página tres.css
*	Página dos.css
*	Página disenos.css

```
/*1. Sisve para cargar el fondo en la pagina index.*/
body{
    background-image: url(/Practica02/images/leaves.png);
}

/*2. Nos permite crer un id que sirve para crear un borde doble*/
#borde {
    border-color: rgb(17, 17, 17);
    border-style: double;
}

/*3. Colocacion para la imagen ec*/
.logo {
    width: 34%;
    float: left;
}

/*4. Colocacion y estilo para el Titulo del index*/
.titulo {
    width: 45%;
    float: left;
    font-size:34px;
    font-family: "Baskerville Old Face";
    color: rgb(251, 255, 0);
    margin: 0px;
}

/*5. Colocacion para la imagen escudo*/
.escudo {
    width: 21%;
    float: left;
}

/*6. Estilo para el footer*/
footer{
    clear: both;
}

/*7. Estilos para ajustar la pagina el body que no se distorsione*/

body {
	margin: 0 auto;
	width: 100%;
	max-width: 1250px;
	min-width: 640px;
}

/*8. Aqui le damos al header un margin de 0 con width del 100%*/
body > header {
	margin: 0;
	width: 100%;
	overflow: hidden;
}

/*ESTILOS PARA EL MENU*/
/*9. En la etiqueta nav osea el menu sirve para redondear los bordes y cambiar el color */
nav{
    /*Bordes redondeados*/
    border-radius:10px;
    background-image: -webkit-gradient(linear, left top, left bottom, from(rgb(3, 3, 3)), to(rgb(27, 150, 207)));
    overflow:hidden;
    padding:4px;
    width:99.4%;
}

/*10. Aqui nos cambiamos los elementos de la etiqueta ul quitandole el stilo y dandole margin y bording*/
nav ul{
    list-style:none;
    margin:0 10px 0 10px;
    padding:0;
}

/*11. Aqui en esta etiqueta li del menu le redondeamor y cambiamos su formato tambien le ponemos en negrita*/
nav ul li{
    /*Bordes redondeados*/
    border-radius:5px;/*Estandar por defecto*/
    float:left;
    font-family:Arial, Helvetica, sans-serif;
    font-size:16px;
    font-weight:bold;
    margin-right:10px;
    text-align:center;

}

/*12. Aqui damos un degradado al fondo cuando pasamos el mouse por algun elemento del menu */
nav ul li:hover{
    /*Degradado de fondo*/
    background-image: -webkit-gradient(linear, left top, left bottom, from(#FFF), to( #E3E3E3));
    background-image: linear-gradient(top, #FFF, #E3E3E3);/*Estandar por defecto*/
}

/*13. Aqui cambiamos los elemntos de la etiqueta a del menu para darle color a las letras sin decoracion*/
nav ul li a{
    color:#f7f7f7;
    display:block;
    padding:10px;
    text-decoration:none;
    /*Transiciones*/
    transition: 0.4s linear all;
}

/*14. Aqui le damos un color negro cuando selecionamos el algun elemento del menu*/
nav ul li a:hover {
    color:rgb(8, 8, 8);
}

/*15. Estilos para la etiqueta h2 del subtitulo*/
#subtitulo{
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    font-size:25px;
    color: rgb(6, 31, 253);
}

/*16. Estilos para el foter pero solo para lo que esta dentro de una etiqueta p*/
footer p{
    color: rgb(255, 0, 0);
    font-size: 12px;
}

/*17. clase para fondo negro*/
.fondo{
    background-color: rgb(3, 3, 3);
}

/*18. Estilos para el texto del index*/
#introduccion{
    font-family: 'Times New Roman', Times, serif;
    font-size: 20px;
}

/*19. Formato para la parte de informacion 3 columnas parte izquierda*/
.imagenesi {
    width: 23%;
    float: left;
}

/*21. Formato para la parte de informacion 3 columnas parte centro*/
.info {
    width: 51%;
    float: left;
    padding: 5px;
    border: 5.5px;
}

/*22. Formato para la parte de informacion 3 columnas parte derecha*/
.imagenesd {
    width: 23%;
    float: right;
}

/*23. Estilos para ajustar la pagina*/
body {
    margin: 0 auto;
    width: 100%;
    max-width: 1340px;
    min-width: 740px;
    /*
    border-color: rgb(0, 0, 0);
    border-style: solid;*/
}

/*24. Aqui le damos al header un margin de 0 con width del 100%*/
body > header {
    margin: 0px;
    overflow: hidden;
}


/*26. Estilo para aplicar borde dobel*/
#borde {
    border-color: rgb(255, 255, 255);
    border-style: double;
}

/*27. Estilo para aplicar un borde a las secciones*/
.borde2{
    border-color: rgb(255, 255, 255);
    border-style: solid;
}

/*28. Estilos para el foter pero solo para lo que esta dentro de una etiqueta p*/
footer p{
    color: rgb(250, 250, 250);
    font-size: 12px;
}

/*29. Para poner un fondo negro*/
#negro{
    background-color: black;
}

/*30. Posicionamiento y estilo de la Columna1*/
#columna1 {
    width: 12%;
    float: left;
    margin: 6px;
    background-color: black;
    border-radius:10px;/*El estandar por defecto*/
}

/*31. Posicionamiento y estilo de la Columna2*/
#columna2 {
    border-radius:10px;/*El estandar por defecto*/
    width: 59%;
    float: left;
    margin: 6px;
}

/*32. Posicionamiento y estilo de la columna3*/
#columna3 {
    border-radius:10px;/*El estandar por defecto*/
    width: 24%;
    float: left;
    margin: 6px;
    background-color: black;
}

/*33. Estilo para el footer*/
footer{
    clear: both;
}

/*34. Formato para el menu de navegacion*/
nav{
    /*Bordes redondeados*/
    border-radius:10px;/*El estandar por defecto*/
    background-image: -webkit-gradient(linear, left top, left bottom, from(rgb(5, 5, 5)), to(rgb(255, 255, 255)));/*Para chrome y Safari*/
    padding:2px;
    width:97.4%;
}

/*35. Formato para lo que se encuentra dentro del menu*/
nav ul{
    list-style:none;
    margin:0 10px 0 10px;
    padding:0;
}

/*36. Formato para las opciones que estan dentro del menu y las letras estilos de fuente*/
nav ul li{
    /*Bordes redondeados*/
    border-radius:5px;/*Estandar por defecto*/
    float:inherit;
    font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    font-size:22px;
    font-weight:bold;
    margin-top:5px;
    text-align:center;

}

/*37. Formato para pintar cuando se pasa por la selecion de un menu*/
nav ul li:hover{
    /*Degradado de fondo*/
    background-image: -webkit-gradient(linear, left top, left bottom, from(rgb(250, 250, 250)), to( #E3E3E3));/*Chrome y Safari*/
}

/*39. Formato para las letras del menu color*/
nav ul li a{
    color:#fd0000;
    display:block;
    padding:5px;
    text-decoration:none;
     /*Transiciones*/
     transition: 0.4s linear all;
}

/*40. Estilos para ajustar la pagina*/
body {
    margin: 0 auto;
    width: 100%;
    max-width: 1340px;
    min-width: 640px;
    /*
    border-color: rgb(0, 0, 0);
    border-style: solid;*/
}

/*41. Aqui le damos al header un margin de 0 con width del 100%*/
body > header {
    margin: 0px;
    overflow: hidden;
}

/*42. Estilo para aplicar borde dobel*/
#borde {
    border-color: rgb(17, 17, 17);
    border-style: double;
}

/*43. Para poner un fondo negro*/
#negro{
    background-color: black;
}

/*44. Estilo para aplicar un borde a las secciones*/
.borde2{
    border-color: rgb(0, 0, 0);
    border-style: solid;
}

/*45. Posicionamiento y estilo de la Columna1*/
#columna1 {
    width: 17%;
    float: left;
    margin: 6px;
    background-color: black;
    border-radius:10px;/*El estandar por defecto*/
}

/*46. Posicionamiento y estilo de la Columna2*/
#columna2 {
    border-radius:10px;/*El estandar por defecto*/
    width: 80%;
    float: left;
    margin: 6px;
}

/*47. Estilo para el footer*/
footer{
    clear: both;
}

/*48. Estilos para el foter pero solo para lo que esta dentro de una etiqueta p*/
footer p{
    color: rgb(10, 10, 10);
    font-size: 12px;
}


/*49. Formato para el menu de navegacion*/
nav{
    /*Bordes redondeados*/
    border-radius:10px;/*El estandar por defecto*/
    background-image: -webkit-gradient(linear, left top, left bottom, from(rgb(5, 5, 5)), to(rgb(255, 255, 255)));/*Para chrome y Safari*/
    padding:2px;
    width:97.4%;
}

/*50. Formato para lo que se encuentra dentro del menu*/
nav ul{
    list-style:none;
    margin:0 10px 0 10px;
    padding:0;
}

/*51. Formato para las opciones que estan dentro del menu y las letras estilos de fuente*/
nav ul li{
    /*Bordes redondeados*/
    border-radius:5px;/*Estandar por defecto*/
    float:inherit;
    font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    font-size:22px;
    font-weight:bold;
    margin-top:5px;
    text-align:center;

}

/*52. Formato para pintar cuando se pasa por la selecion de un menu*/
nav ul li:hover{
    /*Degradado de fondo*/
    background-image: -webkit-gradient(linear, left top, left bottom, from(rgb(250, 250, 250)), to( #E3E3E3));/*Chrome y Safari*/
}

/*53. Formato para las letras del menu color*/
nav ul li a{
    color:#fd0000;
    display:block;
    padding:5px;
    text-decoration:none;
     /*Transiciones*/
     transition: 0.4s linear all;
}

/*54. Estilo para el cuadro de mensaje*/
#mensaje {
    background-color: #fff;
    width: 380px;
    height: 150px;
    font-family: Arial;
}

/*55. Formato y estilo para la parte de email y nombre*/
#nombre, #email {
    background-color: white;
    width: 380px;
    height: 27px;
    font-size: 14px;
}

/*56. Estilo para el boton de enviar*/
#button {
    color: #000;
    width: 100px;
    height: 35px;
}

/*57. Estilos para la etiqueta form del formulario*/
form {
    margin: 0 auto;
    margin-top: 0px;
    margin-right: auto;
    margin-bottom: 0px;
    margin-left: auto;
    width: 400px;
    float: left;
}

/*58. Estilo para la columna dos de el contacto Columna2c*/
#columna2c {
    border-radius:10px;/*El estandar por defecto*/
    width: 78%;
    float: left;
    margin: 6px;
    padding: 10px;
}

/*59. Formato para el segundo parrafo con fondo y tipo de letra*/
.parrafo2{
    text-decoration: none;
    font-style: oblique;
    font-family: Georgia, 'Times New Roman', Times, serif;
    text-align: justify;
}

/*60.Formato para el titulo h1 Ecuador Travel*/
#travel{
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    font-size: 36px;
    color: rgb(250, 8, 8);
}

/*61. Formato para el texto de color azul*/
.textor{
    color: rgb(10, 10, 10);
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-display: inherit;
    text-decoration: initial;
    text-align: justify;
}

/*62. Formato para el texto con fondo Rojo*/
.textoa{
    color: rgb(15, 15, 15);
    font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
    text-align: justify;
}


/*63. Estilos para el titulo de la pagina turismo*/
.titulo{
    font-family: 'Times New Roman', Times, serif;
    font-size: 33px;
    color: rgb(126, 223, 0);
}

/*64. Estilo para el tiulo de h2*/
#titulo2{
    font-size: 24px;
    background-color: rgb(243, 247, 4);
    font-family: cursive;
    font-display: initial;
    color: rgb(250, 250, 250);
    -webkit-text-stroke: 1px black;
}

/*65. Formato y estilo para el primer parafo de la pagina justificada*/
.texto1{
    text-align: justify;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    font-style: italic;
    font-size: 14px;
    color: rgb(255, 255, 255);
}

/*66 Formato para el titulo azul.*/
#titulo21{
    font-size: 24px;
    background-color: rgb(8, 4, 247);
    font-family: inherit;
    color: ivory;
}

/*67. Formato para el texto dos estilos y tamano de letra*/
#texto2{
    text-align: justify;
    font-size: 16px;
    font-family: cursive;
    color: rgb(255, 255, 255);
}

/*68. Formato para el tercer titulo tamano y fondo*/
#titulo22{
    background-color: red;
    color: ivory;
    font-family: unset;
}



/*69. Estilo para el fondo negro de la pagina*/
body{
    background-color: black;
}

/*70Estilo para el tercer parrafo formato y color de letra.*/
article > dd{
    color: blanchedalmond;
    font-style: italic;
    font-size: 16pt;
}

/*71. FOrmato para e titulo numero 4 h2*/
#titulo4{
    font-size: 24pt;
    font-family: 'Times New Roman';
    text-decoration: underline solid;
    color: rgb(255, 255, 255);
    background-color: yellow;
    -webkit-text-stroke: 1px black;
}

/*72.Estilo para el parrafo 4 */
.texto4{
    color: white;
    text-decoration-line: underline;
    font-size: 14pt;
    text-align: justify;
}

/*73.*/
.titulo5{
    background-color: blue;
    color: white;
    font-size: 19pt;
    font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
}

/*74.*/
.texto5{
    font-family: "Consolas", monospace;
    color: white;
    text-align: justify;
}

/*75.Estilos para el parrafo 6*/
.texto6{
    font-size: 12pt;
    font-family: 'Times New Roman', Times, serif;
    text-align: start;
    color: white; 
}


/*COSTA*/
/*77. Fondo de color negro*/
.negro1{
    background-color: black;
}

/*78. Formato para el titulo de la costa*/
.tituloC{
    text-align: center;
    color: rgb(250, 250, 7);
    font-size: 35pt;
    font-family: 'Times New Roman';
}

/*79. Formato para separador*/
.divicion{
    background-color: white;
    color: white;
}

/*80. Formato para los textos dentro de la etiqueta p*/
.textoc1{
    color: white;
    text-align: justify;
    font-family: Arial;
    font-size: 12pt;
}

/*81. Formato para los titulos dentro de las wtiquetas h3*/
h3{
    color: rgb(163, 238, 13);
    font-family: Georgia;
    text-align: left;
    font-size: 16pt;
}

/*82. Posicionamiento y estilo del texto*/
#text {
    width: 68%;
    float: left;
}

/*83. Posicionamiento y estilo de la Columna2 imagen*/
#col {
    width: 28%;
    float: left;
}

/*SIERRA*/

/*84. Formato de borde par alas imagenes*/
.bordei{
    border-color: rgb(255, 255, 255);
    border-style: double;
}
/*85. Formato del titulo de la SIERA*/
.tituloS{
    text-align: center;
    color: brown;
    font-size: 35pt;
    font-family: 'Times New Roman';
}

/*86. FOrmato para los titulos en h3*/
.tit{
    color: rgb(15, 222, 230);
    font-family: Verdana;
    font-size: 18pt;
}

/*87. Pocicionamoento del texto*/
#text1p  {
    width: 68%;
    float: right;
}


/*88. Posicionamiento de la imagen*/
#col1p {
    width: 28%;
    float: left;

}

/*ORIENTE*/
/*89. Esitilo del texto para el contenido*/
.textos1{
    color: white;
    text-align: justify;
    font-family: Impact;
    font-size: 12pt;
}

/*90. Estilo para el titulo de la siera*/
.tituloO{
    text-align: center;
    color: green;
    font-size: 35pt;
    font-family: 'Times New Roman';
}

/*91. Estilos para los titulos de el oriente h3*/
.titO{
    font-size: 19pt;
    color: rgb(245, 190, 11);
    font-family: Times;
}

/*92. Texto y estilo para la informacion del oriente etiquetap */
.texO{
    color: white;
    font-family: Arial;
    font-size: 12pt;
}

/*93. Pocicionamiento de el texto en la pagina del oriente*/
#orip {
    width: 68%;
    float: left;
}

/*94. Posicion de las imagens en la pagina del oriente*/
#oripi {
    width: 28%;
    float: left;
}

/*INSULAR*/
/*95. Estilo para los titulos de oriente h1*/
.tituloI{
    text-align: center;
    color: rgb(1, 30, 196);
    font-size: 35pt;
    font-family: 'Times New Roman';
}

/*96. Formato para ls titulos de h2 en la pagina insular*/
.teinsular{
    font-family: Impact;
    font-size: 22pt;
    color: rgba(255, 167, 5, 0.904);
}

/*97. Estilos para el texto de insular*/
.tinsular{
    font-family: Georgia;
    font-size: 14pt;
    color: white;
    text-align: justify;
}

/*98. Estilos para h4 en el formato*/
h4{
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    color: tomato;
    text-align: justify;
    background-color: white;
}
/*99. Estilos para el footer de contacto*/
body > footer  {
    background-color: rgb(222,128,60);
    color: white;
    color: rgba(255, 255, 255, 0.7);
    font: normal small-caps bold 0.9em/3em
          Quicksand, Verdana, Geneva, sans-serif;
    text-align: center;
 }
```

## b. La evidencia del correcto diseño de las páginas HTML usando CSS. Para lo cuál, se puede generar fotografías instantáneas (pantallazos).⌨️

* Pagina index.html

![1](https://user-images.githubusercontent.com/34387442/67738065-545c4d00-f9db-11e9-941e-d35a3af1b273.png)

* Pagina turismo.html

![2](https://user-images.githubusercontent.com/34387442/67738189-9eddc980-f9db-11e9-88f4-ffa844657ce9.png)

* Pagina costa.html

![3](https://user-images.githubusercontent.com/34387442/67738234-bfa61f00-f9db-11e9-91fa-fcd22d00c34b.png)

* Pagina sierra.html

![4](https://user-images.githubusercontent.com/34387442/67738248-d187c200-f9db-11e9-80a3-93dea8c01104.png)

* Pagina oriente.html

![5](https://user-images.githubusercontent.com/34387442/67738256-dfd5de00-f9db-11e9-93a4-8079d8577a51.png)

* Pagina insular.html

![6](https://user-images.githubusercontent.com/34387442/67738264-ebc1a000-f9db-11e9-9968-3e850f4fdc9d.png)

* Pagina contacto.html

![7](https://user-images.githubusercontent.com/34387442/67738275-f9772580-f9db-11e9-88d8-df430f3e3b09.png)

## c. La evidencia de la validación de cada página HTML.⌨️

* Validacion de index.html

![7](https://user-images.githubusercontent.com/34387442/67738530-1102de00-f9dd-11e9-81a3-1619b3dfb003.png)

* Validacion de turismo.html

![8](https://user-images.githubusercontent.com/34387442/67738557-2546db00-f9dd-11e9-82a6-794949ea2503.png)

* Validacion de costa.html

![9](https://user-images.githubusercontent.com/34387442/67738583-3394f700-f9dd-11e9-9ccc-5912eec56167.png)

* Validacion de sierra.html

![10](https://user-images.githubusercontent.com/34387442/67738594-40194f80-f9dd-11e9-9b57-a8a3e9c11353.png)

* Validacion de oriente.html

![11](https://user-images.githubusercontent.com/34387442/67738604-4b6c7b00-f9dd-11e9-8120-10e9f7557a83.png)

* Validacion de insular.html

![12](https://user-images.githubusercontent.com/34387442/67738619-59220080-f9dd-11e9-8712-e211020858d7.png)

* Validacion de contacto.html

![13](https://user-images.githubusercontent.com/34387442/67738630-6212d200-f9dd-11e9-9e36-2b068b049d11.png)

## d. La evidencia de la validación de las hojas de estilos CSS.⌨️

## e. El informe debe incluir conclusiones apropiadas.⌨️
### Concluciones
```
•	Al crear estilos con archivos CSS nos permite tener una mejor organización al momento de querer dar un formato o diseño a nuestra página web.
•	Al manejar clases id, seudo clases esto nos permite organizar mejor los estilos de nuestras etiquetas para que estas puedan ser llamadas sin necesidad de cambiar el formato de una sección que no deseemos.
•	Manejar de mejor forma las opciones que permiten dar forma a la pagina nos da una idea clara y se adquiere un conocimiento mas avanzado al momento de diseñar otras paginas esto ya que gracias a las opciones de desarrollador de nuestro navegador nos permite modificar y ver el resultado sin necesidad de cambiar en nuestro código.
```
