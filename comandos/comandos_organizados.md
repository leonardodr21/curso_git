### Comandos básicos do Bash

* **`cd`** → muda o diretório atual;

* **`ls`** → lista os itens do diretório atual;

* **`pwd`** → mostra o caminho absoluto do diretório atual;

* **`ls -a`** → mostra todos os arquivos e diretórios, incluindo os ocultos;

* **`cd ..`** → sobe um nível no diretório;

* **`mkdir nome_da_pasta`** → cria uma nova pasta;

* **`cat nome_arquivo`** → mostra o conteúdo de um arquivo;

* **`nano nome_arquivo`** → abre o arquivo em um editor de texto dentro do terminal;

* **`touch nome_novo_arquivo`** → cria um arquivo vazio;

* **`rm nome_arquivo`** → remove um arquivo;

* **`rm -rf nome_do_diretorio`** → remove recursivamente e de forma forçada um diretório e seu conteúdo. **Cuidado:** esse comando pode apagar arquivos permanentemente;

---

### Inicialização e configuração do Git

* **`git init .`** → transforma a pasta atual em um repositório Git;

* **`rm -rf .git`** → remove a pasta `.git`, deixando a pasta comum novamente e eliminando o histórico e as configurações locais do Git;

* **`git config --global user.email "exemplo@email.com"`** → configura o e-mail que será utilizado para identificar os commits;

* **`git config --global user.name "exemplo"`** → configura o nome que será utilizado para identificar os commits;

* **`git status`** → mostra o estado atual do repositório, incluindo arquivos modificados, não rastreados e arquivos preparados para commit;

---

### Commits

* **`git add nome_arquivo`** → adiciona um arquivo à área de staging, preparando-o para o commit. É possível adicionar mais de um arquivo;

* **`git add .`** → adiciona todos os arquivos modificados e não rastreados da pasta atual à área de staging;

* **`git commit -m "mensagem"`** → cria um commit com uma mensagem que descreve as alterações realizadas;

* **`git log`** → mostra o histórico de commits, incluindo informações como autor, data e mensagem;

* **`git diff nome_arquivo`** → mostra as diferenças entre o estado atual do arquivo e a última versão registrada no Git;

* **`git reset nome_arquivo`** → remove o arquivo da área de staging, mantendo as alterações realizadas no arquivo;

* **`git mv nome_antigo nome_novo`** → renomeia ou move um arquivo, registrando a alteração no Git;

---

### Branches

* **`git checkout -b nome_branch`** → cria uma nova branch e muda para ela;

* **`git branch`** → lista as branches locais e indica a branch atual;

* **`git checkout nome_branch`** → muda para a branch especificada;

* **`git merge nome_branch`** → mescla as alterações da branch especificada com a branch atual;

* **`git branch -d nome_branch`** → exclui a branch local especificada;

---

### GitHub e repositórios remotos

* **`git clone link_do_repositorio`** → copia um repositório remoto do GitHub para o computador local;

* **`git push origin nome_da_branch`** → envia os commits da branch local para o repositório remoto, no GitHub;

* **`git pull origin main`** → busca as alterações da branch `main` do repositório remoto e as integra à branch atual. É semelhante a executar um `fetch` seguido de um `merge`;

* **`git fetch`** → busca as informações e atualizações do repositório remoto sem integrá-las automaticamente à branch local.
