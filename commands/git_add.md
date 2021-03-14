## Git Add

#### Verifica quais áreas os arquivos estão alocados:
```
git status
```

#### Adiciona um arquivo ao stage:

```
git add file.txt
```

#### Adiciona todos os arquivos ao stage:
```
git add .
```
#### Remover um arquivo do stage
```
git rm --cached README.md
```

#### Adicionando vários arquivos ao stage de forma gráfica

```
git add -i
```
> Usando o menu escolher cada arquivo que deve estar no stage, evitando o git add para cada arquivo.


#### Adicionando fragmentos de arquivos em commits diferentes

```
git add -p
```