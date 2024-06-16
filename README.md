### comando git

- Inicializa um novo repositório GIT
```js
git init
```

- Clona um repositório para minha máquina local.
```js
git clone [url]
```

- Mostra Mostra o status dos arquivos no meu repositório local.
```js
git status
```

- Adicionar arquivos ao próximo commit.
```js
git add [nome do arquivos]

ou

git add .
```

- Cria um commit com os arquivos adicionados.
```js
git commit -m "[menssagem informativa]"
```

- Envia os commits para o repositório remoto.
```js
git push [alias] [branch]
```

- Atualiza seu repositório local com a versão mais recente do remoto.
```js
git pull [alias] [branch]
```

- Utilizado para exibir o histórico de commits no repositório Git.
```js
git log
```

- Para ver as mudanças em um commit específico
```js
git show [hash do commit]
```

- Volta no tempo para um commit anterior especifico
```js
git checkout [hash do commit]
```

- Revertendo um "git checkout"
```js
git switch -
```

- Criando uma nova branch no repsitório git.
```js
git branch [nome_da_branch]
```

- Mudar de BRANCH
```js
git checkout [nome_da_branch]
```

- Criar e mudar para a nova branch em um único comando
```js
git checkout -b [nome_da_branch]
```

- Apagando uma BRANCH
```js
git branch -d [nome_da_branch]
```

- Para apagar uma branch remota, você usa
```js
git push origin --delete [nome_da_branch]
```


- Unindo duas BRANCH no Git. 
  - primeiro mude para a **branch destino** (branch onde você quer que as mudanças sejam mescladas ),
  - segundo execute o merge da **branch de trabalho** (branch que contém as mudanças que você deseja incorporar) e a de destino
```js
git checkout [branch_destino]
git merge [branch_trabalho]
```

- Enviar commits locais para um repositório remoto(github | gitlab)
```js
 git push origin [nome_da_branch]
 ```