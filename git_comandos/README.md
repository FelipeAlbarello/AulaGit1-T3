# COMANDOS GIT

git init // Inicializa um repositório local <br>
git config --global user.name nomeUsuario // agrega seu nome ao repositório <br>
git config --global user.email nomeUsuario@email.com // agrega seu email ao repositório <br>
git remote add origin https://github.com/DH/RepoRemoto // aponta um repositório remoto <br>
git add . // adiciona todos os arquivos <br>
git add nome_do_arquivo // adiciona o arquivo <br>
git reset nome_do_arquivo // retirar um arquivo que foi adicionado por engano <br>
git reset . // desfazer todos os arquivos que foram adicionados <br>
git status // mostra o estado dos arquivos <br>
git commit -m "o que foi feito" // salva as alterações do arquivo ou dos arquivos <br>
git reset HEAD // desfaz o último commit <br>
git commit --amend -m "Nova mensagem" // editar o último commit ou a última mensagem <br>
git branch nome_da_branch // cria uma nova branch <br>
git push origin master // envia as mudanças para o repositório remoto, caso ele esteja vazio <br>
git rm // remover arquivos de um respositório do git
git rm --cached nome_do_arquivo // para remover esses arquivos apenas do git sem removê-los localmente
