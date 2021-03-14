## Git Commit


#### Commit de arquivos
```
git commit -m "Commit inicial do repositorio"
```
#### Log de Commits
```
git log
```

#### Vendo detalhes do commit
```
git show <hash>
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

#### Revertendo commits
```
git revert <hash>
```
> Em caso de conflitos deve-se resolver e continuar, ou desfazer o revert:

- Continuar após revolver conflitos
```
git revert --continue
```

- Abortando o Revert
```
git revert --abort
```

[⬆ Voltar ao topo](#git)<br />
