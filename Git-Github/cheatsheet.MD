# Comandos Git

## Comandos Iniciales

#### Inizializar Git
```bash
$ git init
```
#### Terminar inizialización de git
```bash
$ rm -rf .git
```
#### Cambiar nombre de rama (master a main)
```bash
$ git branch -M main
```
#### Configuracion para una carpeta en especifico
```bash
$ git config
```
#### Configuracion global de git
```bash
$ git config --global
```
#### Ver commits (el primero config global para cambiar la forma en que se ven, el segundo comando de ejecucion nuevo)
```bash
git config --global alias.lg "log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all"
```
#### Comando de ejecuccion
```bash
git lg
```
## Comandos de seguimiento

#### Agregar todos los cambios al stage area
```bash
$ git add . 
```
#### Saber el estado actual de seguimiento
```bash
$ git status
```
#### Crear commit
```bash
$ git commit -m "mensage"
```
#### Commit realizados
```bash
$ git log
```
####  Comit realizados en una sola linea
```bash
$ git log --oneline
```
#### terminar un comando
```bash
$ q
```
#### volver a un commit
```bash
$ git checkout nameCommit
```
#### Volver a la rama main
```bash
git checkout main
```
#### Restaurar todos los archivos hasta el estado del ultimo commit
```bash
git restore .
```
#### Subir commits
```bash
git push origin main 
```
#### Bajar commits
```bash
git pull origin main 
```
#### Conectar repo local a remoto
```bash
git remote add origin "nombre repo"
```
#### Muestra cambios entre commits
```bash
git diff commit commit
```
#### add y agregar commit ala vez
```bash
git commit -am "mensaje"
```
#### Ver si esta vinculado el repositorio
```bash
git remote -v
```
## Ramas

#### Crear rama
```bash
git branch name
```
#### Muestra las ramas
```bash
gir branch
``` 
#### crear y cambiar a la rama
```bash
git checkout -b name
```
#### Fucionar ramas merge
```bash
git merge rama ramaQueSeQuiereFusionar
```
