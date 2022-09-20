# PM1
## Examen github parte 1

### Comandos utilizados en los ejercicios

* Git init [nombre del nuevo repositorio] o git init. Ambos para crear un repositorio local ya sea en una nueva carpeta o en la carpeta actual
* cd. Para moverse entre carpetas
* ls lista de contenido de una dirección
* pwd para ver la ruta sobre la cual estamos posicionados

* vi [nombre de un archivo nuevo] crea un arcivo nuevo y entra en modo de edición 
* - insert/i para modificar el archivo
* - salir esc, para salir del modo de edición
* * :x para salvar/guardar el archivo

* git add [archivo o carpeta a mandar a staging Area] o usar git add . para aceptar todos los cambios de working directory y pasar a staging area
* git commit -m "Mensaje de confirmación de cambios de staging area" para confirmar cambios del staging area, registra usuario y correo de quien ha modificado, las modificaciones que se realizaron y en qué rama se han realizado
* git status muestra los estados del repositorio local en sus archivos, muestra si hay algunos por confirmar
* git show permite ver el último commit con los cambios realizados
* git log permite ver el historial de cambios del repositorio (commits)
* git reset --hard/--soft/--mixed, cualquiera de esas opciones permite restablecer o volver a una versión anterior, --hard borra el ultimo commit y no guarda nada, --soft mantiene en staging area el commit eliminado y --mixed mantiene en working directory los commits eliminados.
* git branch "nombre de la rama" crea una nueva rama.
* git checkout [nombre de la rama] para moverse entre ramas
* git merge para fusionar los ultimos cambios de una rama hacia la rama actual