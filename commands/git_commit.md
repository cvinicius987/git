## Git Commit

### Descrição

Commits devem conter o minimo de alterações possíveis e mensagens que façam sentido para a alteração realizada.

#### Log de Commits
```
git log
```

#### Vendo detalhes do commit
```
git show <hash>

```
#### Commit de arquivos
```
git commit -m "Commit inicial do repositorio"
```

#### Alterando a mensagem do ultimo commit
```
git commit -m "Nova mensagem" --amend
```

#### Alterando o autor do ultimo commit
```
git commit --amend --reset-author
```
