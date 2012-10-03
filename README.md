Primer-Proyecto-MooWheel
========================

Introduccion
------------

El presente proyecto consta de crear una aplicación en XUL diseñada para utilizar la librería llamada MooWheel.js y
otras adicionales que complementan su funcionalidad. El MooWheel permite el diseño de gráfos circulares con conexiones
entre sus nodos, a partir de un arreglo hecho en javascript.

Descripción del contenido a desplegar
-------------------------------------

El contenido a desplegar se basa en un arreglo hecho en javascript, el cuál es tomado por la librería MooWheel y genera
un grafo circular, que permite ver las conexiones existentes entre los nodos. Todas estas conexiones estan presentes en
el arreglo y la librería interpreta cada uno de ellos.

Definición de estructuras de datos
----------------------------------

El programa lee un arreglo en javascript que esta dividido en:

a. ID: permite que la librería reconosca las conexiones
b. Nombre: es el nombre que se despliega en el grafo cuando es generado visualmente por la librería
c. Conexiones (el cuál es un arreglo): es un arreglo de ID's que establece las conexiones entre los nodos

Forma de compilación, ejecución y utilizacion de la aplicacion
--------------------------------------------------------------

La forma de compilar y ejecutar el proyecto es de la siguiente manera:

a. Abrir en cmd
b. Ir a la carpeta contenedora del firefox.exe
c. Copiar la carpeta del proyecto a C:/
d. Ejecutar en el cmd el siguiente comando:
    firefox.exe -app "C:/myapp/application.ini"
o si tiene instalado el xulrunner
Repetir el paso a.
b. Ir a la carpeta contenedora del xulrunner
c. Ejecutar el siguiente comando
    xulrunner.exe "C:/myapp/application.ini" -jsconsole
    
Limitaciones observadas y posibles mejoras
------------------------------------------

Limitaciones:

a. La librería es muy complicada de utilizar y tenía algunos fallos con respecto a lo que necesitabamos que hiciera con
XUL.
b. XUL no es 100% compatible con la librería por lo tanto no mostraba las conexiones en tiempo real, cuando se elegían.