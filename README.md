#  COMANDOS UTILIZADOS
* //con este comando configuramos la identidad ante git *
* // para configurarlo con nombre de usuario *
** git config --global user.name "nombre_de_usuario"
* // para configurarlo con email *
** git config --global user.email "tuemail@email.com" **
* //para subir primera version*
** git init //se utiliza solo una vez**
* // se reutiliza para volver a subir versiones*
** git add . **
* // se reutiliza *
** git commit -m "nombre de la version" **
** git remote add origin "direccion_ubicacion_carpeta" **
** git push -u origin master //para subir el repositorio, se puede reutilizar **

* //vincular una nueva version *
** git remote add origin DIRECCION_COMPLETA **
** git push -u origin master **

* // para ver el status *
** git status **

* //para sacar un repositorio *
** git clone liga_de_GitHub //la primera vez **
** git pull origin master // las versiones que se vayan subiendo **
