# Repaso git

* Crear un repositorio: `git init`
* Ver estado de un repositorio: `git status`
* Añadir ficheros al repo: `git add <ficheros>`
* Comitear cambios: `git commit -am "Mensaje"`
* Ver todos los commits: `git log` (salir: pulsar `q`)
* Ver los repos remotos vinculados: `git remote -v`
* Añadir un remoto: `git remote add <remote_name> <git_url>`
* Pushear codigo a remoto: `git push origin master` `git push <remote_name> <branch_name`
* Clonar un repositorio: `git clone <repo_url>`
  
# Ramas
* Crear una rama: `git checkout -b <branch_name>`
* Cambiar de rama: `git checkout <branch_name>`
* Merge (traer contenido desde rama <branch_name> a rama actual): `git merge <branch_name>`

## REGLA DE ORO

Cuando me levanto de la silla, hago un `commit`

## SIEMPRE
 **nothing to commit, working tree clean**