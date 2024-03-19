<<<<< Reto 2 >>>>>

Repositorio local

- git init repor_R2 - crea repo en local
- Creamos archivo readme.md
- En terminal nos metemos en la carpeta en la que trabajamos 
- * npm init - para crear proyecto node

No hay repo en remoto, hay que crear uno para enlazar con el local.
- git add .
git commit -m
git push   -> No hay donde pushear

Se crea nuevo repo con mismo nombre que el creado en local
sin archivo readme.md

cogemos: 
- git remote add origin https://github.com/JesusMunnoz/repo_R2.git
- git branch -M main
- git push -u origin main

fusiona los repos local y remoto
cambia nombre de rama "master"(local) a main


<<<<< Reto 3 >>>>>
- Añade el archivo .md creado anteriormente de nuevo al “stage”.


-- NOTAS --

git reset --soft HEAD~  >>> te lleva al apartado en el que tienes que introducir de nuevo git commit -m "comentario"
git reset --soft HEAD~  >>> e lleva al apartado en el que tienes que introducir git add .


<<<<< Reto 4 >>>>>
.gitignore este archivo lo que hace es indicar el tipo de documentos o archivos a ignorar.
como por ejemplo librerias que pesan demasiado.

Y lo quer habría que hacer sería git pull - git init (para proyectos compartidos) en los que los compañeros hayan instalado una librería.

*.tipoArchivo ejemplo:
 - *.txt
 - *.png

