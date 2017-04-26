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
	<a href="#objetivos-de-aprendizaje"><i class="fa fa-check-square-o"></i> Actividad </a> |
	<a href="#aplicaciones-transversales"><i class="fa fa-check-square-o"></i> Transversal</a> |
	<a href="#inicio"><i class="fa fa-check-square-o"></i> Inicio</a> |
	<a href="#desarrollo"><i class="fa fa-check-square-o"></i> Desarrollo</a> |
	<a href="#puesta-en-comun"><i class="fa fa-check-square-o"></i> En común</a> |
	<a href="#reto"><i class="fa fa-check-square-o"></i> Reto</a> |
	<a href="#evaluacion"><i class="fa fa-check-square-o"></i> Evaluación</a>
</div>

<h1>
    <div class="fonth1subtittle">
    <span> Sesión III : Sensores Analógicos y Digitales </span> 
    </div>
</h1>


<br>En esta lección los estudiantes aprenderán como funcionan los componentes de sensores digitales y analógicos de Arduino; así como a ser creativos con sus posibles usos, también cómo traducir los valores digitales a analógicos y viceversa.</br> 
<br>Finalmente serán capaces de desarrollar el proyecto **Misión Imposible**.</br>


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
- Pizarra y proyector.

<h2>
    <div id="resumen-de-leccion" class="fonth2tittle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-list-ol fa-stack-1x colortools" ></i>
        </span> Resumen de lección
    </div>
</h2>

- ¿Que es un sensor?
- ¿Qué es analógico y que digital?
- Diferencias entre pin digital y analógico.
- Qué es la Precisión (Resolución).
- Componentes digitales y analógicos
- Componentes analógicos potenciómetro y LDR.
- Componentes digitales botón y sensor infrarrojo.


<h2>
    <div id="objetivos-de-aprendizaje" class="fonth2tittle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-crosshairs fa-stack-1x colortools" ></i>
        </span> Contenidos y Actividades de aprendizaje
    </div>
</h2>

- **Entender la diferencia entre analógico y digital.** Incidir en los aspectos de la precisión y la resolución. Qué es un ADC de 10 bit.

<div style="text-align: center" ><img style="width:60%" src="http://i.imgur.com/W7mcydS.jpg"/></div><br>

- **Ser capaz de distinguir diferentes componentes analógicos de los digitales.**

<div style="text-align: center" ><img style="width:100%" src="http://i.imgur.com/iGjIObe.png"/></div><br>

- **Entender el funcionamiento de un pin analógico y digital en Arduino.**

<div style="text-align: center" ><img style="width:100%" src="http://i.imgur.com/zEq4vZm.png"/></div>
<div style="text-align: center" ><img style="width:55%" src="http://i.imgur.com/VPNCLgO.png"/></div><br>

- **Entender la resolución y la operación matemática de mapeo.**

<div style="text-align: center" ><img style="width:80%" src="http://i.imgur.com/DDCN8Nr.png"/></div><br>

- **Entender el funcionamiento del componente potenciómetro.** Resistencia eléctrica y Ley de Ohm.

<div style="text-align: center" ><img style="width:35%" src="http://i.imgur.com/hgGXxVQ.jpg"/><img style="height: 270px" src="http://i.imgur.com/kgAQqE1.png"/><img style="width:33%" src="http://i.imgur.com/Jw1Nqfr.png"/></div>
<div style="text-align: center" ><img style="width:50%; height: 325px" src="http://i.imgur.com/YVBaGaB.jpg"/><img style="height: 325px" src="http://i.imgur.com/kGVXejO.gif"/></div><br>

- **Ser capaz de programar con el componente potenciómetro.** Realización de un programa simple que encienda un LED dado un determinado grado de giro del potenciómetro.

<div style="text-align: center" ><img style="width:80%" src="http://i.imgur.com/Q7EQ35I.png"/></div>

- **Entender el funcionamiento del componente LDR.** Que la variación de la resistencia eléctrica de una LDR a la luz depende de la composición química del semiconductor que la forma, dar ejemplos.

<div style="text-align: center" ><img style="width:100%" src="http://i.imgur.com/O8tAsqg.png"/></div>
<div style="text-align: center" ><img style="width: 50%" src="http://i.imgur.com/4tu7z8C.png"/><img style=" width: 50%" src="http://i.imgur.com/dHwZotf.jpg"/></div><br>

- **Ser capaz de programar con el componente LDR.** Realización de un programa simple que encienda un LED cuando se obscurezca la LDR.

<div style="text-align: center" ><img style="width:80%" src="http://i.imgur.com/UBmj3XP.png"/></div><br>

- **Entender el funcionamiento del componente Pulsador.** Entender la electrónica subyacente Pull-Up y Pull-Down del componente electrónico pulsador. Entender los niveles lógicos 0 y 1. Entender el efecto de Rebote.

<div style="text-align: center" ><img style="height: 325px" src="http://i.imgur.com/3Y6SHSi.png"/><img style=" height: 325px" src="http://i.imgur.com/RaPV8q9.png"/></div><br>

- **Ser capaz de programar when_pressed y when_released con el Pulsador.** Que es una pulsación completa. Qué puede llegar a pasar si se mantiene pulsador presionado en el bucle principal de proceso (apartado **Loop**).

