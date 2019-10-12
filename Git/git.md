## Alguns comandos do GIT

**Remover todas as branch locais exceto a branch master**

```
git branch | grep -ve " master$" | xargs git branch -D
```

**Retornar a um determinado commit**

```
git reset --hard (Hash do Commit)
```

**Descartar alterações realizadas localmente**

```
git checkout .
```

**Renomeando o último commit realizado (antes de dar push)**

```
git commit --amend -m "nova mensagem".
```

**Olhar os registros relacionados a ações que foram realizadas dentro do git**

```
 HEAD@{3} : significa três movimentos atrás realizados no git
```

```
 git reflog
```

**Voltar um commit ou um número especifico de commits voltando com as atividades ao stage**

```
git reset HEAD~1 --
```

**Alterar a URL do repositório remoto relacionado**

```
git remote set-url origin {url_do_repositorio}

```
