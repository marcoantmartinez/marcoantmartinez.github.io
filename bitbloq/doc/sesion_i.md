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
    <span> Sesión I : Bloques de Control </span> 
    </div>
</h1>


<br>En estas sesiones los estudiantes aprenderán como funcionan los **bloques de control** principales de Arduino, cómo analizar, diseñar y programar algoritmos, cómo mostrar datos y nociones básicas de sensores y actuadores.</br>
<br>Finalmente serán capaces de desarrollar el proyecto **Quién pulsa el botón más rápido**.</br>


<h2>
    <div id="recursos-necesarios" class="fonth2tittle">
        <span class="fa-stack fa-lg" >
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-wrench fa-stack-1x colortools"  ></i>
        </span> Recursos necesarios
    </div>
</h2>

- Grupos de alumnos configurados, informados y sentados su puesto asignado.
- Cuentas de Bitbloq activadas para los alumnos - grupos
- Placa Arduino con alimentación y conector USB (por alumno o grupo)
- Componente electrónico pulsador.
- Componente electrónico LED.
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
        </span> Contenidos y Actividades de aprendizaje
    </div>
</h2>

- **Entender que es **Arduino** que lo diferencia con un Desktop, Tablet, Móvil.
- **Entender que es un algoritmo y sus partes principales.**
	* Análisis de necesidades para resolución de un problema
	* Concepción abstracta de solución. Pros - Contras y proceso selección.
	* Diseño del algoritmo : diagramas de flujo
- **Ser capaces de inicializar, preparar y ejecutar un algoritmo básico de Arduino.**
	* bitbloq , partes de la aplicación:
		- Proyectos : mis proyectos , compartidos.
		- Nuevo proyecto : Hardware, Software, Información
			- Diseño Prototipo Hardware : Librerías de Placas, de Componentes y de Robots
			- Programación Software con **Bloques**:
				* Apartados Global, Setup y Loop
				* Bloques de comando : componentes, variables, código, matemáticas, texto, control y lógica 
			- Programación Avanzada Software con **Código**
		- Prototipado : Verificación , Carga , Publicación
- **Entender cómo funciona la salida serie de Arduino.**
	* Conexión por USB y Bluetooth
	* Menú de proyecto : Ver \ Mostrar Consola Serial Monitor :
		- Selección de : ruta de comunicación con Placa Arduino, velocidad transmisión.
		- Re-Inicialización del programa.
		- Recepción de mensajes en consola serie PC
		- Envío de mensajes hacia Arduino.
- **Ser capaz de escribir y leer en el puerto serie de Arduino.**
	* Realización primer programa simple en apartado **Setup*, enviando una secuencia de textos con y sin salto de línea, por el puerto serie.
	* Programa simple recepción serie de datos desde PC, textos y números.
- **Entender el bloque de control Esperar.**
	* Bloque Esperar en Básicos
	* Bloque Esperar en Avanzados
- **Ser capa de utilizar el bloque de espera.**
	* Realización programa simple en apartado **Loop**, enviando una secuencia de textos con y sin salto de línea, por el puerto serie, con secuencias de espera intercaladas.
- **Entender como funciona una variable.**
	* Concepto de variable
	* Tipos de variable numérico y texto
	* Bloques de operaciones matemáticas con variables numéricas
	* Bloques de tratamiento de texto con variables de texto
	* Conversión de número a texto
- **Ser capaz de utilizar las variables.**
	* ==Avance necesario:== explicación bloque de control **Repetir** necesario para ejercicios.
	* Realización programa simple en apartado **Loop**, enviando una secuencia de **números naturales de 0 a 10** por el puerto serie, con secuencias de espera intercaladas.
	* Realización programa simple en apartado **Loop**, enviando una secuencia de **números primos de 0 a 100** por el puerto serie, sin secuencias de espera intercaladas.
- **Entender que son y cómo funcionan los bloques de control.**
	* Bloque de control **Sí** y **de lo contrario**
	* Bloque de control **Mientras**
	* Bloque de control **Contar con**
	* Bloque de control en Avanzados **Interrumpir el bucle**
- **Ser capaces de utilizar los bloques de control de forma autónoma.**
	* ==Avance necesario:== pin Digital, pin Analógico, +5 Vcc, GND, Amperios
	* Programar y construir prototipo parpadeo del componente **actuador** LED
	* Programar y construir prototipo Encendido LED tras pulsar componente **sensor** Pulsador (botón).
- **Entender como funciona el bloque de temporizador de Arduino.**
	* Bloque de control **Obtener tiempo de ejecución**




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
- Matemáticas - Algoritmos. Cálculo de Tiempo de reacción. Números primos y aleatorios.


<h2>
    <div id="inicio" class="fonth2tittle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-power-off fa-stack-1x colortools" ></i>
        </span>  Inicio
    </div>
</h2>

- **¿ Es necesaria una Computadora para hacer algoritmos ?** (escuchar respuestas) Recalcar que existen observando la naturaleza, en el ADN y comportamiento de las especies y se consolida en el ser humano cuando este quiere repetir un resultado (p.e. hacer fuego, observación, repetición, prueba y error, transmisión de conocimiento), antes era aprender pasos con boca a boca, con la escritura simples listas ... etc hasta llegar a nuestros días. 
- **Pedir a los alumnos que piensen en algoritmos cotidianos**, darles un ejemplo simple (p.ej. la rutina diaria desde que se levantan, hasta llegan al cole dos alumnos distintos), hacerles ver que aunque no pensamos en ellos, están presentes en todas las actividades diarias de todos nosotros. 
- **Pizarra en grupo : Tomar dos algoritmos uno muy sencillo y otro complicado** (p.e escribir letra A en un papel con lápiz y con impresora**, dividir la clase en dos grupos, hacerles salir a la pizarra y pedirles que desarrollen los pasos en 2 minutos máximo.
- Revisión del trabajo, profundizar en el concepto de complejidad del algoritmo y su división en varios pasos para hacerlo más simple.
- **Acentuar la importancia de la atención al detalle y la precisión** de un algoritmo.
- **Definición formal de Algoritmo** : Es un conjunto prescrito de instrucciones o reglas bien definidas, ordenadas y finitas que permite llevar a cabo una actividad mediante pasos sucesivos que no generen dudas a quien deba hacer dicha actividad. Dados un estado inicial y una entrada, siguiendo los pasos sucesivos se llega a un estado final y se obtiene una solución.


<h2>
    <div id="desarrollo" class="fonth2tittle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-film fa-stack-1x colortools" ></i>
        </span>  Desarrollo
    </div>
</h2>

0. Introducción al curso
	* Presentación del curso : contenido sesiones, programación por pares ... etc.
	* Presentación de sistema de evaluación : acentuar objetivos competenciales.
	* Asegurar que **todo** el aula tiene **todos** los recursos necesarios.
1. Alumnos - grupos Arrancar el navegador Google Chrome e iniciar la sesión del BitBloq
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
>- Los algoritmos divididos deben ser muy precisos haciendo cosas pequeñas.
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

- Avance próxima sesión Desarrollo del prototipo - juego **Quién pulsa el botón más rápido**



<h2>
    <div id="evaluacion" class="fonth2tittle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-check-square-o fa-stack-1x colortools" ></i>
        </span>  Evaluación
    </div>
</h2>

El desempeño del alumno en esta jornada, se evaluará al termino de la próxima sesión **(II)**; por una parte con un test de 10 preguntas para valorar asimilación de conocimientos de cada alumno y por otra parte con la rubrica de evaluación para valorar los objetivos competenciales, según el criterio del profesor.

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