<div style="text-align: center" ><img style="width:90%" src="http://i.imgur.com/jshkSjk.png"/></div><br>

- **Entender el funcionamiento del componente Sensor IR.** Emisor IR, receptor IR y ajuste de umbral.

<div style="text-align: center" ><img style="width: 30%" src="http://i.imgur.com/1U5a2lC.png"/><img style=" width: 70%" src="http://i.imgur.com/x2Pm3I0.png"/></div><br>

- **Ser capaz de programar el componente Sensor IR.** Realización de un programa simple que encienda un LED cuando se le aproxime un objeto blanco y/o cuando se le aproxime un objeto negro.

<div style="text-align: center" ><img style=" width: 80%" src="http://i.imgur.com/sCdroml.png"/></div><br>


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

- Pedir a los alumnos que piensen en hechos cotidianos analógicos y digitales, darles un ejemplos (p.ej. grifo agua, luz de casa, aire acondicionado, música Tocadiscos vs iPod, auriculares ...etc) , hacerles ver que aunque no pensamos en ellos, están presentes en casi todo.

- Pedir a los alumnos que piensen en que sensores conocen, hacer una lista en la pizarra con sus sugerencias, pedirles la clasificación de la lista en analógicos y digitales.

- Sacar dos voluntarios, darles una hoja con la silueta de un muñeco pintado, uno de los alumnos lo cortará a mano y otro con una tijera, ¿Qué corte es más preciso?, hacerles reflexionar sobre la precisión y exactitud.

- Exponer fotografías de sensores comunes (Volumétrico, Screen Touch Sensor, Iterruptor frigorífico) y preguntar por cual creen que es su uso (darles tiempo a especular, luego desvelar). Alimentar el debate de que se podría hacer con ellos.

<div style="text-align: center" ><img style="width: 30%" src="http://i.imgur.com/gEhZiFp.png"/><img style=" width: 30%" src="http://i.imgur.com/S5V6Zoo.png"/><img style=" width: 30%" src="http://i.imgur.com/XuDFFHJ.png"/></div><br>


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

Pedimos a los alumnos reflexionar sobre:
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

<br>Avance próxima sesión, desarrollo del prototipo - juego **Misión Imposible**</br><br><br>



<h2>
    <div id="evaluacion" class="fonth2tittle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-check-square-o fa-stack-1x colortools" ></i>
        </span>  Evaluación
    </div>
</h2>

El desempeño del alumno en esta jornada, se evaluará al termino de la próxima sesión **(IV)**; por una parte con un test de 10 preguntas para valorar asimilación de conocimientos de cada alumno y por otra parte con la rubrica de evaluación para valorar los objetivos competenciales, según el criterio del profesor.

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
    .fontexternallinkcomment{
        float:left;
        width: 300px;
        border-radius: 1px;
        padding:10px; 
        background-color: rgba(255, 255, 255, .5);
        text-align: center;
        line-height:0;
        color:#000000; 
        font-family:'Roboto Slab', serif;
        font-size:18px; 
        font-weight:300;
    }
    .fontexternallink2{
        float:left;
        width: 300px;
        border-radius: 1px;
        border-bottom-left-radius: 50px;
        border-top-right-radius: 50px;
        border-style: solid;
        padding:30px; 
        background-color: #d66c00;
        text-align: center;
        line-height:0;
        color:#ffffff; 
        font-family:'Roboto Slab', serif;
        font-size:23px; 
        font-weight:700;
    }
    .fontseparator{
        float:left;
        width: 25px;
        border-radius: 0px;
        border-style: solid;
        padding:30px; 
        background-color: #ffffff;
        text-align: center;
        line-height:0;
        color:#ffffff; 
        font-family:'Roboto Slab', serif;
        font-size:23px; 
        font-weight:700;
    }
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
    .linksTOC{
        font-size:14px; 
        line-height: 15px;
        color:#729e29;
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
        padding-left: 25px;
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
	.fonth4tittle{
		position:relative;
		left:5%;
		width: 75%;
		padding:20px; 
		line-height:0;
		color:#000000; 
		font-family:'Roboto Slab', serif;
		font-size:20px; 
		font-weight:500;
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
    .fontexternallink{
        width:25%;
        margin-right:1%;
        margin-left:auto;
        border-radius: 50px;
        border-bottom-left-radius: 0px;
        border-top-left-radius: 0px;
        padding:20px;
        background-color: #00f900;
        color: red;
        text-align: center;
        font-family:'Roboto Slab', sans-serif;
        font-style: italic;
        font-size:20px; 
        font-weight:700;
        letter-spacing: 0px;
        line-height: 0px;
    }                
</style>
</details>
<link href="https://fonts.googleapis.com/css?family=Roboto+Slab:100,300,400,700|Roboto:100,100i,300,300i,400,400i,500,500i,700,700i,900,900i" rel="stylesheet" type='text/css'>
<!-- <link href="https://github.com/marcoantmartinez/marcoantmartinez.github.io/blob/master/bitbloq/html/mystyles.css" rel="stylesheet" type="text/css" media="screen"/> 
 -->