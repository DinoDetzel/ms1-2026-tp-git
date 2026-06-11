# Reorganizar el historial de una rama (Rebase)

## git rebase
```
git rebase <nombre_rama_base>

```
Sirve para integrar los cambios de una rama en otra, modificando la base de nuestros commits. A diferencia de "git merge" (que crea un commit de fusión extra y ramifica el historial), rebase toma uno a uno los commits de nuestra rama actual, los levanta temporalmente, actualiza nuestra rama con los últimos commits de la rama base y luego vuelve a aplicar nuestros commits encima. Esto genera un historial completamente lineal, limpio y fácil de leer.