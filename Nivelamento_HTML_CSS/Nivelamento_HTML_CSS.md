# HTML e CSS: ambiente de desenvolvimento, estrutura de arquivos e tags

## 01. O editor de Código VSCode

### 01. Introdução

- Diferença entre CSS e HTML
- Como transformar estes códigos em uma página WEB

### 02. Criando um aqrquivo.

- Nesta aula, os instrutores Rafaella e Guilherme discutem sobre a criação de arquivos HTML e CSS e a relação com a criação de um documento de texto. Eles explicam a diferença entre elementos visuais e de interface presentes nos arquivos de texto, como títulos e parágrafos, que podem ser facilmente formatados usando um editor de texto como o Docs do Google. Os instrutores também falam sobre a importância de entender como os elementos de uma página web funcionam e como eles podem ser representados no HTML usando tags. Além disso, eles destacam a importância de utilizar editores de código específicos, como o Visual Studio Code, para desenvolver códigos HTML e CSS.

- Similaridade do exemplo de uma página HTML com um arquivo DOC
- Criamos o seguinte dentro de um DOC
	- Título
	- Paragrafo
	- Imagem
- No HTML vamos fazer a mesma coisa.
- Trabalharemos com Tag's
- Trabalhamos com ferramentas especificas para desenvolvimento. 
- Vamos utilizar o VSCode

### 03. Preparando o ambiente

- Realizamos a instalação do VSCode


### 04. Instalando o VSCode

- Nesta aula, os instrutores Guilherme Lima e Rafaella Ballerini discutem sobre a instalação do VS Code (Visual Studio Code) e a criação do primeiro arquivo do projeto. Eles explicam passo a passo como baixar e instalar o editor de código, além de mostrar como abrir uma pasta no VS Code. Em seguida, eles falam sobre a criação do primeiro arquivo HTML, explicando a importância do nome padrão "index.html" e mostrando como criar o arquivo tanto pelo explorador do VS Code quanto pelo atalho "Ctrl + N". Eles também mencionam a opção de salvar o arquivo com um nome diferente e como deletar arquivos no projeto. Por fim, eles mencionam que o próximo desafio será implementar o conteúdo do projeto, relembrando o modelo que criaram anteriormente no Google Docs.

- Criamos um diretório chamado portifólio
- Criamos um arquivo index.html

### 05. Iniciando o projeto

- As boas práticas na organização de um projeto podem ser consideradas um dos pilares fundamentais nas etapas iniciais do desenvolvimento. É muito importante iniciarmos da forma correta. Levando em consideração o que vimos anteriormente, podemos afirmar que:

- É uma boa prática criarmos pastas e subpastas que explicitem e organizem os arquivos de código de forma lógica.

### 06. Nome do arquivo

- No mundo fantasia do Pokemon, treinadores pokemon decidem criar um site eletrônico, o Pokémart.com: um site de comércio eletrônico onde os treinadores poderiam comprar e vender itens, como Pokébolas, Potions e Berries. Para começar, por enquanto, seguindo nosso padrão eles precisam criar um arquivo chamado:

- index.html

### 07 Criando seu arquivo HTML principal

- Ao criar um novo projeto é comum seguirmos um padrão para nomear seu arquivo principal e para estruturar a hierarquia de arquivos. Das alternativas abaixo assinale a que apresenta a hierarquia correta de um projeto HTML:

- Pasta do projeto
	index.html
	arquivos do projeto

### 08. Criação de pastas dentro do projeto

### 09. O que aprendemos

 - Diferenciar a criação de um arquivo no Google Docs e no HTML;
 - Fazer download e instalar o Visual Studio Code;
 - Criar pasta e abrir no editor de código.


## 02. Documentação e HTML

### 01 Preparando o ambiente

