# HTML e CSS

## HTML

> HTML é uma linguagem de marcação para definir a estrutura do seu site.



Para definir que o documento é HTML, devemos incluir a seguinte declaração:

###### <!DOCTYPE html>

E para declarar a linguagem do site, no caso, português do Brasil, utilizamos:

###### <html lang="pt-br">



### Head <head>

O Head é a parte da página que contém os meta dados e não é exibida no navegador da Web quando a página é carregada.

- `<title>` : inserido dentro do header, é o título da página, exibido na aba do browser

- `<meta charset="utf-8">`: formato de codificação, é o padrão unicode
- `<link rel="stylesheet" href="styles.css">`: é o link para o css



### Body <body>

É a parte da página visível ao usuário. Todas as informações, títulos, parágrafos, mídias, links, tabelas, listas, formulários, etc.

##### Textos

- `<h1>` : título principal
- `<h2>` - `<h6>`  : títulos secundários
- `<p>` : parágrafo
- `<br>` : quebra de linha

##### Links

- `<a>` : tag de link
- `href` : endereço do link
- `<a href="https:www.w3schools.com">Isso é um link</a>`

→ Target atributte: especifica onde será aberto o link

- `_self` : abre na mesma janela ou tab (default)

- `_blank` : abre o link em uma nova janela ou tab

##### Mídias

→ Imagem (APNG (.apng), GIF (.gif), ICO (.ico), JPEG (.jpg, .jpeg, .jfif, .pjepg, .pjp), PNG (.png), SVG (.svg)

- `<img>` : tag de imagem
- (`src`): fonte (`alt`): texto alternativo
- `<img src="w3schools.jpg" alt="logo W3schools"</a>`
- `<map>` : define um mapa
- `<area>` : define uma área clicável dentro de um mapa
- `<picture>` : define um container para múltiplas imagens

→ iFrame

`<iframe>`: Define um frame inline: `<iframe src="url" title="description"></iframe>`

→ Video

(MP4, WebM, Ogg)

`<video>` : tag de vídeo

`<video autoplay mute><source src="movie.mp4" type="video/mp4"</a></video>`

Youtube video:`<iframe width="420 height="315" src="<https://www.youtube.com/embed/jdhfsldhf></iframe>`

→ Áudio

(MP3, WAV, Ogg audio)

`<audio>` : tag de áudio

`<audio autoplay mute><source src="movie.mp4" type="video/mp4"</a></audio>`

##### Tabelas

- `<table>` : tag de tabela
- `<tr>` : table row
- `<th>` : table header

→ Como default, os elementos são bold e centralizados

- `<td>` : table data/cell

→ Como default, os elementos são regular e alinhados à esquerda

##### Listas

- `<ul>`: lista não ordenada
- `<ol>`: lista ordenada
- `<li>`: item da lista
- `<dl>`: lista descritiva , `<bt>`: termo e `<dd>`: descrição

##### Outras tags

- `<div>`: container para outros elementos html
- `<span>`: elemento genérico para conteúdos
- `<nav>`: elemento de navegação
- `<section>`: define uma seção
- `<article>`: define um conteúdo independente
- `<aside>`: define um content separado, como um sidebar
- `<footer>`: elemento do footer
- `<details>` : define detalhes adicionais que o usuário pode abrir e fechar sob demanda
- `<summary>`: define um heading para o elemento `<details>` element

##### Comentários

`<!--Escreva os seus comentários-->`

Mais informações: [HTML Tutorial](https://www.w3schools.com/html/)



## CSS

> CSS significa Cascading Style Sheets e é uma linguagem para definir estilos.

O link para o arquivo css deve ser inserido no <head> do html, da seguinte forma:

```html
<link rel="stylesheet" href="mystyle.css">
```

##### Sintaxe

Uma regra de CSS consiste em um **seletor** e um **bloco de declaração** (propriedade e valor).

*ex: Vamos definir o estilo do h1 da página*

```css
  **h1** = { color: blue; font-size: 12px;}
```

##### Seletores

- Simple (seleciona por nome, id, class)

```css
p { text-align: center; color: red;}
```

[Seletores simples](https://www.notion.so/0d1e3f0622cc4a2e9024af8d37d6a809)

- [Combinator](https://www.w3schools.com/css/css_combinators.asp) (seleciona baseado no relacionamento entre elementos)
- [Pseudo-class](https://www.w3schools.com/css/css_pseudo_classes.asp) (seleciona o elemento baseado em algum estado)
- [Pseudo-elements](https://www.w3schools.com/css/css_pseudo_elements.asp) (seleciona uma parte de um elemento)
- [Attribute](https://www.w3schools.com/css/css_attribute_selectors.asp) (baseado em um atributo ou valor de atributo)

##### Comentários

```css
/* This is a single-line comment */
```

##### Cores

Cores são especificadas utilizando nomes pré-definidos, RGB, HEX, HSL, RGBA ou HSLA.

HEX → [](https://www.w3schools.com/css/css_colors_hex.asp)[CSS HEX Colors](https://www.w3schools.com/css/css_colors_hex.asp)

Background

- `background-color`
- `background-image`
- `background-repeat`
- `background-attachment`
- `background-position`
- `background` (shorthand property)




