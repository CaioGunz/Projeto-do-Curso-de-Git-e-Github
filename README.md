# Projeto do Curso de Git e Github

## Como fazer login no Git

   A primeira coisa que você deve fazer ao instalar Git é configurar seu nome de usuário e endereço de e-mail. Isto é importante porque cada commit usa esta informação, e ela é carimbada de forma imutável nos commits que você começa a criar:

$ git config --global user.name "Fulano de Tal"
$ git config --global user.email fulanodetal@exemplo.br
   
   Reiterando, você precisará fazer isso somente uma vez se tiver usado a opção --global, porque então o Git usará esta informação para qualquer coisa que você fizer naquele sistema. Se você quiser substituir essa informação com nome diferente para um projeto específico, você pode rodar o comando sem a opção --global dentro daquele projeto.
   Para conferir se o login foi feito corretamente deve se escrever:

$ git config --list 

Estes são os comandos que servem para subir um arquivo para o Github pelo terminal Git Bash

git init ( serve para iniciar um repositório git na pasta em que se encontra os arquivos)

git add README.md (Não é necessario este comando, pois ele só ira adicionar um readme para leitura do usuário no git)

git commit -m "first commit" (Este comando serve para comitar os arquivos com uma mensagem entre "mensagem")

git branch -M main (Este comando serve para criar uma branch main e é necessario apenas no primeiro commit dos arquivos)

git remote add origin https://github.com/CaioGunz/teste.git (Este comando também só é utilizado no primeiro commit dos arquivos e deve ter o link onde está o repositorio do GitHub)

git push -u origin main (Este comando serve para subir os arquivos do Computador(Local) para o GitHub(remoto))
   
O comando para mostrar  os commits que foram feitos é o:

$ git log

e o comando para mostrar essas informações resumidas pode ser usado o:

$ git log --oneline  

assim será mostrado todos os commits sem informações adicionais.

O comando para mostrar  os commits que foram feitos é o:

$ git log

e o comando para mostrar essas informações resumidas pode ser usado o:

$ git log --oneline  

assim será mostrado todos os commits sem informações adicionais. E para ver as alterações do commit usa o comando:

**$ git log -p**


