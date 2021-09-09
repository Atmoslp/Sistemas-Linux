# Sistemas-Linux
Instalación de Sistemas Linux


![ÍNDICE](https://user-images.githubusercontent.com/89795512/132738954-ee56d5e2-8385-4a9b-bf6c-6f18d89e8b70.png)


1.1. Interfaces en modo texto	

    1.2. BASH	
    1.3. Terminales virtuales	
  
2.1. Interfaces gráficas en Linux	

    2.2. XWindow	
    2.3. Gnome	
    2.4. KDE	
    2.5. Xfce	
    2.6. LXDE	
    2.7. Atajos de teclado	

3.1. Programas instalados. Agregar, eliminar y actualizar software del sistema.	

    3.2. Repositorios	
    3.3. Gestor paquetes Synaptic	
    3.4. Centro de software de Ubuntu	
    3.5. Paquetes de instalación	
    3.6. Instalar desde el código fuente	
    3.7. Instalar paquetes .deb	
  
  
4.1. Actualización y mantenimiento de controladores de dispositivos	

  4.2. Actualizar drivers NVIDIA	
  4.3. Actualizar drivers ATI/AMD	
  
  
Configuración del sistema	
Arranque y parada del sistema

<br>
<br>


<b> Utilización del sistema operativo: Modo orden, modo gráfico. </b>

El intérprete de comandos es la interfaz entre el usuario y el SO. Por esta razón, se le da el nombre "shell", que significa "caparazón". Existen distintos intérpretes de comandos en el mundo Unix: csh, bash, tcsh, ksh, zsh.. Pero todos son muy parecido. 

Unix está formado por procesos y ficheros. Y no hay nada más.

    • Los sockets de comunicación son ficheros
    • Los directorios son ficheros
    • Los ficheros son ficheros.
    • Los dispositivos como el disco, el cdrom, la pantalla, están representado como un fichero en el sistema Linux, dentro de /dev

La shell actúa como un intermediario entre el SO y el usuario gracias a líneas de comando que este último introduce. En Linux existen Shell en modo gráfico y en modo texto.

	Los shell en modo gráfico más utilizados en Linux son Gnome y KDE

La función de los shell en modo texto es la de leer la línea de comandos, interpretar su significado, llevar a cabo el comando y después arrojar el resultado por medio de las salidas.

<br>
<br>


<b> Interfaces en modo texto </b>

Es un archivo ejecutable que debe interpretar los comandos, transmitirlos al sistema y arrojar el resultado

Existen varios shells de texto. Los más comunes son:

    • bsh (llamada "Bourne shell")
    • bash ("Bourne again shell")
    • csh ("C Shell")
    • Tcsh ("Tenex C shell")

Sus nombres suelen coincidir con el ejecutable. Cada usuario tiene una Shell predeterminada, la cual se activará cuando se abra un indicador del comando Shell predeterminada. Es posible cambiar de Shell ejecutando el archivo ejecutable correspondiente, por ejemplo:/bin/bash
	
<b> ** 2.1 BASH </B>


El "Bourne Again shell" (Bash) fue creado para usarlo en el proyecto GNU
La intención fue que fuese el intérprete de comandos estándar en el sistema GNU. "Nació" oficialmente el domingo, 10 de enero de 1988. 
Brian Fox fue quien programó las primeras versiones de Bash. Chet Ramey es ahora el mantenedor oficial del shell bash siendo la última versión la 4.4.

Podemos abrir fácilmente un terminal con la combinación de teclas CTRL + ALT +  T o buscando terminal en la búsqueda de Ubuntu.
![image](https://user-images.githubusercontent.com/89795512/132739305-ac601d37-c256-4e89-ab0c-7665f3a22fdd.png)


<br>
<br>

<b> Terminales virtuales </b>

En GNU/Linux disponemos de las llamadas terminales virtuales. Son como varias computadoras dentro de la nuestra. En cada una de ellas podemos registrarnos con usuario y contraseña.

También  podemos tener una cantidad determinada de programas abiertos. Por defecto,  las distribuciones de GNU/Linux incluyen aproximadamente seis terminales virtuales en modo texto y una sola para el modo gráfico.Para acceder a las terminales de modo texto simplemente tenemos que presionar la combinación de teclas siguiente: CTRL+ALT+TECLAFUNCIONx siendo x un numero del 1 al 6 para cada tecla de función (de F1 a F6 o de F2 a F7).

Desde el modo texto para pasar a otra terminal virtual simplemente debemos presionar la combinación de teclas: ALT+TECLAFUNCIONx

¿Ocurre algo al usar terminales virtuales en Linux? En absoluto. Todos los programas quedan en ejecución, por lo que en cualquier momento podemos volver a la terminal anterior para continuar operando la aplicación que teníamos aierta en dicho espacio virtual.

Finalmente para volver de una terminal de texto a una terminal gráfica, debemos presionar una de las siguientes combinación de teclas (dependiendo de la distribución:

ALT+F7

ALT+F1

<br>
<br>



<b> ** 1.1Interfaces gráficas en Linux </b>


3.1 XWindow

X­Window (o sistema de ventanas X en castellano) es el nombre por el que se conoce al entorno gráfico usado por los sistemas Unix. Desarrollado desde mediados de la década de los 80 en el MIT (Instituto Tecnológico de Massachussets) se encuentra actualmente en su versión 11, por lo que normalmente suele ser referenciado como X11. X­Windows proporciona una interfaz gráfica (GUI) al mundo de Linux. XWindows, al igual que el sistema operativo Windows de Microsoft, ofrece una forma de manejo de algunos
de los elementos de interacción más comunes como ventanas, cuadros de diálogo, botones y menús. 

XWindows es quien proporciona las capacidades gráficas que hacen de las plataformas basadas en Linux la elección para el desarrollo de muchas aplicaciones de ingeniería y diseño, y es X­Windows lo que hace posible que Linux sea un competidor serio en el mercado de los sistemas operativos para PC. De forma simple, se puede decir que X­Windows es una interfaz gráfica completa para Linux y, por extensión, para Unix. Pero esto no es todo, X­Windows es un entorno muy configurable que proporciona un amplio abanico de opciones para el usuario y para el diseñador de aplicaciones. X­Windows está compuesto por dos elementos principales: 

