# COMANDOS BÁSICOS DE GIT

## init
*Crear un repositorio Git vacío o reiniciar uno existente.*
### Ejemplo:
    # git init

## status
*Muestra el estado del árbol de trabajo.*
### Ejemplo:
    # git status

## add
*Añadir el contenido del archivo al índice.*
### Ejemplo:
    # git add .

## commit
*Registrar los cambios en el repositorio.*
### Ejemplo:
    # git commit -m "descripcion"

## log
*Mostrar los registros de confirmación.*
### Ejemplo:
    # git log --oneline

## checkout
*Regresa a una versión anterior.*
### Ejemplo:
    # git checkout ID

## reset
*Restablecer el HEAD actual al estado especificado.*
### Ejemplo:
    # git reset

## remote
*Permite enlazar mi repositorio Git local con un repositorio en la nube como GutHub, Bitbucket, etc..*
### Ejemplo:
    # git remote add origin <Repository URL>

## push
*Actualizar las referencias remotas junto con los objetos asociados.*
### Ejemplo:
    # git push -u origin master

## clone
*Clonar un repositorio en un nuevo directorio.*
### Ejemplo:
    # git clone <Repository URL>