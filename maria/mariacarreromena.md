#GIT, TEORÍA
##Git Avanzado: ramas
###Crear una rama
Para crear una nueva rama se utiliza el comando git branch <nombredelarama>.
###Listado de ramas
Para ver las ramas que ya tenemos creadas se usa el comando git branch.
###Cambiar de rama
Si nos queremos mover a una rama que ya está creada hay que usar el comando git checkout <nombrederama>.
Por otro lado, si nos queremos mover a una rama que no está creada tenemos que usar el comando git checkout -b <nombrederama>.
###Eliminar rama
Si queremos eliminar una rama que haya sido fusionada usamos el comando git branch -d <nombredelarama>.
Sin embargo, si queremos eliminar una rama que no haya sido fusionada tendremos que usar el comando git branch -D <nombredelarama>.
Hay que tener en cuenta que no se puede borrar una rama en la que estemos, tendremos que movernos a otra rama y eliminar la que queremos eliminar.
###Fusionar rama
Si queremos fusionar los cambios de dos ramas se utiliza el comando git merge <nombredelarama>. Con esto fusionaremos los cambios de la rama en la que estamos con la rama que queramos fusionar.
Tenemos que tener en cuenta que para fusionar dos ramas no tiene que haber ningún tipo de conflicto.

##Flujo de trabajo en Git
###Ramas principales
Hay varios tipos de ramas principales:
-**master** 
-**develop**
###Ramas auxiliares
Hay varios tipos de ramas auxiliares:
-**ramas de funcionalidad**
-**ramas de versión**
-**ramas de parches**

##GitHub
![Icono Git Hub](C:\Users\GGmery\Desktop\resumen-git\resumen-git\maria\github.png)
*GitHub* Es una página que sirve para poder hostear repositorios y guardarlos en la nube.
###Clonar un repositorio remoto
Se utiliza el comando git clone <url-repositorio> para clonar un repositorio remoto. 
###Añadir un repositorio remoto
Para añadir un código de un proyecto nuevo en local y lo queremos vincular a un repositorio remoto necesitamos usar el comando git remote add <repositorio-remoto> <url>.
###Descargar cambios de un repositorio remoto
Se utiliza el comando git pull <remoto> <rama> para descargar cambios en un repositorio remoto. Se puede utilizar tambien git fetch <remoto> <rama>.
###Subir cambios de un repositorio remoto
Para subir cambios de un repositorio remoto se utiliza el comando git push <remoto> <rama>.
###Eliminar sincronización con un repositorio remoto
Para eliminar la sincronización con un repositorio remoto se utiliza el comando git remote remove <nombredelrepositorio>.
###Subir etiquetas a un repositorio remoto
Para anadir una etiqueta a un repositorio se utiliza git push origin <tag_name>.
###Establecer conexión con GitHub
Necesitamos identificarnos para enlazarnos a un proyecto de GitHub. Para ello hay que seguir los pasos que se encuentran en esta [página][blog]
[blog]: (https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent?platform=windows)
###Cómo contribuir en un proyecto grupal: Pull Request
Un Pull Request, tal y como su nombre indica, es una petición para validar un código. Esto quiere decir que sirve para poder añadir o modificar algo de un repositorio. 
1. Para ello primero tendremos que hacer un fork de un repositorio en GitHub
2. Luego, tendremos que hacer las modificaciones o añadir elementos a través de la consola de comandos o GitKraken.
