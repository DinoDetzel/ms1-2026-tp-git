## Confirmación y guardado de cambios

```
    git commit
```
Guarda de forma permanente todos los cambios realizados en el repositorio local. Del staging area, al local repository. Contiene cambios de los archivos, autor, fecha, mensaje y referencia al commit anterior. Al ejecutarlo nos indica la rama en la que hicimos el commit, el hash del commit (que lo identifica univocamente), su mensaje, la cantidad de archivos y la cantidad de lineas de texto insertadas.
Si se realiza un commit sin agregar un mensaje, git pedira que agreguemos un mensaje y nos indicara que un mensaje vacio abortara el commit.

```
    git commit -m "mensaje"
```
Es importante y obligatorio utilizarlo agregando un mensaje para claridad y orden "git commit -m "mensaje"".

```
    git commit -am "mensaje"
```
Podemos hacer add y commit al mismo tiempo en solo un comando utilizando "git commit -am "mensaje"", pero solo sirve si queremos pasar todos los archivos al staging area y solo para archivos que git tiene trackeados. De querer hacer commit solo a algunos archivos se haria por separado.

---

Importante: el commit representa una idea logica de cambio. A la hora de hacer commit, los cambios realizados deben ser una funcionalidad a la vez, esto permite que a la hora de volver para atras a modificar un archivo que no anda como debiera, no alteremos cambios de otra indole que, por mal uso del comando, quedaron unidos al archivo a modificar
	
Conventional Commits: es importante mantenter las buenas practicas a la hora de realizar los commits y documentar los  cambios realizados, por lo que los mensajes agregados al  commit deben ser capaces de transmitir la idea del cambio de manera resumida y entendible. Ayuda a que los colegas de trabajo entiendan el cambio realizado, y que uno mismo sea capaz, en un futuro, de entender lo que cambió. Conventional Commits es el estándar en la industria para escribir commits de manera estructurada y uniforme. Este plantea un formato aprobado y funcional con la siguiente estructura: tipo(scope): descripción. El tipo de cambio que se realizó, el scope, es decir, el área que abarca la modificacion, y por ultimo la descripción del cambio. Hay variedad de tipos de de commits, ya sean soluciones a bugs (fix), documentacion (docs), agregar funcionalidades (feat) etc. El scope va a depender de la estructura del proyecto y es especifico del proyecto en sí. La descripcion suele comenzar con un titulo general, y luego debajo se agrega un listado mas técnino de los cambios realizados.