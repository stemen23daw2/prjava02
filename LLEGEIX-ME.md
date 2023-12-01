1
Part 1: git clone : https://github.com/dacomo2021daw2/prjava02.git
Part 2: a) git branch branca00
	b) git checkout branca00
	c) git status

5
Part 1: a) git status
	b) git ls-tree -r main
Part 2: git checkout main	git status	git log

7
Part 1: git remote rm origin	git remote -v	git remote add origin https://github.com/stemen23daw2/prjava02.git
Part 2: git checkout branca00

10b
Part 2: git merge branca00

12
a) git push orgin main

14a
git push origin branca01


Respostes:

6
No, perque si canvies d’una branca a altre sense fer commit git no portará el canvis amb tu a l’altre branca.

7
Si, perque com aquest canvi s’habia fet a la branca00 git ho guarda en aquesta branca.

12c
La comanda git push origin main actualitza la branca main al dipòsit remot amb l'origen (origin). Aquesta comanda específica puja només la branca main i no altres branques.

14c
Esta a un commit de distancia.
