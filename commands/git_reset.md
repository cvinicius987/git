## Git Reset

#### Remover um arquivo do stage com reset
```
git reset -- README.md
```

#### Desfazendo o ultimo commit, mantendo as alterações no stage (--soft)
```
git reset HEAD~1
```

#### Desfazendo o ultimo commit, apagando as alterações (--hard)
```
git reset --hard HEAD~1
```

#### Cancelando um git reset, voltando ao ultimo estado
```
git reset 'HEAD@{1}'
```