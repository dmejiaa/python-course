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

Vamos a salirnos tecleando 

    $ exit()


## Anaconda

Además, de python es necesario instalar un montón de paqueterias que son utilizadas en python.
Anaconda es una herramienta fácil de instalar  que basicamente es un gestor abierto de paquetes, un administrador de ambiente y de 
distribución de Python, y que contiene una  colección de más de 720 paquetes open source  que ofrecen apoyo a la comunidad.
Anaconda también trae instalada una interfaz de python mucho más amigable a la hora de estar programando en python llamado jupyter notebook.


Para instalar ANACONDAvayan a la siguiente página:
    
[Insalación Anaconda](https://www.continuum.io/downloads#_macosx)

Den click en el cuadro azul 

    MAC OS X 64-BIT
    GRAPHICAL INSTALLER

Al terminal la descarga en sus computadoras

    Den click en el .pkg 

    Den click en continuar, continuar, continuar, acepto

    Dar click en "Instalar en un disco específico"

    Seleccionar Macintosh HD

    Dar click en continuar

    Dar click en Instalar

Les va a pedir contraseña (si tienen) + Enter

    Dar click en Cerrar

Listo! 
Ya tenemos todo Anaconda Instalado.
Vamos a verificar que tenemos listo el jupyter notebook de ipython.

Vayan a su browser preferido (Chrome o Firefox) y establezcan a uno de ellos como default browser en configuración.

Ahora regresemos a nuestra terminal y escribimos:

    $ipython notebook

Se va a tardar unos 5-10 segundos y te lanzará a nuestro browser prestablecido en una nueva ventana  localhost:8888/tree

Si llegaron hasta aqui felicidades ya tenemos nuestro ambiente instalado
Vamos a seguir verificando que todo corra como debe.

###Verificación

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
    cd python-course && ipython notebook

Nos va abrir nuevamente el browser con nuestra notebook.
Aqui vamos abrir un nuevo archivo 
    

