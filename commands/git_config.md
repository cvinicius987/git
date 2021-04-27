## Git Config

#### Alterando o editor padrão do Git
```
git config --global core.editor "subl -n -w"~
```

#### Alterando usuario e e-mail globais
```
git config --global user.name "Your Name"
git config --global user.email you@example.com
```

#### Resetando configurações locais e globais
```
git config --unset <config-name>

git config --global --unset <config-name>
```
