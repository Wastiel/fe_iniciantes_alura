# Aula 03. Leyout flexbox, Pseudo-classes e Responsividade em CSS

## O que vamos fazer?

- Uma página inspirada no SpotiFy

## Começando o projeto

## Responsividade

- Refatoração é um processo que acontece
- Percebemos um ponto no decorrer do andamento do projeto. 

- Criado o footer da página
	````html
		    <footer class="disclaimer-premium">
        <div class="text">
          <p class="disclaimer-premium__title">Testar o Premium de graça</p>
          <p class="disclaimer-premium__subtitle">
            Inscreva-se para curtir música ilimitada e podcasts só com alguns
            anúncios. Não precisa de cartão de crédito.
          </p>
        </div>
        <div class="button">
          <button type="button">Inscreva-se grátis</button>
        </div>
    </footer>
	````
- Posterior Ajustamos o CSS da mesma
	````css
		.disclaimer-premium {
	    position: fixed;
	    bottom: 0;
	    left: 0;
	    right: 0;
	    background: linear-gradient(to right, #ae2896, #509bf5);
	    padding: 15px 40px;
	    display: flex;
	    justify-content: space-between;
	}
	.disclaimer-premium .text {
	   flex-shrink: 0;
	}
	.disclaimer-premium .disclaimer-premium__title {
	    color: #ffffff;
	    text-transform: uppercase;
	    font-weight: 400;
	    font-size: 12px;
	    margin-bottom: 10px;
	}

	.disclaimer-premium .disclaimer-premium__subtitle {
	    color: #ffffff;
	    font-size: 14px;
	    font-weight: 500;
	}

	.disclaimer-premium button {
	    background-color: #ffffff;
	    color: #000000;
	    font-size: 16px;
	    font-weight: bold;
	    padding: 14px 30px;
	    border: 0px;
	    border-radius: 40px;
	    cursor: pointer;
	    flex-shrink: 0;
	}

	#artistList {
	    display: none;
	}
	````
- Construimos uma organização do projeto.
- Colocamos os arquivos de estilos e os assets dentro da pasta src
	- assets
	- styles
		- reset.css
		- sidebar-footer.css
- Muita repetição no código, vamos refatorar
- Vamos começar a criar um arquivo de variaveis
	- vars.css
- Carrgamos este arquivo no nosso html
- Colocamos uma variavel no nosso projeto
	````css
			:root {
		    /*font*/
		    --font-dm-sans: "DM SANS", sans-serif;
		}
	````
- Comum usar variaveis para organizar melhor o nosso projeto
- Criamos um main content para busca de musicas, login e inscrição
	````html
		    <main>
        <div class="main-container">
            <nav class="header__navigation">
                <div class="navigation">
                    <button class="arrow-left">
                        <img src="./src/assets/icons/small-left.png" alt="Seta Esquerda">
                    </button>
                    <button class="arrow-left">
                        <img src="./src/assets/icons/small-right.png" alt="Seta Direita">
                    </button>

                    <div class="header_search">
                        <img src="./src/assets/icons/search.png" alt="">
                        <input id="search-input" type="text" maxlength="800" placeholder="O que você quer ouvir"/>
                    </div>

                    <div class="header__login">
                        <button class="subscribe">Inscreva-se</button>
                        <button class="login">Entrar</button>
                    </div>
                </div>
            </nav>
        </div>
    </main>
	````
- CSS do main-content
	````css
		/* HEADER*/

		.main-container {
		    max-width: 80vw;
		    height: 100vh;
		    margin-left: 320px;
		    margin-right: 56px;    
		}

		.header__navigation {
		    display: flex;
		    /* ESSES detalhes que tem dentro do display flex, mostra no navegador como fica */
		    justify-content: space-between;
		    align-items: center;
		    padding: 16px;
		    margin: 10px;
		    border-radius: 8px;
		    background-color: #121212;
		    /* padding: 12px; */
		  }
		  
		  .header__navigation .navigation {
		    display: flex;
		    justify-content: space-around;
		    align-items: center;
		  }
		  
		  .header__navigation .navigation .arrow-left {
		    margin-right: 1.25rem;
		  }
		  
		  .arrow-left,
		  .arrow-right {
		    display: flex;
		    align-items: center;
		    justify-content: center;
		    width: 32px;
		    height: 32px;
		    background: var(--bg-icon);
		    background-color: rgba(0, 0, 0, 0.7);
		    border-radius: 50%;
		    border: none;
		    cursor: pointer;
		  }
		  
		  .header__login {
		    display: flex;
		    align-items: center;
		  }
		  
		  .header__search {
		    display: flex;
		    align-items: center;
		    width: 364px;
		    height: 48px;
		    margin-left: 8px;
		    background-color: #242424;
		    border-radius: 500px;
		    border: 1px solid transparent;
		  }
		  
		  .header__search img {
		    width: 16px;
		    height: 16px;
		    margin-left: 10px;
		  }
		  
		  .header__search input {
		    background: transparent;
		    border: none;
		    padding: 0px 100px 0 12px;
		    color: #fff;
		    text-overflow: ellipsis;
		    outline: none;
		    text-overflow: ellipsis;
		    overflow: hidden;
		    white-space: nowrap;
		  }
		  
		  .header__login .subscribe {
		    color: var(--text-sub);
		    font-size: 16px;
		    font-weight: 700;
		    background-color: transparent;
		    margin-right: 32px;
		  }
		  
		  .header__login .login {
		    width: 100px;
		    height: 48px;
		    color: var(--text-base-dark);
		    font-size: 16px;
		    font-weight: 700;
		    border-radius: 40px;
		  }
	````


# Inteligencia artificial 


## Chat GPT

- Função avançada paga
- Tabela de notas
- Analise de dados avançada
- Consegue mandar anexos para o chat gpt
- Solicitamos a criação de uma tabela
- Podemos pedir para ele fazer a Nota Final
- Conversa com o arquivo de excel. 
