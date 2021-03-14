## Git Revert

> Reverte alterações e cria um novo commit baseado na reversão, mantém o histórico dos commits anteriores.

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