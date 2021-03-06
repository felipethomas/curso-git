# curso-git
Curso de Git e Github para iniciantes da Udemy oferecido por Willian Justen

### Instalação:
https://git-scm.com/downloads

### Configuração:
Criar:  
git config --global user.name "Felipe Thomas"  
git config --global user.email "felipecejug@gmail.com"  
git config --global core.editor gedit  
git config --global alias.s status  
  
Visualizar:  
git config user.name  
git config user.email  
git config --list  

### Criar repositório localmente:
mkdir curso-git  
cd curso-git  
git init  
  
### Enviar repositório local para o remoto:
git remote add origin git@github.com:usuario/repositorio.git  
git remote  
git remote -v  
  
### Comandos usados com arquivos:
git status  
git add nome-do-arquivo  
git commit -m "comentario"  
git commit -am "comentario"  
git push -u origin master  

Brach:  
git branch  
git branch -r  
git branch -a  
git checkout -b testing  
git checkout master  
git brach -D testing   
git push origin :branch-a-ser-apagada-remote    
  
Merge:  
git merge testing  
git rebase testing  
  
Revert:  
git revert id-commit  
  
Log:  
git log  
git log --decorate  
git log --author="nome-do-autor"  
git log --graph  
git log --help  
git log --pretty=oneline  
git log --prety=format:"%h %an %ar - %s"  
git log --follow arquivo.txt  
git shortlog  
git shortlog -sm  
git slow hash-do-commit  
  
Diff:  
git diff  
git diff --name-only  
  
Stash:  
git stash  
git stash apply  
git stash list  
git stash clear  
  
Desfazer:  
git checkout nome-do-arquivo  
git reset HEAD nome-do-arquivo  
git reset --soft  
git reset --mixed  
git reset --hard  
https://git-scm.com/book/pt-br/v1/Git-Essencial-Desfazendo-Coisas  
  
Tag:  
git tag  
git tag -a 1.0.0 -m "comentario"  
git tag -d tag-a-ser-apagada-local  
git push origin master --tags  
git push origin :tag-a-ser-apagada-remote  
      
Renomear:    
git mv arquivo-origem arquivo-destino  
  
Apagar:  
rm nome-do-arquivo  
git rm nome-do-arquivo  
git rm --cached nome-do-arquivo   
  
Remote:  
git fetch origin  
git pull  
git pull --rebase  

