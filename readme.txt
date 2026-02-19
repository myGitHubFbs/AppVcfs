--Cuando se crea el proyecto a pie sin ninguna herramienta
git config --global --add safe.directory C:/Fede/Proyectos/AppVcfs

https://github.com/myGitHubFbs/AppVcfs.git

…or create a new repository on the command line
echo "# AppVcfs" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/myGitHubFbs/AppVcfs.git
git push -u origin main

…or push an existing repository from the command line
git remote add origin https://github.com/myGitHubFbs/AppVcfs.git
git branch -M main
git push -u origin main

--Cambios
git add .
git commit -m "Descripción del cambio"
git push