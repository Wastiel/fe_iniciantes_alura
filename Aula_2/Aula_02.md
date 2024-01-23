# Aula 02. Estilo Avançado e Posicionamento: Transformando Layouts

## O que vamos fazer?

- Uma página inspirada no SpotiFy

## Começando o projeto

## Continuando ajustes no menu lateral

- Ben CSS
	- Organização de CSS
- Ajustamos os seguintes pontos do nosso html
	````html
		<div class="library">
            <div class="library__content">
                <button class="library__button">
                    <span class="fa fas fa-book"></span>
                    <span>sua biblioteca</span>
                </button>
                <span class="fa fa-plus"></span>
            </div>
            <section class="section-playlist">
                <div class="section-playlist__content">
                    <span class="text titile">Crie suaprimeira playlist</span>
                    <span class="text subtitle">É facil, vamos te ajudar</span>
                    <button class="section-playlist__button">
                        <span>Criar Playlist</span>
                    </button>
                </div>
            </section>
            <div class="cookies">
                <a href="">Cookies</a>
            </div>
            <div class="languages">
                <button class="languages__button">
                    <span class="fa fa-globe"></span>
                    <span>Portugês do Brasil</span>
                </button>
            </div>
        </div>
	````
- Criamos uma div e colocamos atodos os pontos que faltam para a nossa nav.
- Ajustamos o css do library
	````css
		.library {
    background-color: #121212;
    border-radius: 8px;
    display: flex; /*forma mais flexivel de fazer o display no css, alterar a orientação dos objetos na tela*/
    justify-content: space-between; /*posição justificada*/
    flex-direction: column;
    padding: 4px 8px;
    color: #b3b3b3;
    font-weight: 600;
    font-size: 14px;
    margin-top: 10px;
	}
	````
- fazer o css, seguindo a lógica do hmtl, melhor
- css do library content
	````css
		.library .library__content {
    display: flex;
    justify-content: space-between; 

		}	
	````
- css do library button
	````css
		.library .library__button {
	    display: flex;
	    margin-right: 10px;    
	    color: #b3b3b3;
	    background-color: transparent;
	    border: 0px;
	    font-size: 14px;
	    font-weight: 700;
	    font-family: "DM Sans", sans-serif;
	    text-align: center;
	    text-decoration: none;
	    text-transform: none;
	    padding: 20px 10px;    
		}
	````
- css do icone fa
	````css
		.library .library__button .fa{
	    font-size: 20px;
	    margin-right: 10px;
	    font-weight: 300;
	    padding-right: 8px;
		}
	````
- css do fa-plus
	````css
		.library .library__content .fa-plus {
		    margin: 24px 10px;

		}
	````
- css do section-playlist
	````css
		.section-playlist {
	    display: flex;
	    align-items: flex-start;
	    justify-content: space-between;
	    gap: 20px;
	    background-color: #242424;
	    color: #b3b3b3;
	    font-weight: 600;
	    font-size: 14px;
	    margin: 8px 0px;
	    padding: 16px 20px;
	}
	````
- css .section-playlist__content
	````css
		.section-playlist .section-playlist__content {
		    display: flex;
		    flex-direction: column;
		}
	````
- css do .section-playlist__content .text
	````css
		.section-playlist__content .text {
	    padding-bottom: 14px;
	    color: #fff;
	}
	````
- css .section-playlist__content .title
	````css
		.section-playlist__content .title {
    	font-weight: 700;
		}
	````
- css .section-playlist__content .subtitle
	````css

	````
- css .section-playlist__content .button
	````css
		.section-playlist__content .section-playlist__button{
	    display: flex;
	    justify-content: center;
	    background-color: #fff;
	    color: #000;
	    border-radius: 20px;
	    font-size: 12px;
	    font-weight: 700;
	    font-family: "DM Sans", sans-serif;
	    text-decoration: none;
	    text-transform: none;
	    padding: 10px;
	    margin-top: 12px;    
	    border: 0px;
	    width: 113px;    
	}	
	````
- css cookies
	````css
		.sidebar .cookies {
		    margin: 25px 20px;

		}
	````
- css cookies a 
	````css
		.sidebar .cookies a {
	    color: #b3b3b3;
	    font-weight: 500;
	    font-size: 10px;
	    text-decoration: none;    

	}
	````
- css cookies a:hover
	````css
		.sidebar .cookies a:hover{
	    text-decoration: underline;
	}
	````
- css languages__button
	````css
		.languages .languages__button{
	    align-items: center;
	    background-color: transparent;
	    border: 1px solid #878787;
	    color:#FFF;
	    font-weight: bold;
	    cursor:pointer;
	    width: 170px;
	    margin:8px;
	    padding:8px;
	    border-radius:20px;
	}
	````


- Pseudo classe, ela representa um estado
	- Forma de alterar estados
	- uma interatividade da pagina e não uma animação
# Inteligencia artificial 

## Chat GPT

- Bom para tirar dúvidas de um contexto
- Bom para questionar como fazer determinadas coisas.
- Bom para corrigir erros no código
