
      #  **Agrinho: do campo à cidade, colhendo oportunidades**.
# Formação Matematica II, NRE Ivaiporã, Guarapuava e Pato Branco.
## [Clique aqui para ver o site de exemplo](https://professorrichardson.github.io/Agrinho-2024-formacao/)
# `Parabéns por ter chegado até aqui, agora vamos programar nosso site. `


## Vamos ajustar alguns parâmetros do nosso VS Code que abrimos pelo Codespace.

 1. Vamos instalar essas extensões abaixo no nosso Vs Code.

![brackets](https://github.com/professorrichardson/Agrinho-2024-formacao/assets/125823124/641bfedc-9551-4e33-a1c8-d83f3b43abeb)

![color tag](https://github.com/professorrichardson/Agrinho-2024-formacao/assets/125823124/f3c7a133-8d37-45b2-91d7-d02776b150f0)

![colorize](https://github.com/professorrichardson/Agrinho-2024-formacao/assets/125823124/e75d6102-1ce1-4f21-bb40-38156601f268)

![live server](https://github.com/professorrichardson/Agrinho-2024-formacao/assets/125823124/70067f00-7c0f-4633-80e8-65fcc66f1640)

![rename tag](https://github.com/professorrichardson/Agrinho-2024-formacao/assets/125823124/012c113e-0fc4-44fa-9a2f-a73858017eb0)

### Agora vamos configurar ele para ter a aparência DARK que irá facilitar ver as cores das TAGS HTML, mas se você preferir continuar com o tema LIGHT que é o padrão pode pular essa parte.
> Clique na engrenagem no canto inferior esquerdo depois em temas -> tema de Cores.

![config](https://github.com/professorrichardson/Agrinho-2024-formacao/assets/125823124/d7c5e51a-44ad-4029-9209-2e73f36332f5)

>Abrirá essa tela, escolha GitHub Dark.

![dark](https://github.com/professorrichardson/Agrinho-2024-formacao/assets/125823124/2ed377e5-00b7-4ab2-9010-6343c6f1af17)

## Ao final estará dessa forma

![vscode](https://github.com/professorrichardson/Agrinho-2024-formacao/assets/125823124/f1816526-f171-40f3-8848-6a2951b3497f)

# No seu navegador de preferencia Google Chrome instale essa estenção 

![ex](https://github.com/professorrichardson/Agrinho-2024-formacao/assets/125823124/5ceda614-5c7d-47cd-9fa6-e5465f582d03)

# [Link da extensão](https://chromewebstore.google.com/detail/mobile-simulator-responsi/ckejmhbmlajgoklhgbapkiccekfoccmk?hl=pt-BR)


# Vamos colocar a mão na massa.

Crie tres novos arquivos no explorador do Vs Code.

 - index.html
 - stilo.css
 - main.js
> As imagens ja deixei no projeto para facilitar ( então ficara assim a estrutura:
> {
> img/, 
> index.html, 
> main.js. 
> stilo.css, 
> README.md, 
> LICENSE
> } 
> Não nessecariamente nessa orden. )  
 ![explorador](https://github.com/professorrichardson/Agrinho-2024-formacao/assets/125823124/73bc9c7f-6c81-4c21-9a1a-a4ffc0ca11d7)

 
 # Show agora abra o arquivo index.html 
 Nesse arquivo estará nossas seções do site, vamos adicionar as primeiras linhas de código você poderá copiar ou digitar se preferir 
 ~~~HTML
<!DOCTYPE  html>
<!--começo HTML-->
<html>
<!--Colar aqui as informações do site-->
<body>
<!--Colar/digitar  aqui as seções-->

<!--Colar/digitar  a referência ao arquivo JavaScript-->
</body>
</html>
<!--fim HTML-->
~~~

Entre as tag´s `<html> <body>` colocaremos esse código abaixo ele e responsável por configurar titulo, fonte, decodificador de caracteres, e relacionar nosso arquivo `STILO.CSS` que será nossa estilização do site.

~~~HTML
<!--começo das informações internas do site-->
<head>
<title>Do campo à cidade, colhendo oportunidades</title>
<meta  charset="UTF-8" />
<meta  name="viewport"  content="width=device-width, initial-scale=1" />
<link  rel="stylesheet"  href="stilo.css" />
<link  rel="preconnect"  href="https://fonts.googleapis.com" />
<link  rel="preconnect"  href="https://fonts.gstatic.com"  crossorigin />
<link href="https://fonts.googleapis.com/css2?family=Lustria&display=swap" rel="stylesheet"/>
</head>
<!--fim das informações internas do site-->
~~~
Chegamos agora nas seções do nosso site aonde vamos começar a ver tomar forma, vamos começar pelo cabeçalho do site ou a parte que vemos assim que ele e aberto no navegador coloque esse codigo entre as tag´s  `<body></body>`.

~~~HTML
<!--começo cabeçalho visual do site-->
<header>
	<div  class="cabecalho img">
		<img  class="logo__principal"  src="img/logo.png"  alt="Logo" />
		<h1  class="texto__cabecalho">
			Agrofloresta e a importância da polinização.
		</h1>
		<a  class="cabecalho__botao"  href="https://www.nre.seed.pr.gov.br/modules/conteudo/conteudo.php?conteudo=53" target="_blank" >NRE IVAIPORÃ</a>
			<br />
	</div>
</header>
<!-- fim cabeçalho visual do site-->
~~~

Agora faremos a 1° seção esse codigo será colado ou digitado abaixo do cabeçalho.
~~~html
<!-- primeira seção -->
<section  class="container">
	<div  class="secao1__descricao">
		<p  class="secao1__titulo">O que é uma Agrofloresta?</p>
		<p  class="secao1__texto">
		Agrofloresta é um sistema de uso da terra que combina árvores,
		arbustos, culturas agrícolas e/ou animais em um arranjo ecológico e
		produtivo. Esses sistemas visam imitar as características das
		florestas naturais, promovendo a biodiversidade, a reciclagem de
		nutrientes, a conservação do solo e a regulação do clima. Eles também
		podem proporcionar uma fonte sustentável de alimentos, produtos
		florestais, medicamentos e outros recursos. É uma prática que tem
		ganhado destaque por sua abordagem sustentável e amigável ao meio
		ambiente.
		</p>
	</div>
	<img src="img/bananas.png" alt="imagem de um bananal" class="secao1__imagem"/>
</section>
<!-- fim da primeira seção -->
~~~

Continuando abaixo da 1°, seção colocaremos essa parte.

~~~HTML
<!-- segunda seção -->
<section>
	<div  class="secao2__titulo">
		<p  class="secao2__img__titulo">A produção de mel.</p>
	</div>
	<div  class="secao2__imagens">
		<div>
			<img  src="img/1.png"  alt="Homen colhendo mel" />
		</div>
		<div>
			<img  src="img/2.png"  alt="Homen colhendo mel" />
		</div>
		<div>
			<img  src="img/3.png"  alt="homen coletando mel" />
		</div>
	</div>
	<div  class="secao2__subtitulo">
		<h2  class="secao2__img__subtitulo">
		As abelhas são responsáveis pela produção de mel, cera e outros
		produtos apícolas que podem representar uma fonte adicional de renda
		para os agricultores
		</h2>
	</div>
</section>
<!-- fim da segunda -->
~~~

Continuando abaixo da, 2°, seção colocaremos essa parte de informação.

~~~HTML
<!--terceira seção informações -->
<section  class="container">
	<div  class="secao3__imagem img">
		<div  class="secao3__texto">
			<h1  class="secao3__info">
			"Descubra a doçura da natureza em cada gota de mel e a versatilidade
			dos produtos da colmeia. Experimente a pureza e os benefícios dos
			nossos produtos apícolas!"
			</h1>
				<p  class="secao3__info">LuzIA -02-04-24</p>
		</div>
	</div>
</section>
<!-- fim da terceira seção informações -->
~~~

Continuando abaixo dá, 3°, seção colocaremos essa parte do contato.

~~~HTML
<!-- quarta seção contato -->
<section  class="container secao4">
	<div  class="secao4__imagem">
		<img src="img/pote-mel.png" alt="ilustração de potes de mel"/>
	</div>
	<div  class="secao4__container">
		<p  class="secao4__titulo">Contato</p>
		<p  class="secao4__texto">Luzia</p>
			<br />
			<br />
		<p  class="secao4__email">
		<span>E-mail: </span>
		<a href="mailto:luzia.siscati@escola.pr.gov.br">luzia.siscati@escola.pr.gov.br</a>
		</p>
			<br />
		<p  class="secao4__fone"><span>Telefone: </span><a  href="tel:+554334725739">(43)3472 57-39</a></p>
			<br />
		<p  class="secao4__endereco">
		<span>Endereço: </span>Av. Minas Gerais, 295 - Ivaiporã, PR, 86870-000
		</p>
	</div>
</section>
<!-- fim quarta seção contato -->
~~~

Estamos quase lá essa seção e bem interessante, pois usaremos um trecho de código do curso `Projeto de vida ` do Alura  Aonde acionaremos um relógio do clima `"O relógio indica o tempo que resta para limitar o aquecimento global a 1,5 grau, a meta estabelecida no Acordo de Paris."` uma adaptação par nosso projeto, para os professores de Matemática II programação I ( 2° anos NEM ) não há nescidade, pois não é cobrado o JavaScript nessa etapa sendo assim poderá deixar sem essa parte. Código abaixo será colocado abaixo da, 4° seção.

~~~HTML
<!--quinta seção Relogio clima -->
<section  class="container relogio">
	<div  class="aba-conteudo ativo">
		<h3  class="aba-conteudo-titulo-principal">Relógio do clima</h3>
		<h4  class="aba-conteudo-titulo-secundario">Tempo restante para limitar o aquecimento global</h4>
		<div  class="contador">
			<div  class="contador-digito">
				<p  class="contador-digito-numero"  id="dias0">7</p>
				<p  class="contador-digito-texto">dias</p>
			</div>
			<div  class="contador-digito">
				<p  class="contador-digito-numero"  id="horas0">7</p>
				<p  class="contador-digito-texto">horas</p>
			</div>
			<div  class="contador-digito">
				<p  class="contador-digito-numero"  id="min0">7</p>
				<p  class="contador-digito-texto">min</p>
			</div>
			<div  class="contador-digito">
				<p  class="contador-digito-numero"  id="seg0">7</p>
				<p  class="contador-digito-texto">seg</p>
			</div>
		</div>
	</div>
</section>
<!-- fim da quinta seção relogio do clima -->
~~~

Por fim o nosso Rodapé contendo alguns links colocar abaixo da seção relógio e antes do `</body>`

~~~HTML
<!--rodapé  -->  
    <footer class="rodape">
      <img src="img/logo.png" alt="ceaa" class="rodape__logo" />
      <ul class="rodape__lista">
        <li class="lista__link">
          <a href="https://www.sistemafaep.org.br/agrinho/">AGRINHO 2024</a>
        </li>
        <li class="lista__link">
          <a href="https://www.instagram.com/sistema.faep/">SENAR</a>
        </li>
        <li class="lista__link">
          <a
            href="https://www.nre.seed.pr.gov.br/modules/conteudo/conteudo.php?conteudo=53"
            >NRE IVAIPORÃ</a
          >
        </li>
        <li  class="lista__link">
          <a  
            href="https://www.nre.seed.pr.gov.br/modules/conteudo/conteudo.php?conteudo=50"
            >NRE GUARAPUAVA
          </a>
        </li>
        <li  class="lista__link">
          <a  
            href="https://www.nre.seed.pr.gov.br/modules/conteudo/conteudo.php?conteudo=61"
            >NRE PATO BRANCO
          </a>
        </li>
      </ul>
      <p class="rodape__texto">Site modelo Agrinho 2024</p>
      <p class="rodape__texto">® 2024 -NRE IVAIPORÃ</p>
    </footer>
    <!-- fim rodapé-->
~~~

# Ufa 😌 Terminamos o arquivo index.html como será que está ficando ?

![sohtml](https://s12.gifyu.com/images/SZZ9A.gif)

# 😱😱😱😱😱😱😱😱 Por que está todo desregulado ?

## nos programamos somente o HTML do site temos agora que dar visual nele para isso vamos no arquivo `STILO.CSS` lá fica nossas cores, fontes e demais configurações visuais.

Abra o `stilo.css` e iniciaremos com algumas configurações básicas.

~~~css
* {
	margin: 0;
	padding: 0;
}
/* setup das variaveis*/
:root {
	--verde-fundo: #deece7;
	--branco-principal: #ffffff;
	--fonte-principal: "Lustria";
	--verde-principal: #5fb13b;
	--azul-principal: #0169b4;
	--verde-secundario: #313a22;
	--link: #0a4804;
	--preto-titulo: #000;
}
/* configurações do corpo como fontes e cores*/
body {
	background-color: var(--verde-fundo);
	color: var(--branco-principal);
	font-family: var(--fonte-principal);
	font-size: 20px;
	font-weight: 400;
}

/*Configurações de efeitos do mouse */
a:link {
	text-decoration: none;
	color: var(--link);
}
a.cabecalho__botao:link {
	color: #fff;
}
a:visited {
	color: var(--branco-principal);
}
a:hover {
	text-decoration: underline;
	color: var(--azul-principal);
}
a:active {
	text-decoration: none;
}

/*estilo dos containers genericos*/
.container {
	margin-top: 50px;
	display: flex;
}
~~~

### Como essa parte da estilização e muito grande vamos separar por Media Queries.
  - #### 1025px — 1200px: desktops, telas grandes.;
  - #### 769px — 1024px: iPads, tablets, laptops;
 - #### 320px — 480px: dispositivos móveis celulares.

 ![mq](https://miro.medium.com/v2/resize:fit:900/1*yyB4EpJcUQ5W8h9X8wCm7g.png)

### `Desktop, Tablet, Celular`, assim respeitando a parte responsiva da criação do site, isso quer dizer que o site se adaptará em todas as telas possíveis tornando a navegação mais agradável para o usuário. ( todos os códigos serão um abaixo do outro, pois o CSS e uma folha de estilo em cascata, o navegador lê o código de cima para baixo ).

# Desktop:
Todas estilizações feitas nessa parte terá efeito quando a resolução da tela for entre  acima de `768px`

~~~css
/*estilos do cabeçalho*/
.cabecalho {
	background-image: url("img/4.png");
}
.img {
	width: 100%;
	height: 100%;
	object-fit: cover;
	background-size: cover;
	background-repeat: no-repeat;
	background-position: center  center;
}
.logo__principal {
	margin-top: 100px;
	margin-left: 50px;
}
.texto__cabecalho {
	text-align: center;
	margin-top: 200px;
	margin-bottom: 300px;
	font-size: 80px;
	font-weight: 400;
}
.cabecalho__botao {
	margin-left: auto;
	margin-right: auto;
	display: block;
	margin-top: 5%;
	font-size: 25px;
	font-weight: 400;
}
a.cabecalho__botao {
	width: 180px;
	height: 30px;
	color: #fff;
	padding: 20px;
	border: 5px  solid  #fff;
}
~~~

Seção 1:

~~~css
/* estilo seção 1*/
.secao1__descricao {
	width: 50%;
}
.secao1__titulo {
	font-weight: 700;
	font-size: 48px;
	color: var(--preto-titulo);
	margin-bottom: 0.2em;
}
.secao1__texto {
	margin-top: 35px;
	color: var(--preto-titulo);
	font-size: 30px;
}
~~~

Seção 2:

~~~css
/* estilo seção 2*/
.secao2__img__titulo {
	color: var(--preto-titulo);
	font-weight: 700;
	font-size: 48px;
	margin-left: 40px;
}
.secao2__img__subtitulo {
	margin-top: 35px;
	color: var(--preto-titulo);
	font-size: 25px;
}
.secao1__descricao,
.secao2__img__subtitulo {
	padding: 2em;
}
.secao2__imagens {
	display: flex;
	flex-wrap: nowrap;
	justify-content: space-between;
	padding: 2em;
}
.secao2__imagens  img {
	width: 95%;
}
.secao2__titulo {
	margin: 50px  0px  30px  0px;
}
.secao2__subtitulo  h2 {
	margin-top: 35px;
	color: var(--preto-titulo);
	font-size: 30px;
}
~~~

Seção 3:

~~~css
/* estilo seção 3*/
.secao3__imagem {
	background-image: url("img/mel.png");
}
.secao3__texto {
	margin: 30%  0  30%  0;
}
.secao3__info {
	width: 95%;
	padding: 1em;
	text-align: center;
}
~~~

Seção 4:

~~~css
/* estilo seção 4*/
.secao4__titulo,
.secao4__texto,
.secao4__email,
.secao4__fone,
.secao4__endereco {
	font-size: 25px;
}
.secao4 {
	display: flex;
	justify-content: space-around;
}
.secao4__container {
	flex-wrap: nowrap;
	color: var(--preto-titulo);
	display: flex;
	flex-direction: column;
	justify-content: space-between;
	align-items: center;
	font-size: 20px;
}
.secao4__titulo {
	font-size: 50px;
}
.secao4__imagem  img {
	width: 100%;
}
.secao4__endereco {
	text-align: center;
}
~~~

Seção 5:

~~~css
/*Seçao 5 relogio clima*/
.relogio{
	background-color: var(--verde-principal);
	color: var(--preto-titulo);
	justify-content: space-around;
	padding: 2em;
}
.aba-conteudo.ativo{
	display:block;
}
.aba-conteudo{
	display: none;
}
.aba-conteudo-titulo-principal{
	font-size: 28px;
	text-align: center;
}
.aba-conteudo-titulo-secundario{
	text-align: center;
	color: var(--verde);
	text-transform: uppercase;
}
.contador{
	display:flex;
	justify-content: center;
	flex-wrap: wrap;
}
.contador-digito{
	padding: 0  16px;
	text-align: center;
	min-width: 100px;
}
.contador-digito-numero{
	font-size: 80px;
	margin: 0;
}
.contador-digito-texto{
	color: var(--preto-titulo);
	font-size: 20px;
	margin: 0;
}
~~~

Seção rodapé:

~~~css
/* Rodapé */
.rodape__lista {
	display: flex;
	justify-content: center;
	list-style-type: none;
	margin-top: 1em;
}
.lista__link  a {
	text-decoration: none;
	color: var(--verde-principal);
	margin-left: 1em;
}
.rodape__texto {
	margin: 1em  0em  0em;
	color: var(--verde-principal);
	font-size: 14px;
}
.rodape {
	background-color: var(--verde-secundario);
	text-align: center;
	margin: 5em  0em  0em;
}
.rodape__logo {
	max-width: 200px;
	max-height: 200px;
	width: auto;
	height: auto;
}
.rodape__agrinho {
	max-width: 200px;
	max-height: 200px;
	width: auto;
	height: auto;
	border-radius: 5%;
}
~~~

## Após digitar/colar esses códigos nosso site na resolução de desktop estará assim:
(Somente o relógio ainda não estará funcionando, pois não o programamos ainda).

![pc](https://s12.gifyu.com/images/SZFeB.gif)

# Celular 

### Agora vamos ajustar nosso site para se encaixar nas principais telas de celulares, digite/cole esse código abaixo do que já fizemos anteriormanete no arqquivo `stilo.css`.
Todas estilizações feitas nessa parte terá efeito quando a resolução da tela for entre `320px — 480px`

~~~css
/* ########################## Responsivo para celulares e tablets ##############################*/
/* -- 320px — 480px: dispositivos móveis CELULAR --*/
@media (min-width: 320px) and (max-width: 480px) {
	/* estilo cabeçalho */
		.logo__principal {
	width: 80%;
	}
	.texto__cabecalho {
		text-align: center;
		margin-top: 100px;
		margin-bottom: 180px;
		font-size: 30px;
		font-weight: 400;
	}
	.container {
		flex-flow: column  nowrap;
	}
	
	/* estilo seção 1*/
	.secao1__descricao {
		padding: 1em;
		width: 90%;
	}
	.secao1__titulo {
		text-align: center;
	}
	.secao1__texto {
		font-size: 20px;
	}
	
	/* estilo seção 2*/
	.secao2__img__titulo {
		color: var(--preto-titulo);
		font-weight: 700;
		font-size: 38px;
		text-align: center;
	}
	.secao2__subtitulo  h2 {
		font-size: 20px;
		text-align: center;
	}
	.secao2__imagens {
		flex-wrap: wrap;
	}
	.secao2__imagens  img {
		width: 100%;
	} 
	
	/* estilo seção 3*/
	.secao3__texto {
		margin: 50%  0  50%  0;
		display: flex;
		flex-wrap: wrap;
		justify-content: space-around;
	}
	.secao3__texto  h1 {
		margin-bottom: 50%;
		text-align: center;
	} 
	
	/* estilo seção 4*/
	.secao4 {
		display: flex;
		justify-content: space-around;
	}
	.secao4__container {
		flex-wrap: nowrap;
		color: var(--preto-titulo);
		display: flex;
		flex-direction: column;
		justify-content: space-between;
		align-items: center;
		font-size: 20px;
	}
	.secao4__titulo {
		font-size: 50px;
	}
	.secao4__imagem  img {
		width: 100%;
	}
	.secao4__texto,
	.secao4__email,
	.secao4__fone,
	.secao4__endereco {
		font-size: 20px;
	}
	.secao4__endereco {
		text-align: center;
	}
	
	/* estilo rodapé*/
	.rodape__lista {
		flex-wrap: wrap;
		align-items: center;
		flex-direction: column-reverse;
	}
	.rodape__lista  li {
		margin-bottom: 10px;
	}
}
~~~
#### ficará assim nossa versão para celular (OBS. novamente sem o relógio funcionando falta o Java script):

![mobile](https://github.com/professorrichardson/Agrinho-2024-formacao/assets/125823124/cf7e5763-0359-4844-98e0-a8822f516258)


## Que codigo grande 😭 mas fique tranquilo veja que reescrevemos varias das classes que fizemos no nosso `Desktop` mas isso e nescesario para mudar tamanhos de fonte, espaçamento e etc.. para que se ajuste nessas telas menores, agora faremos as telas intermediarias que chamei de `Tablet`.

# Tablet

### Novamente digite/cole esse código abaixo do que já fizemos anteriormanete no arqquivo `stilo.css`.
Todas estilizações feitas nessa parte terá efeito quando a resolução da tela for entre `481px — 768px`

~~~css
/* -- 481px — 768px: iPads, tablets -- */
@media (min-width: 481px) and (max-width: 768px) {
	.container {
		flex-flow: column  nowrap;
	}
	/* Cabeçalho */
	.logo__principal {
		width: 80%;
	}
	.texto__cabecalho {
		margin-top: 100px;
		margin-bottom: 150px;
		font-size: 30px;
	}

	/* estilo seção 1*/
	.secao1__descricao {
		text-align: center;
		font-size: 25px;
		width: 90%;
	}
	.secao1__imagem {
		padding: 1em;
		width: 95%;
		height: auto;
	}
	 
	/* estilo seção 2*/
	.secao2__imagens  img {
		width: 95%;
	}
	.secao2__img__titulo {
		text-align: center;
	}
	.secao2__subtitulo  h2 {
		font-size: 25px;
	}

	/* estilo seção 3*/
	.secao3__texto  h1 {
		width: 95%;
		padding: 1em;
		margin-bottom: 30%;
	}
	.secao3__texto  p {
		text-align: center;
	}
	.secao3__texto  h2 {
		margin: 50%  0  50%  0;
	}

	/* estilo seção 4*/
	.secao4__container {
		font-size: 28px;
		text-align: center;
	}
	.secao4__titulo {
		font-size: 60px;
	}
	.secao4__texto,
	.secao4__email,
	.secao4__fone,
	.secao4__endereco {
		font-size: 30px;
	}
	.secao4__imagem {
		display: flex;
		justify-content: space-around;
		margin-bottom: 50px;
	}
	
	/* estilo seção rodapé*/
	.rodape__lista  li {
		font-size: 25px;
		margin-bottom: 10px;
	}
}
~~~
####  Nossa versão para Tablet (OBS. novamente sem o relógio funcionando falta o Java script):

![tablet](https://github.com/professorrichardson/Agrinho-2024-formacao/assets/125823124/0451cbf0-1b96-406c-b7d5-cdc1ae48fcf9)

# Nessa etapa já finalizamos a parte responsiva do site e todas suas funções de estilo e ajuste estão funcionando falta somente nosso relógio funcionar.

## para resolvermos isso vamos agora no arquivo `main.js` lembrando que fizemos uma adaptação no codigo do alura irei explicar abaixo.

~~~javascript
/* cria uma variavel de nome 'textos' e referencia ela a classe que contem '.aba-conteudo'*/
const  textos  =  document.querySelectorAll(".aba-conteudo");
/* cria uma variavel de 'contadores' e referencia ela a classe que contem '.contador'*/
const  contadores  =  document.querySelectorAll(".contador");
/* cria uma variavel de 'tempoObjetivo1' e adiciona nela a data de 01/01/2030 */
const  tempoObjetivo1  =  new  Date("2030-01-01T00:00:00");
/* cria uma variavel de nome 'tempo' e referencia ela a variavel tempoObjetivo1 poderia ser um array*/
const  tempo  =  tempoObjetivo1 ;

/* Função que fara todo o calculo matematico para retornar a quantidade de dias horas minutos e segundos
retirando do dia atual - data definida na variavel tempo*/
function  calculaTempo(tempoObjetivo) {
	let  tempoAtual  =  new  Date();
		let  tempoFinal  =  tempoObjetivo  -  tempoAtual;
		let  segundos  =  Math.floor(tempoFinal  /  1000);
		let  minutos  =  Math.floor(segundos  /  60);
		let  horas  =  Math.floor(minutos  /  60);
		let  dias  =  Math.floor(horas  /  24);
		segundos  %=  60;
		minutos  %=  60;
		horas  %=  24;
	if (tempoFinal  >  0) {
		return [dias, horas, minutos, segundos];
	} else {
		return [0, 0, 0, 0];
	}
}
  
/*função que pega o retorno da função 'calculaTempo()' e injeta ou seja escreve dentro do html
o resultado do processamento feito*/
function  atualizaCronometro() {
	document.getElementById("dias0").textContent  =  calculaTempo(tempo)[0];
	document.getElementById("horas0").textContent  =  calculaTempo(tempo)[1];
	document.getElementById("min0").textContent  =  calculaTempo(tempo)[2];
	document.getElementById("seg0").textContent  =  calculaTempo(tempo)[3];
}

/* essa função atualiza os dados de 1 em 1 segundo definidos pelo setInterval(atualizaCronometro, 1000);
isso da o efeito que esta mudando sozinho como um relogio mesmo
*/
function  comecaCronometro() {
	atualizaCronometro();
	setInterval(atualizaCronometro, 1000);
}

/* Por fim esse trecho que e uma função inicia tudo*/
comecaCronometro();
~~~

### Se acaso mesmo assim o relógio não iniciar ficar somente com os numeros `7 7 7 7`, verifique se voce adicionou a tag que referencia o arquivo `main.js` lá no fim do HTML dentro do `index.html`.
como e mostrado abaixo: 

![JS](https://github.com/professorrichardson/Agrinho-2024-formacao/assets/125823124/9e9259a7-a523-4502-896a-75a767277566)


~~~html
<script src="main.js"></script>
~~~

## Chegamos ao fim do nosso site agora para que as modificações fique salvas temos que commitar ou seja confirmar as alterações, pois iremos publicar esse site no GitHub Pages e na Vercel.

## (Primeira opção) Comitando projeto, procure por esse icone no lado direito do seu explorador Vs Code.dev e clique nele.

![comit1](https://github.com/professorrichardson/Agrinho-2024-formacao/assets/125823124/e8a9fe44-02ac-4c2e-9467-4857f72efb09)

#### Agora escreva uma mensagem que se refere as modificações feitas no codigo, toda vez que fizer modificações tem que repetir esse processo para que fique salvo.

![comit2msg](https://github.com/professorrichardson/Agrinho-2024-formacao/assets/125823124/a9adc639-207a-426a-a47b-458784064f9e)

#### Depois de descrever o que foi modificado aperte em Commit & Push ( Em alguns casos pede para sincronizar pode permitir )

![commit botão](https://github.com/professorrichardson/Agrinho-2024-formacao/assets/125823124/dffef7ff-2a76-4a63-9bd1-22ba83faabec)

#### Se ficar assim sem números no icone de Commit e o Botão fica sem função isso quer dizer que ja foi salvo as modificações.![comit finish](https://github.com/professorrichardson/Agrinho-2024-formacao/assets/125823124/37e1694f-9d7f-4ff8-b310-ee84ad92e427)

## (Segunda opção) se você estiver usando o codspace faça desse modo.
![commit](https://github.com/professorrichardson/Agrinho-2024-formacao/assets/125823124/a91ba694-1bf9-4a1f-9d6d-2c55608d16cf)

## Os arquivos serão enviados para um stage isso quer dizer que ainda não foi enviado para o GitHub está aguardando a confirmação pode clicar em (YES).
![commi2t](https://github.com/professorrichardson/Agrinho-2024-formacao/assets/125823124/d550ef84-b30e-4721-bf20-7afe3f5c6b49)

## Agora o botão está escrito (Sync ) se estiver terminado todas as alterações do site pode clicar para que assim seja aplicada as modificações no GitHub.
![commi3t](https://github.com/professorrichardson/Agrinho-2024-formacao/assets/125823124/0a94a2d3-b689-4e36-952f-6c6466b0a3d6)

## Novamente irá pedir se quer confirmar a ação de envio pode clicar em (OK).
![commi4t](https://github.com/professorrichardson/Agrinho-2024-formacao/assets/125823124/7fcde309-71f9-493d-9388-373158024523)


### Agora vamos ajustar nosso repositorio de acordo com as rubricas do concurso.


#### Vamos publicar nosso site no GitHub Pages seguindo os seguintes passos, clique na engrenagem que esta escrito Settings.

![setings](https://github.com/professorrichardson/agrinho-ceaa/assets/125823124/99647d1f-1547-4541-a078-5340283fb568)

#### Depois vá em Pages na lateral esquerda ( procure pela seção Code and automation).

![pages](https://github.com/professorrichardson/agrinho-ceaa/assets/125823124/38edb5de-2957-4ebe-aa21-0ca04d7bd7d7)

####  Clique no botão que esta escrito `None` e selecione `main`.

![build](https://github.com/professorrichardson/agrinho-ceaa/assets/125823124/c339b410-4c71-4ff1-ae9d-1835258c1f96)

#### Depois de alguns minutos seu site estará públicado e aparecerá uma imagen parecida com a abaixo contendo o link da pagina guarde ele para uso fututo.

![link](https://github.com/professorrichardson/agrinho-ceaa/assets/125823124/00373c71-d89e-4d8e-9b70-7a26719c234f)

#### Agora que temos o link do Pages podemos tambem publicar na Vercel e outra plataforma aonde ospedamos nossos projetos feitos em HTML, CSS, JS de forma gratuita, as rubricas pede ou GitHub Pages ou Vercel então vamos ver como fazer mais essa publicação, vá ate o site da Vercel 
# [Site Vercel](https://vercel.com/login)
#### Faça o login usando sua conta GitHub.

![login vercel](https://github.com/professorrichardson/agrinho-ceaa/assets/125823124/6e59e686-2659-4530-852d-31a023a5d1f5)

#### Depois de logar vá em ADD NEW um botão branco no canto superior direito.

![add new](https://github.com/professorrichardson/agrinho-ceaa/assets/125823124/aeace508-51a5-466d-a15e-aaf1725060d2)

#### Selecione Project.

![projeto](https://github.com/professorrichardson/agrinho-ceaa/assets/125823124/6bd0b148-b7a4-4a5a-a584-5df7644b8ab9)

#### Nesta etapa a plataforma Vercel listará todos seus repositorios para que você clique em import, então selecione o repositorio do agrinho que desenvolvemos. `(neste caso Agrinho-2024-formacao)`.

![import](https://github.com/professorrichardson/agrinho-ceaa/assets/125823124/a038869f-2e60-4f8e-a3ab-eb30b4e35bef)

#### Iremos ser redirecionados para parte de deploy nessa etapa podemos colocar um nome mais amigavel ao nosso site, e depois de pronto clicar no botão `deploy`.

![deploy](https://github.com/professorrichardson/agrinho-ceaa/assets/125823124/6cb1a1bb-dd64-4936-abdb-06fc0ae05f7a)

#### Aguarde aparecer a tela abaixo e clique na imagem do site que você será redirecionado para o site, anote novamente a URL ou o nome do site para usarmos na ultima etapa.

![okfinish](https://github.com/professorrichardson/agrinho-ceaa/assets/125823124/37bb9d43-ac9c-4925-a131-a814d30437e6)

####  Volte na parte principal do repositorio no GitHub  vá em README.md e altere os dados citando os nomes dos participantes referenciando as imagens textos coloque os links do seu site hospedado na vercel e Git Pages  como o exemplo abaixo.

![redme](https://github.com/professorrichardson/agrinho-ceaa/assets/125823124/57e1683a-983b-4f1b-88be-a01f38e9cfee)
 ## Dica que vai ajudar muito `Site para criar seu (Readme.md)muito mais fácil`
#  [Link do StackEdit.io](https://stackedit.io/)
 
 # Parabéns mais uma vez por ter concluido as etapas de criação de um site completo com HTML, CSS, JS  e de quebra ainda hospedar ele tornando publico na internet.

## Boa sorte no concurso e que essa formação não acabe somente no Agrinho que seja de grande valia durante suas aulas.

## Obrigado por participar Abraços.

# `Professor: Richardson Schawarski` 

## Agradecimentos aos NRE´s Ivaiporã, Guarapuava e Pato Branco.

### 👏👏👏 😊😊😊😊😊😊😊😊😊😊😊😊😊😊😊😊😊😊😊😊



# Código Completo (HTML)  -> index.html
~~~html
<!--Este modelo pode ser reutilizado para os professores e alunos da rede estadual do Paraná -->
<!-- Agrinho 2024 NRE(Ivaiporã) NRE(GUARAPUAVA) NRE(PATO BRANCO) -->
<!--Desenvolvido : -->
<!-- Professor Richardson Schawarski em parceria com ebaixadora Luzia Siscati NRE Ivaiporã -->

<!DOCTYPE html>
<!--começo HTML-->
<html>

  <!--começo cabeçalho de informações internas do site-->
  <head>
    <title>Do campo à cidade, colhendo oportunidades</title>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <link rel="stylesheet" href="stilo.css" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Lustria&display=swap"
      rel="stylesheet"/>
    </head
  ><!--fim cabeçalho de informações internas do site-->

  <!--Começo corpo do site BODY-->
  <body>

    <!--section header  -->
    <header>
      <!--começo cabeçalho visual do site-->
      <div class="cabecalho img">
        <img class="logo__principal" src="img/logo.png" alt="Logo" />
        <h1 class="texto__cabecalho">
          Agrofloresta e a importância da polinização.
        </h1>
        <a class="cabecalho__botao" href="https://www.nre.seed.pr.gov.br/modules/conteudo/conteudo.php?conteudo=53" 
        target="_blank" >NRE IVAIPORÃ</a>
        <br />
      </div>
    </header>
    <!-- fim cabeçalho visual do site-->

    <!-- primeira seção  -->
    <section class="container">
      <div class="secao1__descricao">
        <p class="secao1__titulo">O que é uma Agrofloresta?</p>
        <p class="secao1__texto">
          Agrofloresta é um sistema de uso da terra que combina árvores,
          arbustos, culturas agrícolas e/ou animais em um arranjo ecológico e
          produtivo. Esses sistemas visam imitar as características das
          florestas naturais, promovendo a biodiversidade, a reciclagem de
          nutrientes, a conservação do solo e a regulação do clima. Eles também
          podem proporcionar uma fonte sustentável de alimentos, produtos
          florestais, medicamentos e outros recursos. É uma prática que tem
          ganhado destaque por sua abordagem sustentável e amigável ao meio
          ambiente.
        </p>
      </div>
      <img
        src="img/bananas.png"
        alt="imagem de um bananal"
        class="secao1__imagem"
      />
    </section>
    <!--  fim da primeira seção -->

    <!-- segunda seção lista  -->
    <section>
      <div class="secao2__titulo">
        <p class="secao2__img__titulo">A produção de mel.</p>
      </div>

      <div class="secao2__imagens">
        <div>
        <img src="img/1.png" alt="Homen colhendo mel" />
      </div>
      <div>
        <img src="img/2.png" alt="Homen colhendo mel" />
      </div>
      <div>
        <img src="img/3.png" alt="homen coletando mel" />
      </div>
      </div>
      </div>

      <div class="secao2__subtitulo">
        <h2 class="secao2__img__subtitulo">
          As abelhas são responsáveis pela produção de mel, cera e outros
          produtos apícolas que podem representar uma fonte adicional de renda
          para os agricultores
        </h2>
      </div>
    </section>
    <!-- fim da segunda seção lista -->

    <!--terceira seção informações  -->
    <section class="container">
      <div class="secao3__imagem img">
        <div class="secao3__texto">
          <h1 class="secao3__info">
            "Descubra a doçura da natureza em cada gota de mel e a versatilidade
            dos produtos da colmeia. Experimente a pureza e os benefícios dos
            nossos produtos apícolas!"
          </h1>
          <p class="secao3__info">LuzIA -02-04-24</p>
        </div>
      </div>
    </section>
    <!-- fim da terceira seção informações -->

    <!-- quarta seção contato   -->
    <section class="container secao4">
      <div class="secao4__imagem">
      <img
        src="img/pote-mel.png"
        alt="ilustração de potes de mel"
      />
    </div>
      <div class="secao4__container">
        <p class="secao4__titulo">Contato</p>
        <p class="secao4__texto">Luzia</p>
        <br />
        <br />
        <p class="secao4__email">
          
          <span>E-mail:  </span><a href="mailto:luzia.siscati@escola.pr.gov.br"> luzia.siscati@escola.pr.gov.br</a>
          
        </p>
        <br />
        <p class="secao4__fone"><span>Telefone: </span><a href="tel:+554334725739">(43)3472 57-39</a></p>
        <br />
        <p class="secao4__endereco">
          <span>Endereço: </span>Av. Minas Gerais, 295 - Ivaiporã, PR, 86870-000
        </p>
      </div>
    </section>
    <!-- fim quarta seção contato -->

     <!--quinta  seção Relogio clima  -->
     <section class="container relogio">
      <div class="aba-conteudo ativo">
        <h3 class="aba-conteudo-titulo-principal">Relogio do clima</h3>
        <h4 class="aba-conteudo-titulo-secundario">Tempo restante para limitar o aquecimento global</h4>
        <div class="contador">
            <div class="contador-digito">
                <p class="contador-digito-numero" id="dias0">7</p>
                <p class="contador-digito-texto">dias</p>
            </div>
            <div class="contador-digito">
                <p class="contador-digito-numero" id="horas0">7</p>
                <p class="contador-digito-texto">horas</p>
            </div>
            <div class="contador-digito">
                <p class="contador-digito-numero" id="min0">7</p>
                <p class="contador-digito-texto">min</p>
            </div>
            <div class="contador-digito">
                <p class="contador-digito-numero" id="seg0">7</p>
                <p class="contador-digito-texto">seg</p>
            </div>
        </div>
    </div>
    </section>
    <!-- fim da quinta seção relogio do clima -->

    <!--rodapé  -->  
    <footer class="rodape">
      <img src="img/logo.png" alt="ceaa" class="rodape__logo" />
      <ul class="rodape__lista">
        <li class="lista__link">
          <a href="https://www.sistemafaep.org.br/agrinho/">AGRINHO 2024</a>
        </li>
        <li class="lista__link">
          <a href="https://www.instagram.com/sistema.faep/">FAEP</a>
        </li>
        <li class="lista__link">
          <a href="https://www.instagram.com/sistema.faep/">SENAR</a>
        </li>
        <li class="lista__link">
          <a
            href="https://www.nre.seed.pr.gov.br/modules/conteudo/conteudo.php?conteudo=53"
            >NRE IVAIPORÃ</a
          >
        </li>
        <li  class="lista__link">
          <a  
            href="https://www.nre.seed.pr.gov.br/modules/conteudo/conteudo.php?conteudo=50"
            >NRE GUARAPUAVA
          </a>
        </li>
        <li  class="lista__link">
          <a  
            href="https://www.nre.seed.pr.gov.br/modules/conteudo/conteudo.php?conteudo=61"
            >NRE PATO BRANCO
          </a>
        </li>
      </ul>
      <p class="rodape__texto">Site modelo Agrinho 2024</p>
      <p class="rodape__texto">® 2024 -NRE IVAIPORÃ</p>
    </footer>
    <!-- fim rodapé-->

    <!--Javascript-->
    <script src="main.js"></script>
    <!--fim Javascript-->
  </body>
  <!--fim corpo site BODY-->
</html>
<!--fim HTML-->
~~~

# Código completo (CSS) -> stilo.css
~~~css
/* ###################################### Estilo do Site para dispositivos de telas grande ############################################# */
* {
  margin: 0;
  padding: 0;
}
/* setup das variaveis*/
:root {
  --verde-fundo: #deece7;
  --branco-principal: #ffffff;
  --fonte-principal: "Lustria";
  --verde-principal: #5fb13b;
  --azul-principal: #0169b4;
  --verde-secundario: #313a22;
  --link: #0a4804;
  --preto-titulo: #000;
}

/* configurações do corpo como fontes e cores*/
body {
  background-color: var(--verde-fundo);
  color: var(--branco-principal);
  font-family: var(--fonte-principal);
  font-size: 20px;
  font-weight: 400;
}
/*Configurações de efeitos do mouse */
a:link {
  text-decoration: none;
  color: var(--link);
}
a.cabecalho__botao:link {
  color: #fff;
}
a:visited {
  color: var(--branco-principal);
}

a:hover {
  text-decoration: underline;
  color: var(--azul-principal);
}

a:active {
  text-decoration: none;
}

/*estilo dos containers genericos*/
.container {
  margin-top: 50px;
  display: flex;
}

/*estilos do cabeçalho*/
.cabecalho {
  background-image: url("img/4.png");
}
.img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center center;
}
.logo__principal {
  margin-top: 100px;
  margin-left: 50px;
}
.texto__cabecalho {
  text-align: center;
  margin-top: 200px;
  margin-bottom: 300px;
  font-size: 80px;
  font-weight: 400;
}
.cabecalho__botao {
  margin-left: auto;
  margin-right: auto;
  display: block;
  margin-top: 5%;
  font-size: 25px;
  font-weight: 400;
}
a.cabecalho__botao {
  width: 180px;
  height: 30px;
  color: #fff;
  padding: 20px;
  border: 5px solid #fff;
}

/* estilo seção 1*/
.secao1__descricao {
  width: 50%;
}
.secao1__titulo {
  font-weight: 700;
  font-size: 48px;
  color: var(--preto-titulo);
  margin-bottom: 0.2em;
}
.secao1__texto {
  margin-top: 35px;
  color: var(--preto-titulo);
  font-size: 30px;
}

/* estilo seção 2*/
.secao2__img__titulo {
  color: var(--preto-titulo);
  font-weight: 700;
  font-size: 48px;
  margin-left: 40px;
}
.secao2__img__subtitulo {
  margin-top: 35px;
  color: var(--preto-titulo);
  font-size: 25px;
}
.secao1__descricao,
.secao2__img__subtitulo {
  padding: 2em;
}
.secao2__imagens {
  display: flex;
  flex-wrap: nowrap;
  justify-content: space-between;
  padding: 2em;
}
.secao2__imagens img {
  width: 95%;
}
.secao2__titulo {
  margin: 50px 0px 30px 0px;
}
.secao2__subtitulo h2 {
  margin-top: 35px;
  color: var(--preto-titulo);
  font-size: 30px;
}

/* estilo seção 3*/
.secao3__imagem {
  background-image: url("img/mel.png");
}
.secao3__texto {
  margin: 30% 0 30% 0;
}
.secao3__info {
  width: 95%;
  padding: 1em;
  text-align: center;
}

/* estilo seção 4*/
.secao4__titulo,
.secao4__texto,
.secao4__email,
.secao4__fone,
.secao4__endereco {
  font-size: 25px;
}
.secao4 {
  display: flex;
  justify-content: space-around;
}
.secao4__container {
  flex-wrap: nowrap;
  color: var(--preto-titulo);
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  font-size: 20px;
}
.secao4__titulo {
  font-size: 50px;
}
.secao4__imagem img {
  width: 100%;
}

.secao4__endereco {
  text-align: center;
}

/*Seçao 5 relogio clima*/
.relogio{
  background-color: var(--verde-principal);
  color: var(--preto-titulo);
  justify-content: space-around;
  padding: 2em;
}
.aba-conteudo.ativo{
  display:block;
}
.aba-conteudo{
  display: none;
}
.aba-conteudo-titulo-principal{
  font-size: 28px;
  text-align: center;
}
.aba-conteudo-titulo-secundario{
  text-align: center;
  color: var(--verde);
  text-transform: uppercase;
}
.contador{
  display:flex;
  justify-content: center;
  flex-wrap: wrap;
}
.contador-digito{
  padding: 0 16px;
  text-align: center;
  min-width: 100px;
}
.contador-digito-numero{
  font-size: 80px;
  margin: 0;
}
.contador-digito-texto{
  color: var(--preto-titulo);
  font-size: 20px;
  margin: 0;
}

/* Rodapé */
.rodape__lista {
  display: flex;
  justify-content: center;
  list-style-type: none;
  margin-top: 1em;
}
.lista__link a {
  text-decoration: none;
  color: var(--verde-principal);
  margin-left: 1em;
}

.rodape__texto {
  margin: 1em 0em 0em;
  color: var(--verde-principal);
  font-size: 14px;
}
.rodape {
  background-color: var(--verde-secundario);
  text-align: center;
  margin: 5em 0em 0em;
}
.rodape__logo {
  max-width: 200px;
  max-height: 200px;
  width: auto;
  height: auto;
}
.rodape__agrinho {
  max-width: 200px;
  max-height: 200px;
  width: auto;
  height: auto;
  border-radius: 5%;
}

/* ########################## Responsivo para celulares e tablets ##############################*/

/* -- 320px — 480px: dispositivos móveis  CELULAR --*/
@media (min-width: 320px) and (max-width: 480px) {
  /* estilo cabeçalho */
  .logo__principal {
    width: 80%;
  }
  .texto__cabecalho {
    text-align: center;
    margin-top: 100px;
    margin-bottom: 180px;
    font-size: 30px;
    font-weight: 400;
  }

  .container {
    flex-flow: column nowrap;
  }
  /* estilo seção 1*/
  .secao1__descricao {
    padding: 1em;
    width: 90%;
  }
  .secao1__titulo {
    text-align: center;
  }
  .secao1__texto {
    font-size: 20px;
  }

  /* estilo seção 2*/
  .secao2__img__titulo {
    color: var(--preto-titulo);
    font-weight: 700;
    font-size: 38px;
    text-align: center;
  }
  .secao2__subtitulo h2 {
    font-size: 20px;
    text-align: center;
  }
  .secao2__imagens {
    flex-wrap: wrap;
  }
  .secao2__imagens img {
    width: 100%;
  }

/* estilo seção 3*/
  .secao3__texto {
    margin: 50% 0 50% 0;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
  }
  .secao3__texto h1 {
    margin-bottom: 50%;
    text-align: center;
  }

/* estilo seção 4*/
.secao4 {
  display: flex;
  justify-content: space-around;
}
.secao4__container {
  flex-wrap: nowrap;
  color: var(--preto-titulo);
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  font-size: 20px;
}
.secao4__titulo {
  font-size: 50px;
}
.secao4__imagem img {
  width: 100%;
}
.secao4__texto,
.secao4__email,
.secao4__fone,
.secao4__endereco {
  font-size: 20px;
}
.secao4__endereco {
  text-align: center;
}

/* estilo rodapé*/
.rodape__lista {
  flex-wrap: wrap;
  align-items: center;
  flex-direction: column-reverse;
}
.rodape__lista li {
  margin-bottom: 10px;
}

}

/* -- 481px — 768px: iPads, tablets -- */
@media (min-width: 481px) and (max-width: 768px) {
  .container {
    flex-flow: column nowrap;
  }

  /* Cabeçalho */
  .logo__principal {
    width: 80%;
  }
  .texto__cabecalho {
    margin-top: 100px;
    margin-bottom: 150px;
    font-size: 30px;
  }

/* estilo seção 1*/
  .secao1__descricao {
    text-align: center;
    font-size: 25px;
    width: 90%;
  }
  .secao1__imagem {
    padding: 1em;
    width: 95%;
    height: auto;
  }

  /* estilo seção 2*/
  .secao2__imagens img {
    width: 95%;
  }
  .secao2__img__titulo {
    text-align: center;
  }
  .secao2__subtitulo h2 {
    font-size: 25px;
  }

  /* estilo seção 3*/  
  .secao3__texto h1 {
    width: 95%;
    padding: 1em;
    margin-bottom: 30%;
  }
  .secao3__texto p {
    text-align: center;
  }
  .secao3__texto h2 {
    margin: 50% 0 50% 0;
  }

    /* estilo seção 4*/
  .secao4__container {
    font-size: 28px;
    text-align: center;
  }
  .secao4__titulo {
    font-size: 60px;
  }
  .secao4__texto,
  .secao4__email,
  .secao4__fone,
  .secao4__endereco {
    font-size: 30px;
  }
  .secao4__imagem {
    display: flex;
    justify-content: space-around;
    margin-bottom: 50px;
  }

  /* estilo seção rodapé*/
  .rodape__lista li {
    font-size: 25px;
    margin-bottom: 10px;
  }
}
~~~

# Código completo (JavaScript) ->main.js
~~~javascript
const textos = document.querySelectorAll(".aba-conteudo");
const contadores = document.querySelectorAll(".contador");
const tempoObjetivo1 = new Date("2030-01-01T00:00:00");

const tempo = tempoObjetivo1 ;

function calculaTempo(tempoObjetivo) {
    let tempoAtual = new Date();
    let tempoFinal = tempoObjetivo - tempoAtual;
    let segundos = Math.floor(tempoFinal / 1000);
    let minutos = Math.floor(segundos / 60);
    let horas = Math.floor(minutos / 60);
    let dias = Math.floor(horas / 24);
  
    segundos %= 60;
    minutos %= 60;
    horas %= 24;
    if (tempoFinal > 0) {
      return [dias, horas, minutos, segundos];
    } else {
      return [0, 0, 0, 0];
    }
  }

  function atualizaCronometro() {
    document.getElementById("dias0").textContent = calculaTempo(tempo)[0];
    document.getElementById("horas0").textContent = calculaTempo(tempo)[1];
    document.getElementById("min0").textContent = calculaTempo(tempo)[2];
    document.getElementById("seg0").textContent = calculaTempo(tempo)[3];
  
    for (let i = 0; i < contadores.length; i++) {
      // contadores[i].textContent = calculaTempo(tempos[i]);
    }
  }

  function comecaCronometro() {
    atualizaCronometro();
    setInterval(atualizaCronometro, 1000);
  }
  
  comecaCronometro();
~~~