- [Link da Imagem](https://github.com/alura-cursos/html-logo/archive/refs/heads/main.zip)

### 02. Documentação e extrutura básica do HTML

- Nesta aula, os instrutores Guilherme e Rafaella discutem sobre o HTML e como escrever texto em HTML. Eles explicam que o HTML é uma linguagem de marcação e não uma linguagem de programação, e que é utilizado para designar as partes do texto em uma página web. Eles mostram trechos de código HTML e explicam o significado de cada tag, como a tag <!DOCTYPE html>, <html>, <head>, e <title>. Eles também mencionam a importância de procurar a documentação da linguagem e recomendam a página de introdução ao HTML do site W3Schools. No geral, é uma introdução importante para quem está começando a aprender HTML.

- Aprender a utilizar a documentação do HTML, CSS e JavaScript
- Vamos utilizar o site como documentação
- [3school](https://www.w3schools.com/html/)
- HTMl é uma linguagem de marcação de texto
	- Diferente de programação
	- HTML descreve a estrutura de uma página.
	- Marcar uma página inteira
- Vamos seguir a documentação e criar a nossa primeira página HTML
- Criamos de forma explicada as tag's abaixo:

	````html
		<!DOCTYPE html>
		<html>
		    <head>
		        <title>Portifólio</title>
		    </head>
		</html>
	````

### 03. A importancia da documentação

- O que é?
	- Guira de toda a pessoa desenvolvedora

- Importância:
	- No aprendizado e no desenvolvimento de aplicações

- Quando devmeos utilizar:
	- Sempre que precissarmos saber a extrutura de um método

- Oura forma de ajuda:
	- Comunidades como as seguintes:
		- [Stackoverflow](https://stackoverflow.com/)
		- [wrschools](https://www.w3schools.com/html/html_intro.asp)

 
### 04. Criando o corpo da página

- Nesta aula, Rafaella e Guilherme discutem sobre a estrutura básica de uma página web em HTML. Eles explicam que a tag <body> define o corpo do documento e é onde devemos adicionar todo o conteúdo visível da página, como cabeçalhos, parágrafos, imagens, hiperlinks, tabelas e listas.

Eles mostram como adicionar um título na página utilizando a tag <h1> e explicam que as tags de heading devem ser utilizadas para marcar títulos e subtítulos, seguindo uma ordem hierárquica.

Também explicam como adicionar um parágrafo na página utilizando a tag <p> e a importância de utilizar as tags apropriadas para cada tipo de conteúdo.

Por fim, mostram como adicionar uma imagem na página utilizando a tag <img>, especificando o caminho da imagem e adicionando um texto alternativo com a propriedade alt.

No geral, a aula aborda os conceitos básicos de estruturação de uma página web em HTML, enfatizando a importância de utilizar as tags corretas e adicionar texto alternativo nas imagens para melhorar a acessibilidade da página.

- Tudo que queremos vizualizar vai ficar dentro da tag <body></body>
- Tudo que queremos como titulo <h1></h1>
- O HTML interpresta de uma maneira diferente as determinadas Tag's.
- para mostrarmos uma imagem <img src="index.png">

- criamos o seguinte projeto
	````html
		<!DOCTYPE html>
		<html>
		    <head>
		        <title>Portifólio</title>
		    </head>    
		        <h1>Isso é um título</h1>        
		        <h2>Isso é um sub-título</h2>  
		        <p>Isto é um paragrafo</p>
		        <img src="html.png" alt="Logo do HTML 5">
		    </body>
		</html>
	````

### 05. Adicionando uma imagem:

- Nessa aula, aprendemos que para inserir uma imagem em sua página é necessário utilizar a tag <img>. Pensando nisso, considere o código a seguir:

	````html
		<!DOCTYPE html>
		<html>
		    <head>
		        <title>Portfólio</title>
		    </head>
		    <body>
		        <h1>Isso é um título</h1>
		        <p>Isso é um parágrafo</p>
		        <img scr="html.png" alt="Logo do HTML 5">
		    </body>
		</html>
	````

- A imagem só será exibida caso exista um arquivo de imagem chamado “html.png” salvo dentro da pasta do projeto.

- Apenas o texto alternativo será exibido e a imagem estará indisponível, porque o atributo src da tag <img> foi escrito incorretamente.

### 06. Quirks Mode e Live Server

- Nesta aula, os instrutores discutiram sobre a manipulação do código HTML de uma página web. Eles removeram a primeira linha do código, que indica a versão do HTML, e perceberam que a página entrou no "Modo Quirks". Explicaram que antigamente era necessário informar para qual navegador a página estava sendo construída, mas atualmente todos os navegadores sabem utilizar o HTML5. Em seguida, restauraram o <!DOCTYPE html> e utilizaram a extensão "Live Server" no VS Code para que a página seja atualizada automaticamente a cada salvamento do código. Isso evita a necessidade de atualizar a página manualmente a todo momento.

- Modo Quirks - era obrigado informar qual navegador a pagina estava sendo construida.
- Hoje todos os navegadores sabem usar em função do modo de compatibilidade. 

- Existe extensões que podem facilitar o nosso desenvolvimento
- Vamos usar uma extenção para vizualisar o nosso documento atualizado automáticamente. 
	- Live Server
- Com ele podemos ver os nossos ajustes em tempo real.

### 07. Quirks Mode

- Como vimos nessa aula, o uso do <!DOCTYPE html> é muito importante para que o navegador utilize o modo padrão e não o “Quirks Mode”. Pensando nisso, assinale a alternativa correta:

- O Quirks Mode é o modo em que o navegador adapta páginas web que estão em versões antigas para que funcionem, o que pode quebrar sua página em HTML 5. Portanto, esse modo deve ser evitado através do uso do <!DOCTYPE html>.

### 08. Para saber mais: Extensões do VSCode

- [Extensões mais usadas](https://www.alura.com.br/artigos/extensoes-vs-code-descubra-as-mais-usadas?_gl=1*1nifmbl*_ga*MTA2Njc5NzMwNS4xNjc4Mjc2NDU2*_ga_1EPWSW3PCS*MTcwNTA5Nzg2Ny42Mi4xLjE3MDUxMDI5NDguMC4wLjA.*_fplc*aDUzTSUyQjN5UVo2eE0zTVN6eHBzSURKYkpSUzNFSWVIVyUyQnRJOThWZmM0bDNsWmxiJTJCNVpOMUFCQ09Ua1pudDdoZDV3OCUyRmhmSmNOaWNYdXhjcG8zSmFTJTJCcU14UXI0JTJGVGo2UWd5NlVORlVSUmlqeHhvZURwQyUyRk9RM2RXU0tuQUElM0QlM0Q.)

### 09. Para saber mais sobre a extrutura do HTML

- A estrutura básica do HTML:
- Para criar um arquivo HTML devemos seguir um padrão:
	````html
		<!DOCTYPE html>
		<html lang="pt-br">
		<head>
		    <meta charset="UTF-8">
		    <meta http-equiv="X-UA-Compatible" content="IE=edge">
		    <meta name="viewport" content="width=device-width, initial-scale=1.0">
		    <title>Document</title>
		</head>
		<body>

		</body>
		</html>
	````

### 10. Mão na massa

- Caminho prático para aprimorar as abilidades tem tecnologias.
- Lísta de exercícios:

````html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="ISO-UTF8">
        <title>Exercícios Mão na Massa 1</title>
    </head>    
        <h1>Resumindo em atividdes o que aprendemso nas primeiras aulas</h1>                
        <p>Nesta aula aprendemos o basico das tag's html para começarmos no mundo da prgramação front end e o aprendizado em tecnologia</p>
        <img src="html.png" alt="Logo do HTML 5">

        <h2>Participantes do projeto</h2>
        <ul>
           <li>Jackson</li>
           <li>Alison</li>
           <li>Natan</li>
        </ul>
        <h2>Idades dos participantes</h2>
        <ol>
            <li>18</li>
            <li>13</li>
            <li>14</li>
        </ol>

    </body>
</html>
````

### 11. Importantes pontos aprendidos nesta aula

- A importância da documentação W3S;
- O que é HTML e porque é considerada uma linguagem de marcação;
- Estruturar um documento HTML com tags e elementos;
- A utilidade da introdução <!DOCTYPE html>;
- Diferença entre a metainformação presente no <head> e o conteúdo presente no <body> de uma página HTML;
- Criar textos alternativos (alts) para uma imagem;
- Acessar a Developer Tools (Ferramentas para Desenvolvedores) de um navegador;
- Quirks mode (modo peculiaridade);
- Utilizar extensões no Visual Studio Code (Live Server por exemplo). 

## 03. Leyoout e tags semânticas

### 01. Projeto da aula anterior

### 02. Preparando o ambiente

- Acessamos o figma
- [figma](https://www.figma.com/)
- Posterior importamos o projeto da alura
- [Projeto da Alura](https://www.figma.com/file/dRdkkewTSz9Xu1TXoQkW0u/Portfolio---Curso-1?type=design&node-id=0%3A1&mode=design&t=XuGrUuV0WIAKkYVd-1)


- Duplicamos o figma da alura
- Duplicate to your drafts

### 03. Projeto no Figma

- Nesta aula, os instrutores Guilherme e Rafaella discutem sobre o processo de desenvolvimento de uma página web. Eles mencionam a importância de ter profissionais que fazem o design da página e aqueles que codificam o design utilizando HTML, CSS e outras tecnologias. Eles explicam que estão utilizando o Figma para desenvolver o projeto e que a designer da Alura, Isa, produziu o layout. Eles destacam que o desafio é codificar o HTML das telas já construídas, utilizando também o CSS para estilizar a página. No próximo passo, eles começarão a trabalhar com o HTML para codificar as telas do projeto.

- Dois tipos de profissional
	- Profissional que vai ter um formato, uma cor
	- Pegamos algo pronto para poder codificar. 
- Ferramenta que utilizamos é o figma para pegar algo pronto.
- Todos os elementos ja foram pré processados. 

- Como funciona o figma 
	- Vamos olhar a imagem e começar a codar
	- Pegaremos algumas informações
	- Vamos usar as seguintes abas:
		- Design
		- Inspecionar
	- Conseguimos ver muitas informações no figma
- Desafio vai ser transformar tudo na página WEB
- Conseguimos ver muitos pontos que já utilizamos 

### 04. Tags semânticas

- Nesta aula, Rafaella e Guilherme discutem sobre como transformar o design do Figma em código HTML. Eles falam sobre a estrutura básica de um documento HTML e mostram atalhos para criar essa estrutura de forma mais rápida. Também explicam o significado das tags <meta> presentes no código, incluindo a tag <meta> com o atributo http-equiv="X-UA-Compatible", que garante o uso da versão mais recente do Microsoft Edge. Eles destacam a importância da codificação UTF-8 para exibir corretamente caracteres especiais. Além disso, abordam a tag <title> para alterar o título da página e discutem sobre a estrutura semântica do HTML, separando os elementos em cabeçalho, conteúdo principal e rodapé. Por fim, mostram como criar essa estrutura básica utilizando as tags <header>, <main> e <footer>.

- Atalhos para iniciar um projeto HTMl com atalhos
	- Digitamos um ! e posterio damos um enter e ele cria toda a extrutura HTML
	````HTML
		<!DOCTYPE html>
		<html lang="en">
			<head>
			    <meta charset="UTF-8">
			    <meta name="viewport" content="width=device-width, initial-scale=1.0">
			    <title>Document</title>
			</head>
			<body>
			    
			</body>
		</html>
	````

- Esta TAg adapta conforme dispositivo.
	- <meta name="viewport" content="width=device-width, initial-scale=1.0">
- Planejar em partes o que vai se desenvolvido
- Em partes, podemos usar o figma para nos auxiliar.
- HTML construimos TAG's de forma semanticara para ajustar estas estruturas
- Estruturas principais
	- Cabecalho
	- Estrutura principal
	- Rodapé

````html
<!DOCTYPE html>
<html lang="pt-br">
	<head>
	    <meta charset="UTF-8">
	    <meta name="viewport" content="width=device-width, initial-scale=1.0">
	    <title>Portifólio</title>
	</head>
		<body>
		    <header></header>
		    <main></main>
		    <footer></footer>    
		</body>
</html>
````

### 05. Acelere sua produtividade no VScode com Emmet

- Para resolver esse problema, podemos contar com o auxílio do Emmet, uma extensão poderosa e amplamente utilizada no VSCode. O Emmet: https://docs.emmet.io/ é uma ferramenta que permite escrever códigos HTML e CSS de forma extremamente rápida e produtiva. Ele utiliza abreviações para gerar estruturas complexas de código com apenas alguns comandos, aumentando significativamente a eficiência do desenvolvedor.

- Emmet, anteriormente conhecido como Zen Coding, é uma ferramenta de codificação avançada desenvolvida por Sergey Chikuyonok. Ele foi projetado para facilitar a escrita de código HTML e CSS de forma rápida e simplificada. O Emmet oferece uma maneira inteligente de criar estruturas complexas por meio de abreviações fáceis de lembrar.

- [emmet](https://docs.emmet.io/)

### 06. Desenvolvendo o HTML

- Nesta aula, Rafaella e Guilherme discutem sobre como estruturar uma página web em HTML. Eles explicam a importância de planejar a estrutura da página com base no design do projeto no Figma. Começam adicionando o título da página usando a tag <h1>. Rafaella mostra como destacar uma parte do texto usando a tag <strong>. Em seguida, adicionam um parágrafo usando a tag <p>. Guilherme explica que os botões serão representados por tags âncora <a>, que permitem redirecionar para outras páginas. Adicionam os links para o Instagram e o GitHub. Rafaella mostra como adicionar uma imagem usando a tag <img>, e eles baixam a imagem do Figma e a adicionam ao código. Ressaltam que ainda é necessário estilizar a página para que fique igual ao design do projeto no Figma.

- Olhamos ao nosso projeto do figma e começamos a desenvolver
- Começando:
	- Primeiramente olhamos para o nosso HTML 
	- No figma começamos da esquerda para a direita
- Pegamos o texto e colocamos na tag h1
- setamos o texto de forma forte <strong>
	- Ajustamos um paragrafo com o descritivo do que estamos
- Vamos usar uma tag angular para direcionar para algum ponto. 
	- <a href="https://instagram.com/rs.willian">Instagram</a>
    - <a href="https://github.com/Wastiel">Github</a>
	
- O nosso código no final fica da seguinte maneira
	````html
		<!DOCTYPE html>
		<html lang="pt-br">
		<head>
		    <meta charset="UTF-8">
		    <meta name="viewport" content="width=device-width, initial-scale=1.0">
		    <title>Portifólio</title>
		</head>
		<body>
		    <header></header>
		    <main>
		        <h1>
		            Eleve seu negócio digital a outro nível 
		            <strong>com um front-end de qualidade<strong>
		        </h1>
		        <p>Olá! Sou Willian Silva, aspirante a desenvolvedor front-end, com foco em Angular, HTML e CSS. Ajudao pequenos negócios e designers a colocarem em prática boas ideias. Vamos juntos alavancar seu negócio com tecnologia e inovação? 
		        </p>
		        <a href="https://instagram.com/rs.willian">Instagram</a>
		        <a href="https://github.com/Wastiel">Github</a>
		    </main>
		    <footer></footer>    
		</body>
		</html>
	````
 ### 07. Para saber mais: tags semânticas

 - Quando começamos um arquivo HTML, há uma estrutura padrão que é usada em qualquer projeto. É importante saber quais são as tags que precisam ser implementadas e entender suas funções dentro do código. Para facilitar esse processo, utilizamos as tags semânticas, que são tags descritivas sobre o conteúdo que armazenam, como é o caso das tags <header>, <main> e <footer>, que conhecemos nessa aula. Elas servem tanto para otimizar a leitura pelos navegadores, como pelas pessoas desenvolvedoras que vão fazer a manutenção do código.

- Para aprender mais sobre as tags que fazem parte da base de um arquivo HTML, você pode ler a documentação MDN “Semântica” e conhecer outros elementos semânticos disponíveis para tornar o seu código mais claro, seja para outras pessoas programadoras, para navegadores ou mecanismos de buscas.

- [semantica](https://developer.mozilla.org/pt-BR/docs/Glossary/Semantics)

### 08. sobre os metadados

- Quando construímos a estrutura básica de tags do HTML, inserimos meta tags dentro da tag <head>. As tags meta determinam os metadados, que são as informações sobre dados de um documento HTML. Logo abaixo, podemos visualizar os metadados que colocamos no código do projeto Portfolio.

- O metadado http-equiv="X-UA-Compatible" content="IE=edge" é utilizado para configurar a página web no Internet Explorer, para que ela esteja sempre em sua versão mais recente.

- O metadado charset="UTF-8" é empregado para repassar aos navegadores qual é o formato de codificação de caracteres utilizado naquele documento.

### 09. Usando Tags Semânticas

- Vimos nas aulas que para escrever um título, um parágrafo, precisamos respeitar uma estrutura básica do HTML. Diante disso, qual das alternativas abaixo contempla a estrutura correta para obtermos como resultado um título e dois parágrafos conforme o exemplo abaixo:

- ALURA - Mergulhe em Tecnologia!
Você vai estudar, praticar, discutir e se aprofundar em uma plataforma que respira tecnologia.
Mergulhe com profundidade e navegue em outras áreas de Tecnologia. Profissional em T. 
	````html
	<h1>ALURA - Mergulhe em Tecnologia!</h1>  
	<p>Você vai estudar, praticar, discutir e se aprofundar em uma plataforma que respira tecnologia.</p>
	<p> Mergulhe com profundidade e navegue em outras áreas de Tecnologia. Profissional em T </p>
	````
### 10. Diferenças entre ancora e botao

- Vimos que para desenvolver diferentes funcionalidades do HTML precisamos entender o comportamento das tags, e que, embora muitas vezes duas ou mais tags sejam parecidas em nome ou finalidade, cada uma é específica à certa situação. Dessa maneira, pensando nas tags <button> de botão e <a> de âncora, marque a alternativa correta que indique a diferença entre elas:

- A tag <button> é diferente da tag <a>, pois, além da semântica, a finalidade também é outra. Usamos <button> para criar um botão de ação e <a> para indicar um link.

### 11. Mão na massa

````html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portifólio</title>
</head>
<body>
    <header></header>
    <main>
        <h1>
            Eleve seu negócio digital a outro nível 
            <strong>com um front-end de qualidade<strong>
        </h1>
        <p>Olá! Sou Willian Silva, aspirante a desenvolvedor front-end, com foco em Angular, HTML e CSS. Ajudao pequenos negócios e designers a colocarem em prática boas ideias. Vamos juntos alavancar seu negócio com tecnologia e inovação? 
        </p>
        <a href="https://instagram.com/rs.willian">Instagram</a>
        <a href="https://github.com/Wastiel">Github</a>
        <img src="imagem_pessoal.jpg" alt="Imagem Pessoal Willian">
    </main>
    <footer></footer>    
</body>
</html>
````

### 12. O que Aprendemos:

- Como consultar o layout do projeto no Figma;
- Escrever o código base do arquivo HTML, usando as tags semânticas que fazem parte da estrutura básica do arquivo;
- A função de cada tag meta.

## 04. Estilizando o projeto com CSS

### 01. Projeto da aula anterior


### 02. Como funciona o CSS

- Nesta aula, Guilherme e Rafaella discutem sobre a importância do CSS na estilização de páginas web. Eles explicam que o CSS é responsável por definir como os elementos devem ser exibidos visualmente, como cores, tamanhos e posicionamentos. O CSS permite aplicar diferentes estilos a um mesmo HTML, utilizando diferentes arquivos .css. Além disso, eles mencionam que o CSS resolveu um problema do HTML, separando a formatação de estilo do código HTML, o que torna as páginas mais visualmente agradáveis e eficientes. O CSS é armazenado em arquivos .css, assim como o HTML é armazenado em arquivos .html.

- Documentação do w3school
- [w3schools](https://www.w3schools.com/)
- Folhas de estilo em cascata.
- Como os elementos HTML devem ser exibidos na tela
- Cor, posicionamento, tamanho, leyaute e etc..
- CSS resulveu um grande problema. 
- Vamos salvar as configurações em um arquivo externo. 

### 03. Incluindo CSS na página

- No vídeo anterior, você aprendeu que as “Folhas de Estilos em Cascata” (CSS) descrevem um conjunto de regras de formatação que controlam a aparência de uma página da internet. Pensando nisso, marque a alternativa correta que apresente a boa prática recomendada na hora de utilizar o CSS:

- É recomendado criar um arquivo CSS externo com extensão .css e incluí-lo na estrutura head do HTML. Assim, conseguimos ter uma estrutura de estilos universal para várias páginas.

### 04. Criando O CSS

- Nesta aula, Rafaella e Guilherme discutem sobre a criação de um arquivo CSS e a estilização de uma página web. Eles explicam a importância de começar pela cor de fundo e cor do texto. Mostram como definir a tag <body> no CSS e como autocompletar propriedades no editor de código. Também ensinam a linkar o arquivo CSS no HTML e como alterar a cor do texto. Por fim, mencionam que os links serão estilizados posteriormente.

- por padrão ciramos um estilo CSS. 
	- style.css
- Vamos começar pela cor do texto. 
- Dentro do arquivo CSS, conseguimos alterar uma tag.
- Formato cascada
- criamos o link do arquivo de estilo com o HTML, dentro do nosso próprio HTML
	- <link rel="stylesheet" href="style.css">

### 05. Estilizando o HTML com CSS

- Para que os estilos em CSS sejam aplicados nos elementos HTML, a folha de estilos precisa estar conectada corretamente no documento HTML através de uma tag <link>, caso contrário, os estilos não serão aplicados.

- Das alternativas abaixo, selecione aquela que apresenta a forma correta de escrever a tag <link> e o local que deve conter essa tag:

	````html
	       <head>
            <link rel="stylesheet" href="nomedoarquivo.css">
        </head>
	````

### 06. Cor de fundo

- Qual das alternativas troca a cor de fundo para vermelho (red)?

	````css
	body {
	  background-color: red;
	  color: blue;
	  font-family: 'Comic Sans MS', sans-serif;
	  font-size: 16px;
	  line-height: 1.5;
	}
	````

### 07. Faça como eu fiz: estilize seu TML

````css
	body {
    background-color: black;
    color: white;
	}
````

### 08. Mão na massa

### 09. O que Aprendemos 

- O que é CSS (Cascading Style Sheets);
- Estilização na prática;
- Propriedades CSS;
- Criar um arquivo externo para estilizar a página;
- Integrar o arquivo CSS ao arquivo HTML.


## 05. Super Estilizando o seu CSS

### 01. Projeto aula anterior

### 02. Cores no CSS

- Nesta aula, Guilherme e Rafaella discutem sobre a representação de cores no Figma e no CSS. Eles explicam que é possível utilizar palavras-chave ou a notação hexadecimal RGB para definir as cores no CSS. Eles também mencionam a importância de adicionar o símbolo "#" antes do valor da cor. Além disso, falam sobre a existência de uma tabela de cores na documentação oficial do Mozilla e a possibilidade de utilizar ferramentas como a roda de cores do Adobe para escolher paletas harmoniosas. No final, eles decidem utilizar as cores "black" e "#F6F6F6" como padrão para o projeto.

- Represnetar cores em formatos diferentes
	- Palavra Chave
	- Valores hex RGB

- Cores faz parte do trabalho do UX
- [Rotas de Cores Adobe](https://color.adobe.com/pt/create/color-wheel)


### 03. para saber mais: escolhendo as cores do projeto

- Utilizamos o CSS para alterar os estilos dos elementos, como por exemplo a cor de fundo, fontes, margens, etc.

- Pensando nisso, qual atributo do CSS utilizamos quando queremos alterar a cor de fundo do <body> para a cor branca?

````css
body{  background: #FFFFFF;}
body{  background-color: #FFFFFF;}
````

### 04. Cor de fundo

- Nesta aula, Rafaella e Guilherme discutem sobre a estilização de elementos de texto em um projeto de Front-end. Eles utilizam a tag <strong> para destacar um trecho específico do título e aplicam a cor hexadecimal #22D4FD a essa tag no arquivo style.css. No entanto, eles percebem que essa cor também é aplicada a outras ocorrências da tag <strong>, o que não é desejado. Eles concluem que precisarão encontrar uma forma de indicar que apenas uma dessas tags usará a cor azul claro.

- Destacar o texto 
- Criamos um style para o solicitado

````CSS
strong {
    color: #22d4fd
}
````
### 05. Destacando o texto

- Nesta aula, os instrutores discutem sobre a estilização de elementos de texto em um projeto de Front-end. Eles utilizam a tag <strong> para destacar um trecho específico do título e aplicam a cor hexadecimal #22D4FD a essa tag no arquivo style.css. No entanto, eles percebem que essa cor também é aplicada a outras ocorrências da tag <strong>, o que não é desejado. Eles concluem que precisarão encontrar uma forma de indicar que apenas uma dessas tags usará a cor azul claro.

````css
body {
    background-color: black;
    color: #F6F6F6;
}

strong {
    color: #22d4fd
}
````

### 06. Para saber mais: destacando o texto

- TAG SPAN

````css
body {
    background-color: black;
    color: #F6F6F6;
}

strong {
    color: #22d4fd
}
span{
    color: #22D4FD;
    border: 1px solid #22D4FD;
    padding: 10px;
}
````

### 07. Projeto Final do curso

- [projeto final do curso](https://github.com/alura-cursos/Portifolio-HTML-e-CSS/tree/aula_5)

### 08. Desafio: Compartilhando seu projeto com o mundo

### 09. Mão na massa

### 10. Para ir mais fundo

Aqui está uma lista de referências para você se aprofundar nos estudos, aprimorar seus conhecimentos e adquirir novas habilidades.

- [HTMl, CSS e JavaScript - Diferenças](https://www.alura.com.br/artigos/html-css-e-js-definicoes?_gl=1*fqrcrp*_ga*MTA2Njc5NzMwNS4xNjc4Mjc2NDU2*_ga_1EPWSW3PCS*MTcwNTE4MjA5OS42Ni4xLjE3MDUxODI2NzUuMC4wLjA.)
Este artigo apresenta uma visão geral das três principais linguagens utilizadas no front-end da programação web. O HTML, sendo uma linguagem de marcação, é usado para estruturar elementos numa página web, enquanto o CSS é uma linguagem de estilo que define a aparência estética dos elementos HTML. Por outro lado, o JavaScript é uma linguagem de programação que adiciona dinamismo e interatividade às páginas web.

- [HTML para Iniciantes](https://www.hostinger.com.br/tutoriais/o-que-e-html-conceitos-basicos)
Este artigo oferece uma introdução clara ao HTML, explicando sua função, estrutura básica, e como ele é usado na criação de páginas web. É uma leitura fundamental para entender a base do desenvolvimento web.


- [Introdução às tags HTML - (Gratuito, Inglês, Tutorial)](https://www.w3schools.com/tags/)
Um guia detalhado sobre as diversas tags HTML disponíveis. Cada tag é explicada com exemplos práticos, facilitando o entendimento de como usar tags para estruturar uma página web.

- [Tutorial de HTML Básico - MDN Web Docs (Gratuito, Português, Online)](https://www.w3schools.com/tags/)
A MDN Web Docs apresenta um guia para iniciantes sobre HTML, cobrindo os conceitos fundamentais e estrutura de um documento HTML. Este tutorial é detalhado e está disponível em português, sendo uma excelente referência para quem está começando.

- [Guia de referência rápida de HTML - HTML Dog (Gratuito, Inglês, Online)](https://developer.mozilla.org/pt-BR/docs/Learn/Getting_started_with_the_web/HTML_basics)
- HTML Dog fornece um guia de referência rápida para tags HTML, atributos, e exemplos. É um recurso útil para consulta rápida durante a prática de codificação ou para esclarecer dúvidas específicas.

- [Estrutura básica de uma página HTML - HTML Dog (Gratuito, Inglês, Online)](https://htmldog.com/references/html/)
- HTML Dog oferece um guia simples e claro sobre a estrutura básica de uma página HTML, explicando a importância de cada seção, incluindo <body>, <head>, <h1>, <p>, e <img>.

- [Tutorial de acessibilidade na web - WebAIM (Gratuito, Inglês, Online)](https://htmldog.com/guides/html/beginner/)
- O WebAIM fornece um tutorial introdutório sobre acessibilidade na web, essencial para entender como tornar o conteúdo acessível a todos os usuários, incluindo aqueles que usam leitores de tela.

- [Modo Quirks e padrões em navegadores - MDN Web Docs (Gratuito, Inglês, Online)](https://webaim.org/intro/)
- A MDN Web Docs oferece uma visão detalhada sobre o Modo Quirks e o Modo Standards, explicando como os navegadores interpretam códigos HTML baseados na presença ou ausência do DOCTYPE.

- [Uso de extensões no Visual Studio Code - Visual Studio Code Docs (Gratuito, Inglês, Online)](https://code.visualstudio.com/docs/editor/extension-gallery)
- Documentação oficial do Visual Studio Code sobre como utilizar extensões, incluindo a instalação e configuração do Live Server, que permite a atualização automática da página HTML durante o desenvolvimento.

- [Live Server Extension para Visual Studio Code - GitHub (Gratuito, Inglês, Online)](https://github.com/ritwickdey/vscode-live-server)
- Página oficial da extensão Live Server no GitHub, fornecendo detalhes sobre suas funcionalidades, instalação e uso, essencial para um desenvolvimento de páginas web mais eficiente.

- [UX/UI Design: Fundamentos para a qualidade na interface de usuário - Interaction Design Foundation (Gratuito/Pago, Inglês, Online)](https://www.interaction-design.org/literature/topics/ux-design)
- A Interaction Design Foundation oferece recursos educativos abrangentes sobre UX/UI Design, fundamentais para entender a importância do design na experiência do usuário.

- [Dicas de CSS (Gratuito, Inglês, Online)](https://css-tricks.com/guides/)
- CSS Tricks apresenta tutoriais completos e dicas sobre CSS, essencial para estilizar páginas da web de acordo com as especificações de design.

- [Guia de estruturação de páginas HTML com semântica - MDN Web Docs (Gratuito, Inglês, Online)](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
- Um guia completo sobre a estruturação de páginas HTML, enfatizando o uso de tags semânticas como <header>, <main>, e <footer>, essencial para criar páginas bem organizadas e acessíveis.

- [Utilizando Emmet para acelerar o desenvolvimento HTML - CSS-Tricks (Gratuito, Inglês, Online)](https://css-tricks.com/emmet/)
- Um artigo detalhado sobre como utilizar Emmet, uma ferramenta de produtividade para desenvolvimento web, para acelerar a escrita de códigos HTML, incluindo a geração automática da estrutura básica da página.

- [Introdução ao HTML5 e tags semânticas - HTML.com (Gratuito, Inglês, Online)](Introdução ao HTML5 e tags semânticas - HTML.com (Gratuito, Inglês, Online))
- Um guia abrangente sobre HTML5, destacando a importância e o uso de tags semânticas como <header>, <main>, <footer>, e <strong>, essenciais para criar uma estrutura de página clara e acessível.

- [Uso efetivo de tags âncora em HTML - W3Schools (Gratuito, Inglês, Online)](https://www.w3schools.com/html/html_links.asp)
- Este recurso explica como usar tags âncora (<a>) em HTML, um componente fundamental para criar links que redirecionam para outras páginas ou recursos.

- [Como inserir Imagens em HTML - MDN Web Docs (Gratuito, Inglês, Online)](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img)
- Um guia detalhado sobre a tag <img> em HTML, incluindo como usar o atributo src para inserir imagens e a importância do atributo alt para acessibilidade.

- [Práticas recomendadas para design responsivo - Smashing Magazine (Gratuito, Inglês, Online)](https://www.smashingmagazine.com/2011/01/guidelines-for-responsive-web-design/)
- Este artigo aborda as melhores práticas para design responsivo em desenvolvimento web, algo crucial para garantir que um site funcione bem em todos os dispositivos e tamanhos de tela.

- [Introdução ao CSS - W3Schools (Gratuito, Inglês, Online)](https://www.w3schools.com/css/)
- Um recurso introdutório ao CSS, oferecendo lições passo a passo sobre como usar CSS para melhorar a aparência das páginas HTML, abordando desde a formatação básica até conceitos mais avançados.

- [Como utilizar folhas de estilo em cascata (CSS) - MDN Web Docs (Gratuito, Inglês, Online)](https://developer.mozilla.org/en-US/docs/Web/CSS)
- Este recurso da MDN Web Docs explica em detalhes como usar CSS para estilizar elementos HTML, incluindo como criar e vincular arquivos CSS externos.

- [Guia de cores e fontes em CSS - Adobe Color (Gratuito, Inglês, Online)](https://color.adobe.com/create/color-wheel)
- Este guia da Adobe ajuda a entender como combinar cores e escolher fontes em CSS, alinhando o design da página web com as especificações do projeto no Figma.

- [Hipsters ponto tech episódio #09 CSS: cansei de ser simples - (Gratuito, Português, Áudio)](https://www.hipsters.tech/css-cansei-de-ser-simples-hipsters-09/)
- Esse episódio é uma excelente opção para aqueles interessados em entender não apenas como usar CSS, mas também para compreender os desafios e soluções que envolvem o uso eficaz dessa linguagem na estilização de páginas web.

### 11. O que aprendemos?

- Utilizar as cores no CSS;
- Utilizar as cores hexadecimais no CSS;
- Utilizar paleta de cores de terceiros;
- Alterar as cores de fundo e dos textos;
- Extrair a cor do Figma para utilizar no CSS;
- Destacar o texto e alterar a cor do texto em destaque.

### 12. Conclusão

### 13. Créditos