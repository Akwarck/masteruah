$ git init
$ git remote add origin https://github.com/Akwarck/masteruah.git
$ touch README.md
$ notepad readme.md
$ git add README.md
$ git commit -m "commit inicial"
$ git push origin master
$ touch 1.txt
$ git tag v0.1
$ git push origin --tags
$ git branch v0.2
$ git checkout v0.2
$ touch 2.txt
$ git add 2.txt
$ git commit -m "commit 2"
$ git push --set-upstream origin v0.2
$ git checkout master
$ git branch
$ git merge v0.2
$ notepad 1.txt
$ git add 1.txt
$ git commit -m "Agregado hola al archivo 1.txt"
$ git checkout v0.2
$ echo Adios >> 1.txt
$ git add 1.txt
$ git commit -m "Agregado adios al archivo 1.txt en la rama v0.2"
$ git checkout master
$ git merge v0.2
$ git branch --merged
$ git branch --no-merged
$ git status
$ notepad 1.txt
$ git add 1.txt
$ git status
$ git commit -m "Conflicto arreglado"
$ git status
$ git tag -a v0.2 -m "Version 0.2"
$ git branch -d v0.2
$ git branch -D v0.2
$ notepad readme.md

|        NOMBRE          |                     GITHUB                                 |
|------------------------|---------------------------------------------------         |
| Julian Mario Retamar Natale| [enlace a github 1](http://https://github.com/Akwarck) |
