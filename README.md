# Comandos Git

**git init** - Para iniciar git en un proyecto y convertirlo en Working Directory.

**git status** - Para ver en que estado se encuentran los archivos.

-----------------------------

**git add [filename]** - Para pasar un archivo específico del Working Directory al Staging Area.

**git add .** - Para pasar todos los archivos del Working Directory al Staging Area.

**git reset [filename]** - Para revertir el track y regresar el archivo del Staging Area al Working Directory.

-----------------------------

**git commit** -m "Mensaje..." - Para pasar los archivos del Staging Area al Local Repository.

**git commit** --amend - Para editar el mensaje del último commit.

**git push** --force origin [rama] - Para forzar un nuevo push con el commit editado (Warning).

**git log** - Para ver historial de commits.

**git reset --hard HEAD~1** - Para eliminar el último commit perdiendo cambios.

**git reset --soft HEAD~1** - Para eliminar el último commit sin perder los cambios.

-----------------------------

**git remote add origin [url]** - Conectar Local Repository con un Remote Repository.

**git push origin [rama]** - Subir Local Repository a Remote Repository.

**git clone [url]** - Para clonar un repositorio remoto.

**git pull origin [rama]** - Para descargar nuevos cambios del Remote Repository en el Local Repository.

-----------------------------

**git branch** - Para ver las ramas creadas.

**git branch [rama]** - Para crear una nueva rama.

**git branch -m [nuevo nombre de rama]** - Para cambiar el nombre de la rama actual.

**git branch -d [rama a eliminar]** - Para eliminar una rama.

**git checkout [rama]** - Para cambiar a otra rama.

**git switch -c [id del commit]** - Para crear una rama con el id del commit.

**git merge [rama]** - Para combinar la rama actual con la rama que se pasa como parámetro en el comando.

