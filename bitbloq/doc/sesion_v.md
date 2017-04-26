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
            <i class="fa fa-microchip fa-stack-1x colortools"></i>
        </span> 
        Programación y Robótica con Arduino
    </div>
</h1>

<div class="linksheader">
	<a href="#recursos-necesarios"><i class="fa fa-check-square-o"></i> Recursos</a> |
	<a href="#resumen-de-leccion"><i class="fa fa-check-square-o"></i> Resumen</a> |
	<a href="#objetivos-de-aprendizaje"><i class="fa fa-check-square-o"></i> Actividad</a> |
	<a href="#aplicaciones-transversales"><i class="fa fa-check-square-o"></i> Transversal</a> |
	<a href="#inicio"><i class="fa fa-check-square-o"></i> Inicio</a> |
	<a href="#desarrollo"><i class="fa fa-check-square-o"></i> Desarrollo</a> |
	<a href="#puesta-en-comun"><i class="fa fa-check-square-o"></i> En común</a> |
	<a href="#reto"><i class="fa fa-check-square-o"></i> Reto</a> |
	<a href="#evaluacion"><i class="fa fa-check-square-o"></i> Evaluación</a>
</div>

<h1>
    <div class="fonth1subtittle">
    <span> Sesión V : Actuadores </span> 
    </div>
</h1>


<br>En esta lección los estudiantes aprenderán como funcionan los componentes electrónicos actuadores de Arduino; así como a ser creativos con sus posibles usos, también que sistemas se utilizan para traducir las señales de los pines digitales de salida, a sonido, luz, movimiento ... etc.</br> 
<br>Finalmente serán capaces de construir el proyecto **Comprobador de pilas** que también puede ser empleado como Voltímetro.</br>



<h2>
    <div id="recursos-necesarios" class="fonth2tittle">
        <span class="fa-stack fa-lg" >
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-wrench fa-stack-1x colortools"  ></i>
        </span> Recursos necesarios
    </div>
</h2>

- Cuentas de Bitbloq activadas para los alumnos - grupos
- Placa Arduino UNO (o superior) con alimentación y conector USB (por alumno o grupo)
- Componente Relé
- Componente Servomotor.
- Componente Servomotor continuo.
- Componente LED RGB.
- Componente Zumbador (Buzzer).
- Pizarra y proyector.


<h2>
    <div id="resumen-de-leccion" class="fonth2tittle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-list-ol fa-stack-1x colortools" ></i>
        </span> Resumen de lección
    </div>
</h2>

- Qué se un actuador
- Que es la corriente eléctrica y cómo se presenta
- Cómo se utiliza el electromagnetismo para conseguir movimiento
- Cómo se usa la señal PWM para controlar actuadores
- Cómo se compone el color con un dispositivo RGB
- Cómo se reproduce el sonido digitalmente
- Circuitos de componentes actuadores digitales


<h2>
    <div id="objetivos-de-aprendizaje" class="fonth2tittle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-crosshairs fa-stack-1x colortools" ></i>
        </span>  Contenidos y Actividades de aprendizaje
    </div>
</h2>

- **Entender que es un "actuador"** en el amplio sentido de la palabra. Recalcar que Arduino sólo conecta actuadores a los pines digitales de salida. Indagar sobre artefactos cotidianos capaces de llevar a cabo interacciones físicas (iluminar, sonar, mover ... etc). ==Las señales eléctricas se convierten en luz, sonido, movimiento ... (otros tipos de energía) mediante los "actuadores"==

- **Ser capaz de distinguir distintos "actuadores".** ¿ Todos los "actuadores" pueden ser conectados comandados por Arduino ? ¿ Qué se necesita para que un actuador se pueda conectar a Arduino ?

<div style="text-align: center" ><img style="width:50%" src="http://i.imgur.com/ZHRWdfS.png"/><img style="width:50%" src="http://i.imgur.com/8Y1TCPg.png"/></div><br>

- **Entender la corriente alterna, continua y cuadrada** . AC / DC / +Vcc / Gnd - masa - tierra - 0v / +5 Vcc 

<div style="text-align: center" ><img style="width:50%" src="http://i.imgur.com/bMS3aPJ.png"/><img style="width:50%" src="http://i.imgur.com/0QMnhfJ.gif"/></div>
<br>

- **Entender la señal PWM y sus aplicaciones.** La modulación de ancho de pulso se emplea para los servomotores de giro continuo y giro seleccionable.

<div style="text-align: center" ><img style="width:89%" src="http://i.imgur.com/9GiDnS5.png"/></div><br>
<div style="text-align: center" ><img style="width:89%;" src="http://i.imgur.com/QTmEH8R.jpg"/></div><br>

- **Entender el modelo de color RGB y cómo lo percibe el ojo.** Sensibilidad del ojo humano al color y la luz. Células Cono (~x6M) y Bastón (~x100M) de la retina (120ªx60ª=570 Megapixel). Creación del color por síntesis aditiva. Replicamos la naturaleza en las cámaras y pantallas.

