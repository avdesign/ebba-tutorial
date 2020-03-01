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

* Qual a principal diferença entre Merge e Rebase?
````
O merge não reordena os commits e ainda muitas vezes gera um commit adicional para ser concluído. O rebase reordena os commits, não gerando assim um commit adicional. 
````
