# Git & GitHub

## Git
**Git es un sistema de control de versiones VCS** creado por Linus Torvalds. Es un sistema que registra los cambios realizados sobre un archivo o conjunto de archivos a lo largo del tiempo, de modo que puedas llevar el historial del ciclo de vida de un proyecto, comparar cambios a lo largo del tiempo, ver quién los realizó o revertir el proyecto entero a un estado anterior.

* Git tiene 3 estados en los que es posible localizar archivos: Staged, Modified y Committed.


## GitHub

**Github es una plataforma** de desarrollo colaborativo para alojar proyectos utilizando el sistema de control de versiones Git.

* GitHub permite alojar proyectos en repositorios de forma gratuita y pública.


## Guía de comandos:

Inicializa el repositorio git

```bash
$ git init
```

Guarda un archivo especifico en Staging.

```bash
$ git add <nombre_archivo>
```

Guarda todos los archivos de la carpeta actual en Staging. 
```bash
$ git add .
```

Agrega al repositorio los achivos que se encuentran en Staging.

```bash
$ git commit -m "mensaje_commit"
```

```bash
$ git status
```

```bash
$ git log <nombre_archivo>
```

```bash
$ git show
```

```bash
$ git push
```

```bash
$ git pull
```