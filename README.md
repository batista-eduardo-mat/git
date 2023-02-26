# Git & GitHub
## Git

**Git es un sistema de control de versiones VCS** creado por Linus Torvalds. Es un sistema que registra los cambios realizados sobre un archivo o conjunto de archivos a lo largo del tiempo, de modo que puedas llevar el historial del ciclo de vida de un proyecto, comparar cambios a lo largo del tiempo, ver quién los realizó o revertir el proyecto entero a un estado anterior.

* Git tiene 3 estados en los que es posible localizar archivos: **Staged**, **Modified** y **Committed**.

## GitHub

**Github es una plataforma** de desarrollo colaborativo para alojar proyectos utilizando el sistema de control de versiones Git.

* GitHub permite alojar proyectos en repositorios de forma gratuita y pública.
#

## Configuración Git:

Configuración por defecto de git
```bash
$ git config --list
```

Configurar variables globales
```bash
$ git config --global user.name "User Name"
$ git config --global user.email "email@example.com"
```
---
## Configuración SSH
---
## Comandos Básicos:

Inicializar el repositorio git:
```bash
$ git init
```

Guardar un archivo Staging:
```bash
$ git add <file_name>
```

Guardar todos los archivos de la carpeta actual en Staging: 
```bash
$ git add .
```

Agregar al repositorio los achivos que se encuentran en Staging:
```bash
$ git commit -m "Commit message"
```
Mostrar el estado actual de los archivos (Staged, Modified o Committed):
```bash
$ git status
```

Mostrar todos los commits de un archivo:
```bash
$ git log <file_name>
```

Mostrar los cambios especificos de cada archivo en el último commit
```bash
$ git log --stat
```

Mostrar los cambios del último commit de un archivo:
```bash
$ git show <file_name>
```

Mostrar las diferencias entre dos commits:
```bash
$ git diff <commit> <commit>
```

Regresar a un commit, conservando los cambios en staging.
```bash
$ git reset <commit> --soft
```

Regresar a un commit. descartando los cambios en staging.
```bash
$ git reset <commit> --hard
```

Cambiar a un commit en el tiempo.
```bash
$ git checkout <commit>
```

Regresar al HEAD.
```bash
$ git checkout HEAD
```

Eliminar el archivo de nuestro repositorio y de staging, conservar en el disco duro.
```bash
$ git rm --cached <file_name>
```

Eliminar el archivo de nuestro repositorio, de staging y del disco duro.
```bash
$ git rm --force <file_name>
```

Eliminar todos los cambios en staging, conservar los cambios en disco duro.
```bash
$ git reset HEAD
```

## Documentar 
```bash
$ git log --oneline
```

```bash
$ git log --decorate
```

```bash
$ git log -p
```

```bash
$ git shortlog
```

```bash
$ git log --graph --oneline --decorate
```


```bash
$ git push
```
```bash
$ git pull
```