Tarea 1:
Para configurar el usuario usamos el comando "git configure --global user.name <nombre usuario>"
Para configurar el correo usamos el comando "git configure --global user.email <email usuario>"

• Preguntas de reflexión: 
1. ¿Para qué sirve el comando git init?¿Qué carpeta oculta se crea automáticamente para rastrear los cambios?.
El comando git init sirve para inicializar la carpeta en la que te ubicas como repositorio de git. La carpeta para rastrear cambios se llaman ".git".
2. ¿Qué comando has usado para confirmar que tu identidad es la correcta antes de empezar?
He utilizado los comandos "git configure user.name" y "git configure user.email"

Tarea 2:

Creamos los archivos, en el archivo .gitignore, añadimos la línea *.txt para que no se rastreen los archivos txt.

• Preguntas de reflexión: 
1. ¿Por qué es importante el uso de .gitignore en proyectos profesionales?
Es importante ya que permite tener controlados que archivos y carpetas son rastreados para nuestros commits y podemos hacer que se ignoren algunos tipos de archivos especificos.
2. Si un archivo está "preparado" (staged), ¿en qué área de Git se encuentra y cuál es el comando para ver esta diferencia antes de confirmar?.
Cuando un archivo esta en staged está en el área de preparación, en el que podremos revisar su estado antes de realizar un commit.

Añadimos el contenido al archivo txt.

Tarea 3:

Creamos la rama con "git checkout -b <nombre rama>" o "git branch <nombre rama>".

• Preguntas de reflexión: 
1. ¿Qué ocurre con los archivos de tu carpeta local cuando saltas de una rama a otra? 
Cuando me muevo entre ramas, los archivos desaparecen y aparecen según el estado en el que esta cada rama.
2. ¿Cuál es la principal ventaja de trabajar con ramas independientes en lugar de hacer todo en la rama main?.
Trabajar con ramas independientes a main te permite tener diferentes espacios de trabajo para aplicar cambios individuales (como añadir estilos en este ejemplo) y ver como funcionan antes de pasarlo a la versión live del programa.

Tarea 4.

Nos conectamos al repositorio de github con "git remote add <repositorio remoto> <enlace>".
Usamos git push para subir la rama main.

• Preguntas de reflexión: 
1. Al clonar un repositorio, ¿qué nombre recibe por defecto el servidor remoto en nuestra configuración local?.
Recibe el nombre de origin
2. ¿Qué comando usarías para ver la URL del servidor remoto que acabas de configurar?
git remote nos permite ver la url del servidor remoto.

Tarea 5.

• Preguntas de reflexión: 
1. ¿Qué comandos has utilizado para comprobar si el repositorio local está actualizado? 
He usado git fetch
2. ¿Cuál es la diferencia fundamental entre ejecutar un git fetch y git pull según lo que acabas de experimentar?.
git fetch solo comprueba si hay cambios en el repositorio remoto, git pull hace lo mismo pero además los introduce en el repositorio local.

Tarea 6.

• Preguntas de reflexión: 
Indica los tres comandos que más te ha costado entender y explica por qué.
Los comandos que más me han costado entender han sido principalmente git fetch y git pull, ya que no entendía en un principio la diferencia entre ambos. También me ha costado entender git remote add porque no sabia que tenia que colocar yo el alias del servidor.



