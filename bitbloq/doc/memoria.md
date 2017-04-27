<!--
edited  : Marco Antonio Martínez Ramos
email   : marcoantmartinez@gmail.com
release : 2017.04.12 v02
review  : 
github  : https://github.com/marcoantmartinez/marcoantmartinez.github.io/tree/master/bitbloq
license : CC BY-SA This learning resource is provided for free by marcoantmartinez@gmail.com under a Creative Commons Attribution-ShareAlike 4.0 International License.
others  : Bitbloq is a project provided for free by BQ (c)
-->









<div id="div_exterior" class="fontbody" > 

<div id="cabecera" class="fontheader" >
<a  style="color:#ffffff;" href="http://bitbloq.bq.com" title="View this resource on Bitbloq site">Bitbloq is a project provided for free by BQ (c)</a>
</div>

<div class="bannerheader">
<a href="a" target="_blank">
    <img src="http://i.imgur.com/vSK3EZk.jpg" alt="">
</a>

<div class="bannerfooter">

<h1 id="propuesta">
<div class="fonth1tittle">
    <span class="fa-stack fa-lg">
        <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
        <i class="fa fa-bullhorn fa-stack-1x colortools"></i>
    </span> 
    Memoria de Proyecto
</div>
</h1>

<!-- <div class="linksheader">
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
    <span> Programación y Robótica con Arduino </span> 
    </div>
</h1>
 -->


<h1 id="programacion">

<div class="fonth1subtittle">
<span> Programación y Robótica con Arduino </span> 
</div>
</h1>




<h2>
    <div id="que-es" class="fonth2tittle">
        <span class="fa-stack fa-lg" >
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-heartbeat fa-stack-1x colortools"  ></i>
        </span> Prólogo
    </div>
</h2>



El trabajo aquí presentado supone el primer paso que he dado para diversificar más mi catálogo de **Consultoría y Formación TI**, introduciéndome en un segmento de mercado que está en continua expansión, me refiero fundamentalmente al movimiento **Maker** en su vertiente de **Robótica en la Escuela**.

Faltaría a la verdad si dijese que este paso lo he dado sólo por cuestiones de competitividad en el mercado de la Formación TI, pues el desarrollo de prototipos con Arduino, Raspberry Pi, ESP8266 y otros cacharros electrónicos siempre ha sido un **Hobby motivador y absorbente a la par**, supongo que es deformación profesional de Ingeniero Industrial ... y también parte del niño curioso que todos llevamos dentro.

Aunque el sendero está por andar, y eso da cierto respeto, espero sobre todo disfrutar del camino en este sector profesional, y que me reporte las mismas satisfacciones del Hobby, ... como cuando hice funcionar mi primer prototipo, la sonrisa de la cara no se me podía borrar, eso era felicidad.

Recuerdo cuando era niño y daba mis primeros pasos en la electrónica, en el modesto taller de reparación de Radio y TV que regentaba el paciente Don Carlos, ... todo era nuevo, no había pregunta mal hecha, todo era posible, ... eso me decía Don Carlos, ... espero que en este acercamiento a la escuela y los clubs Maker, pueda transmitir ese mismo espíritu a los alumnos, **Todo es Posible**.

En aquel tiempo, el camino a andar desde la idea al prototipo era arduo, devorábamos y esperábamos con ansiedad la llegada del último número de la revista Elektor a la biblioteca municipal, en busca de inspiración y soluciones a problemas que la formación más adelante nos desvelaría más sencillos o complejos de lo que entonces imaginábamos.

**Hoy todo a cambiado a mejor**, la gran oferta de placas de prototipado rápido, sus Shields y kits de componentes, los Framework de desarrollo SW gratuitos, el Software de diseño CAD CAM CAE free, la impresión 3D y cortadoras Láser, la movilidad, el Open Source, Drones, el SW Google AI para coches autónomos en RPI, los clubs Maker ... etc ... parece como si todo hubiera explotado al mismo tiempo, ofreciendo una gran paleta de sabores, al alcance de cualquiera que tenga la **ilusión de crear y compartir lo creado**.

