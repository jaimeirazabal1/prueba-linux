Luego tecleamos:
Código :
git init

Nos saldrá algo así:
Código :
Initialized empty Git repository in /home/carlos/cristalab-tuto/.git/

Para añadir archivos, si queremos por ejemplo añadir todos los archivos de la carpeta, tecleamos:
Código :
git add .

Pero si queremos añadir un archivo específico:
Código :
git add nombre-del-archivo.extensión

TODOS los cambios que hagamos requieren un comentario, para ello tecleamos:
Código :
git commit -m 'esto es un comentario'

Para conectarnos al repositorio tecleamos -nótese mi nombre de usuario y el nombre del repositorio-:
Código :
git remote add origin git@github.com:niclick/intro-github-en-ubuntu.git

Si nos sale este error:

Código :
fatal: remote origin already exists

La solución es teclear, y repetir el paso anterior:
Código :
git remote rm origin

Y lo subimos:
Código :
git push -u origin master

Para el README, es necesario crear un archivo llamado README.md y subirlo de la misma manera que los demás.

Y listo a disfrutar de nuestro repositorio.

Eliminar un archivo

Para eliminar un archivo debemos teclear:
Código :
git rm nombre-del-archivo.extensión