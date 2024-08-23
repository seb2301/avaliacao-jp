# avaliacao-jp
Configurando a sua máquina:
Inicie o GitBash e digite:
1-	git init  <-- O comando git init inicializa um novo repositório Git em um diretório existente, criando o subdiretório .git com os arquivos necessários. Para desfazer, basta excluir o diretório .git.-->

2-	git status  <-- O comando `git status` exibe o estado atual do repositório, mostrando arquivos modificados, novos e preparados para commit. Ele apenas informa, sem fazer alterações. -->

3-	git add <filename ou . >  <--O comando `git add <filename ou .>` adiciona arquivos ao índice (staging area), preparando-os para o próximo commit. Para removê-los da staging area, use `git rm --cached <file>`.-->

4-	git rm --cached <file> / git restore --staged <filename ou . >   <--  O comando `git rm --cached <file>` remove arquivos do índice (staging area), mas mantém esses arquivos no diretório de trabalho. Para adicioná-los de volta à staging area, use `git add <filename ou .>`. -->	

5-	git branch  <-- O comando git branch é usado para gerenciar branches no Git. git branch: Lista todas as branches locais existentes no repositório, mostrando em qual branch você está atualmente. git branch -r: Lista todas as branches remotas disponíveis no repositório. git branch -a: Lista todas as branches, tanto locais quanto remotas, em um único comando. -->

6-	git checkout <branchname>  <-- O comando git checkout <branchname> é usado para mudar para uma branch específica em seu repositório Git. Muda para a branch especificada: Quando você executa o comando, o Git troca a branch ativa para a especificada. Atualiza o diretório de trabalho: O conteúdo do diretório de trabalho será atualizado para refletir o estado dos arquivos conforme o que está na branch escolhida. Voltar à branch anterior: Para retornar à branch anterior, você pode usar git checkout <previousbranchname>.

7-	git checkout -b <branchname>  <-- O comando git checkout -b <branchname> cria uma nova branch e muda automaticamente para ela. Para excluir a branch, use git branch -D <branchname>, e para voltar à branch anterior, use git checkout <previous-branchname>. -->

8-	git commit -m "<description>"  <-- O comando git commit -m "<description>" salva as mudanças da staging area no repositório com uma mensagem. Use git reset --soft HEAD~1 para desfazer o commit mantendo as mudanças, ou git reset --hard HEAD~1 para desfazer o commit e as mudanças.  -->

9-	git merge  <branch>  <-- Faz o merge da branch ATUAL na Branch informada -->

10-	git push  <-- O comando git push envia commits do repositório local para o repositório remoto. Use git revert <commit-hash> para criar um commit que desfaz as mudanças de um commit específico. -->

11-	git branch -D <branchname>   <-- O comando `git branch -D <branchname>` exclui a branch especificada do repositório local. A exclusão é permanente, mas a branch pode ser recriada a partir de um commit específico, se necessário.-->

12-	git fetch <-- O comando "git fetch" baixa objetos e referências do repositório remoto, atualizando o repositório local sem mesclar.-->

13-	git pull <-- O comando git pull baixa objetos e referências do repositório remoto, mesclando com a branch atual. É possível usar git reset --hard para reverter ao commit anterior ao pull.-->

