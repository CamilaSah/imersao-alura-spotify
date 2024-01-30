![Front-end-Imersão Front-End Alura](https://github.com/CamilaSah/imersao-alura-spotify/assets/128820692/722f63b9-4884-4ae7-a9d5-89e7a0bbf8cb)
![Static Badge](https://img.shields.io/badge/Status-Conclu%C3%ADdo-%2391DCFF)

<h1> Imersão Front-End Alura - Spotify </h1>

Este projeto prático foi desenvolvido durante a Imersão Front-End da Alura, no qual foi proposto desenvolver uma página inspirada no Spotify, mergulhando em HTML e CSS, além de conhecer um pouco de Javascript e ver o conceito de React.

## :hammer: Funcionalidades do projeto
- `Pesquisar por nome de artista ou gênero`: quando o usuário digitar o nome do artista ou do gênero no campo de pesquisa, aparecerá os resultados da pesquisa embaixo.

![apresentacao-imersao-front-alura840](https://github.com/CamilaSah/imersao-alura-spotify/assets/128820692/91b2e0a7-e82b-47f1-b33e-3b7c0ba4f5a4)


## 📁 Acesso ao projeto

Para poder acessar o projeto, você precisa:
* Baixar a pasta deste projeto.
* Instalar o json-server: simula um servidor local no seu computador.
* Instalar o Node.js: é um ambiente de execução do código Javascript do lado servidor (server side), que permite executar aplicações desenvolvidas com a linguagem sem depender de um navegador.
* Instalar o Live Server: é uma extensão para o Visual Studio Code que cria um servidor local para hospedar seu projeto e atualizar automaticamente a página quando você faz alterações no código. Você pode usar outra aplicação, caso queira.

O passo a passo para conseguir acessar o projeto é:

Caso você ainda não tenha instalado o Node.js e o json-server:
1. Baixar a pasta deste projeto.
2. Entrar no site nodejs.dev e fazer o download no Node.
3. Abrir o projeto no VSCode.
4. Abrir o terminal do VSCode.
5. Clicar em "Terminal" -> “Novo terminal”.
6. Escrever o comando `npm init` para iniciar o npm dentro do projeto.
7. Dar “Enter” em todas as opções.
8. Escrever o comando `npm install -g json-server` para executar a instalação do json-server.

Caso você já tenha instalado o Node.js e o json-server:
1. Baixar a pasta deste projeto.
2. Abrir o projeto no VSCode.
3. Abrir o terminal do VSCode.
4. Clicar em "Terminal" -> “Novo terminal”.
5. Escrever o comando `npx json-server --watch artists.json` para iniciar o servidor.
6. Ele vai iniciar o servidor local em uma porta `[PORT_NUMBER]`. Quando você quiser acessar o URL do servidor vai ser localhost:`[PORT_NUMBER]`/artists.
7. Abrir o `index.html` com o Live Server.
<br>
PS¹.: Você pode usar o terminal do Git Bash ao invés do VSCode, caso queira.
PS².: O projeto só irá funcionar se o servidor local estiver sendo executado no terminal do VSCode ou no Git Bash.

## ✔️ Técnicas e tecnologias utilizadas

Técnicas utilizadas:
- ``Estrutura básica do HTML``: foi utilizada para criar um arquivo HTML funcional, seguindo uma estrutura padrão com ``<head>``,``<body>`` e ``<footer>``.
- ``Tags semânticas``: foram utilizadas as tags ``<section>``, ``<nav>``, ``<main>``, ``<footer>`` e ``<a>`` para construir a página e torná-la mais clara.
- ``Classes no CSS``: foram utilizadas para selecionar e acessar elementos específicos com o intuito de utilizar no CSS e no Javascript.
- ``Reset CSS``: foi utilizada para limpar todos os padrões dos navegadores.
- ``Flexbox``: foi utilizado para fazer o posicionamento dos elementos.
- ``Estilos de texto e fontes``: foram utilizados para alterar o tamanho, tipo e peso da fonte com ``font-size``, ``font-family`` e ``font-weight``.
- ``Ícones``: foi utilizado o fontawesome para adicionar o ícone da página, no qual foi importado seu código e utilizou-se a classe para adicionar determinado ícone.
- ``Hover``: foi utilizado para estilizar elementos ao passar o mouse sobre eles com o seletor ``hover``.
- ``Variáveis CSS``: foram utilizadas para conseguir manipular e reutilizar valores no código, como as cores e fontes.
- ``Media Queries``: foi utilizada para adaptar o site para diversos tamanhos de tela, configurando os seus pontos de quebra do layout, os famosos Break Points.
- ``Função getElementById()``: faz uma busca do elemento pelo ID.
- ``Função addEventListener()``: permitiu que fossem configuradas funções a serem chamadas quando o usuário colocasse algum valor no input.
- ``Arrow functions``: sintaxe mais curta quando comparada a uma expressão de função para declarar a função que não será nomeada novamente.
- ``Template string (${})``: foi utilizado para mudar o texto da fonte da imagem de forma dinâmica.
- ``element.innerText``: esta propriedade permite inserir textos no HTML.
- ``Atributo classList``: foi utilizado para adicionar e remover uma classe em um elemento HTML através do JavaScript, com as funções add e remove.
- ``Método fetch``: é um método assíncrono e tem como parâmetro obrigatório a URL da API.
- ``Método then()``: foi utilizado para acessar o valor retornado do fetch API.
- ``Método json()``: foi utilizado para converter dados em JSON.

Tecnologias e ferramentas utilizadas:
- ``HTML5``: foi utilizado para a construção desse site e inserção de conteúdo por meio dos hipertextos.
- ``CSS``: foi utilizada para estilização da página.
- ``VS Code``: O código foi desenvolvido neste editor de código.
- ``Developer Tools``: foi utilizada para escolher o tipo de dispositivo a ser visualizado, inspecionar os elementos HTML, alterar o tamanho da tela e  os estilos CSS da página temporariamente e abrir a visualização responsiva.
- ``Extensão Live Server``: é uma extensão para o Visual Studio Code que cria um servidor local para hospedar seu projeto e atualizar automaticamente a página quando você faz alterações no código. 
- ``Git``: Ferramenta de controle de versão de seu arquivo, projeto ou código. 
- ``GitHub``: Plataforma para gerenciar seu código e criar um ambiente de colaboração entre devs (permite compartilhamento de código através da criação de repositórios), utilizando o Git como sistema de controle.
- ``Vercel``: Colocar o projeto no ar e compartilhar com o mundo.

## 📚 Mais informações da Imersão
A Imersão foi ministrada pelos professores: [Guilherme Lima](https://www.linkedin.com/in/guilherme-lima-developer/), [Mayara Cardoso](https://www.linkedin.com/in/mayara-cardoso-556a45162/) e [Fernanda Degoli](https://www.linkedin.com/in/fernandadegolin/) e contou com este cronograma:
<br>
![image](https://github.com/CamilaSah/imersao-alura-spotify/assets/128820692/3241c4b1-e359-4dda-99c1-2359c74d5f1c)

# Autor

| <img src="https://github.com/CamilaSah/site-pessoal/assets/128820692/bed790ab-3722-4503-8fed-c786e774661b" width="100"><br>[<sub>Camila Sayuri Tokubo</sub>](https://www.linkedin.com/in/camila-tokubo/)|
| :---: |
