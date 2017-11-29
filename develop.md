#Develop
Branche ou les devs vont travailler, reçoit les hotfix et les features une fois qu'ils sont finis

##Release d'une nouvelle feature
depuis develop
git merge feature/<feature-name>
git checkout -b release/<release-name>
vim readme.md
git commit -m "UPDATED readme.md"
--- preparation de la release --
git checkout master
git merge release/<release-name>
