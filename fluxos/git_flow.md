## fluxo sobre branches
A partir da `main`, é criada uma branch `develop`, que servirá como base para as próximas branches.

As próximas branches serão criadas a partir da `develop`.

Quando o trabalho de uma branch for finalizado, deverá ser realizado um merge com a `develop`.

Somente quando a `develop` estiver mais robusta, estável e sem erros ou bugs, deverá ser realizado o merge com a `main`.

A imagem abaixo busca representar esse fluxo:

* **Círculo:** representa um commit.
* **Linha azul:** representa um checkout.
* **Linha verde:** representa um merge.
* **Linha preta:** representa a transição entre commits.

![fluxo de branches](../imgs/fluxo.png)

## Prefixos padrões das branches
* **docs:** apenas mudanças na documentação;

* **feat:** adição de uma nova funcionalidade;

* **fix:** correção de um bug;

* **perf:** mudanças no código focadas em melhorar a performance;

* **refactor:** mudanças no código que não adicionam uma funcionalidade e também não corrigem um bug;

* **style:** mudanças no código que não afetam seu significado, como espaços em branco, formatação, ponto e vírgula, etc.;

* **test:** adição ou correção de testes.


## Prefixos padrões de commits
* **fix:** correção de um bug;

* **feat:** adição de uma nova funcionalidade;

* **docs:** apenas mudanças na documentação;

* **style:** mudanças no código que não afetam seu significado, como espaços em branco, formatação, ponto e vírgula, etc.;

* **refactor:** mudanças no código que não adicionam uma funcionalidade e também não corrigem um bug;

* **build:** modificações em arquivos de build e dependências;

* **test:** adição ou correção de testes;

* **chore:** tarefas repetitivas, manutenção ou infraestrutura. Ex.: adicionar um pacote ao `.gitignore`. Não inclui alterações no código.


Você pode colocar as fontes ao final do documento desta forma:

### Fontes

* **DEV Community — “Padrões e Nomenclaturas no Git: Um Guia Prático”**, de Guilherme Gomes. O artigo aborda padrões para commits, branches e o fluxo entre `main`, `dev`, `feature`, `bugfix` e `hotfix`. ([DEV Community][1])
  [Acessar artigo no DEV Community](https://dev.to/gguife/padroes-e-nomenclaturas-no-git-um-guia-pratico-3l2f?utm_source=chatgpt.com)

* **Medium / Prolog App — “Nossos padrões de nomenclatura para branches e commits”**, de Luiz Felipe. O artigo apresenta convenções para nomes de branches e commits, incluindo os tipos `docs`, `feat`, `fix`, `perf`, `refactor`, `style` e `test`, além da estrutura de mensagens de commit. ([medium.com][2])
  [Acessar artigo no Medium](https://medium.com/prolog-app/nossos-padr%C3%B5es-de-nomenclatura-para-branches-e-commits-fade8fd17106?utm_source=chatgpt.com)

[1]: https://dev.to/gguife/padroes-e-nomenclaturas-no-git-um-guia-pratico-3l2f "Padrões e Nomenclaturas no Git: Um Guia Prático - DEV Community"
[2]: https://medium.com/prolog-app/nossos-padr%C3%B5es-de-nomenclatura-para-branches-e-commits-fade8fd17106 "Medium"
