# curso-git
Curso de Git e Github para iniciantes da Udemy oferecido por Willians Justen

### Instalação:
https://git-scm.com/downloads

### Configuração:
Criar:  
git config --global user.name "Felipe Thomas"  
git config --global user.email "felipecejug@gmail.com"  
git config --global core.editor gedit  

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
  
### Comandos do dia-a-dia
git status  
git add <nome-do-arquivo>  
git commit -m "comentario"  
git commit -am "comentario"  
git push -u origin master  
  
Log:  
git log  
git log --decorate  
git log --author="nome-do-autor"  
git log --graph  
git shortlog  
git shortlog -sm  
git slow <hash-do-commit>  
  
Diff:  
git diff  
git diff --name-only  
  
Desfazer:  
git checkout <nome-do-arquivo>  
git reset HEAD <nome-do-arquivo>  
git reset --soft  
git reset --mixed  
git reset --hard  

 
