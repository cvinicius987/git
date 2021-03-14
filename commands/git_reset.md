## Git Reset

> Reseta o repositário entre os commits existentes.

```
#### Desfazendo o ultimo commit, mantendo as alterações nos arquivos (--soft)
```
git reset HEAD~1
```
#### Desfazendo o ultimo commit, mantém os arquivos igual ao ultimo commit (--hard)
```
git reset --hard HEAD~1
```

#### Desfazendo o ultimo commit, mantém os arquivos igual ao ultimo commit (--hard)
```
git reset --hard HEAD~1
```

#### Cancelando um git reset, voltando ao ultimo estado
```
git reset 'HEAD@{1}'
```