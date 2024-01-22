# Aula 01. Revisão: HTML, CSS e JS na prática

## O que vamos fazer?

- Uma página inspirada no SpotiFy

## Conceitos

- HTML
	- Estrutura da página
	- Esqueleto da página
- CSS
	- Vai dar beleza
	- Vai dar estilo
	- tudo relacionado ao estilo
- JavaScript
	- Dinamismo
	- Interagir com o usuário

- Em comparação com o corpo humano:
	- HTMl: esqueleto
	- CSS: Nosso corpo, beleza
	- JS: Nosso cerebro

## Começando o projeto

- Criamos o diretório
	- spotify-imersao-alura
	- index.html
	- style.css
	- script.js

- Nao se procupar com uma estrutura muito grande, posterior ao longo do projeto, vamos reestruturando. 
	- Vamos sentindo ao decorrer do projeto o momento de ampliar o projeto.
- ! + enter, ocorre da criação da estrutura bassica do HTML
	````html
		<!DOCTYPE html>
		<html lang="en">
		<head>
		    <meta charset="UTF-8">
		    <meta name="viewport" content="width=device-width, initial-scale=1.0">
		    <title>Document</title>
		</head>
		<body>
		    
		</body>
		</html>'
	````

- Vamos linkar nosso css
	- digitando link e dando tab ou enter ele cria o seguinte comando html
	- <link rel="stylesheet" href="">

- Colcoamos estilização tanto de fundo quanto de titulo.
	- Testamos com o live server, uma extensao que emula um servidor.

- Sempre que quebramos em muitos pequenos pedaços o desenvolvimento.

- Criamos uma side bar com o seguinte atalho
	- div.sidebar e damos enter
	- Com isto ele já cria automáticamente a div com a formatação da class
	- <div class="sidebar"></div>

- colocamos uma nav na nossa pagina.
	- Utilizamos esta tag nav para navegação

