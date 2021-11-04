# COMANDOS GIT

git --version <br>
Para saber a versão do git que está instalada no computador<br>

README.md<br>
Serve como um arquivo de instruções.<br>
md - markdown - linguagem de marcação.<br>

git init <br>
Deve dar o comando na pasta para que ele incie um repositório local<br>
Nesse momento é criada uma pasta do git<br>

git add nome_do_arquivo <br>
Adiciona os arquivos para area de stage.<br>

git add.<br>
Adiciona todos os arquivos.<br>

git status<br>
Mostra a situação dos arquivos<br>

git commit -m "mensagem do commit"<br>
Salva/atualiza as alterações. Criar ponto na história.<br>

git show numero do commit<br>
mostra as mudanças na história especificada<br>

git show<br>
mostra o ultimo ponto ou mudança na história<br>

git log <br>
mostra os pontos, os commits nesse projeto ou as mudanças<br>

git branch -M "nome da branch"<br>
Muda o nome da branch que está sendo usada.<br>

git remote add origin url do git<br>
Faz a conexão do repositório local com o remoto.<br>

git remote -v<br>
visualizar os repositórios remotos<br>

git push -u origin main<br>
Serve para mandar os arquivos do repositório local para o repositório remoto<br>

---

Quando forem feitas alterações nos arquivos<br>
Deve-se novamente adiciona-los no stage<br>
git add nome do arquivo<br>

git commit -m "nova alteração"<br>
No github aparece o momento que isso é feito e o nome da mensagem.<br>
Caso no github seja clicado nele, mostra as alterações que foram feitas no arquivo
em questão.<br>

Existe como usar direto o comando<br>
git commit -am "mensagem"<br>
Adiciona e commita, todos os arquivos<br>

git push<br>
Manda as mudanças do repositorio para o repositorio remoto.<br>

Para adicionar alguma nova feature ou alteração no projeto.<br>
Criamos uma branch.<br>
git checkout -b "nome da branch"<br>
Quando for criada, será mudado o local de trabalho da main para o nome da branch.<br>

Outra maneira é<br>
git branch nome da branch<br>
git checkout nome da branch<br>

Para visualizar no terminal todas as branchs<br>
git branch<br>

Para deletar uma branch<br>
git branch -D nome da branch<br>

git add .<br>
git commit -m "alteração no projeto ou nova feature"<br>
git push origin nome da branch<br>

---

OBS: CASO o git merge de uma branch seja feito na main<br>
teriamos que dar um git checkout da branch e um git merge main<br>
para unirmos de forma correta a branch main da branch criada<br>

---

Git rebase e merge ambos integram mudanças de um branch para outro.<br>
A diferença é como isso é feito. Git rebase move um feature branch para a master.<br>
Git merge adiciona um novo commit, preservando o histórico.<br>

---

git checkout main<br>
serve para voltarmos para a branch principal<br>

git merge nome da branch(isso precisa ser feito na branch criada e não na main)<br>
Serve para mesclar a branch com a principal<br>

git push origin main<br>

Para trazer um repositório remoto, ja existente, para o meu repositório local<br>
só apertar code no github e copiar o link.<br>
git clone nome do link<br>

---<br>

Caso seja feita alguma alteração direto no github ou feito por outra pessoa<br>
no repositório remoto no e eu não tenho atualizado no meu repositório local<br>
é necessário eu atualizar o meu repositório local com o remoto<br>
para isso usamos o comando:<br>
git pull<br>

O botao fork no github, serve para copiar um repositório de outra pessoa para<br>
o repositório no meu perfil.<br>

Para que não precise ficar colocando o email e senha toda hora que fizer o<br>
git push, só dar o comando git config credential.helper store<br>

Para desfazer uma alteração antiga local que foi feita, ou arquivo deletado<br>
git log, copiar o commit correspondente.<br>
git checkout commit correspondente -- nome do arquivo<br>

Caso seja deletado um arquivo, para restaurar ele<br>
git checkout -- nome do arquivo<br>
caso não tenha sido feito nenhum commit antes<br>
