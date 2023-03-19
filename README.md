<ol>
  <li>
  $ git init
  </li>

<img src="git/capturas git/1.jgp" />

  <li>
  $ git clone https://github.com/Akwarck/masteruah
  $ git remote add origin https://github.com/Akwarck/masteruah.git
  </li>
 
  <li>
  $ touch README.md
  $ notepad readme.md
  </li>

<li>
$ git add README.md
$ git commit -m "commit inicial"
</li>

<li>
$ git push origin master
</li>

<li>
$ touch 1.txt
</li>

<li>
$ git tag v0.1
</li>

<li>
$ git push origin --tags
</li>

<li>
$ git branch v0.2
$ git checkout v0.2
</li>

<li>
$ touch 2.txt
</li>

<li>
$ git add 2.txt
</li>

<li>
$ git commit -m "commit 2"
$ git push --set-upstream origin v0.2
</li>

<li>
$ git checkout master
$ git branch
$ git merge v0.2
</li>

<li>
$ notepad 1.txt
$ git add 1.txt
$ git commit -m "Agregado hola al archivo 1.txt"
$ git checkout v0.2
$ echo Adios >> 1.txt
$ git add 1.txt
$ git commit -m "Agregado adios al archivo 1.txt en la rama v0.2"
$ git checkout master
$ git merge v0.2
</li>

<li>
$ git branch --merged
$ git branch --no-merged
</li>

<li>
$ git status
$ notepad 1.txt
$ git add 1.txt
$ git status
$ git commit -m "Conflicto arreglado"
$ git status
</li>

<li>
$ git tag -a v0.2 -m "Version 0.2"
$ git branch -d v0.2
$ git branch -D v0.2
</li>

$ notepad readme.md
 </ol>

<table>
  <tr>
    <th>NOMBRE</th>
    <th>GITHUB</th>
<tr> 
  <th>Julian Mario Retamar Natale</th>
  <th>https://github.com/Akwarck</th>
  </tr>
</table>
