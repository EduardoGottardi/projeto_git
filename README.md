# Projeto de Git e Github

## Instalação do Git

Comando para configurar o Git após a instalação

```
git config --global user.name "Nome aqui"
git config --global user.email "Email aqui"
```


```
    Curso Entra21
```


# Comando basicos para enviar/trazer codigo entre o remoto e o local

```bash
git push origin main # envia do local para o remoto
git pull origin main # traz do remoto para o local

git branch -m master main

Mudar o master para main
-------------------------------------------
verificar se tem algum sistema .git
.gt /S/Q
--------------------
Criar um repositorio git
git init
------------------------
git status
mostra o status do arquivo git

--------------------------------
adicionar arquivo git no repositorio
git add "nome do arquivo"
ou
para adicionar todos os arquivos
git add .
--------------------------
git commit -m "nome do commit"
nome do diretorio git
------------------------------------------------
git remote add origin https://github.com/larissabandeirajs/OsSistema.git
adicionando o link onde esse diretorio ira se hospodar
---------------------------------------------------
enviando os arquivos no github
git push -u origin master

------------------- alterar um arquivo

ir ate o repositorio e escrever
git add .
----------------------
dar um commit no arquivo que ira ser feito o update
commit -m "banco de dados"
-----------------------
git branch -M main
----------------
informar o local do repositorio
git pull origin master

--------------------------
adicionar ao repositorio
git push origin master


==========================INICIO===================================

Set your username:
git config --global user.name "FIRST_NAME LAST_NAME"
Set your email address: git config --global user.email "MY_NAME@example.com"

git config user.game
-------------------------------------

git branch -m master main

Mudar o master para main
-------------------------------------------
verificar se tem algum sistema .git
.gt /S/Q
--------------------
Criar um repositorio git
git init
------------------------
git status
mostra o status do arquivo git

--------------------------------
adicionar arquivo git no repositorio
git add "nome do arquivo"
ou

git add .
--------------------------
git commit -m "nome do commit"
nome do diretorio git
------------------------------------------------
git remote add origin https://github.com/larissabandeirajs/OsSistema.git
adicionando o link onde esse diretorio ira se hospodar
---------------------------------------------------
enviando os arquivos no github
git push -u origin master


------------------- alterar um arquivo

ir ate o repositorio e escrever
git add .
-------------------------------------------------
dar um commit no arquivo que ira ser feito o update
commit -m "banco de dados"
--------------------------------------------------
git branch -M main
--------------------------------------------
informar o local do repositorio
git pull origin master

----------------------------------------------
adicionar ao repositorio
git push origin master



=======================ALTERAÇÃO PART 2
git init
-------------------------
git reset --hard [sua branch]
------------------------------
OU

git reset
------------------------------ALTERAR OU
git add .
git commit -m "...blablabla"
git push origin [sua branch]


===============================Esquecer de dar o commit

caso abre o vi se nao usar o -m com a mensagem no git commit
apertar o i
digita a mensagem
apertar a tecla ESC
:wp
git remote add origin
link_doProjeto_github



=================alterar codigo no remoto e trazer para o pc

git pull origin main <- pasta local no computador, abrir com git branch

git pull origin nome_da_branch
trazer o codigo alterado no remoto para o local


=======================clonar o arquivo
git clone link_github
```

## Páginas

[scrum](scrum.md)

[Kanban](kanban.md)

[Comandos básicos de git](comandos_básicos.md)



## Logos

![Imagem da logo Git](imagens/git.png)



## Fontes

Documentação da linguagem [Markdown](https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

Texto legal

Texto vindo do github



