# GIT e GITHUB Ninja

## Commands for GIT

###### git --version
visualiza a versão do git

###### git 
Comandos de ajuda

###### git init
Inicializa um repositório GIT

###### git status 
Verifica em qual status o projeto se encontra

###### git config --global user.name "Caio Willian"
###### git config --global user.email "teste@teste.com"
Adiciona usuário para configurações globais no git

###### git config -l
Lista as configurações de usuários existentes (verifica se os comandos de config funcionaram corretamente)

###### git log
Exibe um log de todos os commits feitos

###### git diff 
Exibe os arquivos que foram modificados

###### git add .
Adiciona múltiplos arquivos de uma única vez

###### git diff --staged
Verifica as alterações que foram feitas no Staging Area que não tem no .git Directory

###### git diff < nome do arquivo >
Verifica as alterações que foram feitas no arquivo selecionado

###### git log --name-status 
Visualiza o nome dos arquivos que foram alterados

###### git diff < hash1 hash2 > ou git diff < hash >
Verifica as alterações feitas entre dois commits.
Obs. Pode colocar somente os primeiros 7 dígitos do hash

###### git rm < nome do arquivo >
Remove o arquivo da árvore de diretórios do git

## ESTÁGIOS DO GIT 

## No total o git possue 3 estágios

###### working Directory
(É onde está sendo trabalhado agora) 

## command: git status
Exibe o status que os arquivos se encontram

###### Staging Area 
(É quando o arquivo é adicion) 
## command: git .add

###### .git directory
(É um repositório) Neste ponto o arquivo está fazendo parte da árvore do git. 
## command: commit

![alt text](https://raw.githubusercontent.com/CaioWillianMoreira/git-e-github-ninja/master/git-estagios.png)