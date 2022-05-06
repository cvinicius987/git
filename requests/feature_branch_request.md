## Feature Branch Rebase Main

### Regular Rebase

#### Realizar o checkout da main
```
git checkout main
```

#### Realizar o Fetch da main

```
git fetch origin main
```

#### Realizar o checkout da feature branch
```
git checkout <feature-branch>
```

#### Realizar o rebase
```
git push --force origin <feature-branch>
```
ou 

> Em caso de outras pessoas terem enviado commits para a FB, preserva os commits, mais seguro que o *--force*
```
git push ----force-with-lease origin <feature-branch>
```