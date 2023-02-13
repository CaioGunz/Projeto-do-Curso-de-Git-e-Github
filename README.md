# Projeto do Curso de Git e Github

## Como fazer login no Git

   A primeira coisa que você deve fazer ao instalar Git é configurar seu nome de usuário e endereço de e-mail. Isto é importante porque cada commit usa esta informação, e ela é carimbada de forma imutável nos commits que você começa a criar:

**$ git config --global user.name "Fulano de Tal"**

**$ git config --global user.email fulanodetal@exemplo.br**
   
   Reiterando, você precisará fazer isso somente uma vez se tiver usado a opção --global, porque então o Git usará esta informação para qualquer coisa que você fizer naquele sistema. Se você quiser substituir essa informação com nome diferente para um projeto específico, você pode rodar o comando sem a opção --global dentro daquele projeto.
   Para conferir se o login foi feito corretamente deve se escrever:

**$ git config --list** 

**$ git config --local user.name "Nome da pessoa"** (Este comando serve para que o nome da pessoal que esta moodificando seja apenas para um repositorio definido e não global.) 

-----------------------------------------------------------------------------------------------------

   ## Comandos mais usados:
   Estes são os comandos que servem para subir um arquivo para o Github pelo terminal Git Bash:

**$ git init** (serve para iniciar um repositório git na pasta em que se encontra os arquivos)

**$ git add README.md** (Não é necessario este comando, pois ele só ira adicionar um readme para leitura do usuário no git)

**$ git commit -m "first commit"** (Este comando serve para comitar os arquivos com uma mensagem entre "mensagem")

**$ git branch -M main** (Este comando serve para criar uma branch main e é necessario apenas no primeiro commit dos arquivos)

**$ git remote add origin https://github.com/CaioGunz/teste.git** (Este comando também só é utilizado no primeiro commit dos arquivos e deve ter o link onde está o repositorio do GitHub)

**$ git push -u origin main** (Este comando serve para subir os arquivos do Computador(Local) para o GitHub(remoto))

**$ git status** (é o comando em que verifica qual arquivo foi modificado e se ele ja foi comitado, caso não tenha sido o nome do arquivo vai aparecer em vermelhor, e depois de ser comitado ira aparecer em verde após rodar o este comando)

**$ git pull (URL do repositório)** (Serve para puxar um repositórios para um desktop local)

**$ git clone (Endereço/URL)** (Serve para clonar um repositório de um endereço)

**$ git branch (nome do novo branch)** (Serve para criar um novo branch(linha de desenvolvimento))

**$ git checkout (Nome da Branch)** (Serve para mudar em qual branch você está)

**$ git merge  (nome da branch)** (Serve para unir duas branch diferentes, no nome da branch deve ser colocado qual vai ser unida. Quando feito isso vai aparecer para confirmar apertando **:x**)

**$ git rebase (nome da branch)** (Serve para que o git una o commit citado com a master e a master passe a frente daquela branch e traz todos os commits da outra branch para a master junto com os que ela já possui e mantem o último trabalho feita na master)

**$ git revert (has do commit)** (Serve para reverter um commit que foi enviado com erro)


-----------------------------------------------------------------------------------------------------

## Outros comandos do Git

**$ git checkout -- (nome do arquivo)** (Serve para descartar as últimas alterações feitas)

**$ git log** (O comando para mostrar  os commits que foram feitos)

**$ git log --oneline** (É o comando para mostrar essas informações resumidas pode ser usado, assim será mostrado todos os commits sem informações adicionais)

**$ git log -p** (Para mostrar qual foram as modificações feitas no repositório)

**$ git remote add (nome do repositorio) e a URL(de qualquer endereço)** (Serve para adicionar um repositorio remoto pelo terminal git)

**$ git remote** (Serve para listar os repositorios)

**$ git remote -v** (Serve para mostrar o endereço do repositorio local)

**$ git stash** (Serve para armazenar temporariamente o que foi modificado  sem precisar commitar)

**$ git stash list** (Serve para mostrar a lista de stash salvo)

**$ git stash pop** (Serve para remover a ultima modificação feita e aplicar no arquivo)

**$ git checkout (7 primeiros digitos do hash da branch)** (Serve para navegar entre os commits)

**$ git tag -a (versão) (-m "", não é obrigatório colocar uma mensagem)** (Serve para marcar um release do código, tornando pronto para um usuário baixar)

**$ git push (branch) (nome da release)** (Serve para fazer um push de uma TAG/Release)

-----------------------------------------------------------------------------------------------------

## Comandos para usar no terminal do git (serve para linux também) e Navegar/Criar pastas e arquivos

**cd ..** serve para voltar uma pasta (ou subir como  alguns chamam)

**mkdir (nome da pasta)** serve para criar uma pasta

-----------------------------------------------------------------------------------------------------

## Alguns sites para ajudar no dia a dia com o GitHub:

Git log cheatsheet:
   https://devhints.io/git-log

