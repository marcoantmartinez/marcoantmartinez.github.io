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

<div class="fontheader" >
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
        <i class="fa fa-graduation-cap fa-stack-1x colortools"></i>
    </span> 
    Propuesta Didáctica
</div>
</h1>

<div class="linksheader">
<a href="#proyecto"><i class="fa fa-check-square-o"></i> Proyecto</a> |
<a href="#contexto"><i class="fa fa-check-square-o"></i> Contexto</a> |
<a href="#objetivos"><i class="fa fa-check-square-o"></i> Objetivos</a> |
<a href="#contenidos-plan"><i class="fa fa-check-square-o"></i> Contenidos y Planificación</a> |
<a href="#evaluacion"><i class="fa fa-check-square-o"></i> Evaluación</a>
</div>

<details class="linksTOC">

- [Proyecto](#proyecto)
  * [Justificación](#justificacion)
- [CLI](#cli)
- [Highights](#highights)
- [Usage](#usage)
- [API](#api)
  * [toc.plugin](#tocplugin)
  * [toc.json](#tocjson)
  * [toc.insert](#tocinsert)
  * [Utility functions](#utility-functions)
- [Options](#options)
  * [options.append](#optionsappend)
  * [options.filter](#optionsfilter)
  * [options.slugify](#optionsslugify)
  * [options.bullets](#optionsbullets)
  * [options.maxdepth](#optionsmaxdepth)
  * [options.firsth1](#optionsfirsth1)
  * [options.stripHeadingTags](#optionsstripheadingtags)
- [About](#about)
</details>

<!-- MarkdownTOC depth=3-->


<!-- /MarkdownTOC -->



<div style="text-align: center" ><a href=""><img src="http://i.imgur.com/3SsE7lB.png"/></a></div>




<h1 id="programacion">

<div class="fonth1subtittle">
<span> Programación y Robótica con Arduino </span> 
</div>
</h1>









<h2 id="proyecto">
<div id="que-es" class="fonth2tittle">
    <span class="fa-stack fa-lg" >
        <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
        <i class="fa fa-graduation-cap fa-stack-1x colortools"  ></i>
    </span> Proyecto Educativo "Programación y Robótica"
</div>
</h2>

<h3 id="justificacion"><div class="fonth3tittle">Justificación</div></h3>

En el día a día el uso de la tecnología nos pasa desapercibido, debido a la inmersión de esta en todas las facetas de nuestra vida, en poco menos de tres décadas ha pasado de ser una herramienta de expertos, a ser algo de uso general y sencillo. 
<br><br>
Si miramos con más detalle la última década, la progresión de esta inmersión tecnológica se ha visto acelerada por nuevas herramientas (Tecnologías de Información) que hacen que pasar de una **idea** a el desarrollo de un **prototipo funcional** sea algo al alcance de cualquier persona.
<br><br>
En los últimos años, el colectivo que forma este movimiento **creativo** se está mirando desde todos los sectores, como una apuesta clara para crear **futuro** en todas la facetas de la actividad humana.
<br><br>
Con todo esto es fácil imaginar que esta aceleración de la inmersión tecnológica, seguirá adelante, y que el dominio de la **programación** y la **robótica** será de gran ayuda para los profesionales del futuro.
<br><br>

<h3><div id="finalidad" class="fonth3tittle">Finalidad</div></h3>

Esta propuesta tiene como objeto introducir al alumno en el **Pensamiento Computacional** mediante la programación de aplicaciones informáticas, orientadas a realizar proyectos sencillos, que interactuarán con el mundo real (luz, sonido, movimiento, ... etc), utilizando la plataforma hardware de prototipado rápido **Arduino** y componentes electrónicos (sensores y actuadores) compatibles con esta.

<div class="success">

> - La programación por bloques es un método sencillo para comenzar a adquirir la competencia de **pensamiento computacional**, y anima a los alumnos a descubrir el mundo de la programación. A tal fin se ha seleccionado la aplicación online **BitBloq** por ser la más cercana a este método de aprendizaje.

> - Los componentes electrónicos serán circuitos electrónicos Sensores y Actuadores adaptados para ser compatibles con Arduino, estos facilitarán al alumno la comprensión e interacción con el mundo físico real, mediante los proyectos que van a desarrollar.

</div>

Los capacidades que el alumno desarrollará durante son:

- Como fin primordial, fomentar la **creatividad** del alumno y que **sienta muy cercana y sencilla la tecnología** que le rodea, haciéndole ver que **todas la ideas que tenga el alumno**, son realizables en proyectos reales, y que la clave para lograrlo, es **analizar las necesidades** del proyecto y de **dividir los problemas** y sus soluciones en **partes más sencillas** y manejables.

- Cómo fin secundario el alumno tomará conciencia del movimiento global **D.I.Y** (hazlo tú mismo) o **MAKER**, que promueve la autonomía en el aprendizaje, el conocimiento colaborativa, el ingenio personal y las oportunidades de emprendimiento.

- También se alimentará el **espíritu crítico** haciendo que el alumno elija una solución, de entre las muchas posibles y que valore los pros y contras de estas, antes de hacer su elección final. Otra parte importante será que el alumno aprenda que **los errores son parte normal del proceso de innovación y creación** y que lo importante es seguir adelante, intentando nuevas soluciones.

- En los proyectos finales aquí propuestos, será hará indispensable que el alumno **coopere y trabaje en equipo**, requiriéndose que esas **partes más sencillas** que han desarrollado individualmente, encajen perfectamente para dar forma a la funcionalidad final del proyecto.










<h2>
<div id="contexto" class="fonth2tittle">
    <span class="fa-stack fa-lg" >
        <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
        <i class="fa fa-key fa-stack-1x colortools"  ></i>
    </span> Contextualización 
</div>
</h2>

<h3><div id="organizacion" class="fonth3tittle">Organización del Aula</div></h3>

Para la realización de los ejercicios propuestos en las actividades, se utilizará la **Programación por Pares**; dos alumnos por puesto de trabajo, esto favorece varios aspectos en el aprendizaje del alumno:

>- Se potencia el trabajo en equipo, alternando **Roles** de Análisis, Diseño, Desarrollo, Implementación y Prueba.
>- Se incentiva el aprendizaje colaborativo, los conocimientos de uno se suman al par.
>- Mejora la concentración y el enfoque en el ejercicio, disminuyendo los errores.
>- Se mejoran las competencias de razonamiento, dialogo y aceptación de ideas del par.

Cada alumno tendrá su propio Kit Arduino, al que ensamblará los circuitos electrónicos de sensores y actuadores que se requieran en cada ejercicio.

En el supuesto de que existan alumnos de distintos niveles ESO (p.ej. 1º, 2º y 3º) se procurará crear parejas homogéneas (un alumno de nivel ESO superior al otro) para facilitar la asimilación de contenidos.

<h3><div id="conocimiento" class="fonth3tittle">Conocimiento Previo del Alumno</div></h3>

Está propuesta didáctica está orientada a alumnos que tengan conocimientos de **2º ESO** idealmente, (aunque también es fácil adaptar los contenidos para alumnos de 3º y 4º ESO, ampliando el alcance de los proyectos). 
Algunos de los conocimientos que servirán de apoyo para el desarrollo de los proyectos son :

- Matemáticas : 
- Algoritmos. 
- Cálculo de Tiempo de reacción. 
- Números aleatorios.
- Proporcionalidad (Regla de 3), Algoritmo (Mapeo)
- Resolución (precisión y exactitud)
- Cálculo de área, área media, 
- Suma de Gráficas (suma de señales).
- Física : 
- Tiempo de reacción y medida (mili segundos)
- Sensores y Actuadores
- Electrónica de diodo y pulsador
- Ley de Ohm, Resistencia, Voltaje e Intensidad.
- Analógico, Digital
- Espectro de Luz (Luz visible, Luz infrarroja)
- Corriente alterna, continua y conmutación. 
- Sonido.
- Biología : 
- Oído y Ojo Humano.
- Dibujo Técnico : 
- Diagramas de flujo.
- Simbología técnica de circuitos.
- Tecnologías de Información: 
- Programación algorítmica 
- Programación por bloques, variables, puerto serie, aleatoriedad, concatenación de texto
- Control de eventos
- Actuadores PWM

Durante el curso se utilizarán estos conocimientos como base, para introducir al alumno los conceptos relacionados con la algorítmica, y cómo funcionan actuadores y sensores.

<h3><div id="recursos" class="fonth3tittle">Recursos necesarios</div></h3>

Los recursos listados a continuación serán revisados con los responsables del programa educativo del centro, a fin de adaptarlos a sus necesidades.

- 10 Ordenadores Portátiles para los alumnos (con OS Linux, MacOS ó Windows) y Google Chrome instalado.
- 1 proyector y 1 pizarra digital
- Mesas configurables que permitan trabajar por pares o en grupo
- Wifi configurado en los portátiles con conexión a Internet
- Cuentas de acceso por alumno pre-configuradas en Bitbloq
- 20 Kits de robótica Arduino. Se recomienda [BQ Zum Box](https://www.bq.com/en/zum-kit) o similar.

<h3><div id="eleccion-arduino" class="fonth3tittle">Sobre la elección de Arduino</div></h3>

**¿ Por qué Arduino UNO y no otra plataforma ?** Afortunadamente, hoy existen muchas plataformas económicas de prototipado rápido que elegir, para desarrollar nuestros proyectos **MAKER**, pero Arduino se ha alzado entre todas ellas, cómo la opción favorita del movimiento **MAKER** al ofrecer sencillez de conexión y uso de la  electrónica de sensores y actuadores, dispone de pines entrada/salida digital(x14), de entradas analógicas (x6) con una resolución de 10bit, salidas PWM (x4 útiles; entre otros para servos), comunicación entrada/salida por puerto serie (UART), capacidad de desarrollo a alto y bajo nivel, gran número de kits de sensores y actuadores económicos ... etc.

Además muchas de las alternativas que hay a Arduino se basan en el estándar Arduino.

Normalmente suele ser el complemento ideal para placas como **Raspberry Pi** cuyo punto fuerte está en el sistema operativo, la capacidad de computo y la versatilidad de integración con otras plataformas con OS UNIX, Windows o MacOS.

Por otro lado la comunidad **MAKER** de Arduino es muy grande, y existe un elevado número de plataformas OnLine gratuitas donde aprender de otros **Maker** y donde compartir nuestros proyectos personales. [Instructables](http://www.instructables.com), [Make](http://makezine.com), [Circuits IO](https://circuits.io), [Arduino Create](https://create.arduino.cc), [BitBloq](http://bitbloq.bq.com) son algunos ejemplos de la gran difusión que tiene Arduino.

<h3><div id="eleccion-bloques" class="fonth3tittle">Sobre la elección de la programación con bloques:</div></h3>


<p style="text-align: center" ><a href=""><img src="http://i.imgur.com/VU9Zx9n.png"/></a></p>

Como ya se adelantaba en la introducción, la programación por bloques es un método sencillo para comenzar a adquirir la competencia de **pensamiento computacional**, se trata de que cada instrucción del programa, se monta visualmente una detrás de otra, de forma intuitiva, como montando un **Puzle**.

<p style="text-align: center" ><a href=""><img src="http://i.imgur.com/kDve3Ci.png"/></a></p>

Son muchas las aplicaciones ( [Scratch](https://scratch.mit.edu), [Code Studio](https://studio.code.org)...etc ) que usan la programación por bloques para acercar la computación a niños o personas sin conocimientos de Tecnología de Información, haciéndolo un juego.

El proceso cognitivo que favorece la creación de un algoritmo en la mente del alumno, se refuerza automáticamente al representarlo en bloques. Para ilustrarlo vamos a poner un sencillo ejemplo de un programa de suma realizado con bloques:

<p style="text-align: center" ><a href=""><img src="http://i.imgur.com/ycDNEh4.png"/></a></p>

La secuencia de instrucciones de arriba abajo es:
1. A vale 10
2. B vale 5 
3. C vale A + B
4. Envío el valor C por puerto serie.

Si este programa lo quisiéramos desarrollar en la **sintaxis tradicional escrita** sería así:

<p style="text-align: center" ><a href=""><img src="http://i.imgur.com/ZeRrOb4.png"/></a></p>

Aunque los dos programas hacen la misma suma, interpretar el código tradicional requiere más conocimientos que la programación por bloques, también las posibilidades de cometer errores al escribir mal la sintaxis, o declarar mal el tipo de una variable, o inicializar mal la librería de comunicación serie, u olvidarse de cerrar una instrucción con punto y coma, ... etc se incrementan.

La **curva de aprendizaje** se reduce drásticamente al programar con bloques, el alumno puede enfocarse más en la creación del algoritmo y su secuencia de control.

<h3><div id="eleccion-bitbloq" class="fonth3tittle">Sobre la elección del IDE: BitBloq</div></h3>

<p style="text-align: center" ><a href=""><img src="http://i.imgur.com/nRb5ufI.png"/></a></p>

Para programar Arduino (por bloques o de forma tradicional) necesitamos un IDE (Entorno de Desarrollo Integrado) una aplicación sobre la que plasmar el código y luego pasarla a Arduino a través del puerto USB. La página web de Arduino facilita la [descarga](http://www.arduino.org/downloads) de un IDE para el desarrollo tradicional de código. 

Aunque existen muchos otros IDE para el desarrollo por bloques con Arduino, estos presentan ciertas complejidades de instalación o configuración; desde el punto de vista de mantenimiento de las aplicaciones del aula, otros simplemente restricciones de propiedad intelectual. **BQ** con **Bitbloq** ha sabido sumar la facilidad de instalación, configuración y seguimiento en un Aula, con la potencia de una librería de bloques de sensores y actuadores, permitiendo un mayor rendimiento y asimilación de contenidos del alumno.

Estos son los motivos que nos han llevado a escoger [BitBloq](http://bitbloq.bq.com) como IDE, es una aplicación On-Line que provee de forma gratuita el fabricante de electrónica de consumo [BQ](https://www.bq.com/en/maker-world) y que permite tanto el **desarrollo por bloques** como el **desarrollo tradicional**.

Además ofrece más ventajas que facilitan el aprendizaje y el seguimiento del aula:
- Se puede programar la placa **Arduino UNO** estándar (además de productos BQ)
- Las librerías de circuitos sensores y actuadores ya están integradas y listos para usar como bloques
- El IDE incluye el monitor/editor de puerto serie
- El alumno documentará sus creaciones directamente
- El alumno compartirá sus creaciones con el resto del aula en la nube Bitbloq o en redes sociales.
- El seguimiento de los proyectos del aula por parte del profesorado es más sencillo
- Es multiplataforma (Linux, MacOS, Windows). Funciona sobre el cliente Google Chrome
- El alumno descubrirá proyectos en la comunidad Bitbloq realizados por otros usuarios
- Facilita al alumno la transición al desarrollo tradicional de código, para aumentar la complejidad de los proyectos

---









<h2>
<div id="resumen" class="fonth2tittle">
    <span class="fa-stack fa-lg">
        <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
        <i class="fa fa-crosshairs fa-stack-1x colortools" ></i>
    </span> Definición de Objetivos de Aprendizaje
</div>
</h2>

<h3><div id="objetivos-tecnicos" class="fonth3tittle">Objetivos Técnicos</div></h3>

- Comprender y saber programar con bloques :
- Que es un algoritmo
- Qué es el puerto serie de Arduino
- Qué es una variable
- Que es un pulsador y un diodo
- Qué son los bloques de control
- Cómo medimos tiempos con Arduino
- Comprender y saber programar sensores :
- Que es un sensor
- Qué es analógico y que digital
- Diferencias entre pin digital y analógico
- Qué es la Precisión (Resolución)
- Componentes digitales y analógicos
- Componentes analógicos potenciómetro y LDR
- Componentes digitales botón y sensor infrarrojo
- Comprender y saber programar actuadores :
- Qué se un actuador
- Que es la corriente eléctrica y cómo se presenta
- Cómo se utiliza el electromagnetismo para conseguir movimiento
- Cómo se usa la señal PWM para controlar actuadores
- Cómo se compone el color con un dispositivo RGB
- Cómo se reproduce el sonido digitalmente
- Circuitos de componentes actuadores digitales

<h3><div id="objetivos-competenciales" class="fonth3tittle">Objetivos Competenciales</div></h3>

- Promover en el alumno la habilidad de aplicar el pensamiento computacional a la resolución de problemas.
- Mejorar en el alumno la creatividad, motivación al logro y autonomía para gestar soluciones a problemas comunes.
- Promover el aprendizaje colaborativo y el trabajo en equipo.

---
<br><br>







<h2>
<div id="contenidos-plan" class="fonth2tittle">
    <span class="fa-stack fa-lg">
        <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
        <i class="fa fa-binoculars fa-stack-1x colortools" ></i>
    </span> Contenidos y Planificación
</div>
</h2>

En base a los objetivos de aprendizaje citados anteriormente, se han desarrollado los contenidos específicos y las actividades dispuestas en una plan de trabajo, dividiéndolo en **6 sesiones** de **2 horas** cada una (12 horas en total).

Al comienzo de la Sesión I se realizará una presentación de los objetivo y alcance de los contenidos del curso a los alumnos.

Se alternará una sesión de **Teoría y Asimilación** de contenidos que incluye las "Prácticas y Aplicación" de los mismos, con otra de **Realización de un Proyecto Práctico**, en el que el alumno demostrará que ha asimilado los conceptos teóricos y su autonomía al saber aplicarlos a un contexto real.

En las sesiones de proyecto se aplicará el **Proceso de Pensamiento Computacional** promoviendo la resolución de problemas mediante el análisis, el diseño de soluciones reales y poniéndolas a prueba.

Al termino del proyecto el alumno **documentará y compartirá** su trabajo en la nube con el aula. También se realizará una **evaluación** de conocimientos con un **examen tipo test**.

Cada sesión incluye también el apartado **"Puesta en Común"** que persigue el desarrollo de los objetivos competenciales, promoviendo la creatividad y la innovación, ante todo se estimulará al alumno para que busque **retos** y soluciones a problemas cotidianos, mediante la **generación de ideas**

Al termino de la sesión VI se reservará tiempo para la **Mejora Continua** pidiendo a los alumnos que valoren su satisfacción con el curso y sugerencias de mejora.

<h3><div id="contenidos" class="fonth3tittle">Contenidos:</div></h3>


<h4><div class="fonth4tittle">

Sesión I - **Bloques de Control** :</div></h4>
<div style="left:8%; position: relative; width:90%;">

**Sesión de teoría y asimilación sobre cómo se programan los comandos de control en Arduino.**
Presentación del curso Programación y Robótica Arduino. Los contenidos serán : Entender que es un algoritmo y sus partes principales. Ser capaces de inicializar, preparar y ejecutar un algoritmo básico de Arduino. Entender cómo funciona la salida serie de Arduino. Ser capaz de escribir y leer en el puerto serie de Arduino. Entender el bloque de espera. Ser capa de utilizar el bloque de espera. Entender como funcionan los bloques de control. Ser capaces de utilizar los bloques de control de forma autónoma. Entender como funciona una variable. Ser capaz de utilizar las variables. Entender como funciona el bloque de temporizador de Arduino. 
</div><br>


<h4><div class="fonth4tittle">

Sesión II - **Proyecto ¿ Quién Pulsa Botón Más Rápido ?** :</div></h4>
<div style="left:8%; position: relative; width:90%;">

**Sesión práctica en al que el alumno realizará un prototipo que sea capaz de mostrar el tiempo que tardamos en pulsar un botón, tras recibir el aviso de una cuenta atrás.** Para llevarlo a cabo utilizará el proceso de pensamiento computacional con las siguiente fases: Análisis del problema y Diseño. Desarrollo de Bloques. Implementación. Prueba y Documentación. Puesta en común. Al final de esta sesión se realizará un examen tipo test para comprobar la asimilación de conocimientos sobre el uso de los bloques de control en Arduino.
</div><br>


<h4><div class="fonth4tittle">

Sesión III - **Sensores Analógicos y Digitales** :</div></h4>
<div style="left:8%; position: relative; width:90%;">

**Sesión de teoría y asimilación sobre cómo se programan los Sensores Analógicos y Digitales en Arduino**. Los contenidos serán : Entender la diferencia entre analógico y digital. Ser capaz de distinguir los componentes analógicos de los digitales. Entender el funcionamiento de un pin analógico y digital en Arduino. Entender la resolución y la operación matemática de mapeo. Entender el funcionamiento del componente potenciómetro. Ser capaz de programar con el componente potenciómetro. Entender el funcionamiento del componente LDR. Ser capaz de programar con el componente LDR. Entender el funcionamiento del componente Pulsador. Ser capaz de programar when_press y when_release con el Pulsador. Entender el funcionamiento del componente Sensor IR. Ser capaz de programar el componente Sensor IR.
Puesta en común.
</div><br>


<h4><div class="fonth4tittle">

Sesión IV - **Proyecto , Misión Imposible** :</div></h4>
<div style="left:8%; position: relative; width:90%;">

**Sesión práctica en al que el alumno realizará un prototipo que sea capaz de hacer saltar una alarma visual y sonora cuando se interrumpa el haz láser de una barrera perimetral**. Para llevarlo a cabo utilizará el proceso de pensamiento computacional con las siguiente fases: Análisis del problema y Diseño. Desarrollo de Bloques. Implementación. Prueba y Documentación. Puesta en común. Al final de esta sesión se realizará un examen tipo test para comprobar la asimilación de conocimientos sobre el uso de Sensores Analógicos y Digitales en Arduino.
</div><br>


<h4><div class="fonth4tittle">

Sesión V - **Actuadores** :</div></h4>
<div style="left:8%; position: relative; width:90%;">

**Sesión de teoría y asimilación sobre cómo se programan los Actuadores en Arduino**. Los contenidos serán : Entender que es un actuador. Ser capaz de distinguir los distintos actuadores. Entender la corriente alterna, continua y conmutada. Entender la señal PWM y sus aplicaciones. Entender el modelo de color RGB y cómo lo percibe el ojo. Entender el sonido y cómo se reproduce digitalmente. Entender el funcionamiento del componente RELÉ. Ser capaz de programar aplicaciones para un RELÉ. Entender el funcionamiento del componente servo continuo. Entender el funcionamiento del componente servomotor. Ser capaz de programar el posicionamiento de un servomotor. Entender el funcionamiento del componente LED RGB. Ser capaz de programar colores diferentes con el LED RGB. Entender el funcionamiento del componente Buzzer. Ser capaz de programar melodías con el componente Buzzer. Puesta en Común
</div><br>


<h4><div class="fonth4tittle">

Sesión VI - **Proyecto , Comprobador de Baterias AA / AAA** :</div></h4>
<div style="left:8%; position: relative; width:90%;">

**Sesión práctica en al que el alumno realizará un prototipo que sea capaz de mostrar el nivel de capacidad que tiene una batería AA / AAA mostrándolo en forma analógica sobre una escala semicircular**. Para llevarlo a cabo utilizará el proceso de pensamiento computacional con las siguiente fases: Análisis del Problema y Diseño. Desarrollo de Bloques. Implementación. Prueba y Documentación. Puesta en común. Al final de esta sesión se realizará un examen tipo test para comprobar la asimilación de conocimientos sobre el uso Actuadores con Arduino.
</div><br>





<h3><div id="que-es" class="fonth3tittle">Planificación:</div></h3>

<div style="left:8%; position: relative; width:90%;">

Las planificación se ha dividido en tres bloques, que constan de dos sesiones cada uno, debido a que dichas sesiones comparten íntimamente los contenidos y el test de evaluación de conocimientos.
<br><br>
Las actividades en verde son de tipo teórico y/o de introducción, las actividades marcadas en rojo son de comprobación de asimilación y/o prácticas.
<br><br>
Así mismo, los bloques han de impartirse en el orden establecido, ya que para asimilar el conocimiento de los últimos, es imprescindible haber asimilado el conocimiento de los bloques anteriores.
<br><br>
A continuación se exponen los diagramas de Gantt que ilustran los tiempos estimados para el desarrollo de los contenidos/actividades de cada bloque y sesión :

</div>


<h4><div class="fonth4tittle" >	

Planificación **Sesiones I y II** </div></h4>
<div style="left:8%; position: relative; width:90%;">
<img style="" src="http://i.imgur.com/a8lo4mr.png"/>
</div><br><br>


<h4><div class="fonth4tittle" >	

Planificación **Sesiones III y IV** </div></h4>
<div style="left:8%; position: relative; width:90%;">
<img style="" src="http://i.imgur.com/6YkfJTC.png"/>
</div><br><br>


<h4><div class="fonth4tittle" >	

Planificación **Sesiones V y VI** </div></h4>
<div style="left:8%; position: relative; width:90%;">
<img style="" src="http://i.imgur.com/q6fjcBK.png"/>
</div>

---
<br><br>












<h3><div id="que-es" class="fonth3tittle">Sesiones</div></h3>

<div style="left:8%; position: relative; width:90%;">

Los enlaces presentados a continuación mostrarán el programa de actividades a seguir para cada una de las 6 sesiones, la estructura de programa en cada sesión es similar y consta de las siguientes partes:

- **Introducción :** Expone el objetivo general de la sesión.
- **Recursos necesarios :** Medios y/o recursos que se necesitan para impartir el contenido.
- **Resumen de lección :** Son los puntos prioritarios que deberán tratarse.
- **Objetivos de aprendizaje :** Son contenidos y objetivos técnicos específicos que posteriormente se evaluarán en el test del bloque.
- **Aplicaciones transversales :** Son las materias y sus áreas de aplicación en otras asignaturas, que serán tratadas durante la sesión.
- **Inicio :** Expone los puntos que se tratarán como introducción a los contenidos de la sesión.
- **Desarrollo :** Expone los pasos que se seguirán para el desarrollo de la/s actividad/es de la sesión.
- **Puesta en común :** Expone como conducir el espacio reservado al final de la sesión para que los alumnos compartan sus experiencias de aprendizaje durante la sesión, posibles aplicaciones de lo aprendido, y un apartado de conclusión donde se resaltará los conceptos importantes.
- **Reto :** Este apartado en la sesión teórica, hará una introducción a la sesión de proyecto siguiente. Este apartado en la sesión de proyecto planteará cuestiones para mejorar o ampliar la aplicación del prototipo construido.
- **Evaluación :** En el formato propuesto, la evaluación de objetivos técnicos (tests) y competenciales (rubrica evaluación) se realizará al concluir el bloque.

A continuación se exponen los enlaces que llevan cada una de las sesiones que componen esta propuesta didáctica de "Programación y Robótica" con Arduino.
</div>
<br><br>


<div style="left:8%; position: relative; width:90%;">

**Bloque I**
</div>

<div class="fontseparator"></div>

<div class="fontexternallink2">
<a style="color:#ffffff" href="sesion_i.html">Sesion I  teoria</a>
</div>
<div class="fontseparator"></div>
<div class="fontexternallink2">
<a style="color:#ffffff" href="sesion_ii.html">Sesión II - proyecto</a>
</div>

<br><br>
<div class="fontseparator"></div>
<div class="fontexternallinkcomment">
Bloques de Control
</div>
<div class="fontseparator"></div>
<div class="fontexternallinkcomment">
¿Quién Pulsa Más Rápìdo?
</div>
<br><br><br>






<div style="left:8%; position: relative; width:90%;">

**Bloque II**
</div>

<div class="fontseparator"></div>
<div class="fontexternallink2">
<a style="color:#ffffff" href="sesion_iii.html">Sesión III - teoría</a>
</div>
<div class="fontseparator"></div>
<div class="fontexternallink2">
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
<div class="fontexternallink2">
<a style="color:#ffffff" href="sesion_v.html">Sesión V - teoría </a>
</div>
<div class="fontseparator"></div>
<div class="fontexternallink2">
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




<br>
---
<br>









<h2>
<div id="resumen-de-leccion" class="fonth2tittle">
    <span class="fa-stack fa-lg">
        <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
        <i class="fa fa-check-square-o fa-stack-1x colortools" ></i>
    </span> Evaluación
</div>
</h2>

La evaluación de aprovechamiento del curso por parte del alumno se reflejará con una **puntuación final**. Esta nota estará compuesta por **dos puntuaciones que tendrán el 50%** de peso respectivamente, en la puntuación final.

**La primera nota** será la resultante de la media que resulte de los **tres "Test de Compresión"** que se harán al finalizar cada uno de los tres bloques. Cada uno de los "test de comprensión" estará compuesto por 10 preguntas tipo test que versarán sobre los temas y los proyectos impartidos.

**La segunda nota** será la resultante de la media de evaluación del profesor en base a la **Rubrica de evaluación** orientada a valorar los objetivos **técnicos y competenciales** que el alumno ha alcanzado durante el curso.

Ambas puntuaciones se sumarán para dar una percepción de aprovechamiento del curso, ponderado de 0 a 10 puntos.

<h3><div id="que-es" class="fonth3tittle">TestS de Comprensión</div></h3>

<div style="left:8%; position: relative; width:90%;">

Los **TestS de Comprensión** además de servir para evaluar el conocimiento del alumno, incorpora una componente de repaso de la lección, incluyendo introducciones simples al contenidos que se han impartido.<br><br>

Una copia del test se entregará a cada alumno, impresos en color y buena calidad, junto con hoja que tiene la tabla de respuestas, donde el alumno se identificará con nombres, apellidos, curso, grupo, ... etc y emitirá sus respuestas. Los Tests serán devueltos al profesor, para ser reutilizados en más sesiones junto con las respuestas del alumno.<br><br>

A continuación se exponen los enlaces que llevan cada uno de los **test** de los tres bloques.
</div>
<br>


<div class="fontseparator"></div>
<div class="fontexternallink2">
<a style="color:#ffffff" href="sesion_ii_test.html">Test sesiones I y II</a>
</div>
<div class="fontseparator"></div>
<div class="fontexternallink2">
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
<div class="fontexternallink2">
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




<h3><div id="que-es" class="fonth3tittle">Rubrica de Evaluación</div></h3>

<div style="left:8%; position: relative; width:90%;">

La rubrica de evaluación será la herramienta utilizada para evaluar objetivamente el desempeño del alumno en los **objetivos competenciales**, como parte de la **Presentación del Curso**, el alumno recibirá esta información para que sepa con claridad lo que se espera de él.<br><br>
Al termino de cada proyecto el profesor evaluará a cada alumno en las competencias descritas, registrando la nota.<br><br>
</div>

<div style="left:8%; position: relative; width:90%;">
<img style="" src="http://i.imgur.com/kLE7j8Q.png"/>
</div><br><br>



<h3><div id="que-es" class="fonth3tittle">Mejora Continua</div></h3>

<div style="left:8%; position: relative; width:90%;">

Como parte indispensable del curso, al final de este, se entregará un cuestionario a los alumnos para evaluar su percepción de calidad del curso, que aspectos les han gustado más y cuales menos, cuales creen que faltan, cuales creen que se podría mejorar ... etc.<br><br>

Este **feedback** además de ser un requisito necesario para mejorar el curso, servirá para mejorar y adaptar los contenidos y métodos, para futuras sesiones de participación de esta propuesta educativa.<br><br>

</div>


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