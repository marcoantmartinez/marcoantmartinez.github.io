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
    <span> Sesión IV - Proyecto</span> 
    </div>
    <div class="fonth1subtittle">
    <span> Misión Imposible </span> 
    </div>
</h1>

<div style="text-align: center" ><a  href=""><img src="http://i.imgur.com/3brNg5um.jpg"/></a></div>

En está sesión de proyecto se aplicará el **Proceso de Pensamiento Computacional** promoviendo la resolución de problemas mediante el análisis, el diseño de soluciones reales y poniéndolas a prueba.

El alumno demostrará su autonomía para analizar, diseñar, construir y probar el proyecto, demostrando los conocimientos técnicos adquiridos en la sesión previa, donde se expuso al teoría sobre los **Sensores Analógicos y Digitales** y cómo usar las librerías de Bitbloq para realizar aplicaciones en Arduino.

Al termino del proyecto el alumno **documentará y compartirá** su trabajo en la nube con el aula. También se realizará una **evaluación** de conocimientos con un **examen tipo test**.

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
- Componente Potenciómetro.
- Componente LDR.
- Componente Pulsador.
- Componente Sensor IR.
- Puntero Láser (2 ó 4).
- Pizarra y proyector.

<h2>
    <div id="resumen-de-leccion" class="fonth2tittle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-list-ol fa-stack-1x colortools" ></i>
        </span> Resumen de lección
    </div>
</h2>

- Exposición del reto
- Asimilación del contenido 
- Análisis de necesidades
- Generación de ideas para solución
- Diseño del diagrama de flujo
- Desarrollo de programa con bloques
- Construcción del prototipo
- Prueba del prototipo
- Documentación y compartir el prototipo.
- Documentación de Mejoras y otras aplicaciones del prototipo
- Auto valoración del proyecto por el alumno


<h2>
    <div id="objetivos-de-aprendizaje" class="fonth2tittle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-crosshairs fa-stack-1x colortools" ></i>
        </span> Objetivos de aprendizaje
    </div>
</h2>

- Construir de forma autónoma el prototipo con calidad y buen funcionamiento
- Desarrollar el programa de bloques con la menor complejidad posible
- Aplicar los pasos del método de "Pensamiento Computacional"
- Documentar y publicar el proyecto con calidad para que otros puedan utilizarlo
- Ser creativo en la solución o ampliando el alcance del proyecto


<h2>
    <div id="aplicaciones-transversales" class="fonth2tittle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-random fa-stack-1x colortools" ></i>
        </span>  Aplicaciones Transversales
    </div>
</h2>

- Tecnologías de Información - Programación, control por eventos.
- Física - Analógico, Digital, Luz visible, Luz infrarroja,  Resistencia eléctrica, Precisión.
- Matemáticas - Regla de 3 (operación mapeo), Resolución.


<h2>
    <div id="inicio" class="fonth2tittle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-power-off fa-stack-1x colortools" ></i>
        </span>  Inicio
    </div>
</h2>

<div style="text-align: center" ><a  href=""><img src="http://i.imgur.com/q4sutpe.jpg"/></a></div>


- Se expone el enunciado de forma simple: "**Queremos un prototipo que sea capaz de activar la detección de luz láser roja y que al interrumpirse la detección de luz láser, salte una alarma visual y sonora. Al desactivar el detector se notificará el número de interrupciones de luz, que se han producido**".

<div class="success">
En este proyecto el alumno previsiblemente encontrará varias dificultades de orden técnico: 

- Relativa a la acumular el dato de las alarmas producidas para posteriormente presentarlo.
- Relativa al momento en el que se detecta la pulsación del botón, si se hace when_press dará más problemas que si se hace when_release, por ejemplo al desactivar la alarma, si usan el método when_press la alarma podría volver a activarse si la pulsación no es rápida.
- Relativa a conseguir la entonación, cadencia y repetición para producir un sonido de alarma con el buzzer.
- Relativa a la correcta incidencia del laser en la LDR.
- Relativa al ajuste del umbral de señal de Luz que debe medir el circuito LDR, pues debe tener en cuenta las condiciones de Luz ambiental máxima.
- Relativa al funcionamiento del LDR, más intensidad luz, menos resistencia = menos voltaje.

</div>

<h2>
    <div id="desarrollo" class="fonth2tittle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-film fa-stack-1x colortools" ></i>
        </span>  Desarrollo
    </div>
</h2>

- Se promueve el análisis de necesidades : se les pide que elaboren una lista de problemas a resolver. Tras un tiempo de reflexión se pone en común en la pizarra.

- Se promueve el diseño del diagrama de flujo : Tras un tiempo de reflexión se pone en común en la pizarra. Es importante que tengan claro que el diseño es mejorable y que si quieren lo pueden hacer.

<div style="text-align: center" ><img src="https://cdn.rawgit.com/marcoantmartinez/marcoantmartinez.github.io/1eea74e5/bitbloq/doc/impossible_mission.svg" alt=""></div>

- Se comienza el desarrollo en bitbloq : modelando el prototipo y programando los bloques.

<div style="text-align: center" ><a href=""><img src="http://i.imgur.com/AMGULBe.png"/></a></div>

- Se realizan las conexiones del prototipo y se realizan las pruebas.

<div style="text-align: center" ><a href=""><img src="http://i.imgur.com/L0aVnyz.png"/></a></div>

- Se procede a la documentación detallada del proyecto en Bitbloq en el apartado del información.

<div style="text-align: center" ><a href=""><img src="http://i.imgur.com/tGdiiz7.png"/></a></div>

- Se comparte públicamente el proyecto con la comunidad del usuarios de BitBloq. 

<h2>
    <div id="puesta-en-comun" class="fonth2tittle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-users fa-stack-1x colortools" ></i>
        </span>  Puesta en Común
    </div>
</h2>

Pedimos a los alumnos reflexionar sobre:
- ¿ Qué complicaciones han surgido ? ¿ Cómo las han resuelto ?
- Imaginar que cosas se podrían hacer con un potenciómetro.
- Imaginar que cosas se podrían hacer con una LDR.
- Imaginar que cosas se pueden hacer con un botón.
- Imaginar que cosas se pueden hacer con un sensor infrarrojo.
- Imaginar que otros sensores se podrían utilizar.
- ¿Es sencillo o complicado hacer lo que imaginan?

**Conclusión**:
>- Las computadoras necesitan traducir los valores analógicos de la naturaleza a digital.
>- Se pueden utilizar muchos sensores digitales y analógicos.
>- Arduino puede leer sensores digitales y analógicos.


<h2>
    <div id="reto" class="fonth2tittle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-trophy fa-stack-1x colortools" ></i>
        </span>  Reto
    </div>
</h2>

<br>Desarrollo del juego **Misión Imposible**</br>

>- ¿ Qué criterio debemos emplear para incrementar el contador de alarma ?
>- ¿ Qué información podemos añadir al contador de alarmas ?
>- ¿ Qué pasa si ponemos varios espejos para hacer rebotar la luz del láser ?</br>
>- ¿ Qué otros usos se pueden dar a este circuito ?

<br></br>

<h2>
    <div id="evaluacion" class="fonth2tittle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-check-square-o fa-stack-1x colortools" ></i>
        </span>  Evaluación
    </div>
</h2>

Al termino de la sesión se evaluará con un test de 10 preguntas la asimilación de conocimientos de cada alumno.

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