Llevar ese espíritu de **"ilusión por crear"** a las aulas, es el objetivo que subyace en este primer trabajo "Propuesta de Programación y Robótica con Arduino" y Bitbloq.

**Hoy, el futuro lo puedes crear tú, ¿ te atreves ?**



<br>
<h2>
    <div id="que-es" class="fonth2tittle">
        <span class="fa-stack fa-lg" >
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-handshake-o fa-stack-1x colortools"  ></i>
        </span> Requisitos
    </div>
</h2>

Este apartado tiene por objeto exponer las necesidades a cubrir por las soluciones recogidas en el documento **"Propuesta Didáctica"**, a saber:

- **Currículo del alumno** : incorporar capacidades técnicas de "Programación y Robótica con Arduino".

- **Crear itinerario formativo** que permita en 6 sesiones de 2 horas, garantizar la asimilación efectiva del contenido, para un aula de 20 alumnos (1º-2º ESO, 12 años en adelante) sin conocimientos previos de programación y robótica.
	- Establecer los objetivos de contenidos técnicos del curso

	- Establecer los objetivos competenciales a cubrir por el curso
	- Establecer la guía de actividades detallada para las 6 sesiones
	- Establecer la planificación detallada de las sesiones.
	- Establecer la sistema evaluación de calidad educativa.
		- Evaluación de grado de consecución de objetivos de los alumnos
			* Objetivo de asimilación de contenidos técnicos 
			* Objetivos competenciales

		- Evaluación de calidad del curso.
- **Hacer la selección justificada de herramientas** hardware y software que mejor se adapten para alcanzar los objetivos.
- **Recursos de partida** : contar con la existencia de los siguientes medios: 10 Laptop, 1 proyector, 1 pizarra digital, Mesas adaptables para trabajo en grupo o individual, Conexión a Internet, 2 Kits de robótica Arduino.








<br>
<h2>
    <div id="que-es" class="fonth2tittle">
        <span class="fa-stack fa-lg" >
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-university fa-stack-1x colortools"  ></i>
        </span> Propuesta Didáctica
    </div>
</h2>

Para cumplir los requisitos expresados arriba, se ha creado un documento denominado **"Propuesta Didáctica"** que recoge la **Descripción detalla de las Soluciones y Actividades** que han de adoptarse para cumplirlos.

A continuación **resumimos** los puntos más importantes recogidos en dicho documento:



<h3 id="objetivos-tecnicos" ><div class="fonth3tittle"><i style="" class="fa fa-graduation-cap fa-1x"></i> Proyecto Educativo</div></h3>

- **Justificación** : Los empleos del futuro no se entienden sin las TI, el profesional del futuro los necesitará para acceder al mercado laboral.

- **Finalidad** : Dotar al alumno de las habilidades de :
	- Pensamiento Computacional, Programación y Prototipado con Arduino.
	- Autonomía al crear, Creatividad, Espíritu Crítico e Innovación.
	- Trabajo en Equipo y participación en el Conocimiento Colaborativo.



<h3 id="objetivos-tecnicos" ><div class="fonth3tittle"><i style="" class="fa fa-key fa-1x"></i> Contextualización</div></h3>

- **Organización del Aula** : Programación por Pares para mejorar el rendimiento y competencias de razonamiento, dialogo y aceptación de ideas distintas.

- **Conocimientos Transversales** : Valor añadido, se impartirán conocimientos suficientes para comprender los principios de Física, Matemáticas, Biología, ... etc que hacen que un componente electrónico funcione.
- **Recursos necesarios :** Es una recopilación de los medios materiales y de configuración requeridos para impartir las clases.
- **¿Por qué se ha elegido ?:**
	- **Arduino** : Muy difundido en comunidad Maker. GPIO completísima no tiene rival. Integración sencilla con otras placas. Catálogo amplio de Shields y componentes electrónicos. Multitud de IDEs para programar. Favorece emprendimiento con Hardware Open Source. Comunidad Maker muy activa y en continua expansión. 
	- **Programación Bloques** : Reduce la curva de aprendizaje para programar. Representación de un programa en bloques, refuerza el proceso cognitivo que crea los algoritmos.
	- **Bitbloq IDE** : Orientada a programación por bloques. Orientada al Aula permite : seguimiento profesor, compartir conocimiento y  colaboración entre alumnos. Permite documentar los proyectos. Hace fácil la transición al desarrollo en Processing. Cero problemas de instalación, mantenimiento y control de configuración.



