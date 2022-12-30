## Exercicio1

este exercicio consiste em:
criar um repositorio local, adicionar arquivos, fazer o push do repositorio online e ver no github

## passo a passo
* criar uma pasta na tua raiz: 
cd ../
mkdir nomedapasta
* entrar na pasta: 
cd nomedapasta
* abrir o vs code dentro dessa pasta:
code .
* tornar a pasta rastreava para o git: 
git init
* adicionar os arquivos ou edições que quiser na pasta
* feitas as edições vai no github e clica em:
(+) -> new repositorio
* depois que criar o repositorio no github pega o link (url_novo_repositorio) 
* no terminal code novo fazes um: 
git remote add origin url_novo_repositorio
* checa se o link com o repositorio deu certo: 
git remote -v
* verificar se tem algo pra adicionar e comitar
git status
git add .
git commit - m "comentario"