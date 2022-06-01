### GITHUB_a_R

# Conectar los programas desde GitHub a R estudio

# Crear un nuevo repositorio en nuestra cuenta de Github (o utilizar uno ya existente): pulsar el botón “Create repository”.

# Copiar al portapapeles la dirección url que aparece en la barra del navegador.

# En RStudio seleccionamos crear “New project”, elegimos "Version Control" y luego seleccionamos “Git”.

#Introducimos en el primer cuadro de texto la url copiada anteriormente.

#Pulsamos "Create Project".

#A continuación podrá consultarse la pestaña “Git” y ver la información asociada al repositorio descargado.

### Flujo de trabajo 

# A) PUSH (Subir de R estudio a GITHUB)
# Esto permite subir desde la consola de R estudio distintos archivos al repositorio de GitHub
# Seguir los siguientes pasos en R estudio:
# 1- Crear un archivo, un scripts o un .rmd(archivo markdown) y lo guardan
# 2- Ir en el panel de R estudio a la opcion GIT 
# 3- Selecciona el o los archivos creados/ existentes que quieras subir al repositorio GitHub marcando las casillas "Staged"
# 4- Hacer click en "commit", se desplega una ventana
# 5.a- En esta nueva ventana puedes indicar en el panel "commit menssage" un breve comentario sobre el archivo que estas subiendo.
# Como observacion, esta ventan de comentarios se utiliza para informar sobre los cambios realizados dentro del archivo, como control de versiones
# 5.b- Pulsar el boton "commit" para confirmar el archivo
# 6- Se pulsa el boton "Push" (flecha verde hacia arriba) para subir los cambios a GitHub
# 7- Ir a la web de GitHub, si estas en ella actualizar, para ver los archivos en linea hasta el ultimo "commit" realizado 

# B) PULL (Descargar de GitHub a R estudio)
# Esto permite descargar archivos mediante R estudio desde GitHub y almacenarlos en tú repositorio local.
# Seguir los siguientes pasos en tu cuenta web de GitHub
# 1- Puedes Crear o Editar un fichero del repositorio GitHub, para editar... pulsar sobre el icono de lapiz (sector derecha de la pantalla)
# 2- Realizamos alguna modificacion sobre el fichero
# 3.a- Pulsar en la parte inferior de la pag web boton "commit changes" 
# 3.b- Aqui puedes indicar los cambios que estas realizando al archivo
# 4- Abrir el programa R estudio
# 5- Ir al panel de Git 
# 6- Pulsar "Pull" flecha celeste hacia abajo, esto permite a R estudio descargar el ultimo archivo trabajado en GitHub
# 7.a- Ver si los archivos descargados estan en el repositorio local
# 7.b- Ver si los archivos modificados descargados, estan en el repositorio local.




 