## Git Rebase

#### Unindo vários commits de forma gráfica (Utilizado para enviar alterações unificadas para um repositório remoto)
```
git rebase -i HEAD~3
```
> Lista os commits que fazem parte do filtro, normal deixar o primeiro como <b>pick</b> e os demais como squash.