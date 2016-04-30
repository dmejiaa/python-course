# Curso de Python


¡Hola a todos los inscritos!

Este es un pequeño tutorial de instalación que queremos que todos los alumnos realicen antes 
de la clase para tener todas las herramientas y programas instalados para comenzar el curso de python.
Veremos la instalación de los siguientes componentes en sus Mac's:

- [Python](#python)
- [Anaconda](#anaconda)

## Python

En sus computadoras ya tienen instalado python. 
Esto lo pueden verificar haciendo lo siguiente:

    cmd + Space

Escribir 

    terminal + Enter

Se abrirá el bash de Mac que es el Command Line. 

Escriban

    $ python

Voilá ya tiene python :)
Todas las Macs traen por default instalado Python. Pueden ingresar el siguiente comando para verificar:

    2+2

Les dará 4, pero ahora esto no nos intersa, queremos armar un ambiente mucho más robusto.
Vamos a salirnos tecleando:

    $ exit()


## Anaconda

Además, de Python es necesario instalar un montón de paqueterias que son utilizadas.
Anaconda es una herramienta fácil de instalar que basicamente es un gestor abierto de paquetes, un administrador de ambiente y de 
distribución de Python, y que contiene una colección de más de 720 paquetes open source  que ofrecen apoyo a la comunidad.
Anaconda también trae instalada una interfaz de python mucho más amigable a la hora de estar programando en python llamado jupyter notebook.


Para instalar ANACONDA vayan a la siguiente página:
    
[Insalación Anaconda](https://www.continuum.io/downloads#_macosx)

Den click en el cuadro azul del lado derecho 
    
    PYTHON 3.5
    MAC OS X 64-BIT
    GRAPHICAL INSTALLER

Al terminal la descarga en sus computadoras

    1. Den click en el .pkg 

    2. Den click en continuar, continuar, continuar, acepto

    3. Dar click en "Instalar en un disco específico"

    4. Seleccionar Macintosh HD

    5. Dar click en continuar

    6. Dar click en Instalar

Les va a pedir contraseña (si tienen) + Enter

    7. Dar click en Cerrar

Listo! 
Ya tenemos Anaconda Instalado.  

### Browser Default
Vamos a verificar que tenemos listo el jupyter notebook de ipython.

Vayan a su browser preferido (Chrome o Firefox) y establezcan a uno de ellos como default browser en configuración.

###Ipython Notebook
Ahora regresemos a nuestra terminal y escribimos:

En la terminal vamos a nuestro dirección root

    $ cd 

Escribimos 

    $ pwd 
Para checar en que directorio están. Les debería de salir algo asi:

    /Users/SU_USUARIO

Escribimos 

    $ cd Documents && mkdir python-course

Aqui nos dirigmos a nuestra carpeta de Documents y creamos una carpeta  llamada "python-course" para guardar todos nuestros trabajos ahí.

Escribmos 

    $ cd python-course && ipython notebook
    $ipython notebook

Se va a tardar unos 5-10 segundos y te lanzará a nuestro browser prestablecido en una nueva ventana localhost:8888/tree

Si llegaron hasta aqui felicidades ya tenemos nuestro ambiente instalado!!!!
Vamos a seguir verificando que todo corra como debe.

### Abrir un archivo en Python 3

Aqui vamos abrir un archivo nuevo.

    1. Dar click en New (lado derecho)
    2. Python 3

Se abrirá nuestra libreta. En la parte superior pueden cambiar el nombre del archivo a "notebook1"
Vamos a meter nuestor primer comando en donde dice "In [ ]:"

    print ("Hello World!")

Debe imprimirse

    Hello World!

Para salir vamos a File -> Close and Halt y luego cerramos nuestra ventana y vamos a la terminal.
Aqui escribimos lo siguiente:

    ctrl + c 
    y + enter


Todo listo para nuestra clase el lunes!


    