<h3 id="objetivos-tecnicos" ><div class="fonth3tittle"><i style="" class="fa fa-crosshairs fa-1x"></i> Definición de Objetivos de Aprendizaje</div></h3>

- **Objetivos Técnicos** : Funcionamiento y Programación por Bloques, Programación de sensores Analógicos y Digitales y Programación de Actuadores.

- **Objetivos Competenciales** : Promover en el alumnos las habilidades de pensamiento computacional, autonomía y motivación al logo, así como de trabajo en equipo y aprendizaje colaborativo.




<h3 id="objetivos-tecnicos" ><div class="fonth3tittle"><i style="" class="fa fa-binoculars fa-1x"></i> Contenidos y Planificación</div></h3>

- ++**Sesiones**++ :

	- **x3 Sesiones Teóricas** : Teoría y Funcionamiento de los Bloques Bitbloq con Arduino y sus componentes electrónicos Sensores y Actuadores. Incluye prototipado de prácticas sencillas en Arduino para consolidar conocimientos.

	- **x3 Sesiones de Proyecto** : El alumno construye de forma autónoma un prototipo con Arduino, aplicando el proceso de pensamiento computacional, lo documenta y lo comparte con el aula en la nube Bitbloq.

- ++**Planificación de Sesiones**++ :

	A cada sesión teórica le sigue una de proyecto relacionada con la teoría ya impartida.

<div style="position:relative; left: 0%; width: 100%; text-align: center" ><img src="https://cdn.rawgit.com/marcoantmartinez/marcoantmartinez.github.io/00b42bec/gantt.svg" alt=""></div><br> 

- ++**Actividades y sus objetivos de aprendizaje**++ : 

	Las actividades de las sesiones resolverán el aprendizaje de los siguientes contenidos.

	- **Sesión I** - Comprender y saber programar con bloques :
	  - Que es un algoritmo
	  - Qué es el puerto serie de Arduino
	  - Qué es una variable
	  - Que es un pulsador y un diodo
	  - Qué son los bloques de control
	  - Cómo medimos tiempos con Arduino

	- **Sesión II** - Construir un prototipo Arduino de forma autónoma con **Bloques de Control**.
	- **Sesión III** - Comprender y saber programar sensores :
	  - Que es un sensor
	  - Qué es analógico y que digital
	  - Diferencias entre pin digital y analógico
	  - Qué es la Precisión (Resolución)
	  - Componentes digitales y analógicos
	  - Componentes analógicos potenciómetro y LDR
	  - Componentes digitales botón y sensor infrarrojo
	- **Sesión IV** : Construir un prototipo Arduino de forma autónoma con componentes electrónicos **Sensores**.
	- **Sesión V** : Comprender y saber programar actuadores :
	  - Qué se un actuador
	  - Que es la corriente eléctrica y cómo se presenta
	  - Cómo se utiliza el electromagnetismo para conseguir movimiento
	  - Cómo se usa la señal PWM para controlar actuadores
	  - Cómo se compone el color con un dispositivo RGB
	  - Cómo se reproduce el sonido digitalmente
	  - Circuitos de componentes actuadores digitales
	- **Sesión VI** : Construir un prototipo Arduino de forma autónoma con componentes electrónicos **Actuadores**.








<h3 id="objetivos-tecnicos" ><div class="fonth3tittle"><i style="" class="fa fa-check-square-o fa-1x"></i> Evaluación</div></h3>

<div style="left:8%; position: relative; width:90%;">

La evaluación **consta de tres partes**:
<br><br>

**1.- Evaluación de Comprensión de Contenidos** : Se realizará mediante tests de 10 preguntas que el alumno responderá al final de cada sesión de proyecto (3 TestS en total). Los Test incorporan una componente de repaso de la lección, incluyendo resúmenes del contenido impartido, que sirven de introducción las preguntas.

