# Desafio de Projeto sobre Git/Github da DIO
Repositório criado para o Desafio de Projeto

## Links Úteis

[Sintaxe Básica Markdown](https://www.markdownguide.org/basic-syntax/)

# Comandos Básicos Git 

**1. git config**

Esse comando é fundamental para configurar sua identidade de usuário, inserindo informações como nome e email que serão empregadas em cada *commit*.

Exemplo: _**$ git config –global user.name “Seu nome”**_

​				_**$ git config –global user.email “Seu email”**_



**2. git init**

Esse é o comando que você irá utilizar para criar um novo projeto de git. O comando irá criar um repositório novo em branco e, a partir daí, será possível armazenar seu código fonte, alterar, salvaguardar alterações etc.

Exemplo: Se você já possui um repositório anterior ou deseja criar um repositório com um nome em específico, você pode passar o nome como parâmetro do comando:

_**$ git init <O nome do seu repositório>**_



**3. git clone**

Esse comando Git cria uma cópia exata de um repositório já existente.

O git clone executa um comando git init internamente. Além disso, ele verifica todo o conteúdo do projeto.

Exemplo: _**git clone <URL do seu projeto>**_



**4. git add**

Esse comando Git adiciona os arquivos especificados de código ao seu repositório, sejam arquivos novos ou arquivos anteriores que foram alterados. Oferece diferentes possibilidades de sintaxe.

Exemplo:

_**$ git add seu_arquivo**_(esse comando irá adicionar o arquivo em específico ao repositório)

_**$ git add \***_ (esse comando irá adicionar todos os arquivos novos e/ou modificados ao repositório)



**5. git commit**

É fundamental se estabelecer uma diferença entre git add e git commit:

- git add adiciona seus arquivos modificados à fila para serem submetidos a um commit posteriormente. Os arquivos **não** passaram por um commit.
- O git commit executa o commit dos arquivos que foram adicionados e cria uma nova revisão com um log. Por outro lado, se você não adicionar nenhum arquivo, o git não fará o commit de nada.

É possível combinar as duas ações em um único comando: **$ git commit -a**.

É importante adicionar uma mensagem para a execução de um commit. 

Exemplo: _**$ git commit -m “seu comentário”**_



**6. git push**

Esse comando serve para subir suas modificações para um repositório **remoto**.



**7. git pull**

O comando Git pull baixa o conteúdo do que foi alterado no repositório remoto para o seu repositório local e imediatamente atualiza seu conteúdo para a última versão.

Exemplo: _**$ git pull <URL>**_

## Passo a Passo Novo Repertório para Iniciantes (como eu :baby:)

Acessar GitHub; 

Clicar em Novo Repositório Lado superior da Tela;

Preencher Nome e Descrição; 

Flegar Readme;

Clicar em Criar Repositório;

Após criar é possível fazer alterações e incluir informações.

Após fazer alterações clicar em commit. 

Após esses passos será necessário **Baixar o Repositório para trabalhar "na minha máquina"**

Criar uma pasta no seu computador. 

No **gitHub** acessar o repositório (clicar em cima do nome dele).

No botão verde "Code" copiar a URL (pode ser copiada em HTTP, SSH ou Github CLI).

Ir até a pasta criada no computador (é possível cria a pasta no próprio Gitbash), clicar com o botão direito dentro da pasta e clicar em gitbash here. 

Digitar no Gitbash: **git clone**, copiar a URL e clicar em enter. 

Após fazer isso verá que na pasta do computador terá o arquivo Readme e o arquivo .git (trouxemos tudo que foi feito no GitHbub para o computador).

No Gitbash digitando **cd** e o nome do repositório (se digitar cd, digitar as primeiras letras do nome do repositório e clicar tab ele já busca o repositório) e clicar em enter, estará dentro do repositório. 

digitar **git status** e enter para ver se está tudo ok. 

Dentro da pasta você poderá incluir novos arquivos e pastas. 

Após fazer alterações no computador será necessário "levar" isso para o GitHub. 

Pelo **git status** você poderá ver que ele já entendeu que tem arquivos novos. 

Será necessário dar **git add.** ou **git add -A**

Digitando **git add.** irá adicionar todos os arquivos.

Após adicionar digitar **git status** e verá que fora adicionados, pois está escrito em verde. (quando está escrito em vermelho é porque é necessário adicionar e aparecerá a informação dizendo que é necessário adicionar)

**PARA INCLUIR NO GitHub**

Digitar **git commit -m** e escrever um comentário entre aspas (o comentário é muito importante) clicar em enter.

Digitar **git status** e clicar enter: irá mostrar que é necessário "dar um push" para enviar para a nuvem. 

Digitar **git push origin main** (main é a branch que queremos enviar)