<div style="text-align: center" ><img style="width: 350px; height: 350px" src="http://i.imgur.com/X3YxuVg.png"/><img style="width: 350px; height: 350px" src="http://i.imgur.com/QqF1nrW.jpg"/></div>
<div style="text-align: center" ><img style="width: 70%" src="http://i.imgur.com/sAyxvwy.jpg"/><img style="height: 145px" src="http://i.imgur.com/AbChmEL.jpg"/></div><br>



- **Entender el sonido y cómo se reproduce digitalmente.** Cómo funciona el oído humano. Series de Fourier o suma de señales para componer otra. Composición del sonido analógico. Efecto piezoeléctrico. Respuesta de un Zumbador a las distintas frecuencias.

<div style="text-align: center" ><img style="width:89%; height: 300px" src="http://i.imgur.com/6jqZRtO.png"/></div>
<div style="text-align: center" ><img style="width:89%; height: 300px" src="http://i.imgur.com/PrNb8kj.png"/></div>
<div style="text-align: center" ><img style="width:89%; height: 300px" src="http://i.imgur.com/2jNRIYX.png"/></div><br>

- **Entender el funcionamiento del componente RELÉ.** ¿ Qué es un Opto-Acoplador ? ¿ Cuándo utilizar la salida de pin digital Arduino y cuando un Relé ?

<div style="text-align: center" ><img style="width:70%" src="http://i.imgur.com/JebxOHl.png"/></div>
<div style="text-align: center" ><img style="width:50%" src="http://i.imgur.com/yuvg4Rf.png"/><img style="width:50%" src="http://i.imgur.com/AzKUzek.png"/></div><br>

- **Ser capaz de programar aplicaciones para un componente electrónico RELÉ.** Hemos visto que debido al opto-acoplador es igual que un diodo LED.

- **Entender el funcionamiento del componente servo continuo.** ¿ Por qué introducimos un bloque de espera entre las ordenes de giro ?

<div style="text-align: center" ><img style="width:35%" src="http://i.imgur.com/gJ7d8lu.png"/><img style="width:65%" src="http://i.imgur.com/5dlTISV.png"/></div><br>

- **Entender el funcionamiento del componente servomotor.**

<div style="text-align: center" ><img style="width:50%" src="http://i.imgur.com/ZHL0Pod.png"/><img style="width:50%" src="http://i.imgur.com/SQrPMz2.png"/></div><br>

- **Ser capaz de programar el posicionamiento de un servomotor.** Realizar un sencillo programa que a través del puerto serie de la Computadora se de la orden a Arduino de poner el brazo del servo en un ángulo determinado.

<div style="text-align: center" ><img style="" src="http://i.imgur.com/oba1azs.png"/></div><br>

- **Entender el funcionamiento del componente LED RGB.** Un LED RGB en realidad son 3 LEDs en la misma cápsula y se logra hacer la síntesis aditiva seleccionando a cuantos se encienden simultáneamente y por cuanto tiempo. ¿ Que hacemos para que brille menos ? Área media de la señal cuadrada.

<div style="text-align: center" ><img style="width:65%" src="http://i.imgur.com/8S8qvGJ.png"/><img style="width:35%" src="http://i.imgur.com/8Y1TCPg.png"/></div><br>

- **Ser capaz de programar colores diferentes con el LED RGB.** Realizar un sencillo programa que sea capaz de cambiar el color del LED RGB de Rojo a Verde a Azul, cuando un potenciómetro pase por las posiciones derecha, centro e izquierda respectivamente.


<div style="text-align: center" ><img style="" src="http://i.imgur.com/btjqcXY.png"/></div><br>

- **Entender el funcionamiento del componente Zumbador (Buzzer).**

<div style="text-align: center" ><img style="width:25%" src="http://i.imgur.com/ZHRWdfS.png"/><img style="width:75%" src="http://i.imgur.com/9lTIosb.png"/></div><br>

