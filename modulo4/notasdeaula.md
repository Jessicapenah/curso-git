## Fazendo um fork
Fork é um jeito de contribuir para projetos de outras pessoas
fork no github 
vai em code no github
copia o url
aqui da um git clone

## Atualizar o fork 
da pra fazer via github ou por linha de comando:
git remote add upstream (url do repositorio)
git fetch upstream -> fetch é similar ao pull e ele pega todas as atualizações do outro
git rebase upstream/master - ele rebalencea o teu branch comparando com esse lugar que vais puxar a atualização

## Criando branch
criei a branch
adicionei uma notas
fiz a receita:
git status
git add .
git status
git commit -m "com comentários"
faz o push (atualização no repositorio virtual)
git push --set-upstream origin 'nome da branch'

## Pull resquest 
fez o pull request: so copiar o link que aparece apos o executar o git push
subiu no github subemeteu 
a autora vai receber e revisar e pedir alteraççao
altero aqui mesmo
e faço 
git add .
git commit -m "comentarios"
git push
