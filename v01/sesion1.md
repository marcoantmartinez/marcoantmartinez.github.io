<!---
edited  : Marco Antonio Martínez Ramos
email   : marcoantmartinez@gmail.com
release : 2017.04.01
review  : na
github  : https://github.com/marcoantmartinez/marcoantmartinez.github.io/tree/master/bitbloq
license : CC BY-SA This learning resource is provided for free by marcoantmartinez@gmail.com under a Creative Commons Attribution-ShareAlike 4.0 International License.
others  : Bitbloq is a project provided for free by BQ (c)

HelveticaNeue-Thin
-->

<link href="https://fonts.googleapis.com/css?family=Roboto+Slab:100,300,400,700|Roboto:100,100i,300,300i,400,400i,500,500i,700,700i,900,900i" rel="stylesheet" type='text/css'>

<style>

.bannerheader{
width:100%; 
margin: 0 auto;
display: table; 
min-width: 800px; 
max-width: 900px; 
background-color:#ffffff; 
	border:10px solid #96c93e;
}
<!---
.bannerfooter{
width:100%;
background:#ffffff; 
border:10px solid #ffffff;
position:relative; 
top:0;  
left:0; 
border: 2;
background-image: url("https://s-media-cache-ak0.pinimg.com/originals/7f/6c/91/7f6c917473453d67602d42f38dfb94f2.png"); 
background-repeat: no-repeat ;
-webkit-background-size: cover;
-moz-background-size: cover;
-o-background-size: cover; 
background-size:100% 40%; 
background-position: bottom
}
.linksheader{
padding:10px;
text-align:center; 
font-size:14px; 
color:#729e29
}
.fontnotes{
width:33%;
margin-left:auto; 
margin-right:0;
border-radius: 15px;
padding:2px;
text-align:center;
background-color:#ff8000;
padding: 0px;
font-family: Roboto, serif; 
font-size: 13px; 
font-weight: 300; 
letter-spacing: 0px
}
.fontbody{
width: 100%; 
overflow: auto; 
background-color: #ffffff; 
position: absolute; 
top: 0px; 
left: 0px; 
font-size: 18px; 
font-family: 'Roboto-Light', sans-serif ; 
font-weight: lighter; 
letter-spacing: 0px;
line-height: 26px; 
}
.fonth1tittle{
top:0%;
width:100%; 
border-radius: 15px;
padding:0px;
background: linear-gradient(to right, #5e8421, #c1f37b 100%);
line-height:0px;
color:#ffffff;
font-family:'Roboto Slab', serif;
font-size:36px; 
font-weight:700;
}
.fonth2tittle{
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
.fontheader{
width:50%;
margin: 0 auto;
position: absolute;
left: 25%; 
top:0px; 
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
-->
</style>


<div id="div_exterior" class="fontbody" > 

<div class="fontheader" >
	<a  style="color:#476419;" href="http://bitbloq.bq.com" title="View this resource on Bitbloq site">Bitbloq is a project provided for free by BQ (c)</a>
</div>

<div class="bannerheader">
	<a href="a" target="_blank">
	    <img src="https://s-media-cache-ak0.pinimg.com/originals/02/be/06/02be068cf3467a0e5665fc6e8dcd7eb7.jpg" alt="">
	</a>

<div class="bannerfooter">

<h1>
    <div class="fonth1tittle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-sitemap fa-stack-1x colortools"></i>
        </span> 
        Bloques de control
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

<div class="fontnotes">
    <span class="fa-stack fa-lg">
        <i class="fa fa-circle fa-stack-2x fa-inverse" ></i>
        <i class="fa fa-exclamation-triangle fa-stack-1x colornotes" ></i>
    </span> Actividades de las sesiones 1 y 2
</div>


<br>En estas sesiones los estudiantes aprenderán como funcionan los bloques de control principales de Arduino, cómo programar algoritmos, cómo mostrar datos y qué son los sensores y actuadores.</br>
<br>Finalmente serán capaces de desarrollar el juego **Quién pulsa el botón más rápido**.</br>


<h2>
    <div id="recursos-necesarios" class="fonth2tittle">
        <span class="fa-stack fa-lg" >
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-wrench fa-stack-1x colortools"  ></i>
        </span> Recursos necesarios
    </div>
</h2>

- Cuentas de Bitbloq activadas para los alumnos - grupos
- Placa Arduino con alimentación y conector USB (por alumno o grupo)
- Componente pulsador.
- Componente LED.
- Pizarra y proyector.

<h2>
    <div id="resumen-de-leccion" class="fonth2tittle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-list-ol fa-stack-1x colortools" ></i>
        </span> Resumen de lección
    </div>
</h2>

- ¿Que es un algoritmo?
- ¿Qué es el puerto serie de Arduino?
- ¿Qué es una variable?
- ¿Que es un pulsador y un diodo?
- ¿Qué son los bloques de control?
- ¿Cómo medimos tiempos con Arduino?


<h2>
    <div id="objetivos-de-aprendizaje" class="fonth2tittle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-crosshairs fa-stack-1x colortools" ></i>
        </span> Objetivos de aprendizaje
    </div>
</h2>


- Entender que es un algoritmo y sus partes principales.
- Ser capaces de inicializar, preparar y ejecutar un algoritmo básico de Arduino.
- Entender cómo funciona la salida serie de Arduino.
- Ser capaz de escribir y leer en el puerto serie de Arduino.
- Entender el bloque de espera.
- Ser capa de utilizar el bloque de espera.
- Entender como funcionan los bloques de control.
- Ser capaces de utilizar los bloques de control de forma autónoma.
- Entender como funciona una variable.
- Ser capaz de utilizar las variables.
- Entender como funciona el bloque de temporizador de Arduino.

<h2>
    <div id="aplicaciones-transversales" class="fonth2tittle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-random fa-stack-1x colortools" ></i>
        </span>  Aplicaciones Transversales
    </div>
</h2>

- Tecnologías de Información - Programación, algorítmica, bloques control, variables, puerto serie, aleatoriedad, concatenación de texto.
- Física - Tiempo de reacción y medida (mili segundos), Sensores y Actuadores, Electrónica de diodo y pulsador, ley de Ohm, Resistencia, Voltaje e Intensidad.
- Matemáticas - Algoritmos. Cálculo de Tiempo de reacción. Números aleatorios.


<h2>
    <div id="inicio" class="fonth2tittle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-power-off fa-stack-1x colortools" ></i>
        </span>  Inicio
    </div>
</h2>

- Pedir a los alumnos que piensen en algoritmos, darles un ejemplo, hacerles ver que aunque no pensamos en ellos, están presentes en todas las actividades diarias de todos nosotros.
- Tomar dos algoritmos uno muy sencillo y otro complicado, dividir la clase en dos grupos, hacerles salir a la pizarra y pedirles que desarrollen los pasos en 5 minutos máximo.
- Revisión del trabajo, profundizar en el concepto de complejidad del algoritmo y su división en varios pasos para hacerlo más simple.


<h2>
    <div id="desarrollo" class="fonth2tittle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-film fa-stack-1x colortools" ></i>
        </span>  Desarrollo
    </div>
</h2>

1. Arrancar el navegador Google Chrome e iniciar la sesión del BitBloq
2. Los alumnos - grupos, siguen las actividades de esta sección guiados paso a paso por el profesor.
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
- Imaginar que otras cosas se podrían hacer con un botón.
- Imaginar que otros sensores se podrían utilizar.
- Imaginar que otras cosas se podrían hacer con un Led.
- Imaginar que otros actuadores se podrían utilizar.
- Es sencillo o complicado hacer lo que imaginan.

**Conclusión**:
>- Los algoritmos son sencillos si los dividimos en partes pequeñas.
>- Se pueden utilizar muchos sensores.
>- Se pueden utilizar muchos actuadores.


<h2>
    <div id="reto" class="fonth2tittle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-trophy fa-stack-1x colortools" ></i>
        </span>  Reto
    </div>
</h2>

- Desarrollo del juego **Quién pulsa el botón más rápido**
>- ¿ Qué pasa si el tiempo que hay entre el Preparados, Listos, Ya del juego **"Quién pulsa el botón más rápido"** es aleatorio entre 1 y 5 segundos ?
>- ¿ Qué otros usos se pueden dar a este circuito ?



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
	<img style="width: 36px" src="https://s-media-cache-ak0.pinimg.com/originals/cc/19/c9/cc19c961beb4192c9faee7345b0dbe6f.png" alt=""><br>View and edit this resource on GitHub
</a>

</div>

</div>
</div>
</div>