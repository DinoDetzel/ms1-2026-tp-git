```
    git reset --soft
```

Este comando se utiliza para deshacer los últimos commits sin perder tu trabajo, osea los cambios que haces quedan. Lo que hace es borrar el registro del commit en el historial, pero mantiene todos tus cambios guardados, para modificarlo o volverlo a empaquetar

```
    git reset --hard
```

Este comando lo que hace es borrar los ultimos commits, osea cada vez que volver un commit para atrás se pierde y eliminar por completo cualquier cambio que se haya echo en el codigo, dejando tu carpeta exactamente como estaba en el commit del pasado al que decidiste volver.