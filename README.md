# Git & GitHub

## Git
**Git es un sistema de control de versiones VCS** creado por Linus Torvalds. Es un sistema que registra los cambios realizados sobre un archivo o conjunto de archivos a lo largo del tiempo, de modo que puedas llevar el historial del ciclo de vida de un proyecto, comparar cambios a lo largo del tiempo, ver quién los realizó o revertir el proyecto entero a un estado anterior.

* Git tiene 3 estados en los que es posible localizar archivos: Staged, Modified y Committed.


## GitHub

**Github es una plataforma** de desarrollo colaborativo para alojar proyectos utilizando el sistema de control de versiones Git.

* GitHub permite alojar proyectos en repositorios de forma gratuita y pública.

## Configuración Git:

Configuración por defecto de git
```bash
$ git config --list
```

Configurar variables globales
```bash
$ git config --global user.name "Nombre Usuario"
$ git config --global user.email "email@ejemplo.com"
```



## Guía Básica de comandos:

Inicializar el repositorio git


```bash
$ git init
```

Guardar un archivo especifico en Staging.

```bash
$ git add <nombre_archivo>
```

Guardar todos los archivos de la carpeta actual en Staging. 
```bash
$ git add .
```

Agregar al repositorio los achivos que se encuentran en Staging.

```bash
$ git commit -m "Mensaje commit"
```g

```bash
$ git status
```

```bash
$ git log <nombre_archivo>
```
Mostrar los cambios existentes de un archivo
```bash
$ git show <nombre_archivo>
```

```bash
$ git push
```

```bash
$ git pull
```