# Cola de uso geral do git  

Resumo comandos:  
+--------------------------------------------  
```
$ git init  
$ git status  
$ git add <file> (. para incluir todos os arquivos)  
$ git commit -m <mensagem>  
$ git pull  
$ git push <remote> <branch>  
$ git checkout <branch>  
$ git remote -v  
$ git config <--global> user.name  
$ git config <--global> user.email  
$ git reser HEAD~  
$ git fetch  
$ git reset --hard origin/main  
```
+--------------------------------------------  

#### Como eu geralmente faço:  
  - ```git init``` para inicializar um repo local, caso ele não exista;  
  - ```git remote add origin <url>``` para settar o repositório da nuvem, esse url é o repositório do github de sua preferencia, com .git no final (segue imagem 1);  
  - ```git checkout <branch>``` para alterar em qual branch você está atualmente, por hora, a branch padrão é a [master], mudar pra main na maioria dos casos;  
  - ```git pull``` puxa todas as mudanças novas que ocorreram no repo da nuvem para o repo local, quando estiver em um projeto com várias pessoas, utilizar isso com frequencia;  
  - ```git status``` verifica o status do repo local em relação ao repo, modificações, arquivos novos e deletados  ;
  - ```git add <files>``` Seleciona arquivos que vão para a nuvem com o próximo git push, seleciona todos os arquivos quando for ```git add .```;  
  - ```git commit -m <message>``` Cria um commit e adiciona uma mensagem pra ele;  
  - ```git push``` Manda os arquivos commitados para a nuvem
  
### Referências:  
[How to push git branch to remote](https://devconnected.com/how-to-push-git-branch-to-remote/)  
[How to upload a project to Github](https://stackoverflow.com/questions/12799719/how-to-upload-a-project-to-github)  
[How do I undo the most recent local commits in Git?](https://stackoverflow.com/questions/927358/how-do-i-undo-the-most-recent-local-commits-in-git)
[Force overwrite of local file with what's in origin repo?](https://stackoverflow.com/questions/3949804/force-overwrite-of-local-file-with-whats-in-origin-repo)
