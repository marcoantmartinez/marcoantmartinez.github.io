<p style="text-align:center;">
<img src="https://s-media-cache-ak0.pinimg.com/originals/02/be/06/02be068cf3467a0e5665fc6e8dcd7eb7.jpg" vidth="100%"/></p>

<h1>
    <div style="width:100%; border-radius: 15px;padding:0px;background-color:#5e8421;line-height:0;color:#ffffff">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-sitemap fa-stack-1x" style="color:#5e8421" ></i>
        </span> BLOQUES DE CONTROL
    </div>
</h1>

<br>En esta lección los estudiantes aprenderán como funcionan los bloques de control principales de Arduino, cómo programar algoritmos, cómo mostrar datos y qué son los sensores y actuadores. </br>
<br>Finalmente serán capaces de desarrollar el juego **Quién pulsa el botón más rápido**.</br>


<h2>
    <div style="width:75%;border-radius: 15px;padding:0px;background-color:#729f28;line-height:0;color:#ffffff">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-wrench fa-stack-1x" style="color:#729f28" ></i>
        </span> Recursos necesarios
    </div>
</h2>

- Cuentas de Bitbloq activadas para los alumnos - grupos
- Placa Arduino con alimentación y conector USB (por alumno o grupo)
- Componente pulsador.
- Componente LED.
- Pizarra y proyector.

<h2>
    <div style="width:75%;border-radius:15px;padding:0px;background-color:#729f28;line-height:0;color:#ffffff">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-list-ol fa-stack-1x" style="color:#729f28" ></i>
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
    <div style="width:75%;border-radius:15px;padding:0px;background-color:#729f28;line-height:0;color:#ffffff">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-crosshairs fa-stack-1x" style="color:#729f28" ></i>
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
    <div style="width:75%;border-radius:15px;padding:0px;background-color:#729f28;line-height:0;color:#ffffff">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-random fa-stack-1x" style="color:#729f28" ></i>
        </span>  Aplicaciones Transversales
    </div>
</h2>

- Tecnologías de Información - Programación, algorítmica, bloques control, variables, puerto serie, aleatoriedad, concatenación de texto.
- Física - Tiempo de reacción y medida (mili segundos), Sensores y Actuadores, Electrónica de diodo y pulsador, ley de Ohm, Resistencia, Voltaje e Intensidad.
- Matemáticas - Algoritmos. Cálculo de Tiempo de reacción. Números aleatorios.


<h2>
    <div style="width:75%;border-radius:15px;padding:0px;background-color:#729f28;line-height:0;color:#ffffff">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-power-off fa-stack-1x" style="color:#729f28" ></i>
        </span>  Inicio
    </div>
</h2>

- Pedir a los alumnos que piensen en algoritmos, darles un ejemplo, hacerles ver que aunque no pensamos en ellos, están presentes en todas las actividades diarias de todos nosotros.
- Tomar dos algoritmos uno muy sencillo y otro complicado, dividir la clase en dos grupos, hacerles salir a la pizarra y pedirles que desarrollen los pasos en 5 minutos máximo.
- Revisión del trabajo, profundizar en el concepto de complejidad del algoritmo y su división en varios pasos para hacerlo más simple.


<h2>
    <div style="width:75%;border-radius:15px;padding:0px;background-color:#729f28;line-height:0;color:#ffffff">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-film fa-stack-1x" style="color:#729f28" ></i>
        </span>  Desarrollo
    </div>
</h2>

1. Arrancar el navegador Google Chrome e iniciar la sesión del BitBloq
2. Los alumnos - grupos, siguen las actividades de esta sección guiados paso a paso por el profesor.
3. Resolver las dudas de los alumnos según vayan apareciendo.




<h2>
    <div style="width:75%;border-radius:15px;padding:0px;background-color:#729f28;line-height:0;color:#ffffff">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-users fa-stack-1x" style="color:#729f28" ></i>
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
    <div style="width:75%;border-radius:15px;padding:0px;background-color:#729f28;line-height:0;color:#ffffff">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-trophy fa-stack-1x" style="color:#729f28" ></i>
        </span>  Reto
    </div>
</h2>

- Desarrollo del juego **Quién pulsa el botón más rápido**
>- ¿ Qué pasa si el tiempo que hay entre el Preparados, Listos, Ya del juego **"Quién pulsa el botón más rápido"** es aleatorio entre 1 y 5 segundos ?
>- ¿ Qué otros usos se pueden dar a este circuito ?



<h2>
    <div style="width:75%;border-radius:15px;padding:0px;background-color:#729f28;line-height:0;color:#ffffff">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-check-square-o fa-stack-1x" style="color:#729f28" ></i>
        </span>  Evaluación
    </div>
</h2>

Al termino de la sesión se evaluará con un test de 10 preguntas la asimilación de conocimientos de cada alumno.
