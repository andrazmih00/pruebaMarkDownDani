# GitHub

GitHub es una plataforma de desarrollo colaborativo que permite almacenar, gestionar y compartir proyectos de código. Basada en Git, facilita el control de versiones y la colaboración entre programadores mediante herramientas como pull requests, ramas y revisiones de código, ayudando a equipos a trabajar juntos en proyectos de software de forma eficiente.

## ¿Por qué utilizar GitHub?

GitHub ofrece grandes facilidades para la creación de trabajos colaborativos. De igual manera, no censura o discrimina lenguaje de programación alguno, los acepta a todos sin inconveniente, por lo que le facilita el trabajo a la gran mayoría de los desarrolladores.

Te permite subir tus repositorios de código para que sean almacenados en la nube a través del sistema de control de versiones de Git y participar también en el desarrollo de proyectos de terceros, lo que significa que cualquier usuario de GitHub puede encontrar tu código, aprender de él y mejorarlo. Al igual que tú puedes acceder a los repositorios de código de otras personas.

## ¿Como usar GitHub?

**1. Crear un Repositorio de GitHub**

Lo primero que debes tener es una cuenta creada en GitHub. Registrarse es gratuito. Una vez que tengas la cuenta, inicia sesión con tu usuario y clave. Luego, sigue estos pasos:

* En la esquina superior derecha de cualquier página, encontrarás un signo de + que sirve para realizar las acciones de la página. Das clic en el símbolo y creas un **nuevo repositorio**.
  
* Una vez realizado eso, debes llenar los datos que se solicitan, darle un nombre y definir si será público o privado y colocar una pequeña descripción sobre tu repositorio.

* Activa el checkbox que dice iniciar tu repositorio con un **README**, este será tu primer archivo, la presentación de tu proyecto.

* Presiona el botón de “crear repositorio” y listo. Ya tienes tu primer repositorio creado.

**2. Crear ramas (branches) en GitHub**

Rama (branch) se puede ver como el mapa lineal de los commits que has realizado al archivo. Cuando empezamos un proyecto con GitHub, automáticamente nos crea una rama llamada master, a partir de la cual comenzaremos a crear nuestras propias ramas.

* Entra en tu repositorio.
* En la parte superior de la página da clic en **Rama actual**. En la lista de rama selecciona la rama llamada master, que será nuestra base para la que estamos creando.
* Luego presiona **New Branch** (Nueva Rama).
* Añade el nombre de tu nueva rama.
* Selecciona la rama actual (master) en la que se basara la nueva rama.
* Presiona **Create Branch** (Crear Rama).

**3. Entender los commits de GitHub**

*Commit* es la denominación que se le da a los cambios guardados en Github. En otras palabras, commit es la acción de subir los archivos con los cambios realizados en tus repositorios y guardarlos.

Para realizar el commits de Github debes seguir los siguientes pasos:

1.- Se debe verificar el estado de nuestro repositorio ejecutando el siguiente comando:
  
      git status

Una vez realizado el comando anterior, te aparecerá una lista con los archivos que fueron modificados y con los que están agregados al índice, listos para subir.

2.- Si aún existen archivos sin agregar al índice, debes ejecutar el siguiente comando:

      git add

De esta forma se añaden todos los cambios pendientes.

3.- Ahora vamos a generar el commit ejecutando el siguiente comando:

    git commit -m "Un comentario de los cambios realizados"

Es importante que en este paso agregues una descripción clara, esta se guardará en el historial y podremos entender mejor los cambios más adelante. Cuando no se describen bien los cambios que se realizaron, volver a reparar un bug (error) puede ser una pesadilla.

**4. Crear solicitudes de extracción (pull requests) en GitHub**

Las solicitudes de extracción o **pull requests** son el formato para contribuir con los cambios que realizaste a un código base **para que sean fusionados**.

Los pasos que debes seguir son los siguientes:

1.-Haz clic en el botón bifurcación (Fork) en la página de GitHub que contiene la base de código original al que deseas contribuir, para crear una misma copia en tu cuenta. Bifurcar un repositorio te permite realizar cambios y experimentos sin la preocupación de afectar el proyecto original.

2.- Obtén la URL de la bifurcación que acabas de crear.

3.- Usa el comando *git clone* para clonar la base de código de Fork en la página de tu Github en tu computadora local.

      git clone

4.- Realiza los cambios que consideres necesarios en tu repositorio local. Agrega y modifica archivos.

5.- Ahora inserta el repositorio de código local en el repositorio de código de Fork en Github, con los siguientes comandos:

      git add
------------------------------------------------------------------------------------

      git commit
------------------------------------------------------------------------------------

      git push

6.- Vuelve a la página de tu fork en Github.

7.- Presiona el botón Solicitud de Extracción (pull request).

8.- Dale un nombre a tu solicitud de extracción, colocando los detalles de los cambios que realizaste y finalmente presiona el botón enviar.

https://www.xataka.com/basics/que-github-que-que-le-ofrece-a-desarrolladores
https://platzi.com/blog/que-es-github-como-funciona/#:~:text=GitHub%20te%20permite%20subir%20tus,%C3%A9l%20y%2C%20por%20qu%C3%A9%20no%2C








  



