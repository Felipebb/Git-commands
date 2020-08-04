# Git-Commands
Comandos básicos para quem desenvolve com controle de versão através do Git.

# 📝Comandos Git básicos

* git clone url

Faz o download do projeto para o seu computador, preferencialmente criar uma pasta para guardar apenas o projeto.
As urls como exemplo podem ser de projetos do github ou Team Foundation Service, enfim qualquer plataforma onde seja possivel o clone do projeto através da Url.

* git add .

Adiciona as alterações feitas

* git status

Checa o estado atual do repositório. Como exemplo, mostra os arquivos que não foram "Commitados", ou mostra que não existem modificações a serem gravadas.

* git commit -m "comentario do que fiz"

Comentário preferencialmente explicando o que foi feito

* git push -u origin nome_branch_destino

Faz o upload dos commits.

* git pull

Faz o download dos dados remotos.

* git stash

Guarda as alterações e volta ao status anterior.

* git stash pop

recoloca as alterações que foram guardadas anteriormente

* git reset --hard HEAD

Volta ao zero, elimina os commits

* git checkout nome_branch

Navegação/troca entre branchs.

* git checkout -b nome_nova_branch

Cria uma nova branch local

* git merge nome_branch

Mescla  a branch atual com outra branch

* git branch -d localBranchName

Deleta a branch local

* git push origin --delete remoteBranchName

Deletar branch remota

Algumas vezes, em alguns repositórios é necessario o login para clonagem, a identificação ocorre através dos comandos abaixo:

* git config --global user.name "John Doe"
* git config --global user.email johndoe@example.com
 
