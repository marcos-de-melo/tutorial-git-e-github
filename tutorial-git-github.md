# TUTORIAL GIT E GITHUB
## GIT

* Configuração básica de usuario no git
> git config --global user.name "Marcos de Melo"
> git config --global user.email "marcdmelo@gmail.com"

* Definir gerenciamento de uma pasta pelo git
> git init  // cria a pasta oculta .git para o git poder gerenciar a pasta

* Verificar o status da pesta
> git status

* Adicionar 
> git add .

* Remover do add
> git reset HEAD nome-do-arquivo


* Comitar 
> git commit -m "msg" 
> git commit -a -m "mensagem aqui" // faz o commit sem passar pelo add

* Verificar alterações
> git diff // ver as alterações antes de add
> git diff --stage // ver as alterações feitas nos arquivos que estão no stage


> git log // histõrico de todos os commits
> git log -p //
> git log -p -1 //
> git log --pretty=oneline // mostra somente a chave e o nome

> gitk

* Voltar estado de commit anteriores
> git checkout -- nome-do-arquivo

>git tag -a v1.0 -m "Versão 1.0" // cria uma tag 
> git tag // mostra as tags existentes
> git show v1.0
> git checkout v1.0
> git tag -d v1.0 // deleta a tag








> git commit --amend -m "mensagem edição do ultimo commit"
> git rm


* Ramificações
> git branch // lista todos os branches
> git branch teste
> git checkout branch 'master'
> git merge teste
> git branch -d teste

* repositorio remoto
> git init --bare
> git clone file:////pastaremota/diretorio_remoto/cliente1 projeto1
> git push origin master / main
> 








