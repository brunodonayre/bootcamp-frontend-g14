#Bootcam Frontend G14

#Revisión de estatus de los archivos
* git status 

#Guardar cambios de un archivo en específico
* git add index.html

#Escribiendo el nombre de la modificación
* git commit -m "Mi primera página"

#Guardar los cambios de todos los archivos modificados
* git add -A 

#detalla los cambios de forma mas corta y describe los id
* git log --oneline --graph
* git log --oneline #lista con id mas resumida
* git log 

#detalla los cambios en cada commit pero requiere los id
* git show "porción de id" 

#creamos un repositorio en github 
$ git remote add origin https://github.com/brunodonayre/bootcamp-frontend-g14.git
$ git branch -M main
$ git push -u origin main

#Creando ramas de trabajo
*git checkout -b <nombre-de-la-rama>
