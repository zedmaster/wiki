# GIT


## Extrair e aplicar Path de uma versão de outro branch

**Extrair um commit atraves a partir do HEAD**

```
 git format-patch -1 HEAD
 ```
 
**Aplicar**

```
 git apply --check 0001-meu-commit.patch
 git apply 0001-meu-commit.patch
 ```
