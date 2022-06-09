# Práctica 2
## Creación básica de entorno de ejecución de Azure Machine Learning

![Logo](https://github.com/AngelAlbertoCT/Creacion-basica-Azure-Machine-Learning/blob/main/Imagenes/Nub8-Machine-Learning-With-Azure-2.jpg)

En esta práctica se aprende a crear unentorno de ejecución de Azure Machine Learning. Se utilizarán las herramientas que nos proporciona Azure desde la página http://portal.azure.com/ .

Lo primero será ingresar al [portal de Azure](http://portal.azure.com/) con nuestro usuario y contraseña y lo primero que veremos será nuestra pantalla principal del portal. 

![Imgaml](Imagenes\Imagen1.png)

Para crear un área de trabajo nueva, podemos buscar en la barra del buscador **Azure Machine Learning** o bien seleccionarlo desde la página inicial en el apartado de **Servicios de Azure**. Ahí nos mandará a la siguiente pantalla:

![Imgaml](Imagenes\Imagen2.png)

Presionaremos el botón **crear** para crear nuestro grupo de recursos. Hay que recordar que los requisitos mínimos que se necesitan para crear un recurso en Azure es:
* Una suscripción en Azure
* Un grupo de recursos
* Una región
* Un nombre para el recurso 

Para elegir la carpeta de recursos podemos seleccionar alguna (si ya está creada anteriormente) o crear un nuevo grupo desde la opción **Crear nuevo**. Ahí debemos de nombrar nuestro grupo de recursos. En este caso la nombraremos como **SesionAIP_2**. Para el área de trabajo será nombrado como **Practica2**. Al llenar este par de campos, el resto se autocompletarán, por lo que solo debemos avanzar presionando el botón **Revisión y creación**.

![Imgaml](Imagenes\Imagen3.png)

Se realizará la validación correspondiente y posteriormente presionamos el botón **Crear** y esperaremos a que finalice la creación de nuestro recurso.

![Imgaml](Imagenes\Imagen3.png)
![Imgaml](Imagenes\Imagen4.png)
![Imgaml](Imagenes\Imagen5.png)

Al finalizar el proceso, seleccionamos **Ir al recurso**, pero no trabajaremos en la página a la que nos rediriga; para esto trabajaremos en https://ml.azure.com/ . Al entrar a esta página, podremos observar que ya se ve reflejada nuestra área de trabajo. La seleccionaremos para poder entrar y trabajar sobre ella.

![Imgaml](Imagenes\Imagen6.png)

Del lado izquiero podemos observar la gran variedad de herramientas con las que contamos. 

![Imgaml](Imagenes\Imagen7.png)

Posteriormente vamos a seleccionar un **Proceso** que es una herramienta de las que se encuentran del lado izquierdo de nuestra pantalla. Al hacer esto, procederemos a seleccionar **+ Nuevo**

![Imgaml](Imagenes\Imagen8.png)

Al crear una nueva instancia de proceso, necesitamos realizar la configuración correspondiente. Lo primero será darle un nombre a nuestro proceso. Para esta práctica la nombraremos **notebook-practica2**. Para el tipo de máquina virtual dejaremos **CPU** que es la seleccionada por defecto. Finalmente para el tamaño de la máquina virtual se recomienda elegir la opción **Standard_DS11_v2**. Al finalizar esta configuración, podemos seleccionar el botón **Crear** y esperaremos a que finalice el proceso.

![Imgaml](Imagenes\Imagen9.png)

![Imgaml](Imagenes\Imagen10.png)

![Imgaml](Imagenes\Imagen11.png)

Para esta práctica también se utilizará la herramienta **Notebook**. Esta herramienta es un entorno virtual que sirve para ejecutar código Python, regularmente. La ventaja de esto es que, no existe la necesidad de instalar el lenguaje de programación en la computadora que trabajemos, sino que, todo el proceso se ejecutará en la nube.  

Al abrir nuestra herramienta, vamos a crear un archivo en  **Crear archivo** y lo nombraremos como **HelloWorld.ipynb**

![Imgaml](Imagenes\Imagen12.png)

Al finalizar la creación de nuestro documento, vamos a proceder a crear nuestro primer programa en Python utilizando las herramientas de **Azure**. Procedemos a escribir el código correspondiente para imprimir el famoso mensaje "Hello world". Finalmente corremos nuestro programa con el botón que se encuentra a la izquierda de nuestra línea de código **Ejecutar celda**

![Imgaml](Imagenes\Imagen13.png)

Y así es como podemos apoyarnos de Azure para poder crear un entorno de ejecución. Como se pudo observar, son pasos sencillos los que se tienen que seguir y toma poco tiempo el proceso de creación.
