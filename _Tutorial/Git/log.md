# Git Log
* Ver os logs de todos seus commits em ordem decrescente:
````
$ git log
````
* Ver os detalhes dos logs:
````
$ git log -p
````
* Ver a quantidade dos ultimos commits:
`````
$ git log -p -2
````
* Ver as estatisticas dos stats +linhas -Linhas Deletadas:
````
$ git log --stat
````
* Ver os comites em uma linha:
````
$ git log --pretty=oneline
````
* Ver has, quem, hórario e o commit:
````
 git log --pretty=format"%h - %an, %ar : %s"
````
