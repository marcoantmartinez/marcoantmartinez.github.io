<!---
edited  : Marco Antonio Martínez Ramos
email   : marcoantmartinez@gmail.com
release : 2017.04.01 v01
review  : na
github  : https://github.com/marcoantmartinez/marcoantmartinez.github.io/tree/master/bitbloq
license : CC BY-SA This learning resource is provided for free by marcoantmartinez@gmail.com under a Creative Commons Attribution-ShareAlike 4.0 International License.
others  : Bitbloq is a project provided for free by BQ (c)
-->

<div id="div_exterior" class="fontbody" > 

<div class="fontheader" >
	<a  style="color:#ffffff;" href="http://bitbloq.bq.com" title="View this resource on Bitbloq site">Bitbloq is a project provided for free by BQ (c)</a>
</div>

<div class="bannerheader">
	<a href="a" target="_blank">
	    <img src="http://i.imgur.com/vSK3EZk.jpg" alt="">
	</a>

<div class="bannerfooter">

<h1>
    <div class="fonth1tittle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-sitemap fa-stack-1x colortools"></i>
        </span> 
        Programación y Robótica con Arduino
    </div>
</h1>

<div class="linksheader">
	<a href="#recursos-necesarios"><i class="fa fa-check-square-o"></i> Recursos</a> |
	<a href="#resumen-de-leccion"><i class="fa fa-check-square-o"></i> Resumen</a> |
	<a href="#objetivos-de-aprendizaje"><i class="fa fa-check-square-o"></i> Objetivos</a> |
	<a href="#aplicaciones-transversales"><i class="fa fa-check-square-o"></i> Transversales</a> |
	<a href="#inicio"><i class="fa fa-check-square-o"></i> Inicio</a> |
	<a href="#desarrollo"><i class="fa fa-check-square-o"></i> Desarrollo</a> |
	<a href="#puesta-en-comun"><i class="fa fa-check-square-o"></i> En común</a> |
	<a href="#reto"><i class="fa fa-check-square-o"></i> Reto</a> |
	<a href="#evaluacion"><i class="fa fa-check-square-o"></i> Evaluación</a>
</div>

<h1>
    <div class="fonth1subtittle">
<span> Sesiones I y II - Test de Comprensión</span> 
    </div>
    <div class="fonth1subtittle">
    <span> Bloques de Control </span> 
    </div>
</h1>

A continuación se presentan algunas preguntas para comprobar la comprensión de la lección **"Sensores Analógicos y Digitales"**.

<div class="warning">

**Reglas del test :**
>- Este test cuenta para la calificación del curso.
>- Se dispone de 20 min para realizar el test.
>- Puedes saltar las preguntas y volver a ellas más tarde si lo deseas.
>- Se dispone de un único intento para realizar este test.
>- Cada pregunta acertada otorgará 1 punto. 
>- Si no contestas la pregunta o eliges la respuesta incorrecta, sumarás 0 puntos.
</div>



<div class="fonttest">

## **Pregunta 1**
Hemos visto el concepto de Algoritmo y cómo se aplica a la programación con Arduino.

<div style="text-align: center" ><img style="width:50%" src="http://i.imgur.com/WIEJ8pZ.png"/><img style="width:50%; height: 325px" src="http://i.imgur.com/4tu7z8C.png"/></div>
<div style="font-weight:300;">
En la definición formal de algoritmo que se presenta a continuación, rellena los huevos que faltan con la palabra oportuna:
</div>
<div class="fontdefinition">

