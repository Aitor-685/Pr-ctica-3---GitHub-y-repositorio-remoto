# 1.1 Para crear los directorios use el comando mkdir y para crear el archivo el comando touch:
# mkdir GitObesoAitor2425 y touch README.md

# 1.2 Inice el directorio con el comando git init, cree el arvhico .gitignore y lo configure para ignorar archivos de log y carpetas de configuracion temporales. El archivo .gitignore es una herramienta esencial para mantener los repositorios Git limpios y organizados, asegurando que solo los archivos relevantes para el proyecto sean versionados y compartidos. Ayuda a evitar la inclusión de archivos temporales, configuraciones locales o datos sensibles, mejorando tanto el rendimiento como la seguridad del repositorio. Cree un carpeta para poner la estructura de web con el comando mkdir mi-web y despues cree los arvhivos con el comando touch.

# 1.3 Utilice el comando git add. para anadir los archivos, despues hice el commit y por ultimo hice el comando git log para comprovar que se hizo el git.

# 2.1 Con README.md: El repositorio tiene una estructura básica con documentación inicial. Es útil para proyectos que desees compartir o colaborar desde el principio.
# Sin README.md: El repositorio está vacío y no tiene documentación inicial, lo que significa que deberás crear los archivos manualmente si deseas agregar información sobre el proyecto.
# Los comandos que me indica para crear un repositorio son:
# echo "# Pr-ctica-3---GitHub-y-repositorio-remoto" >> README.md
# git init, git add README.md, git commit -m "first commit", git branch -M main, git remote add origin https://github.com/Aitor-685/Pr-ctica-3---GitHub-y-repositorio-remoto.git y git push -u origin main

# 2.2 Utilice el comando git checkout -b feature/documentacion para crear una rama y cambiarme a ella despues cree el archivo docs.md y despues para rellenar use un echo, despues lo añadi con el git add y despues hice el commit y por ultimo use el comando git diff para ver las diferencias entre ambas ramas que tengo.

# 2.3 Por ultimo cambia a la rama main y despues hice git pull  para descargar y fusionar los cambios mas recientes

# 3.1 Cree el archivo app.py dentro del direcotrio src con el comando touch y despues lo llene con el comando echo despues lo añadi con el add despues un commit y por ultimo hice un status para ver el estado y por ultimo visualice el historial de commit.

# 3.2 Borre el archivo app.py con el comando rm src/app.py, despues para recuperar el archivo use el comando git checkout -- src/app.py y por ultimo use el comando ls src/ para confirmar que lo he recuperado.

# 3.3 Utilice el comando git checkout main para cambiar a la rama main despues realise el merge con git merge feature/documentacion y por ultimo lo verifique con el git log 
