git init **inicia um repositório local no  diretório**

git add . **adiciona todos os arquivos do diretório ao repositório local**

git commit -m "mensagem" **cria um repositório online e deixa os arquivos online**

git branch -M main **renomea a branch para main/padrão para projetos**

git remote add origin linkDoRepositórioNoGithub **upa os arquivos do repositório online para o repositório criado no github**

git push -u origin main **upa os arquivos do repositório online para o repositório criado no github**

git clone linkDoRepositórioNoGithub **faz download do repositório na pasta em que você estiver no terminal**

git status **mostra os arquivos alterados, adicionaddos no repositório local e os que ainda não foram adicionador**

git log **mostra as ultimas versões do repositório**

git pull origin main **puxa os arquivos do repositório no github e baixa no seu repositório remoto**

git revert idDOCommit **reverte o commit selecionado**

git reset --hard idDoCommitAnterior(para o qual quer voltar) **apaga o commit do seu repositório local**

**também é possível fazer essa mudanças pela interface do vscode**