- Ser capaz de programar melodías con el componente Zumbador (Buzzer). Vamos a programar la partitura de la música [**Frère Jacques**](https://soundcloud.com/sonoma-entertainment/frere-jacques-mr-ray-the), sus notas musicales son :


		Frère Jacques Notes:

		C D E C C D E C
		E F G E F G
		G A G F E C G A G F E C
		C G C C G C

	Esta vez escribiremos el código en desarrollo tradicional utilizando la pestaña "Código" e introduciendo el siguiente "código escrito en Processing" :

	```arduino

	int sound = 9;

	void setup(){
	  pinMode(sound,OUTPUT);
	}

	void loop(){

	 tone(sound,261,500);//c 
	 delay(500);
	 noTone(sound);
	 tone(sound, 294,500);//d
	 delay(500);
	 noTone(sound);
	 tone(sound,329,500);//e
	 delay(500);
	 noTone(sound);
	 tone(sound,261,500);//c
	 delay(500);
	 tone(sound,261,500);//c 
	 delay(500);
	 noTone(sound);
	 tone(sound, 294,500);//d
	 delay(500);
	 noTone(sound);
	 tone(sound,329,500);//e
	 delay(500);
	 noTone(sound);
	 tone(sound,261,500);//c
	 delay(550);
	 noTone(sound);
	 tone(sound,329,500);//e
	 delay(500);
	 noTone(sound);
	 tone(sound,349,500);//f
	 delay(500);
	 noTone(sound);
	 tone(sound,392,500);//g
	 delay(550);
	 noTone(sound);
	 tone(sound,329,500);//e
	 delay(500);
	 noTone(sound);
	 tone(sound,349,500);//f
	 delay(500);
	 noTone(sound);
	 tone(sound,392,500);//g
	 delay(900);

	}
	```

	... ahora sólo queda completarlo, copiando y pegando lo que falta ... la nota que falta **a = 440**

<h2>
    <div id="aplicaciones-transversales" class="fonth2tittle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-random fa-stack-1x colortools" ></i>
        </span>  Aplicaciones Transversales
    </div>
</h2>

- Tecnologías de Información - Programación, actuadores PWM, mapeo de valores.

- Física - Corriente alterna, continua, conmutada, Luz y sonido.
- Matemáticas - Cálculo de área, área media, Regla de 3 (operación mapeo), Suma de señales.
- Biología - Oído y Ojo humano.
- Dibujo Técnico - Simbología técnica de los circuitos implicados.
- Música - Partituras


<h2>
    <div id="inicio" class="fonth2tittle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-power-off fa-stack-1x colortools" ></i>
        </span>  Inicio
    </div>
</h2>

- Pedir a los alumnos que piensen usos diarios de la electricidad.

- Con esa lista de usos, construir una lista paralela de actuadores que se vean implicados, clasificándola en el medio físico sobre el que actúan.

- Exponer fotografías de actuadores y preguntar por cual creen que es su uso. ¿ Cuántas aciertan ?

<div style="text-align: center" ><img style="height: 250px" src="http://i.imgur.com/BWsGDfZ.png"/><img style="width:33%" src="http://i.imgur.com/OJLsLYD.png"/><img style="width:33%" src="http://i.imgur.com/HizxEAU.png"/></div>
<div style="text-align: center" ><img style="width:33%" src="http://i.imgur.com/oX2CfBx.png"/><img style="width:33%" src="http://i.imgur.com/ruvAMk8.png"/><img style="width:33%" src="http://i.imgur.com/ja2V0V4.png"/></div>
<div style="text-align: center" ><img style="width:40%" src="http://i.imgur.com/UhSO9UC.png"/><img style="width:33%" src="http://i.imgur.com/g2MzOj1.png"/><img style="height: 250px" src="http://i.imgur.com/XD21WER.png"/></div>




<h2>
    <div id="desarrollo" class="fonth2tittle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-film fa-stack-1x colortools" ></i>
        </span>  Desarrollo
    </div>
</h2>

1. Arrancar el navegador Google Chrome e iniciar la sesión del BitBloq

2. Los alumnos - grupos, siguen las explicaciones e instrucciones del profesor, que utiliza como guía el programa de contenidos y ejercicios contenidos en el apartado "Contenidos y Actividades de Aprendizaje" de esta sesión.

3. Resolver las dudas de los alumnos según vayan apareciendo.


<h2>
    <div id="puesta-en-comun" class="fonth2tittle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-users fa-stack-1x colortools" ></i>
        </span>  Puesta en Común
    </div>
</h2>

- Imaginar que cosas se podrían hacer con un Relé.
- Imaginar que cosas se podrían hacer con un servomotor.
- Imaginar que cosas se podrían hacer con un LED RGB.
- Imaginar que cosas se pueden hacer con un Buzzer.
- Imaginar que cosas se pueden hacer con un sensor infrarrojo.
- Imaginar que otros actuadores se podrían utilizar.
- ¿Es sencillo o complicado hacer lo que imaginan?

**Conclusión**:
>- Las señales eléctricas se convierten en luz, sonido, movimiento ... (otros tipos de energía) mediante los "actuadores".

>- Se pueden utilizar muchos actuadores.

>- Arduino de serie sólo puede utilizar actuadores en los pines digitales.


<h2>
    <div id="reto" class="fonth2tittle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-trophy fa-stack-1x colortools" ></i>
        </span>  Reto
    </div>
</h2>

<br>Avance próxima sesión, desarrollo del prototipo - proyecto **Comprobador de pilas AAA y AA**</br><br>




<h2>
    <div id="evaluacion" class="fonth2tittle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-check-square-o fa-stack-1x colortools" ></i>
        </span>  Evaluación
    </div>
</h2>

El desempeño del alumno en esta jornada, se evaluará al termino de la próxima sesión **(VI)**; por una parte con un test de 10 preguntas para valorar asimilación de conocimientos de cada alumno y por otra parte con la rubrica de evaluación para valorar los objetivos competenciales, según el criterio del profesor.

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
	</style>
</details>
<link href="https://fonts.googleapis.com/css?family=Roboto+Slab:100,300,400,700|Roboto:100,100i,300,300i,400,400i,500,500i,700,700i,900,900i" rel="stylesheet" type='text/css'>
<!-- <link href="https://github.com/marcoantmartinez/marcoantmartinez.github.io/blob/master/bitbloq/html/mystyles.css" rel="stylesheet" type="text/css" media="screen"/> 
 -->