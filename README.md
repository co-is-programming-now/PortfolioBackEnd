*how initialice a local repository on my pc?*

--if you have to create a new repo

git init

git config user.name emai and password this last cames from an access token
git remote add origin url
git push -u origin main

--if you have to push and existing repo

git remote add origin url
git branch -M main
git push -u origin main

remember how actualice the changes on the portfolio and upload to my repo 

git branch

git checkout <branch>

git status
git add . 
git commit -m "como voy a ir actualizando los cambios"

git branch 
git checkout main

git merge develop <siempre va el nombre de la rama origen>

<use the local branch in this case main and the remote branch where want displace the changes>
git push origin main:develop 

fail