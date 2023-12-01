#  Tabla comandos MD

|Comando|  Función | Ejemplo |
|---|---|---|
|init   |iniciar un repositorio|git init despliegue_demo |
|config |configuracion global del usuario  | git config --global user ...  |
|add    |añadir archivo a stage  | git add readme.md  |
|commit |añadir archivo al area de intercambio | git commit -m"..."  |
|status |ver estado de git  git status| git status  |
|log    |ver los registros del commit   |git log/ git log --oneline   |
|diff   |Muestra la diferencia de un archivo entre 2 "procesos", como un commit y un stage   |git diff readme.md  |
|show   | e utiliza para ver detalles ampliados de objetos de Git, como blobs, árboles, etiquetas y confirmaciones | git show v2.0.0:Muestra la etiqueta pasada por parámetro  |
|tag    |crea una etiqueta  |git tag nombre   |
|restore|restauraun archivo o proyecto por compleo  |  git restore --source=HEAD README.md |
|revert |revierte un commit   |git revert 865eed2   |
|reset  |restaura una copia anterior   |git reset HEAD readme.md   |
|branch |muestra las ramas existentes y la actual   |git branch   |
|switch |cambia de rama   |git switch nombre de la rama   |
|merge  |fusiona las ramas   |desde una de las ramas git merge nombre de la otra rama   |
|remote |añade un repositorio remoto o muestra los existentes  |git remote -v git remote add origin   |
|clone  |descarga una copia de un repositorio remoto  |git clone direccion repositorio   |
|push   |sube uno ovarios archivos al repositorio remoto   |git push nombre   |
|pull   |descarga el contenido d eun repositorio remoto   |git pull direccion   |
|fetch  |similar a git pull. No aplica los cambios en el repositorio local   |git fetch ...   |