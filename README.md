## Trabalhando com Branches:
* "Ramo" é uma ramificação do seu projeto.
* É um ponteiro móvel para um commit no histório do repositório;
* Quando vc cria uma nova Branch a partir de outra existente, a nova se inicia apontando para o mesmo commit da Branch que estava quando foi criada.

| Command| Note | 
|----------------------|-----------------|
| echo "[file content]" > commit-1-branch-main.txt | create a new txt file with content | 
| git checkout -b test | create a New branch named "test" | 
| q | exists screen, when getting stuck after "git log"| 
| git checkout main | retunr to the main branch |
| git branch -v | List last commit to each branch | 
| git merge [branch name] | to merge both branches, copy changes from test to main |
| git branch -d [name of the branch] | to delete the branch | 


