const minutos = Math.round((dados.tempo_medio - horas)
* 100)
const porcentagemConectada = ((pessoasConectadas /
pessoasNoMundo) * 100).toFixed(2)

const paragrafo = document.createElement(‘p’)
paragrafo.classList.add(‘graficos-container__texto’)
paragrafo.innerHTML = `Você sabia que o mundo tem
<span>${pessoasNoMundo} bilhões</span> de pessoas e
que aproximadamente <span>${pessoasConectadas}
bilhões </span> estão conectadas em alguma rede social
e passam em média <span>${horas}</span> horas e
<span>${minutos}</span> minutos conectadas.
<br> Isso significa que aproximadamente ${porcentagemConectada}%
de pessoas estão conectadas em alguma rede social.`


.graficos-container {
margin: 5rem;
}

.graficos-container__texto {
font-size: 1.3rem;
text-align: center;
}

.graficos-container__texto {
font-size: 1.3rem;
text-align: center;
padding: 2rem;
border: var(--secundary-color) solid 2px;
}

span {
font-weight: bold;
color: var(--secundary-color);
}

paragrafo.innerHTML = `Você sabia que o mundo tem
<span>${dados.total_pessoas_mundo}</span> de pessoas e
que aproximadamente <span>${dados.total_pessoas_
conectadas}</span> estão conectadas em alguma rede
social e passam em media

<span>${dados.tempo_medio}</span> horas conectadas.`

async function visualizarInformacoesGlobais() {
const res = await fetch(url);
const dados = await res.json();
console.log(dados);
}


{
“total_pessoas_conectadas”: 5.04e9,
“tempo_medio”: 2.38,
“total_pessoas_mundo”: 7.888e9
}


async function visualizarInformacoesGlobais() {
const res = await fetch(url);
const dados = await res.json();
console.log(dados.tempo_medio);
}


async function visualizarInformacoesGlobais() {
const res = await fetch(url)
const dados = await res.json()
const paragrafo = document.createElement(‘p’)
paragrafo.classList.add(‘graficos-container__texto’)
}

async function visualizarInformacoesGlobais() {
const res = await fetch(url)
const dados = await res.json()
const paragrafo = document.createElement(‘p’)
paragrafo.classList.add(‘graficos-container__texto’)
paragrafo.innerHTML = `Você sabia que o mundo tem
${dados.total_pessoas_mundo} de pessoas e
que aproximadamente ${dados.total_pessoas_conectadas}
estão conectadas em alguma rede social e passam em média
${dados.tempo_medio} horas conectadas.`
console.log(paragrafo)
}

<main class=”graficos-section”>
<section id=”graficos-container” class=
”graficos-container”>
<!-- crie os gráficos aqui -->
</section>
</main>

async function visualizarInformacoesGlobais() {
const res = await fetch(url)
const dados = await res.json()
const paragrafo = document.createElement(‘p’)
paragrafo.classList.add(‘graficos-container__texto’)
paragrafo.innerHTML = `Você sabia que o mundo tem
${dados.total_pessoas_mundo} de pessoas e
que aproximadamente ${dados.total_pessoas_conectadas}
estão conectadas em alguma rede social e passam em média
${dados.tempo_medio} horas conectadas.`
const container = document.getElementById(‘graficos-
container’)
container.appendChild(paragrafo)
}

const url = ‘https://raw.githubusercontent.com/
guilhermeonrails/api/main/dados-globais.json’

const url = ‘https://raw.githubusercontent.com/
guilhermeonrails/api/main/dados-globais.json’
console.log(url);

<footer>
<p>Desenvolvido por Gui Lima</p>
</footer>
<script type=”module” src=”graficos/
informacoesGlobais.js”></script>

async function
visualizarInformacoesGlobais() {
}

async function visualizarInformacoesGlobais() {
const res = await fetch(url);
}

async function visualizarInformacoesGlobais() {
const res = await fetch(url)
const dados = res.json()
console.log(dados);
}


const url = ‘https://raw.githubusercontent.com/
guilhermeonrails/api/main/dados-globais.json’

async function visualizarInformacoesGlobais() {
const res = await fetch(url)
const dados = res.json()
console.log(dados);
}
visualizarInformacoesGlobais()


async function visualizarInformacoesGlobais() {
const res = await fetch(url)
const dados = await res.json()
console.log(dados);

@import
url(‘https://fonts.googleapis.com/css2?
family=Nunito+Sans:ital,opsz,
wght@0,6..12,200..1000;1,6..12,200..1000&display=swap’);

:root {
--bg-color: #222831;
--primary-color: #DDDDDD;
--secundary-color: #F05454;

:root {
--bg-color: #222831;
--primary-color: #DDDDDD;
--secundary-color: #F05454;
--font: “Nunito Sans”, sans-serif;
}

body {
background-color: var(--bg-color);
}

<head>
<meta charset=”UTF-8”>
<meta name=”viewport” content=”width=device-width,
initial-scale=1.0”>
<title>Redes Sociais</title>
<link rel=”stylesheet” href=”style.css”>
</head>

body {
background-color: var(--bg-color);
color: var(--primary-color);
font-family: var(--font);
}

body {
background-color: var(--bg-color);
color: var(--primary-color);
font-family: var(--font);
height: 100vh;
margin: 0;
}

header {
background-color: var(--primary-color);
text-align: center;
}

h1 {
font-size: 2rem;
color: var(--bg-color);
font-weight: 700;
}

nav {
display: flex;
justify-content: center;
font-weight: 400;
}


nav a {
text-decoration: none;
color: var(--bg-color);
margin: 0rem 2rem 3rem 0rem;

header {
background-color: var(--primary-color);
text-align: center;
padding: 1px;
}

nav a {
text-decoration: none;
color: var(--bg-color);
margin: 0rem 2rem 3rem 0rem;
font-size: 12rem;
}

nav a:hover {
text-decoration: underline;
transform: scale(0.90);
transition: transform 0.1s;

footer {
display: flex;
align-items: center;
justify-content: center;
background-color: var(--primary-color);
color: var(--bg-color);

footer {
display: flex;
align-items: center;
justify-content: center;
background-color: var(--primary-color);
color: var(--bg-color);
width: 100%;
height: 3rem;
margin-top: 2rem;


