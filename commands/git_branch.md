
## Git Branch

#### Baixando branches de repositórios remotos:

```
git branch -r | grep -v '\->' | while read remote; do git branch --track "${remote#origin/}" "$remote"; done
```
*Obs: Este somente se as branches não existirem localmente.*
```
git fetch --all
```
```
git pull --all
```
#### Removendo branches locais
```
git branch -D <nome>
```
#### Removendo branches remotas
```
git push origin --delete nome-da-branch
```
#### Renomeando branches locais e remotas
Branches remotas não são renomeadas, são deletadas e substituidas por uma nova branch.

**Branch atual:** feature/nova-funcionalidade

**Nova Branch:** feature/nova-funcionalidade-de-produtos
```
git branch -m feature/nova-funcionalidade-de-produtos
```
```
git push origin :feature/nova-funcionalidade feature/nova-funcionalidade-de-produtos
```
