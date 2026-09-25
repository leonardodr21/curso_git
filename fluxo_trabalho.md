## Fluxo de trabalho Git local
1. Criar diretorio (pasta) do projeto
2. iniciar git dentro do diretorio --> git init .
3. git checkout -b nova_branch
4. editar ou criar arquivos 
5. git status
6. git add <nome_arquivo> -->pode ser utilizado o . para adicionar todos os arquivos da pasta atual para o commit
7. git status 
8. git commit -m "mensagem enviada no commit"
9. git status
10. git checkout main 
11. git merge <nova_branch>
12. git branch -d nova <nome_branch>
13. git status
14. retorna ao passo 3

## Fluxo de trabalho Github <> (projetos open-source)
1. fork do projeto para seu próprio github
2. git clone <endereco do projeto fork>
3. git checkout -b <nova_branch>
4. alterações de arquivos
5. git status
6. git add <nome_arquivo>
7. git status
8. git commit -m "nova mensagem"
9. git push <nova_branch>
10. abrir pull request no github da branch fork para main do projeto original
11. excluir <nova_branch> origin
12. checkout main
13. git branch -d <nova_branch>