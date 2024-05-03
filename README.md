# README

## Genesis - Jogo Genius

Este é um simples jogo Genius implementado em HTML, CSS e JavaScript.

### Estrutura do Projeto

O projeto consiste em três arquivos principais:

1. `index.html`: Este é o arquivo principal que define a estrutura da página HTML. Ele contém a marcação HTML para os elementos da página, como botões e contêineres.

2. `style.css`: Este arquivo contém estilos CSS para estilizar os elementos HTML. Ele define as cores, tamanhos, posicionamentos e outros estilos visuais para os elementos da página.

3. `script.js`: Este arquivo contém o código JavaScript para adicionar interatividade à página. Ele manipula eventos do usuário, como cliques e teclas pressionadas, e atualiza dinamicamente o conteúdo da página conforme necessário.

### Estrutura do HTML

O arquivo HTML (`index.html`) consiste nas seguintes partes principais:

- `<!DOCTYPE html>`: Declara o tipo de documento HTML.

- `<html lang="en">`: Define a raiz do documento HTML e especifica o idioma como inglês.

- `<head>`: Contém metadados sobre o documento, como a codificação de caracteres, viewport e referências a arquivos CSS e JavaScript externos.

- `<meta charset="UTF-8">`: Define o conjunto de caracteres como UTF-8 para suportar uma ampla gama de caracteres.

- `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Configura a largura da viewport para o tamanho do dispositivo e define a escala inicial como 1.

- `<link rel="stylesheet" href="style.css">`: Referência ao arquivo CSS externo para estilização da página.

- `<title>Genesis</title>`: Define o título da página exibido na aba do navegador.

- `<body>`: Contém o conteúdo visível da página, como elementos HTML e scripts.

- `.main-game`: Div que envolve todo o conteúdo do jogo.

- `.genius`: Div que contém os botões coloridos do jogo.

- `.blue`, `.yellow`, `.red`, `.green`: Divs que representam os botões azul, amarelo, vermelho e verde, respectivamente.

### Interação JavaScript

O arquivo JavaScript (`script.js`) é responsável por adicionar interatividade ao jogo. Ele manipula eventos do usuário, como cliques nos botões, e atualiza dinamicamente o conteúdo da página conforme necessário.

### Como Jogar

O jogo Genius consiste em memorizar e repetir sequências de cores que são geradas aleatoriamente. Para jogar, aguarde até que uma sequência de cores seja exibida no jogo, e então clique nos botões na mesma ordem em que foram exibidos. Se você acertar a sequência corretamente, o jogo aumentará a dificuldade, adicionando mais cores à sequência. Se você errar, o jogo terminará.

### Como Executar

Para jogar o jogo, basta abrir o arquivo `index.html` em um navegador da web compatível.