- Vamos utilizar muitas div's para organizar o nosso código.
- Vamos criar uma imagem, com texto alternativo
- Pegamos a pasta assets do projeto 
	- [Projeto Spotify](https://github.com/mayaracardoso/spotify-imersao/tree/develop)
- Criamos a pasta de assets pq vimos a necessidade de criar
- Adicionamos o icone do spotify:
	- <img src="./assets/icons/logo-spotify.png" alt="Logo do spotify">
- O icone ficou grande
- Foi questioando o que fazer primeiro, coloca rtodos os elementos e depois arrumar a página ou colcoar os elementos e ja ir arrumando os mesmos
	- Ambas profissionais deram opinioes diferentes:
		- Uma coloca tudo e arruma o css depois
		- Outra coloca e vai arrumando
- retiramos o teste h1
- criamos uma lista
	- ul.li*2 e ele cria uma lista com duas linhas
- Começamos a criar o resto do nosso menu
	- Inicio
	- Buscar
- Vamos usar o site fonteawesome.com para pegar os icones
	[Fontwesome](www.fontawesome.com)
- Para usar os icones, vamos fazer um porte
	````html
		  <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.15.4/css/solid.css"
		    integrity="sha384-Tv5i09RULyHKMwX0E8wJUqSOaXlyu3SQxORObAI08iUwIalMmN5L6AvlPX2LMoSE" crossorigin="anonymous" />
		  <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.15.4/css/fontawesome.css"
		    integrity="sha384-jLKHWM3JRmfMU0A5x5AkjWkw/EYfGUAGagvnfryNV3F9VqM98XiIH7VBGVoxVSc7" crossorigin="anonymous" />
	````
- Adicionamos o icone da home e da lupa
	````html
		 <div>
                    <ul>
                        <li>
                            <a href="">
                                <span class="fa fa-home"></span>
                                <span>Inicio</span>
                            </a>
                        </li>
                        <li>
                            <a href="">
                                <span class="fa fa-search"></span>
                                <span>Buscar</span>
                            </a>                            
                        </li>
                    </ul>
                </div>
	````
- criamos a classe .sidebar__nagivation e configuramos a emsma da seguinte maneira:
	````css
		.sidebar__navigation {
		    background-color: #121212;
		    border-radius: 8px;
		    padding: 16px 0 0 16; /*ordem do relaogio, cima, direita, baixo esquerda*/
		}
	````
- Ajustamos o sidebar, para o contexto dos menus
	````css
		.sidebar {
    position: fixed; /* Ficar fixo na sua posição*/
    top: 0; /*para ficar grudado no top*/
    left: 0;
    bottom: 0;
    padding: 12px; /*vamos colocar so um valor*/
    width: 300px; /*largura*/

	}
	````
- Ajustamos o icone:
	- Criamos uma div para englobar somente a imagem com uma class
	````html
		<div class="logo">
                    <a href="">
                        <img src="./assets/icons/logo-spotify.png" alt="Logo do spotify">
                    </a>
        </div>        
	````
	````css
		/*Colocamos a classe e a tag do que queremos ajustar*/
		.logo img {
		    width: 80px; /*largura*/
		}
	````
- reset css
	- Retira estilos pre prontos, com o rest de css
	````css
		/* http://meyerweb.com/eric/tools/css/reset/ 
		   v2.0 | 20110126
		   License: none (public domain)
		*/

		html, body, div, span, applet, object, iframe,
		h1, h2, h3, h4, h5, h6, p, blockquote, pre,
		a, abbr, acronym, address, big, cite, code,
		del, dfn, em, img, ins, kbd, q, s, samp,
		small, strike, strong, sub, sup, tt, var,
		b, u, i, center,
		dl, dt, dd, ol, ul, li,
		fieldset, form, label, legend,
		table, caption, tbody, tfoot, thead, tr, th, td,
		article, aside, canvas, details, embed, 
		figure, figcaption, footer, header, hgroup, 
		menu, nav, output, ruby, section, summary,
		time, mark, audio, video {
			margin: 0;
			padding: 0;
			border: 0;
			font-size: 100%;
			font: inherit;
			vertical-align: baseline;
		}
		/* HTML5 display-role reset for older browsers */
		article, aside, details, figcaption, figure, 
		footer, header, hgroup, menu, nav, section {
			display: block;
		}
		body {
			line-height: 1;
		}
		ol, ul {
			list-style: none;
		}
		blockquote, q {
			quotes: none;
		}
		blockquote:before, blockquote:after,
		q:before, q:after {
			content: '';
			content: none;
		}
		table {
			border-collapse: collapse;
			border-spacing: 0;
		}
	````
	- Setamos o reset.css no nosso html
	`````html
		 <title>Spotify Imersão</title>
	    <link rel="stylesheet" href="reset.css">
	    <link rel="stylesheet" href="styles.css">
	``````
- Realizamos mais alguns ajustes em outros pontos do CSS da nossa página
	````css
		.sidebar__navigation .logo {
	    background: #121212;
	    display: flex;
	    border-radius: 8px;   
	    padding: 16px 0 0 16px;  /*ordem do relaogio, cima, direita, baixo esquerda*/
		}
		/*Colocamos a classe e a tag do que queremos ajustar*/
		.logo img {
		    width: 80px; /*largura*/
		}
	```` 
- Tamanho do texto, reflte para o icone
- Ajustamos a fonte das escritas
	````css
	 .sidebar nav ul li a {
    color: #b3b3b3;
    text-decoration: none;
    font-weight: 600;
    font-size: 14px; /*tamanho do texto reflete para o icone*/
    font-family: "DM Sans", sans-serif;	
	}
	````

# Inteligencia artificial 

## Chat GPT

- O chat gpt é bom em código
- Pedirmos um site de mascote
- Pedirmos para ele tirar o CSS do arquivo HTML
- podemos pedir o reset CSS
- Luri, IA da Alura
- 