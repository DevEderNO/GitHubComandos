<!--Feito por Khalleb Ribeiro-->

# Comandos Básicos - GitHub #

## Descrição da documentação ##
Nessa documentação será mostrado alguns dos principais códigos usados no Git, de modo que venha facilitar a vida do programador no seu dia a dia. </br>

## Comandos ##

- **sudo apt-get install git** </br>
    Instalação do git no linux ubuntu.
- **Download do Git para outros sistemas operacionais.** </br>
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
- **git log --oneline** </br>
    Listando as mensagens dos commit's.
- **git log --author= "Rousseff"** </br>
    fazer um filtro no log, com isso retorna apenas *commit's* feito pelo autor Rousseff.
- **git remote add origin https://github.com/fulanodasilva/meurepositorio.git** </br>
    Apontando seu projeto para o GitHub.
- **git push origin master** </br>
    Enviando as alterações para o GitHub.
- **git clone https://github.com/fulanodasilva/meurepositorio.git** </br>
    Obtendo um projeto no GitHub
- **git diff** </br>
    Verificando as diferenças entre o arquivo alterado e o que foi comitado anteriormente.
- **git diff --staged** </br>
    Mostrando as diferenças entre os arquivos na área de stage e a última versão que foi comitada.
- **git rm  “nome do arquivo.java”** </br>
    Com o camando acima pode está removendo o arquivo e editando na stage.
- **git mv meuArquivo meuArquivoRenomeado.java** </br>
    Renomeando um arquivo.
- **git mv meuAqruivo caminho/meuArquivo.java** </br>
    O comando mv serve para tanto, renomear um arquivo ou mover um arquivo para outra pasta.
- **git checkout -- meuArquivo.java** </br>  
- **git reset -- meuArquivo.java** </br>
    Removendo alterações de um arquivo quando estiver na área de stage.
- **git reset HEAD nomeArquivo.java** </br>
    Retirando um arquivo da stade para o dirtório de trabalho.
- **git show HEAD** </br>
    Mostra o que foi alterado no último commit.
- **git revert --no-edit 1512154** </br>
    Desfazendo mudanças já comitadas.
    Nesse comando, o código 1512154 repres  enta o último commit efetuado.
- **git --help**</br> 
    Dúvidas sobre os comandos no git.
- **git config user.email** </br>
    Verificando qual email está configurado no meu git.
- **git config user.name** </br>
    Verificando qual email usúario configurado no meu git.
- **git clean -f** </br>
    Remover todos arquivos que ainda não estão na stade.
- **git branch** </br>
    Verificando em qual branch estou no momento.
- **git branch nomeMeuBranch** </br>
    Criando uma branch.
- **git checkout nomeMeuBranch** </br> 
    Alterando para outra branch.
- **git branch --move branchNomeAtual branchNovoNome** </br>
    Renomeando o nome da branch.
- **git branch -d nomeBranch** </br>
    Removendo a branch.
- **git merge nomeMinhaBrach** </br>
    Pegando as alterações que foram feitas na branch "nomeMinhaBrach" e jogando na branch "master".

## Outros Comandos ##
- **pwd** </br>
    Saber qual diretório estou no momento.
- **clear**</br>
    Limpar o terminal
- **ls -la** </br> 
    visualizar arquivos ocultos no windows e linux.
- **cat. arquivo.java** </br>
    abrir arquivos ocultos.
- **mkdir nomedapasta** </br>
    cria uma pasta em qual diretório você está no momento.
    
    #### Legende conosco ####
  