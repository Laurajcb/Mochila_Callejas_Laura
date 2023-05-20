# CHEETSHEET

### CONFIGURAR HERRAMIENTAS
```
Configura la información del usuario para todos los respositorios locales :
$ git config --global user.name "[name]"
Establece el nombre que desea esté anexado a sus transacciones
de commit
$ git config --global user.email "[email address]"
Establece el e-mail que desea esté anexado a sus transacciones de commit
```

### CREAR REPOSITORIOS
```
Inicia un nuevo repositorio u obtiene uno de una URL existente :
$ git init [project-name]
Crea un nuevo repositorio local con el nombre especificado
$ git clone [url]
Descarga un proyecto y toda su historia de versión
```

### EFECTUAR CAMBIOS
```
Revisa las ediciones y elabora una transacción de commit
$ git status
Enumera todos los archivos nuevos o modificados que se deben confirmar
$ git add [file]
Toma una instantánea del archivo para preparar la versión
$ git reset [file]
Mueve el archivo del área de espera, pero preserva su contenido
$ git commit -m "[descriptive message]"
Registra las instantáneas del archivo permanentemente en el historial de versión
```

### CAMBIOS GRUPALES
```
Nombra una serie de commits y combina esfuerzos ya culminados :s
$ git branch
Enumera todas las ramas en el repositorio actual
$ git branch [branch-name]
Crea una nueva rama
$ git checkout [branch-name]
Cambia a la rama especificada y actualiza el directorio activo
$ git merge [branch]
Combina el historial de la rama especificada con la rama actual
$ git branch -d [branch-name]
Borra la rama especificada
```


### REPASAR HISTORIAL
```
Navega e inspecciona la evolución de los archivos de proyecto
$ git log
Enumera el historial de la versión para la rama actual
$ git log --follow [file]
Enumera el historial de versión para el archivo, incluidos los cambios de nombre
$ git show [commit]
Produce metadatos y cambios de contenido del commit especificado
```
