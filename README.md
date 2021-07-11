## REPOSITÓRIO DE TESTES E ESTUDOS SOBRE GIT :open_file_folder: 🚀


- Git Branching
    * Criando uma nova branch 
        > `git branch testing`
    * Criando branch e trocando para ela
        > `git checkout -b testing`
    * Trocando de branch
        > `git checkout testing`
    * Obtendo lista de branches
        > `git branch`
    * Verificando o último commit em cada branch
        > `git branch -v`  
    * Histórico de commits mostrando ponteiros de branch
        > `git log --oneline --decorate --graph --all`

- Git branches e mesclagem básica
   * Criando uma branch, trocando para branch principal e executando a mesclagem
      1. `git checkout -b testing` 
      2. `git checkout main`
      3. `git merge testing`
   
   * Após mesclagem podemos deletar a branch
      1. `git branch -d testing`  
   
   * Branches que contém trabalhos que ainda não foram mesclados
      > `git branch --no-merged`

   * Verificar branches com trabalhos já mesclados
     > `git branch --merged`
   
   * Alterando nome da branch local e remotamente
     1. Local: `git branch --move bad-branch-name corrected-branch-name`
     2. Remoto: `git push --set-upstream origin corrected-branch-name` 
     3. Excluindo branch com o nome errado: `git push origin --delete bad-branch-name`
 

Referência:
<a href="https://git-scm.com/book/en/v2">Git book</a>

### Autor
---

Lennon de Oliveira
 


 [![Linkedin Badge](https://img.shields.io/badge/-Lennon-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/johnlennondeoliveira/)](https://www.linkedin.com/in/johnlennondeoliveira/) 
