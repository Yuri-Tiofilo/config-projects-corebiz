## Se ambientalizando de desenvolvimento Corebiz

### Iniciando o projeto

Iniciasse geralmente antes de tudo ao abrir o projeto, deve-se colocar na branch develop, aonde após isso deverá iniciar uma feature no git flow.

````
  git flow feature start feature_branch
````

Dependendo do projeto e do package.json deve ser visto qual o comando para iniciar o projeto.

````
EX: ELG -> yarn dev
````

[Charles] -> No Charles temos a mesma configuração que neste caso é mandar para a pasta dist o MAP LOCAL. Mesmas configuração que já foi feita no padawan.

Após isso podesse dar o comando de CTRL + F5 no site para que as configurações do projeto e as configs funcionem.

## Padrão de commit

````
git commit -m "fix/feat(page change): message in english (number task) "
````

## Padrão de commit quando vai trocar a versão:

````
git commit -m "feat (general): update version (n-task)
````
