# FabianOrecchia
1.	¿Qué es git?

Es un sistema de control de versiones, el mismo controla o administra las distintas versiones de un proyecto. A medida que el proyecto va evolucionando con el tiempo GIT ayuda a controlar las diferentes versiones del mismo.

 
2. ¿Por qué queremos utilizar git?

Por qué nos va a ayudar a tener un listado de los cambios que se van efectuando dentro de un código. También ayudar a los diferentes desarrolladores a controlar su código. 
El mismo se puede subir a la web y diferentes desarrolladores pueden editar tu código para mejorarlo o aplicar cambios desde una copia que ellos pueden alterar sin modificar la original sin la autorización del dueño o creador del mismo.

3. ¿Qué es el bash que instala git?

Es una herramienta tipo consola como CMD, pero con mejores funcionalidades. Se pueden ejecutar comandos para acceder a diferentes directorios o carpetas. 
Desde el bash se pueden manipular o gestionar yodo el proceso al momento de realizar un proyecto.

4. Describa los estados (working directory, staging area, repository)

Working Directory: es donde el desarrollador va a estar trabajando con todos los archivos. Cuando se llega a una primera versión del software se traspasa al Staging Área.
Staging área: donde se van a ir agregando los archivos que el desarrollador va a preparar para el guardado. Es decir, se van guardando las diferentes versiones.
Repository:  Finalmente cuando se esta decidido sobre los cambios en un proyecto se van a pasar a un repositorio.

5. Describa el flujo para crear un nuevo repositorio git.

Primero nos ubicamos en la carpeta donde estamos trabajando nuestro proyecto mediante el bash. Despues ejecutamos el comando git init para da comienzo al proyecto. Ejecutamos el comando commit el cual crea un punto de control. Mas tarde ejecutamos el comando git remote add origin [dirección en "github.com" donde se va a guardar el proyecto]. Por último ejecutamos el comando git push -u origin master.

6. Describa el flujo para agregar un archivo simple al repositorio.

Para agregar los archivos al repositorio se utiliza el comando git add "nombre del archivo" o bien git add .(punto) para agregar todos los archivos juntos.

7. Describa el flujo para cambiar el archivo agregado y guardar los cambios en el repositorio.
Mediante el comando git checkout -- revertimos los cambios de los archivos. Ejecutamos el comando git commit para guardar en el repositorio.

8. ¿Cómo hago para ignorar un archivo o carpeta?
Para poder ignorar un archivo/carpeta, se debe crear un archivo dentro del código con el siguiente nombre “.gitignore”.
Ahora bien, dentro de ese archivo .gitignore, se deben escribir los nombres de los archivos o carpetas que el desarrollador quiere ignorar. 



9. Explique qué es un branch. Dé un pequeño ejemplo de cómo haría uno.

Un Branch es una copia en paralelo del código original, tiene varios usos, por ejemplo, se puede crear una rama paralela para poder crear una nueva funcionalidad sin que el código original se vea afectado en caso de que esa nueva opción no funcione.
Se hace mediante comandos, con el comando “git branch” nos muestra la opción master (La original). Podemos crear una rama mediante la línea de comando: git branch “Nombre de la versión alternativa”.

10. ¿Qué hago con `git add.`?
Es para poder pasar los archivos desde el working directory hacia el staging área.

11. ¿Cómo cambiamos de un branch a otro?
Para mover de la versión original del código a la alternativa, se ejecuta el comando: git checkout *Nombre de la versión alternativa*

12. Investigue qué es Markdown y responda todas las preguntas anteriores en este lenguaje (con el nombre de archivo RESPUESTAS.md). Súbalo al repositorio.

Markdown es un lenguaje de marcado que facilita la aplicación de formato a un texto empleando una serie de caracteres de una forma especial. En principio, fue pensado para elaborar textos cuyo destino iba a ser la web con más rapidez y sencillez que si estuviésemos empleando directamente HTML
