git config --global user.name "over"
git config --global user.email "over@gmail.com"

git init
git add .
git commit -m "v-001"

git log -> muestra todos los commit que se a echo 

git branch -> mostrar todas las ramas 
git branch rama-nueva -> crea una rama nueva 
git checkout rama-nueva -> ingresa dentro de la rama

git merge rama-nueva -> fusiona o trae todos los cambios de rama-nueva a master,  osea a la rama de donde se hace el merge
git branch -d rama-a-eliminar -> con -d eliminamos la rama

git switch -c rama-2 -> crea y accede dentro de la rama creada
git switch rama-nueva -> accede dentro de una rama

<!-- PARA QUE TE PUEDAS CONECTAR A GITHUB -->
git remote add origin https://github.com/vraemtec/git-and-github.git
git push -u origin master

git pull origin master(rama que quieres bajar) -> actualizas tu codigo con lo de online a especifico rama