Un algoritmo es un conjunto de ==**[A] &#160; &#160; &#160;**== bien definidas, ordenadas, conectadas y finitas que permiten llevar a cabo una ==**[B] &#160; &#160; &#160;**== determinada. Se puede representar un algoritmo empleando un diagrama de ==**[C] &#160; &#160; &#160;**== . Arduino procesa algoritmos escritos en código fuente o en ==**[D] &#160; &#160; &#160;**==  del Bitbloq.
</div>
</div><br>
<div style="margin-left:5%; line-height: 40px;">
	<form action="">
		<strong> [A] </strong>&#160; &#160; &#160;
		<label class="checkbox-inline"><input type="radio" name="a" value="a"> conexiones &#160; &#160; &#160;</label>
		<label class="checkbox-inline"><input type="radio" name="a" value="a" > pruebas &#160; &#160; &#160;</label>
		<label class="checkbox-inline"><input type="radio" name="a" value="a" > instrucciones &#160; &#160; &#160</label>
	</form>
	<form action="">
		<strong> [B] </strong>&#160; &#160; &#160;
		<label class="checkbox-inline"><input type="radio" name="a" value="a"> capacidad &#160; &#160; &#160;</label>
		<label class="checkbox-inline"><input type="radio" name="a" value="a" > tarea &#160; &#160; &#160;</label>
		<label class="checkbox-inline"><input type="radio" name="a" value="a" > ampliación &#160; &#160; &#160;</label>
	</form>
	<form action="">
		<strong> [C] </strong>&#160; &#160; &#160;
		<label class="checkbox-inline"><input type="radio" name="a" value="a"> fluencia &#160; &#160; &#160;</label>
		<label class="checkbox-inline"><input type="radio" name="a" value="a" > decisión &#160; &#160; &#160;</label>
		<label class="checkbox-inline"><input type="radio" name="a" value="a" > flujo &#160; &#160; &#160;</label>
	</form>
	<form action="">
		<strong> [D] </strong>&#160; &#160; &#160;
		<label class="checkbox-inline"><input type="radio" name="a" value="a"> componentes &#160; &#160; &#160;</label>
		<label class="checkbox-inline"><input type="radio" name="a" value="a" > bloques &#160; &#160; &#160;</label>
		<label class="checkbox-inline"><input type="radio" name="a" value="a" > controles &#160; &#160; &#160;</label>
	</form>
</div>


<br>
<br>
<div class="fonttest">

## **Pregunta 2**
Arduino a través de su Puerto Serie puede recibir y enviar datos, de y hacia otros dispositivos, respectivamente. Revisa cuidadosamente el siguiente programa que envía datos por el puerto serie.

<div style="text-align: center" ><img style="" src="http://i.imgur.com/roMSrKb.png"/></div>
<div style="font-weight:300;">

A continuación te mostramos cuatro líneas de la salida de texto de Monitor del Puerto Serie, ¿ Cuál de las siguientes salidas de texto, observaremos cuando activemos el **Monitor del Puerto Serie** ? (elige la opción correcta)
</div>
</div><br>
<div style="margin-left:5%; line-height: 40px;">
	<form action="">
		 <input type="radio" name="gender" value="male"> a.&#160; &#160; &#160;<img style="height: 70px" src="http://i.imgur.com/YakDSU3.png"/><hr><br>
		 <input type="radio" name="gender" value="female"> b.&#160; &#160; &#160;<img style="height: 70px" src="http://i.imgur.com/KFZy6rO.png"/><hr><br>
		<input type="radio" name="gender" value="other"> c.&#160; &#160; &#160;<img style="height: 70px" src="http://i.imgur.com/B8OuWMF.png"/> <hr><br>
		<input type="radio" name="gender" value="other"> d. &#160; &#160; &#160;<img style="height: 70px" src="http://i.imgur.com/tN3pfJk.png"/> 
	</form>
</div>


<br>
<br>
<div class="fonttest">

## **Pregunta 3**
Una Variable es un nombre simbólico que le damos a un espacio reservado en la memoria del ordenador para almacenar un dato. Hemos realizado un pequeño programa con el que hacemos sumas y restas de cuatro variables, revisalo cuidadosamente.

<div style="text-align: center" ><img style="height:400px" src="http://i.imgur.com/5PrwMCR.png"/></div>
<div style="font-weight:300;">
Cual será el valor de salida que observemos el puerto serie. (elige una opción correcta)
</div>
</div><br>
<div style="margin-left:5%; line-height: 40px;">
	<form action="">
		<input type="radio" name="vehicle" value="Bike"> a.-&#160; &#160; &#160; 1<br>
		<input type="radio" name="vehicle" value="Bike"> b.-&#160; &#160; &#160; 11<br>
		<input type="radio" name="vehicle" value="Bike"> c.-&#160; &#160; &#160; 3<br>
		<input type="radio" name="vehicle" value="Bike"> d.-&#160; &#160; &#160; 5<br>
	</form>
</div>


<br>
<br>
<div class="fonttest">

## **Pregunta 4**
***
Uno de los circuitos más sencillos que se puede hacer con Arduino es encender y apagar un diodo LED (Diodo Emisor de Luz).

