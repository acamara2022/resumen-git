# RESUMEN SOBRE LO APRENDIDO EN ESTA UNIDAD CON GIT
## UTILIZACIÓN DE COMANDOS BÁSICOS

>Creación de un repositorio: **git init**
>
>Creación de un archivo: **notepad**
>
>Comprobar el estado de los archivos sobre los que estamos trabajando: **git status**
>
>Mandar un archivo de la workspace a stage: **git add nombre de archivo**
>
>Mandar un archivo del stage al repositorio local: **git commit -m'*inserte aquí descripción commit*'**
>
>Mandar todos los archivos de la workspace al stage: **git commit** .
>
>Enviar todos los cambios realizados al repositorio local sin pasar por el stage (*Recodar que esto no se puede realizar con archivo unstracked*): **git commit -a -m'descripción del commit'**
>

### OTROS COMANDOS

>Lista de commits realizados: **git log --online** o **git log**



## COMANDOS AVANZADOS EN GIT

>Creación de una nueva rama: **git checkout** *nombre de la rama*
>
>Creación de una nueva rama y movernos a ella: **git checkout -b** *nombre de la rama*
>
>Eliminación de una rama fusionada: **git branch -d** *nombre de la rama*
>
>Eliminación de una rama **NO** fusionada: **git branch -D** *nombre de la rama*
>
>Fusionar una rama con otra: **git merge** *nombre de la rama que queremos fusionar* (Recodar que tenemos que estar con el Head en la rama a la que queremos fusionar los cambios, como es lógico no podemos fusionar unos cambios de una rama si estamos justo en la rama donde hemos realizado los cambios).
>
>Lista de todas las ramas: **git branch**
>
>Si una rama ya está creada y nos queremos mover hacia ella: **git checkout** *nombre de la rama a la que nos queremos mover*
>
## COMANDOS USADOS PARA TRABAJAR CON UN REPOSITORIO REMOTO

>Copiar el repositorio remoto en nuestro repositorio local: **git clone** *dirección de repositorio*
>
>Añadir un repositorio remoto: **git remote add** *nombre del repositorio* *url repositorio*
>
>Descargar cambios de un repositorio remoto, los traemos a nuestra zona de trabajo: **git pull** *nombre repositorio remoto* *rama que queremos*
>
>Descargar los últimos cambios del repositorio remoto y añadirlos a la última versión de nuestro repositorio: **git pull origin master**
>
>Descargar los últimos cambios del repositorio remoto pero no integrarlos en el repositorio local: **git fetch remoto rama**
>
>Subir los cambios a un repositorio remoto: **git push origin master** o **git push remoto rama**

>
La información para escribir este texto ha sido obtenida de [(https://gist.github.com/dasdo/9ff71c5c0efa037441b6)]



>![Esto es una imagen](resources/git.png)

>Esto es una lista ordenada;
1. Manzana
2. Pera
3. Naranja

>Esto es una lista desordenada:
- Manzana
- Pera
- Naranja

>Un poco de código:
`var markdown = 'hola';`