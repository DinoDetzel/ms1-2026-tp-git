# Cambiar de rama

```
    git checkout <nombre_rama>
```
Con "git checkout <nombre_rama>" nos vamos a ubicar en la rama elegida. 

---

```
    git checkout -b <nombre_rama>
```
También funciona para crear una rama y moverse a ella con "git checkout -b <nombre_rama>".

---

```
    git checkout HEAD~
```

Este comando se utiliza para cuando el usuario quiere volver commits atrás, osea que ya realizo. El head es un puntero para ver donde estas parado actualmente y ~ esta tildacion te indica ir para atrás en la historia del commits

---

```
    git checkout --
```

Este comando se utliza para voler a la ultima rama que estuviste o te dice en que rama estas parado actualmente

---

Aclaracion: Es un comando mas complejo puesto a que hace muchas mas cosas, incluso cosas destructivas. Como punto a favor, funciona en todas las versiones de git. Además, al cambiar de rama, uno se lleva los cambios no agregados a la rama a la que uno cambio.
