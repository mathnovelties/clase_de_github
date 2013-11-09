clase_de_github
===============

Este es un repositorio para aprender Github

Esta es la primera modificacion del archivo README del repositorio de GitHub.

Una vez instalas GIT, debes configurarlo:

git config --global user.name "user"
git config --global user.email "user@domain.com"

Generando tu Public Key:

ssh-keygen 

Leyendo tu llave para copiarla a Github:

cat ~/.ssh/id_rsa.pub

Arrancando tu proyecto:

Iniciar nuevo repositorio 
git init

crear un archivo
touch README

agregar dicho archivo
git add README

actualizar github
git commit -m "tu primer commit"

actualizar GitHub
git push origin master
