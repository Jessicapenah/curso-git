## Branch
o comando necessario para criar uma branch e ja ir pra essa branch:
    git checkout -b modulo-3

verificar quantas branch a gente tem:
    git branch
    o que tiver com * é a branch que voce ta

para voltar/ir para uma git especifica:
    git checkout (nome da branch)


quando voce faz o commit em uma branch so vai existir aquela pasta, aruivo ou conteudo nessa branch

## Enviando a branch do local para o remoto

## git merge
fazendo o merge entre branchs
git merge (nome da branch) -> vai mergear na tua branch atual (acho)


## receita:
git status
git checkout -b (nome da branch) -> se quiser criar uma branch nova
alterações
git add .
git status
git commit -m "comentarios sobre alterações"
git merge (nome da branch para ser adicionada) -> lembre de estar na branch que queres mergear 
git push -> para fazer o update no github