<div style="text-align: center" ><img style="" src="http://i.imgur.com/jLLRD7i.png"/></div>
<div style="text-align: center" ><img style="" src="http://i.imgur.com/sAyxvwy.jpg"/></div>
<div style="font-weight:300;">
Aunque existen mucho modelos y formas, comparten muchas características, indica cuales de las características mencionadas abajo son típicas de un Diodo LED: 
</div>
</div><br>
<div style="margin-left:5%; line-height: 40px;">
	<form action="">
		<input type="checkbox" name="vehicle" value="Bike"> a.- Necesitan una resistencia en serie para limitar la corriente y no quemarse.<br>
		<input type="checkbox" name="vehicle" value="Bike"> b.- Todos los modelos emiten luz visible al ojo humano<br>
		<input type="checkbox" name="vehicle" value="Bike"> c.- Su conexión no se ve afectada por la polaridad<br>
		<input type="checkbox" name="vehicle" value="Bike"> d.- Las TV, Tablets y Smartphone más modernos tienen millones de LED formando Pixels<br>
	</form>
</div>


<br>
<br>
<div class="fonttest">

## **Pregunta 5**
Arduino es capaz de medir intervalos de tiempo que suceden durante la secuencia de instrucciones. Revisa cuidadosamente el código que exponemos a continuación que aprovecha está capacidad de Arduino.

<div style="text-align: center" ><img style="" src="http://i.imgur.com/klARPaF.png"/></div>
<div style="font-weight:300;">
Una vez analizado el código, queremos saber que les sucede los valores de las variables A y B al terminar el programa. ¿ cual de las siguientes afirmaciones es correcta ? (elige una respuesta)
</div>
</div><br>
<div style="margin-left:5%; line-height: 40px;">
	<form action="">
		<input type="radio" name="vehicle" value="Bike"> a.- La variable A y B tendrán el mismo valor, pues obtienen tiempo de la misma línea de ejecución<br>
		<input type="radio" name="vehicle" value="Bike"> b.- La variable B valdrá 1000 veces la A, pues hay un periodo de 1000 repeticiones entre ellas<br>
		<input type="radio" name="vehicle" value="Bike"> c.- B = A + 1000<br>
		<input type="radio" name="vehicle" value="Bike"> d.- La variable B será mayor que la variable A<br>
	</form>	
</div>

<br>
<br>
<div class="fonttest">

## **Pregunta 6**
Arduino dispone de una instrucción para generar números aleatorios, mira cuidadosamente el código que hemos realizado con el bloque [Aleatorio entre] de Bitbloq (random en código nativo)

<div style="text-align: center" ><img  src="http://i.imgur.com/XST7Tx6.png"/></div>

<div style="font-weight:300;">
Ahora arrancamos el programa y queremos saber aproximadamente tardará el LED en encenderse desde que Arduino detecta que hemos pulsado el botón. (elige una respuesta)
</div>
</div><br>
<div style="margin-left:5%; line-height: 40px;">
	<form action="">
		<input type="radio" name="gender" value="female"> a. - Entre 30 y 60 segundos <br>
		<input type="radio" name="gender" value="female"> b. - Más de 30 segundos<br>
		<input type="radio" name="gender" value="male"> c. -  Menos de 60 segundos<br>
		<input type="radio" name="gender" value="female"> d. - Inmediatamente <br>		
	</form>
</div>



<br>
<br>
<div class="fonttest">

## **Pregunta 7**
Estamos probando el bloque de control [mientras] (while en codigo nativo) de Bitbloq.

<div style="text-align: center" ><img style="width:30%" src="http://i.imgur.com/z4wiLDv.png"/><img style="width:70%" src="http://i.imgur.com/nq34yLS.png"/></div>

<div style="font-weight:300;">
Ahora queremos saber cual de las siguientes afirmaciones es la correcta: (elige una respuesta)
</div>
</div><br>
<div style="margin-left:5%; line-height: 40px;">
	<form action="">
		<input type="radio" name="gender" value="female"> a. - El LED se apagará en cuanto bajemos el botón <br>
		<input type="radio" name="gender" value="female"> b. - El LED se apagará cuando completemos dos pulsaciones del botón<br>
		<input type="radio" name="gender" value="male"> c. -  El LED no se apagará, pues el botón no puede tener al mismo tiempo valor false y true <br>
		<input type="radio" name="gender" value="female"> d. - El LED se apagará al completar una pulsación del botón<br>		
	</form>