**2.- Rubrica de Evaluación de Objetivos Competenciales** : Evaluará objetivamente el desempeño alcanzado por el alumno en los **objetivos competenciales**. En la primera sesión y como parte de la **Presentación del Curso**, el alumno recibirá esta información, para que sepa con claridad lo que se espera de él.

**3.- Mejora Continua** : Al finalizar el curso se entregará un cuestionario anónimo a los alumnos para evaluar su percepción de la calidad del curso, que aspectos les han gustado más, cuales menos, cuales creen que faltan, cuales creen que se podría mejorar ... etc. Este feedback además de ser un requisito necesario para mejorar el curso, servirá para mejorar y adaptar los contenidos y métodos, para futuras ampliaciones de contenidos de esta propuesta educativa y otras.
</div>







<br>
<h2>
    <div id="que-es" class="fonth2tittle">
        <span class="fa-stack fa-lg" >
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-book fa-stack-1x colortools"  ></i>
        </span> Documentación Presentada
    </div>
</h2>

Los siguientes enlaces presentan los documentos realizados para dar soporte al detalle de la **Propuesta Didáctica** del curso de **Programación y Robótica con Arduino**:



<br>
<h3 id="objetivos-tecnicos" ><div class="fonth3tittle"><i style="" class="fa fa-university fa-1x"></i> Propuesta Didáctica</div></h3>

<div style="float:left; width:100%;"></div>

<div class="fontseparator"></div>
<div id="test_sesion_i_ii" class="fontexternallink2">
<a style="color:#ffffff" href="propuesta.html">Propuesta Didáctica</a>
</div>
<div class="fontseparator"></div>

<div style="float:left; width:100%;"></div>

<div class="fontseparator"></div>
<div class="fontexternallinkcomment">
Programación y Robótica
</div>
<div class="fontseparator"></div>
<div style="float:left; width:100%;"></div>

<br><br><br><br><br>





<br>
<h3 id="objetivos-tecnicos" ><div class="fonth3tittle"><i style="" class="fa fa-cog fa-1x"></i> Guías de Actividades de las Sesiones</div></h3>

<div style="left:8%; position: relative; width:90%;">

**Bloque I**
</div>

<div class="fontseparator"></div>

<div id="actividad_sesion_i" class="fontexternallink2">
<a style="color:#ffffff" href="sesion_i.html">Sesion I  teoria</a>
</div>
<div class="fontseparator"></div>
<div id="actividad_sesion_ii" class="fontexternallink2">
<a style="color:#ffffff" href="sesion_ii.html">Sesión II - proyecto</a>
</div>

<br><br>
<div class="fontseparator"></div>
<div class="fontexternallinkcomment">
Bloques de Control
</div>
<div class="fontseparator"></div>
<div class="fontexternallinkcomment">
¿Quién Pulsa Más Rápido?
</div>
<br><br><br>






<div style="left:8%; position: relative; width:90%;">

**Bloque II**
</div>

<div class="fontseparator"></div>
<div id="actividad_sesion_iii" class="fontexternallink2">
<a style="color:#ffffff" href="sesion_iii.html">Sesión III - teoría</a>
</div>
<div class="fontseparator"></div>
<div id="actividad_sesion_iv" class="fontexternallink2">
<a style="color:#ffffff" href="sesion_iv.html">Sesión IV - proyecto</a>
</div>

<br><br>
<div class="fontseparator"></div>
<div class="fontexternallinkcomment">
Sensores Analógicos y Digitales
</div>
<div class="fontseparator"></div>
<div class="fontexternallinkcomment">
Misión Imposible
</div>
<br><br><br>



<div style="left:8%; position: relative; width:90%;">

**Bloque III**
</div>

<div class="fontseparator"></div>
<div id="actividad_sesion_v" class="fontexternallink2">
<a style="color:#ffffff" href="sesion_v.html">Sesión V - teoría </a>
</div>
<div class="fontseparator"></div>
<div id="actividad_sesion_vi" class="fontexternallink2">
<a style="color:#ffffff" href="sesion_vi.html">Sesión VI - proyecto</a>
</div>

