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
Añade archivos específicos al área de preparación (staging area):
```
git add nombre_del_archivo
```

Añadir todos los archivos modificados:
```
git add .
```

## Hacer un Commmit
Para guardar los cambios con un mensaje descriptivo:
```
git commit -m "Descripción de los cambios"
```

## Ver el historial de Commits
Revisar el historial de commits realizados en el repositorio:
```
git log
```

## Crear y Cambiar de Ramas
Crea una nueva rama:
```
git checkout -b nombre_de_la_rama

```

Cambiar a una rama existente:
```
git checkout nombre_de_la_rama
```

## Fusionar rama:
Fusiona una rama con la rama actual:
```
git merge nombre-de-la-rama
```

## Ver Diferencias Entre Archivos
Ver las diferencias entre el estado actual y el último commit:
```
git diff
```

## Eliminar Archivos
Eliminar un archivo del repositorio y del disco:
```
git rm nombre_del_archivo
```

Eliminar un archivo solo del repositorio (mantenerlo en el disco):
```
git rm --cached nombre_del_archivo
```

## Deshacer Cambios
Deshacer cambios locales no añadidos al staging:
```
git checkout -- nombre_del_archivo
```

Restaurar archivos del último commit (no recomendable si ya has hecho un push):
```
git reset --hard
```

## Conectar con un Repositorio Remoto
Añadir un repositorio remoto:
```
git remote add origin https://github.com/tu_usuario/nombre_del_repo.git
```

## Subir Cambios a un Repositorio Remoto
Subir cambios a la rama principal del repositorio remoto:
```
git push origin main
```

## Descargar cambios de un repositorio remoto:
Descargar y fusionar cambios desde el repositorio remoto:
```
git pull
```

## Clonar un Repositorio
Clonar un repositorio remoto en tu máquina local:
```
git clone https://github.com/usuario/nombre_del_repo.git
```

## Ignorar Archivos
Para ignorar archivos no deseados, crea un archivo .gitignore y añade las rutas o extensiones de archivos a ignorar:
```
touch .gitignore
echo ".DS_Store" >> .gitignore
```

## Subir cambios de un repositorio remoto:
```
git push origin main
```