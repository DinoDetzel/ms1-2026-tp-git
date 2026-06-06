# Configuración inicial de git

## Configuracion de usuario:
```
	git config --global user.name "Juan Perez"
```
Sirve para asignar un nombre al usuario que esta
usando git en ese momento. Los cambios realizados se van a 
guardar con el nombre configurado. Es necesario para hacer
los commit.

```
	git config --global user.email "juan@gmail.com"
```

Sirve para asignar un mail al usuario que esta
usando git en ese momento. Los cambios realizados se van a 
guardar con el mail configurado. Es necesario para hacer
los commit.


---

##
```
	git config --global init.defaultBranch main
```
*Sirve para que cuando creemos nuevos repositorios
la rama principal se llame "main" y evitar nombres 
como "master"

```
	git config --global --list
```
*Sirve para que git nos muestre la configuracion
que previamente establecimos, esto es el usuario
y mail.
