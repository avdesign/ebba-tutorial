# Git rebase
* Trazer o branch para o master
````
$ git rebase nome_branch
````
* Resolva todos os conflitos manualmente, marcar como resolvido
````
git rebase --continue
````
* Para pular o commit execute
````
$ git rebase --skip
````
* Para abortar e voltar ao estado anterior
````
git rebase --abort
````
