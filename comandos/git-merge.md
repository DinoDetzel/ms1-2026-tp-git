# Fusionar ramas

```
    git merge <nombre_rama>
```
Sirve para que todos los cambios realizados en una rama, se agreguen a otra. Con "git merge <nombre_rama>", siendo <nombre_rama> la rama con los cambios, y estando parados en la rama que queremos que los	reciba, podremos pasar los cambios de una a la otra. Merge es un commit, por lo que necesita que agreguemos un titulo y mensaje. Al realizarlo git nos indicara cuantos archivos se agregaron a la rama y cuantas lineas fueron modificadas, en caso de haber editado un archivo, indicara la cantidad de lineas eliminadas tambien.

## En caso de conflictos

```
    git merge --abort
```
En caso de conflictos entre ramas, en las que en las dos se modifico un mismo archivo en la misma linea, git indicara que el merge fallo y sugerira que lo solucione para luego commitearlo. En el caso de un conflicto se puede hacer "git merge --abort", simplemente aborta el merge y nos deja con las ramas como estaban para proceder de otra manera. 

---

Una forma de solucionar el conflicto es entrar directamente al archivo problematico y editar manualmente las lineas en las que hay conflicto, git indicara a qué rama pertenece cada version del archivo. Para concluir el merge, luego de un conflicto, git necesitara que hagamos "git commit", y nos hara un mini resumen de lo que ocurrio, nos indicara si hubieron conflictos, nos dirá qué hacer en caso de que nos arrepintamos de hacer merge, ademas de pedirnos un mensaje para el merge.