</div>


<br>
<br>
<div class="fonttest">

## **Pregunta 8**
Revisa con cuidado el siguiente código:

<div style="text-align: center" ><img style="" src="http://i.imgur.com/FBvSi4g.png"/></div>

<div style="font-weight:300;">

Indica cual de las siguientes salidas de texto, se vera en el puerto cuando termine el programa.
</div>
</div><br>
<div style="margin-left:5%; line-height: 40px;">
	<form action="">
		<input type="radio" name="gender" value="female"> a. - "A es igual o menor que B"<br>
		<input type="radio" name="gender" value="female"> b. - "A es mayor que B"<br>	
	</form>
</div>


<br>
<br>
<div class="fonttest">

## **Pregunta 9**
Revisa cuidadosamente los dos códigos que se presentan a continuación:

<div style="text-align: left" >
	Código A :<br> <img style="" src="http://i.imgur.com/W6HmG42.png"/><br>
	Código B : <br> <img style="height: 400px" src="http://i.imgur.com/kxK7Pyq.png"/>
</div>

<div style="font-weight:300;">
¿ Encienden el LED bajo las mismas condiciones ? (elige una respuesta)
</div>
</div><br>
<div style="margin-left:5%; line-height: 40px;">
	<form action="">
		<input type="radio" name="gender" value="female"> a. - No <br>
		<input type="radio" name="gender" value="female"> b. - Sí <br>
	</form>
</div>


<br>
<br>
<div class="fonttest">

## **Pregunta 10**

<div style="text-align: center" ><img style="" src="http://i.imgur.com/oVb3ykm.png"/></div>
Un alumno ha realizado un prototipo que ayuda a su padre en el taller añadiendo seguridad a una máquina. Mira cuidadosamente el código del prototipo:

<div style="text-align: center" ><img style="" src="http://i.imgur.com/a3BRj1O.png"/></div>

<div style="font-weight:300;">

El prototipo tiene conectado un **Relé** que abre y corta la corriente de una **potente sierra eléctrica**. Su padre le ha pedido que cuando pulse el **boton_On** la sierra **se ponga en marcha**, y que cuando pulse el **boton_Off** la sierra **se apague** y que permanezca **apagada 2 minutos**, y que durante esos dos minutos si pulsamos el **boton_On** este no haga nada. <br><br>
¿ Cumple el prototipo con las especificaciones del padre ? (elige una respuesta)
</div>
</div><br>
<div style="margin-left:5%; line-height: 40px;">
	<form action="">
		<input type="radio" name="gender" value="female"> a. - Sí<br>
		<input type="radio" name="gender" value="female"> b. - A medias<br>
		<input type="radio" name="gender" value="male"> c. -  No <br>		
	</form>
</div>


<br>
<br>

***
<div class="fontfooter">
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
	<img alt="Creative Commons License" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" />
</a></br>This learning resource is provided for free by 
<a rel="email" href="marcoantmartinez@gmail.com">marcoantmartinez@gmail.com</a> under a 
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
</br>
<a href="https://github.com/marcoantmartinez/marcoantmartinez.github.io/tree/master/bitbloq" title="View and edit this resource on GitHub">
	<img  src="https://gp3.googleusercontent.com/wtHpmmmue7Q9JT9JYxJ1AUgPKhzA0kZlSIiiYGFjJvvzqqrBaefU01uKg-CGJsUZk8Mxk1tQsiuY6DSHMhcrsZuP6z55YHWwvKECmG3BTzsyoHO03l-AMYwHiZ3Lyd_YZ9cUjA=s32-p-k" alt=""><br>View and edit this resource on GitHub 
</a>
</div>

