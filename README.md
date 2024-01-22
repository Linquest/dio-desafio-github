# Desafio Git e GitHub

Este é um desafio que tem como objetivo ensinar o que é e como usar as funções básicas de Git e GitHub, tais como:

- Inicializar um repositório local
- Adicionar arquivos ao controle de versão
- Fazer commits das alterações
- Criar um repositório remoto
- Sincronizar o repositório local com o remoto
- Criar e mesclar branches
- Resolver conflitos
- Fazer pull requests
- Clonar e forkar repositórios

## Como participar

Para participar deste desafio, você deve seguir os seguintes passos:

1. Faça um fork deste repositório para a sua conta do GitHub
    Para fazer um fork, basta clicar no botão “Fork” no canto superior direito da página do repositório no GitHub. Isso vai criar uma cópia do repositório na sua conta.
2. Clone o repositório forkado para o seu computador
    Para clonar o repositório, abra o git bash e navegue até a pasta onde você quer salvar o projeto. Em seguida, digite o seguinte comando, substituindo <seu_usuario> pelo seu nome de usuário do GitHub:

```bash
git clone https://github.com/<seu_usuario>/desafio-git-github.git

3. Crie uma branch com o seu nome
    Para criar uma branch com o seu nome, digite o seguinte comando, substituindo <seu_nome> pelo seu nome:
 git checkout -b <seu_nome>

4. Complete as tarefas propostas no arquivo TAREFAS.md
    Para completar as tarefas, você deve abrir o arquivo TAREFAS.md com o seu editor de texto preferido e seguir as instruções. Você pode usar o comando `cat` para ver o conteúdo do arquivo no terminal:

```bash
cat TAREFAS.md

5. Faça um commit das suas soluções
    Para fazer um commit das suas soluções, você deve primeiro adicionar os arquivos modificados ao stage com o comando `git add`. Você pode adicionar todos os arquivos de uma vez com o ponto (.) ou especificar os nomes dos arquivos que você quer adicionar. Por exemplo:

```bash
git add .
    ou
git add TAREFAS.md

6. Faça um push da sua branch para o seu repositório remoto
    Para fazer um push da sua branch para o seu repositório remoto, você deve usar o comando `git push` com o nome do seu repositório remoto (geralmente `origin`) e o nome da sua branch. Por exemplo:

```bash
git push origin <seu_nome>

7. Abra um pull request para este repositório original
    Para abrir um pull request, você deve acessar o seu repositório no GitHub e clicar no botão "Compare & pull request" que vai aparecer na página principal. Isso vai abrir uma página onde você pode revisar as suas alterações e escrever um título e uma descrição para o seu pull request. Depois de preencher essas informações, clique no botão "Create pull request" para enviar o seu pedido de mesclagem para o repositório original.

## Recursos úteis

Aqui estão alguns recursos úteis para você aprender mais sobre Git e GitHub:

- [Git - Documentação oficial](https://gist.github.com/lohhans/f8da0b147550df3f96914d3797e9fb89)
- [GitHub - Guia do iniciante](https://www.alura.com.br/artigos/escrever-bom-readme)
- [Curso de Git e GitHub da Alura](https://gist.github.com/f8da0b147550df3f96914d3797e9fb89)
- [Livro Pro Git](https://dev.to/guilhermemanzano/como-criar-um-readme-md-para-o-github-do-jeito-certo-2lgg)
- [Markdown - Guia de referência](https://github.com/mende1/guia-definitivo-de-markdown)