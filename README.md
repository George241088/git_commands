# Comandos útiles de Git
##Pequeño resumen de los comandos
1. git init             -> Inicializar el repositorio git
2. git add .            -> Es para agregar todos los archivo al proyecto, Es como prepar a los archivos para que esten listos para la fotografia
3. git reset .          -> Es para revertir el git add, por si aun faltan archivos o hay archivos que no se quieren contemplar.
4. git commit -m "Comentarios del commit" -> Se toma la fotografia para utilizarlo en toda la historia del repositorio, para ocuparlo si queremos regresar a este punto
5. git checkout -- .    -> Este comando nos sirve para revertir al ultimo Checkout y recuperar cambios o incluso si borramos algun archivo
6. git log              -> Nos muestra un historico de todos los commits que se han hecho
7. git commit --amend   -> Esto nos va a permitir modificar informacion del ultimo comit, como el comentario
8. git git checkout -b nueva-rama -> Este comando es para crear una nueva rama Branch
9. git branch           -> Esto nos hace un listado de las ramas
10. git checkout master -> Cambiamos a la rama master
11. git merge nueva-rama -> Se fuciona todo lo de nueva-rama  a la rama que estamos usando, en este caso master. 
12. git branch -d nueva-rama
13. git push            ->Despliega los cambios al repositorio remoto, usar git add., git commit - m "" , y despues git push
14. git commit -am "msg"     ->Se realizan los comandos git add ., y git commit -m "msg" juntoc en un solo comando