</div>
</div>
</div>
<details>
	<style>
		.bannerheader{
			width:100%; 
			margin: 0 auto;
			display: table; 
			min-width: 900px; 
			max-width: 900px; 
			background-color:#ffffff; 
			border:10px solid #96c93e;
		}
		.bannerfooter{
			width:100%;
			background:#ffffff; 
			padding: 5%;
			position:relative; 
			top:0;  
			left:0; 
			background-image: url("http://i.imgur.com/EnY10RD.png"); 
			background-repeat: no-repeat ;
			-webkit-background-size: cover;
			-moz-background-size: cover;
			-o-background-size: cover; 
        /*background-size:100% auto; */
			background-position: bottom;
		}
		.linksheader{
			padding:10px;
			text-align:center; 
			font-size:14px; 
			color:#729e29
		}
		.fontnotes{
			width:80%;
            border-radius: 15px;
			margin-left:5%; 
			margin-right:auto;
			border-radius: auto;
			text-align:left;
			background-color:#ffffff;
			padding: 5px;
			font-family: 'Roboto Slab', serif; 
			font-size: 18px; 
			font-weight: 700; 
			letter-spacing: 0px
		}
		.fontbody{
			width: 100%; 
			overflow: auto; 
			background-color: #ffffff; 
			position: absolute; 
			top: 0px; 
			left: 0px; 
			font-size: 20px; 
			font-family: 'Roboto Light', sans-serif ; 
			font-weight: lighter; 
			letter-spacing: 0px;
			line-height: 25px;
			margin: 0 0; 
		}
		.fonth1tittle{
			position:absolute;
			left:0%;
			top:-6px;
			width:100%; 
			border-radius: 0px;
			padding:0px;
			background: linear-gradient(to right, #96c93e, #96c93e 100%);
			line-height:0px;
			color:#ffffff;
			font-family:'Roboto Slab', serif;
			font-size:36px; 
			font-weight:700;
			text-align: center;
			border:0px solid blue;
		}
		.fonth1subtittle{
			position:relative;
			left:0px;
			top:0px;
			width:100%; 
			border-radius: 0px;
			padding:0px;
			background: linear-gradient(to right, white, white 100%);
			line-height:0px;
			color: #5e8421;
			font-family:'Roboto Slab', serif;
			font-size:36px; 
			font-weight:700;
			text-align: center;
			border:30px solid white;
		}
		.fonth2tittle{
			position:relative;
			left:-5%;
			width: 75%;
			border-radius: 15px;
			padding:0px; 
			background-color: #96c93e;
			line-height:0;
			color:#ffffff; 
			font-family:'Roboto Slab', serif;
			font-size:23px; 
			font-weight:700;
		}
		.fonth3tittle{
			position:relative;
			left:5%;
			width: 75%;
			border-radius: 0px;
			padding:20px; 
			background-color: #ffffff;
			line-height:0;
			color:#5e8421; 
			font-family:'Roboto Slab', serif;
			font-size:23px; 
			font-weight:700;
			border-bottom:1.5px solid #96c93e;
		}
		.fontheader{
			width:50%;
			margin: 0 auto;
			position: absolute;
			left: 25%; 
			top:5px; 
			border:0px solid #000000;
			text-align: center; 
			color:#476419;
			font-family: Roboto, serif; 
			font-size: 13px; 
			font-weight: 300; 
			letter-spacing: 0px
		}
		.fontfooter{
			width:52%;
			margin: 0 auto;
			text-align: center; 
			color: #729e29; 
			font-family: Roboto, serif; 
			font-size: 13px; 
			font-weight: 300; 
			letter-spacing: 0px
		}
		.colortools{
			color:#5e8421;
		}
		.colornotes{
			color:#ff8000;
		}
		.fontlittle{
            font-family:'Roboto Slab', sans-serif;
            font-size:18px; 
            font-weight:300;
            letter-spacing: 0px;
            line-height: 20px;
		}
		.fonttest{
			border-radius: 23px;
			padding:20px;
			background-color: rgba(225, 225, 225, .5);
            font-family:'Roboto Slab', sans-serif;
            font-size:23px; 
            font-weight:700;
            letter-spacing: 0px;
            line-height: 30px;
		}
		.fontdefinition{
			border-radius: 23px;
			padding:20px;
			background-color: #ffffff;
			color: green;
            font-family:'Roboto Slab', sans-serif;
            font-style: italic;
            font-size:23px; 
            font-weight:300;
            letter-spacing: 0px;
            line-height: 30px;
		}
	</style>
</details>
<link href="https://fonts.googleapis.com/css?family=Roboto+Slab:100,300,400,700|Roboto:100,100i,300,300i,400,400i,500,500i,700,700i,900,900i" rel="stylesheet" type='text/css'>
<!-- <link href="https://github.com/marcoantmartinez/marcoantmartinez.github.io/blob/master/bitbloq/html/mystyles.css" rel="stylesheet" type="text/css" media="screen"/> 
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
 -->