# Comandos Básicos - GitHub #


<!--<img src="http://i.imgur.com/kDCcizZ.png" width="120">-->


<!--* [Verificar site](https://github.com/wpbrasil/odin)-->

## Descrição da documentação ##
Nessa documentação será mostrado os principais códigos usados no Git, de modo que venha facilitar a vida do programador no seu dia a dia. </br>

## Comandos ##

- **sudo apt-get install git** </br>
    Instalação do git no linux ubuntu.
- **Download do Git para outros sistemas operacionais** </br>
   [Clique aqui.](https://git-scm.com/downloads)
- **git --version**</br>
    Saber a versão atual do git. 
- **git config --global user.name "Dilma Rousseff"** </br>
    Configurando o seu nome do Git.
- **git config --global user.email "dilma171@gmail.com"** </br>
    Configurando o seu email no Git.
- **git config --global color.ui true** *Opcional* </br>
    Ativando cores diferentes no terminal.    
- **git config --global core.editor "notepad.exe"** *Opcional* </br>
    Configurando qual editor de texto fará a edição das mensagens de commit e tags.
- **git config --list**</br> 
    Veririfacando quais configuraões estão no Git.
- **git init** </br>
    Transformando um diretório de trabalho em um repositório Git.
- **git status** </br>
    Visualizando arquivos no repositório Git.
- **git add .** </br>
    Para que todos os arquivos do diretório sejam rastreados.
- **git add “nome do arquivo.java”** </br>
    Rastrar apenas um arquivo do diretório.   
- **git commit -m "Primeiro commit"** </br>
    *Comitando* um arquivo.
- **git log** </br> 
    Verificando o histórico das alterações gravadas no repositório.
- **git log --author="Rousseff"** </br>
    fazer um filtro no log, com isso retorna apenas comit's feito pelo autor Rousseff.
- **git remote add origin *https://github.com/fulanodasilva/meurepositorio.git* ** </br>
    Apontando seu projeto para o GitHub.
       
    
    

- git config user.email
    Qual email está configurado
- git config user.name
    Qual nome está configurado
- ls -la 
    visualizar arquivos ocultos no windows e linux
- cat .gitconfig | cat. arquivo.java
    abrir arquivos ocultos
- mkdir nomedapasta 
    cria uma pasta em qual diretório você está no momento







- git log --grep="Primeiro" 
    Faz uma condição para buscar a palavra 'Primeiro' nos comit's

- git push origin master
    Será enviado o código para o git hub.
- git diff
    Verificar o que foi alterado no conteúdo;
- git diff --staged
    Vai está verificando o que foi mudado no repósitorio na stand e no diretorio de trabalho.
- rm “nome arquivo.java”
    excluir um arquivo e vai para a lixeira
- git rm  “nome do aruqivo.java” 
    exclui tudo e não vai para a lixeira, pois já vai para o branch
- git commit --amend
    Alterar a mensagem do ultimo commit.
- git checkout -- “nome do arquivo.java”
    restaurar um arquivo que foi modificado para o diretorio de trabalho;
- git reset HEAD meuArquivo.java 
    remove o arquivo que está área de stade e volta para o diretorio de trabalho.
- touch  nomeArquivo 
    Cria um novo arquivo
- mv meuArquivo meuArquivoRenomeado.java
    Renomear um arquivo 
    Após ter nomeado o arquivo será obrigatorio fazer o camando.
    git rm meuAqruivo
- git mv meuArquivo meuArquivoRenomeado.java
    Vai renomear o arquivo, e com isso não será necessário fazer o processo anterior. 
- git mv meuAqruivo caminho/meuArquivo.java
    O comando mv serve para tanto, renomear um arquivo ou mover um arquivo para outra pasta
- git commit --amend -m “Texto” 
    Desfazer o ultimo  commit no stande 
- git clean -n 
    vou está verificando no meu arquivo de trabalho o que será removido
- git clean -f
    vou força o git remover os arquivos que estão no meu arquivo de trabalho.
- git checkout 0b8d9f7 -- meuArquivo.java
    Vai pegar um determinado commit  da branch atual e recuperar ele. Obs: Os numeros significa a hash que quero recuperar. não precisa digitalizar a hash inteira.

## Outros Comandos ##
- pwd --> Em qual diretório estou no momento.
- **git --help**</br> 
    Dúvidas sobre os comandos no git.
- **clear**</br>
    Limpar a tela.