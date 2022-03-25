## Sintaxis Readme
```
https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
```

### Subir cambios al repositorio remoto

1. Crear una rama para trabajar en tus cambios. El atributo -b nos crea la rama si no existe, en caso de que exista no es necesario ponerlo.
```
git checkout -b "NOMBRE_ESTUDIANTE|GRUPO|PAREJA-NOMBRE_PRACTICA"
```
2. Seleccionar los cambios a guardar
```
git add .
```
3. Guardar los cambios localmente con un commit
```
git commit -m "NOMBRE_ESTUDIANTE|GRUPO|PAREJA-NOMBRE_PRACTICA: Mensaje explicativo de lo que está guardando"
```
4. Descargar los cambios de la rama principal
```
git pull --rebase origin main
```
4.1. Si se está trabajando en equipo o en parejas deben publicar la rama primero y hacer el pull de esta rama
```
git pull --rebase origin NOMBRE_ESTUDIANTE|GRUPO|PAREJA-NOMBRE_PRACTICA
```
5. Subir los cambios a su rama
```
git push origin NOMBRE_ESTUDIANTE|GRUPO|PAREJA-NOMBRE_PRACTICA
```

### Lista de Comandos

- **git init**: lo usamos para determinar la carpeta en la que vamos a trabajar.

- **git status**: lo usamos para saber si tenemos un archivo añadido o borrado en nuestro proyecto, para saber en la rama en la que estamos y si tenemos commits.

- **git add**: es para añadir un archivo a nuestra rama seguidamente ponemos entre comillas el nombre de nuestro archivo o poner un punto para añadir todos los archios de nuestra carpeta.

- **git rm**: lo usamos para borrar un archivo que hayamos añadido, para eliminarlo por completo de nuestra rama usamosgit rm --cached.

- **git commit**: se usa para añadir un commit a nuestra rama, también podemos ponerle un -m seguidamente ponemos entre comillas nuestro ensaje.

- **git config**: muestra configuraciones de git también podemos usar –list para mostrar la configuración por defecto de nuestro git y si añadimos --show-origin inhales nos muestra las configuraciones guardadas y su ubicación.

- **git config --global user.name**: cambia de manera global el nombre del usuario, seguidamente ponemos entre comillas nuestro nombre.

- **git config --global user.email**: cambia de manera global el email del usuario, seguidamente ponemos entre comillas nuestro nombre.

- **git log**: se usa para ver la historia de nuestros archivos, los commits, el usuario que lo cambió, cuando se realizaron los cambios etc. seguidamente ponemos el nombre de nuestro archivo.