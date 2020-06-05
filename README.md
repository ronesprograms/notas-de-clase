# cursos-platzi
notas de los cursos en platzi

en este curso aprederemos comandos git para elcontrol de versiones

PASOS PARA CREAR UN PROYECTO

1. creamos un repositorio en google drive

mkdir "C:\Users\ASUS\Google Drive (ronesprograms@gmail.com)\platzi-cursos\curso-git"

git init


2. Clonamos en la laptop el repositorio de google

git clone "C:\Users\ASUS\Google Drive (ronesprograms@gmail.com)\platzi-cursos\curso-git"

cd curso-git


3. Creamos un repositorio en github cursos-platzi

https://github.com/ronesprograms/cursos-platzi.git


4. Agregamos el repositorio github al proyecto en la laptop

git remote add github-origin https://github.com/ronesprograms/cursos-platzi.git

$ git remote
github-origin
origin

$ git remote -v
github-origin   https://github.com/ronesprograms/cursos-platzi.git (fetch)
github-origin   https://github.com/ronesprograms/cursos-platzi.git (push)
origin  C:\Users\ASUS\Google Drive (ronesprograms@gmail.com)\platzi-cursos\curso-git (fetch)
origin  C:\Users\ASUS\Google Drive (ronesprograms@gmail.com)\platzi-cursos\curso-git (push)

6. enviamos el proyecto a github
git push github-origin master

5. hacemos un merge con el repositorio de github.


#Inicializar el repositorio.
$ git init 