<br><br>
<div class="fontseparator"></div>
<div class="fontexternallinkcomment">
Actuadores
</div>
<div class="fontseparator"></div>
<div class="fontexternallinkcomment">
Comprobador Baterías AAA/AA
</div>


<br><br>




<br>
<h3 id="objetivos-tecnicos" ><div class="fonth3tittle"><i style="" class="fa fa-check-square-o fa-1x"></i> Tests de Evaluación para el Alumno</div></h3>

<div class="fontseparator"></div>
<div id="test_sesion_i_ii" class="fontexternallink2">
<a style="color:#ffffff" href="sesion_ii_test.html">Test sesiones I y II</a>
</div>
<div class="fontseparator"></div>
<div id="test_sesion_iii_iv"  class="fontexternallink2">
<a style="color:#ffffff" href="sesion_iv_test.html">Test sesiones III y IV</a>
</div>

<div style="float:left; width:100%;"></div>

<div class="fontseparator"></div>
<div class="fontexternallinkcomment">
Bloques de Control
</div>
<div class="fontseparator"></div>
<div class="fontexternallinkcomment">
Sensores Analógicos y Digitales
</div>

<div style="float:left; width:100%;"></div>

<div class="fontseparator"></div>
<div  id="test_sesion_v_vi" class="fontexternallink2">
<a style="color:#ffffff" href="sesion_vi_test.html">Test sesiones V y VI</a>
</div>
<div class="fontseparator"></div>
<div class="fontexternallinkcomment">
</div>

<div style="float:left; width:100%;"></div>

<div class="fontseparator"></div>
<div class="fontexternallinkcomment">
Actuadores
</div>
<div class="fontseparator"></div>
<div class="fontexternallinkcomment">
</div>

<div style="float:left; width:100%;"></div>

<br><br><br><br><br><br><br><br><br><br>





<br>
<h3 id="objetivos-tecnicos" ><div class="fonth3tittle"><i style="" class="fa fa-check-square fa-1x"></i> Rúbrica de Evaluación para el Alumno</div></h3>

<div class="fontseparator"></div>
<div id="test_sesion_i_ii" class="fontexternallink2">
<a style="color:#ffffff" href="rubrica.html">Rúbrica Evaluación</a>
</div>
<div class="fontseparator"></div>

<div style="float:left; width:100%;"></div>

<div class="fontseparator"></div>
<div class="fontexternallinkcomment">
Objetivos Competenciales
</div>
<div class="fontseparator"></div>
<div style="float:left; width:100%;"></div>

<br><br><br><br><br>






<br>
<h3 id="objetivos-tecnicos" ><div class="fonth3tittle"><i style="" class="fa fa-gift fa-1x"></i> Encuesta de Satisfacción con el Curso</div></h3>

<div class="fontseparator"></div>
<div id="test_sesion_i_ii" class="fontexternallink2">
<a style="color:#ffffff" href="encuesta.html">Cuestionario Calidad</a>
</div>
<div class="fontseparator"></div>

<div style="float:left; width:100%;"></div>

<div class="fontseparator"></div>
<div class="fontexternallinkcomment">
Encuesta Anónima para Alumno
</div>
<div class="fontseparator"></div>
<div style="float:left; width:100%;"></div>

<br><br><br><br><br>
















<br>
<br><br><br><br>

***
<div class="fontfooter">
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
	<img alt="Creative Commons License" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" />
</a></br>This learning resource is provided for free by 
<a rel="email" href="marcoantmartinez@gmail.com">marcoantmartinez@gmail.com</a> under a 
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
</br>
<a href="https://github.com/marcoantmartinez/marcoantmartinez.github.io/tree/master/bitbloq" title="View and edit this resource on GitHub">
	<img src="http://i.imgur.com/MijfOYX.png" alt=""><br>View and edit this resource on GitHub  
</a>
</div>

</div>
</div>
</div>
<details>
	<style>
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
		.fontseparator{
			float:left;
			width: 20px;
			padding:30px; 
			background-color: rgba(255, 255, 255, .5);
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
/*			background-image: url("http://i.imgur.com/EnY10RD.png"); 
*/			background-repeat: no-repeat ;
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