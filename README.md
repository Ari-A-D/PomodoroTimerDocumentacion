<h1>My Timer - POMODORO</h1>

<p>
  <img src="![vista](https://github.com/Ari-A-D/PomodoroTimerDocumentacion/assets/54744627/fd526be7-fcb5-4ea7-ab9c-253f80746c1d)" alt="Vista principal POMODORO" width="40%">
</p>

<h2>Resumen</h2>
<p>Para la tediosa tarea de los programadores que no encuentran tiempo o se ven inmersos en la programación y olvidan documentar, ya sea el codigo o realizar un seguimiento para luego presentar en su informe. Creo un timer básico programable, en este caso con el fin de controlar las horas para mi ultima practica profesional. El mismo
hace una cuenta regresiva con las horas a trabajar, realiza cortes para que te tomes el tiempo de escribir un breve resumen de lo que se esta desarrollando y/o documentar, "Corta" las actividades que estes realizando con una ventana emergente para forzarte a completarlo.
La escritura lo vuelca en un excel, que se crea con la fecha del dia y guarda también la hora dentro. Crea un excel por día, con el fin de tener un seguimiento de las horas invertidas también para se cobradas.</p>
<h2>Tecnologia</h2>
<p>El mismo esta realizado en python, TeX y la interfaz con una libreria de HTML para python.</p>
<h1>Especificaciones del programa</h1>
<p>Fue hecho un ejecutable portable (llevarlo en un pendrive de manera presencial al lugar de trabajo) con el fin de que el tiempo transcurrido fuera innamobible para realmente utilizar las horas correspondientes, una vez terminado el tiempo programado se reiniciara, por lo que se pueden crear varios ejecutables para varias tareas, fue creado con la idea de que lo utilice el empleador y solo el mismo lo controle.</p>  
<h2>Funciones de los botones</h2>
<ul>
  <li>Iniciar: inicia el temporizador (cuenta regresiva del tiempo hacia atrás)</li>
  <li>Pausar: pausa el temporizador para que puedas realizar actividades no relacionadas con programar</li>
  <li>Detener: detiene el temporizador, si la ventana se cierra, cuando se vuelve a ejecutar el programa, el inicio será desde el momento que se detuvo, por lo que se seguiran computando las horas que se debe cumplir</li>
</ul>
<h2>Funcion documentar</h2>
<ul>
  <li>Documenta cuando inicia el boton y luego mediante intervalos de tiempo programado</li>
  <li>Si se pausa solo se documentará cuando se inicia nuevamente y luego volverá a hacerlo por intervalos</li>
  <li>Cuando se detiene, también documenta cuando se da incio al temporizador y vuelve a cumplir la función de intervalos</li>
</ul>
<h2>Planilla de documentación</h2>
<p>Cuando se realiza el guardado de la documentación y/o escritura, una ventana emergente previa al alerta de "guardado exitoso" pregunta si esta en modo presencial o remoto. 
Una vez realizado el guardado, si es la primera vez que se inicia el temporizador en el día, creara un excel que tendrá como nombre la FECHA. Si se pausa o detiene, o simplemente se vuelve a iniciar por mero error, y el excel del día ya se creó, solo seguirá actualizando las filas de la planilla de ese día.<br>
El excel tiene 3 columnas, la primera que guarda la fecha y la hora, la segunda tiene el modo de trabajo que puede ser "presencial" o "remoto" y la tercera guarda la descripción de lo que ingreso en la ventana documentar. Los excel se pueden encontrar en la carpeta "bitácora" que se creo para contener los excels.</p>
