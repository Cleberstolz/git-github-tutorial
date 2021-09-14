# Git e GitHub

### Descrição

Este repositório foi criado para resolver o desafio de git e github na DIO, passando assim um breve tutorial sobre.

### O que é Git?

Git é um sistema de versionamento de código, imagina em um trabalho onde você está criando um texto, e um colega fala
que quer mudar algo, então você muda e o mesmo colega diz que antes estava melhor, mas agora você já nao tem mais a versão
anterior.

###### Link para Download
[Git Download](https://git-scm.com/downloads)

O git ajuda nisso ele cria versões do seu código para que você sempre controle as mudanças que foram feitas.

### O que é GitHub?

E o GitHub o que é? O GitHub é uma plataforma para você hospedar o seu código e poder usar eles em outros computadores.

### Alguns conceitos

##### Branch

Branch nada mais é do que uma ramificação da linha principal, quando você desenvolve o seu projeto você está em uma linha principal, porém você pode criar ramificações do seu projeto para que você possa fazer um código e se finalizar como esperado voce juntar ele com a linha principal e colocar em aplicação, ou então você pode esquecer ele e nao vai ser alterado a linha principal.

*Vale lembrar que não necessariamente precisa ser feita a ramificação da linha principal pode fazer uma ramificação de outra ramificação!*

![imagem-sobre-ramificação](https://zepel.io/blog/content/images/2020/05/feature-branch-with-develop-git-workflow-2.png)

![imagem-sobre-branch](https://res.cloudinary.com/practicaldev/image/fetch/s--Jc-acrrl--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/i/69payngupg75rqgabwdg.png)

##### Commit

O commit nada mais é do que postar as alterações. _Mas lembre! é postar no seu repositório local e não no GitHub!_

##### Merge

Merge é a junção de uma Branch com a linha principal entao quendo voce ver que sua ramificação deu boa! o merge vai colocar a sua
alteração na linha principal. *Também pode ser a junção de uma branch com outra branch!*

##### Remote

O Remote é quem faz a ligação entre o seu repositório local com o repositório do GitHub.

##### Push

O Push é utilizado para empurrar os seus arquivos para o GitHub.

##### Pull

O pull serve para puxar os arquivos para sua máquina.

##### Clone

O Clone é usado para pegar o repositório do GitHub e trazer para sua máquina.

##### Pull Request

O pull request é para sugerir suas alterações para o criador do repositório e aí ele vai avaliar se implementa ou não.

### Alguns comandos

git --version => Para ver a versão do git. <br>
git init => para inicializar um repositório na pasta em sua máquina. <br>
git add "nome do arquivo" ou "." para ir tudo => para adicionar o arquivo na área de espera para ser comitado. <br>
git status => Para conferir as mudanças que estão prontas para serem comitadas. <br>
git commit -m "título da alteração" => Para postar as alterações. <br>
git remote add origin "link-do-repositorio-no-github" => para conectar o repositório local com o remoto. <br>
git push -u origin master => Para empurrar os arquivos para o gitHub. <br>

git checkout -b "nome" => para criar uma ramificação ou seja uma branch. <br>