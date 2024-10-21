# Git Commands Cheat Sheet

Este repositorio contiene una lista de comandos útiles, frecuentemente usados en Git, junto con una breve descripción de cada uno.

## Configuración Inicial
Antes de empezar a usar Git, configura tu nombre y correo electrónico:
```
git config --global user.name "Tu Nombre"
git config --global user.email "tu.email@example.com"
```

## Verifica la configuración actual
```
git config --list
```

## Crear un repositorio:
```
git init
```

## Ver el estado del repositorio:
```
git status
```

## Añadir archivos al Staging Area:
```
git add nombre_del_archivo
```

## Ver el historial de commits:
```
git log
```

## Crear una nueva rama:
```
git checkout -b nueva-rama
```
## Fusionar rama:
```
git merge nombre-de-la-rama
```

## Descargar cambios de un repositorio remoto:
```
git pull
```

## Subir cambios de un repositorio remoto:
```
git push origin main
```
