# Git e GitHub

### Descrição

Este repositório foi criado para resolver o desafio de git e github na DIO, passando assim um breve tutorial sobre.

### O que é Git?

Git é um sistema de versionamento de código, imagina em um trabalho onde você está criando um texto, e um colega fala
que quer mudar algo, entao voce muda e o mesmo colega diz que antes estava melhor, mas agora voce ja nao tem mais a versão
anterior.

###### Link para Download
[Git Download](https://git-scm.com/downloads)

O git ajuda nisso ele cria versões do seu código para que você sempre controle as mudanças que foram feitas.

### O que é GitHub?

E o GitHub o que é? O GitHub é uma plataforma para você hospedar o seu codigo e poder usar eles em outros computadores.

### Alguns conceitos

##### Branch

Branch nada mais é do que uma ramificação da linha principal, quando você desenvolve o seu projeto você esta em uma linha principal, porem voce pode criar ramificações do seu projeto para que voce possa fazer um codigo e se seu codigo finalizar como esperado voce juntar ele com a linha principal e colocar em aplicação, ou entao voce pode esquecer ele e nao vai ser alterado a linha principal.

*Vale lembrar que nao necessariamente precisa ser feita a ramificação da linha principal pode fazer uma ramificação de outra ramificação!*

![imagem-sobre-ramificação](https://zepel.io/blog/content/images/2020/05/feature-branch-with-develop-git-workflow-2.png)

![imagem-sobre-branch](https://res.cloudinary.com/practicaldev/image/fetch/s--Jc-acrrl--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/i/69payngupg75rqgabwdg.png)

##### Commit

O commit nada mais é do que postar as alterações. _Mas lembre! é postar no seu repositorio local e não no GitHub!_

##### Merge

Merge é a junção de uma Branch com a linha principal entao quendo voce ver que sua ramificação deu boa! o merge vai colocar a sua
alteração na linha principal. *Também pode ser a junção de uma branch com outra branch!*

##### Remote

O Remote é quem faz a ligação entre o seu repositorio local com o repositorio do GitHub.

##### Push

O Push é utilizado para empurrar os seus arquivos para o GitHub.

##### Pull

O pull serve para puxar os arquivos para sua máquina.

##### Clone

O Clone é usado para pegar o repositorio do gitHub e trazer para sua máquina.

##### Pull Request

O pull request é para sugerir suas alterações para o criador do repositorio e aí ele vai avaliar se implementa ou não.

### Alguns comandos

git --version => Para ver a versão do git.
git init => para inicializar um repositorio na pasta em sua máquina.
git add "nome do arquivo" ou . para ir tudo => para adicionar o arquivo na area de espera para ser comitado.
git status => Para conferir as mudanças que estão prontas para serem comitadas.
git commit -m "titulo da alteração" => Para postar as alterações.
git remote add origin "link-do-repositorio-no-github" => para conectar o repositorio local com o remoto.
git push -u origin master => Para empurrar os arquivos para o gitHub.

git checkout -b "nome" => para criar uma ramificação ou seja uma branch.