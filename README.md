# Shell-Git-Config
Fiz este script para ajudar meus amigos que estão começando no Git
# Para iniciantes

Desenvolvi este simples script para ajudar todos que estão inicindo com Git e não tem muitas praticas com os comandos da plataforma,
então resolvi cria-lo para ajudar os que estão apenas começado.

#Objetivo

Como já citado o objetivo é auxiliar os que estão começando, então ele é bem basico, contem apenas os comandos de add e commit, além de criar
o repositorio local e fazer a configuração de usuario e email.

Espero ajudar o maximo de pessoas possivel.


# Primeiro configure o nome e email de usuario que será exibido nos commits;
# Para isso utilize os seguintes comandos:


git config --global user.name "Seu nome"
git config --global user.email "Seu email"

"Verificando configuração"
git config --global user.name
git config --global user.email

#Iniciando o repositorio

Comando para iniciar repositorios em clientes
git init

Comando para iniciar repositorios em servidor
git init --bare

#Realizando troca de areas no git

git add #Envia o arquivo para a Staging Area

#Para acrescentar comentarios no commit utilize o seguinte comando:

git add -a #Com este comando entramos em um arquivo, neste pode ser feito uma descrição melhor do que foi feito no commit


#Exemplos de "git add"

git add .  #Coloca todos os arquivos da pasta na Staging Area 
git add arquivo1.txt arquivo2.txt  #Coloca os arquivos citados especificamente na Staging Area

#Comando para exibir todos os arquivos e suas modificações

git diff --> Mostra todos as modificações dos arquivos que vao ser feitas no commit
git diff arquivo_especifico.txt --> Mostra as alterações feitas em arquivo especifico que vao para o commit


#Sites que utilizam git
gitlab
bitbucket
github

#Vinculando a conta do Git com o Github

Adicione o remote origin para que o git saibao o caminho do diretorio no github

git remote add origin master Seu link https do repositorio

Exemplo: git remote add orihin master https://github.com/M3nin0/Aprendendo_Git.git

#Pull
Depois de definir basta dar pull para sincronizar o repositorio local com o repositorio do gitub

git pull origin "Nome da branch"

#Exemplo

git pull origin master


#Para subir as informações da maquina para o servidor 

git push origin "nome da branch"

#Exemplo

git push origin master

Lembrando que sempre deve ser feito a definição com o comando git remote

#Clonando repositorios do github para sua maquina

Utilize o comando clone

git clone "link do projeto"

Exemplo git clone https://github.com/M3nino/Snort-Config
