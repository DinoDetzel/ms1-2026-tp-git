## Comparar dos commits entre sí

##  ´git diff´ 
```
 git diff <hash_commit_A> <hash_commit_B>`

```

Sirve para comparar distintos commits.

```
git diff <hash de un commit> HEAD

```
Compara un commit especifico con el ahora del repositorio.

```
git diff <hash de un commit>

```
Compara un commit especifico con el ahora del repositorio.

```
git diff <hash de un commit> HEAD~1

```
Compara un commit especifico con un commit antes del HEAD (actualidad del repositorio).

```
git diff rama-origen..rama-destino

```
Compara el HEAD de distintas ramas. 

```
git diff rama-origen..rama-destino –stat

```
No dice los cambios específicos, sino que dice que archivos fueron modificados y cuantas líneas de agregaron o se quitaron.

```

```

```




---