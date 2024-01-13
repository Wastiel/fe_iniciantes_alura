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