# Historial de commits de un repositorio.

## `git log`

```
	git log
```
Muestra el historial de commits de un repositorio. `git log` muestra para cada commit:
    - Hash del commit (identificador unico).
    - Autor del commit.
    - Fecha y hora en que se realizo.
    - Mensaje del commit.

---

```
    git log --help
```
O en linux y Mac.
```
    man git-log
```
Documentacion oficial (manual) de `git log` con ejemplos.

---

## Principales comandos de `git log`.

`git log` cuenta con una amplia variedad de opciones para explorar el historial de un repositorio. A continuación, se muestran los comandos más importantes y utilizados en el trabajo diario con Git. Muchas de estas opciones pueden combinarse entre si para mejores busquedas.

---

```
    git log --oneline
```
El parametro `--oneline` muestra el historial de forma resumida, cada commit en una sola linea. Para cada commit muestra:
    - Hash abreviado.
    - El mensaje del commit.

---

```
    git log --graph
```
El parametro `--graph` muestra el historial de commits con una representación gráfica en texto de las ramas (branches) y las fusiones (merges) del repositorio.

---

```
    git log -n <cantidad>
```
El parametro `-n <cantidad>` limita la cantidad de commits que se muestran en el historial. Git mostrara unicamente los n commits mas recientes.

---

```
    git log --since="<fecha>"
```
```
    git log --after="<fecha>"
```
Los parametros `--since` y `--after` permiten una busqueda del historial mostrando unicamente aquellos realizados despues de una fecha determinada.

---

```
    git log --until="<fecha>"
```
```
    git log --before="<fecha>"
```
Los parametros `--until` y `--before` permiten una busqueda del historial mostrando unicamente aquellos realizados antes de una fecha determinada.

---

```
    git log --author="<autor>"
```
El parametro `--author` permite una busqueda del historial mostrando unicamente aquellos realizados por un autor especifico.

---

```
    git log --branches
```
El parametro `--branches` Muestra el historial de commits de todas las ramas locales del repositorio.

---

```
    git log --tags
```
El parametro `--tags` muestra el historial de commits asociados a las etiquetas (tags) del repositorio, permitiendo revisar las distintas versiones.

---

```
    git log --remotes
```
El parametro `--remotes` muestra el historial de commits que son alcanzables desde las ramas remotas del repositorio.

---

```
    git log --numstat
```
El parametro `--numstat` muestra el historial de commits junto con estadísticas numéricas de los cambios realizados en cada archivo. Ademas de la informacion habitual, muestra:
    - Cantidad de líneas agregadas.
    - Cantidad de líneas eliminadas.
    - Nombre del archivo modificado.

---