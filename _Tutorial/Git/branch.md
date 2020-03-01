# Git branch

* Mostrar o branch
````
$ git branch
````
* Criar um branch
````
$ git checkout -b nome-do-branch
````
* Voltar para o master
````
$ git checkout master
````

Após uma funcionalidade ser desenvolvida e o merge realizado, você poderá optar por remover o branch. É isso mesmo =)

Remover um branch não significa que você removerá os commits que você realizou, pois o merge já foi feito.

Para remover um branch utilize o comando
````
$ git branch -D nome-do-branch
````