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

Diferente do commit anterios, assumimos que repositórios já estão conectados.

Adicionando arquivo ao commit:

``` git add  <filename>```

Adicionando todos os arquivos ao commit:

``` git add  .```

Atualizar repositório github:

``` git push```

## Gitignore

Como sabemos é comum geramos alguns arquivos temporários ou arquivos de compilação, para evitar poluição do repositório é recomendado utilização de gitignore.


### Modo de uso

Basta criar um arquivo chamado ```.gitignore```, aplicando as regras presentes neste arquivo para todos os arquivos, pastas e sub-pastas localizados na pasta no qual o ```.gitignore``` está, é geralmente criado na pasta raiz.

### Exemplo
Neste exemplo temos um ```.gitignore``` usado geralmente em projetos Java.
```
# Created by https://www.gitignore.io/api/java

### Java ###
# Compiled class file
*.class

# Log file
*.log

# BlueJ files
*.ctxt

# Mobile Tools for Java (J2ME)
.mtj.tmp/

# Package Files #
*.jar
*.war
*.ear
*.zip
*.tar.gz
*.rar

# virtual machine crash logs, see http://www.java.com/en/download/help/error_hotspot.xml
hs_err_pid*

# End of https://www.gitignore.io/api/java
```
