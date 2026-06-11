## Deshacer cambios realizados sin dejar rastros

```
    git reset --soft HEAD~1
```

Este comando se utiliza para deshacer los últimos commits sin perder tu trabajo, especificando el numero de commits a deshacer a la derecha de "HEAD~", como se ve en el ejemplo. Es decir, los cambios realizados quedan guardados, se borra el registro del commit en el historial, y mantiene todos tus cambios guardados para modificarlo o volverlo a empaquetar.

---

```
    git reset --hard HEAD~1
```

En este caso, a diferencia de utilizar el paramentro "--soft", no solo borra la cantidad de commits especificada, sino que tambien borra los cambios de los archivos commiteados, dejandolos igual que antes de ser modificados.