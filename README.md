# clase-de-github
Este es un ejemplo para aprender

Una vez instalado GIT, se debe configurar:

git config --global user.name "Jhoan Sebastian"
git config --global user.email "sebatian...@hot..."

Generar una llave SSH
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

Leyendo llave para copiar texto para subir llave a repositorio remoto "github"
cat /.ssh/id_rsa_pub

Arrancar proyecto
git init

Crear archivo
toucu "Nombre"

Agregar archivo a repositorio CENTRAL (el de la maquina)
git add "Nombre"

guardar cambios en repositorio central
git commit -m "comentario"

Agregar repositorio remoto
git remote add origin (Direccion repo)

Traer contenido de repositorio remoto
git pull origin master

Enviar cambios a repositorio remoto
git push origin master