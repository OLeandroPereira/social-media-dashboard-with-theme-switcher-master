<div id="top">

# - Painel de mídia social com alternador de temas

## Índice

<br>

- [O desafio](#the-challenge)
- [Visão geral](#visão-geral)
- [Captura de tela](#captura-de-tela)
- [Links](#links)
- [Meu processo](#meu-processo)
- [Tecnologias](#tecnologias-utilizadas)
- [O que aprendi](#o-que-eu-aprendi)
- [Desenvolvimento contínuo](#desenvolvimento-contínuo)
- [Recursos úteis](#useful-resources)
- [Autor](#autor)
- [Agradecimentos](#agradecimentos)

<br>

## Visão geral
![](./meuprocesso.jpg)
### O desafio

Os usuários devem ser capazes de:

- Visualize o layout ideal para o site, dependendo do tamanho da tela do dispositivo
- Veja os estados de foco para todos os elementos interativos na página
- Alterne o tema de cores para sua preferência
<br>
<br>
<br>
<h1>

### Captura de tela
<br>

<h3>Tema Dark</h3>
<div align="center">
  <img src="design/active-states-dark.jpg"/>
</div>
<h3>Tema Light</h3>
<div align="center">  
  <img src="design/active-states-light.jpg">
 </div>


### Links


- Veja o deploy: [Painel de Mídia Social](https://paineldemidiasocial.netlify.app/)

<h1></h1>

## Meu processo

### Tecnologias utilizadas

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- JavaScript 
<br>
<br>
<h1>

### O que eu aprendi

Neste projeto melhorarei minha técnica no posicionamento dos elementos, utilizando o Flexbox e Grid layout. A responsividade foi um dos desafios a serem superados neste projeto, mas depois de tanta persistência e estudo consegui solucionar o problema.

Usei o JavaScript para fazer alteração do tema do painel, e foi mais fácil do eu imaginava.
<br>
<br>

<a href="#top"> Voltar ao topo</a>
<h1>

### HTML

Em contato diariamente no desenvolvimento deste projeto, venho cada vez mais consolidando os meus conhecimentos, e a cada projeto realizado esta ficando mais fácil na declaração das div's e classes.

```html
<div class="overview__box">
  <div class="first">
      <p>Page Views</p>
      <img src="/images/icon-facebook.svg" alt="Facebook">
  </div>
  <div class="second"> 
    <h2>87</h2>
      <div class="indicator">
          <img src="/images/icon-up.svg" alt="Ícone up" class="icon-up">
          <span class="up">3%</span>
      </div>
  </div>
</div>
```
<br>
<h1>

### CSS

Este projeto foi ótimo para eu evoluir minha técnica na utilização da propriedade display Grid.

```css
.dashboard-overview {
    display: grid; 
    height: 10rem;
    grid-column-gap: 24px;
    grid-row-gap: 20px;
    grid-template-columns: repeat(4, 1fr);
  }
```
<br>
<h1>

### JavaScript

Estarei incremetando esta linguagem nos meus projetos, a minha meta é me aprofundar nos conceitos e praticas para aprimorar os meus conhecimentos e técnicas. 

```js
const checkbox = document.querySelector('#checkbox');
const body = document.querySelector('body');

checkbox.addEventListener('click', function(){
    body.classList.toggle('toggle')
})
```
<h1>

<br>

### Desenvolvimento contínuo

*Estou tendo contato diariamente com código, e está sendo incrível a evolução que venho obtendo nesses últimos dias, meu objetivo principal é estar cada dia mais preparado tecnicamente para realização de grandes projetos.*

<h1>


### Recursos úteis

- [Grid Layout](https://grid.layoutit.com/) - Isso me ajudou a elaborar o display grid no projeto. Gostei muito deste modelo e vou usá-lo daqui para frente.

<br>
<h1>

## Autor LEANDRO PEREIRA

## Me siga nas Redes:

<a href="https://linkedin.com/in/leandropereira-dev/" target="_blank">
    <img align="center" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin"/>
</a>
<a href="https://www.instagram.com/le_codigo/" target="_blank">
    <img align="center" src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white/le_codigo" alt="linkedin"/>
</a> 

<br>
<br>
<h1>

## Agradecimentos

*Quero agradecer o Andre Cruz da comunidade CODE, por ter disponibilizado o seu tempo para me ajudar no conceito inicial da linguagem Javascript.*

<br>
<br>
<br>
<a href="#top">Voltar ao topo</a>