## Manejo de ramas

```
    git branch
```
Mostrara todas las ramas y en la que estamos parados.

```
    git branch <nombre_rama>
```
Si agregamos un nombre al comando "git branch <nombre_rama>" creara la rama y nos mantendra en la rama en la que estabamos anteriormente.

```
    git branch -d <nombre_rama>
```
Para borrar una rama podemos ejecutar "git branch -d <nombre_rama>", asi como borra las rama, borrara los commits realizados en ella. Si git detecta que queremos borrar una rama con commits no mergeados, nos preguntara si queremos borrarla antes de hacerlo. 
Aclaracion: No podemos borrar una rama en la que estamos parados (a la que apunta HEAD).