# Aula 05. Angular e React

## O que vamos fazer?

- Entender ambos os frameorks

## Começando o projeto

## Responsividade

- React, biblioteca de javaScript
- Criando projeto react
	- npx create-react-app spotify-react
- Dentro da pasta SRC que vamos trabalhar
- Iniciamos a aplicação
	- npm start
- React Trabalha com um conceito jsx
- Trabalha tudo dentro do JS
- Tudo dentro do react é um componente
- Tudo sobre compoennte
	- Header
	- Main
	- Table
- Craimos uma pasta
	- Header
		- Header.js
		- Header.css
- Criamos os CSS's e colocamos dentro de onde queremos.
- React é className ao invez de class
- Pegamos a pasta asset e colocamos dentro do nosso projeto. 
- No React importamos muitas coisas. 
- No final ficamos com 3 códigos:
- header.css
	````css
		/* HEADER */
.header__navigation {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem;
    margin: 10px;
    border-radius: 8px;
    background-color: #121212;
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
    width: 2rem;
    height: 2rem;
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
    border: transparent;
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
  }
  
  .header__login .subscribe {
    color: #a7a7a7;
    font-size: 16px;
    font-weight: 700;
    background-color: transparent;
    margin-right: 32px;
    border: none;
  }
  
  .header__login .login {
    width: 100px;
    height: 48px;
    color: #000;
    font-size: 16px;
    font-weight: 700;
    border-radius: 40px;
    border: none;
    background-color: #fff;
  }
  
  /* HOVER */
  
  .header__search:hover {
    border: 1px solid #fff;
  }
  
  .header__login .subscribe:hover {
    transform: scale(1.04);
    color: #fff;
    cursor: pointer;
  }
  
  .header__login .login:hover {
    transform: scale(1.04);
    cursor: pointer;
  }

  .header__login .login:hover {
    transform: scale(1.04);
    cursor: pointer;
  }
  /* FIM HOVER */
  
  /*FIM HEADER */
  
  
 
	````
- header.js
	````js
		import React from "react";
		import './header.css';
		import smallRight from '../assets/icons/small-right.png';
		import smallLeft from '../assets/icons/small-left.png';
		import search from '../assets/icons/search.png';

		const Header = () => {
		    return(
		        <nav className="header__navigation">
		        <div className="navigation">
		          <button className="arrow-left">
		            <img src={smallLeft} alt="" />
		          </button>
		          <button className="arrow-right">
		            <img src={smallRight} alt="" />
		          </button>

		          <div className="header__search">
		            <img src={search} alt="" />
		            <input id="search-input" maxlength="800" autocorrect="off" autocapitalize="off" spellcheck="false"
		              placeholder="O que você quer ouvir?" value="" />
		          </div>
		        </div>

		        <div className="header__login">
		          <button className="subscribe">Inscreva-se</button>
		          <button className="login">Entrar</button>
		        </div>
		      </nav>
		    )
}

export default Header;

````
- O nosso cabecalho aparece de maneira clean.
- Desafio mudar, tudo para React
- Proximidade de pessoas 

# Inteligencia artificial 


## Chat GPT
- Mais do mesmo

