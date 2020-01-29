# Manual de Usuario Github

### Breve Introducción a los Sistemas de Controles de Versiones




### Aspectos básicos de GIT

Git es un sistema de control de versiones distribuido que se diferencia del resto en el modo en que modela sus datos. La mayoría de los demás sistemas almacenan la información como una lista de cambios en los archivos, mientras que Git modela sus datos más como un conjunto de instantáneas de un mini sistema de archivos.

### Uso básico de GIT

#### Creación de un repositorio 

Hacer click en el siguiente botón para crear un nuevo repositorio.  

![Crear Nuevo Repositorio](https://github.com/John-DAW/Manual_De_GitHub/blob/master/2020-01-29%2013_12_46-Window.png?raw=true)


 
Damos un nombre al repositorio. En este caso le llamamos **manual**.
Es opcional incluir una descripción de nuestro repositorio, pero nos ayudará a saber qué contiene el repositorio.
Después selecionanmos **Public** en vez de Private. Esto permite que el repositorio lo pueda ver cualquier persona, pero nosotros elegimos quien puede hacer commits.
Selecionamos **Initialize this repository with a README**. Esto crea un archivo README donde podemos explicar qué es nuestro repositorio y para qué funciona. Ademas clona el repositorio en la máquina local.
También nos da la opción de añadir un .gitignore para selecionar archivos que no queremos que se suban al repositorio.
Por último nos da la opción de añadir una licencia a nuestro proyecto.
Cuando este todo bien configurado, hacemos click en  **Create Repository**

![Propiedades del Repositorio](https://github.com/John-DAW/Manual_De_GitHub/blob/master/Repositorio.png?raw=true)


### Subir un archivo al repositorio

Una vez dentro de nuestro repositorio podemos crear, subir o encontrar archivos. Vamos a crear un archivo: 


![Creación de un archivo]()

Se ha creado un archivo **prueba.txt**. Ahora tenemos que hacer un **commit** para que resida en nuestro repositorio. 

![Commit de archivo prueba.txt]()

Necesitamos crear un pequeño resumen de los archivos que vamos a modificar del repositorio. Este paso no se puede omitir. Lo que si que es opcional es si queremos añadir más información del commit que vamos a realizar. 

Tenemos dos opciones: 

1. Hacer un commit al branch Master 
2. Crear un nuevo Branch 

Selecionamos la primera opción. 

### Editar un archivo del repositorio

Podemos modificar un archivo desde la propio página web utilizando el siguiente icono dentro del archivo seleccionado.

![Editar un archivo](https://github.com/John-DAW/Manual_De_GitHub/blob/master/Editar.png?raw=true)

o podemos clonar el repositorio a nuestro ordenador y luego lanzar un commit al branch Master. 