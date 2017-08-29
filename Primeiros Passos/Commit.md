# Commit
## Primeiro Commit

Primeiro commit necessita de uma atenção especial, pois ele fara ligação entre seu projeto local e o repositório online.



Criando um novo repositório:

``` git init ```


Adicionando arquivo ao commit:

``` git add  <filename>```

Adicionando todos os arquivos ao commit:

``` git add  .```

Conectando repositório local ao repositório github:

SSH: ``` git remote add origin git@github.com:<username>/<repository-name>.git ```

HTTPs: ```git remote add origin https://github.com/<username>/<repository-name>.git```

Atualizar repositório github:

``` git push -u origin master ```
## Outros Commits

Diferente do commit anterios, assumimos que respositórios já estão conectados.

Adicionando arquivo ao commit:

``` git add  <filename>```

Adicionando todos os arquivos ao commit:

``` git add  .```

Atualizar repositório github:

``` git push```
