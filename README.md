# Data Dive Crunch Time
![The Data Dive Crunch Time project](images/datadivecrunchtimelogo.jpg)

Este es el repositorio del equipo 4, para el proyecto de la asignatura "Introducción a Data Science", de cuarto de los grados de Ingeniería 

## El procedimiento para el trabajo será el siguiente:
- La rama principal es la rama `main`. 
- Cada miembro tendrá que clonar el repositorio de su equipo en su ordenador. 

``` shell
git clone git@github.com:mkesslerct/datadive_team4.git
```
- Es imprescindible, cada vez que un miembro quiera trabajar en el proyecto, que realice un `pull` desde la rama `main` del repositorio en Github a su rama `main` de su repositorio local.

``` shell
git pull origin main
```
- Cada vez que el miembro de un grupo quiera contribuir al proyecto,  tendrá que crear, **en su repositorio local**, una rama para él, con el nombre que escoja, supongamos por ejemplo que sea `dev-mk`.

``` shell
git checkout -b dev-mk
```
- Trabajará en su rama `dev-mk`, hace un commit local con sus cambios, y una vez  que quiere contribuir sus progresos al repositorio en github, tendrá que hacer un push al repositorio.

``` shell
git push -u origin dev-mk
```
- Una vez que el miembro ha hecho su push de la rama `dev-mk` al repositorio Github, tiene que abrir un pull request en Github.
  - Al crear el pull request, tiene que escoger `dev-mk` como la rama "compare", y la rama `main`, como la rama "base"
- Cuando el pull-request haya sido aceptado, y que el miembro que lo ha abierto haya comprobado que todos los cambios se han incorporado a la rama `main`, podrá borrar la rama `dev-mk` tanto en su repositorio local como en Github.
Para borrar la rama `dev-mk` en el repositorio local:

``` shell
git branch -d dev-mk
```
