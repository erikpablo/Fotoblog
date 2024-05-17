# Meu Projeto Web

Bem-vindo ao meu projeto web! Este README irá guiá-lo pelos conceitos avançados de CSS e HTML que foram utilizados neste projeto.

## Conteúdos

- [Conceitos Avançados de CSS](#conceitos-avançados-de-css)
  - [Animações](#animações)
  - [Grid Layout](#grid-layout)
  - [Transições](#transições)
  - [Variáveis CSS](#variáveis-css)
- [Tags Semânticas em HTML](#tags-semânticas-em-html)

## Conceitos Avançados de CSS

### Animações

As animações em CSS permitem a criação de efeitos dinâmicos que tornam a experiência do usuário mais interativa e interessante. Utilizamos a propriedade `@keyframes` para definir as etapas da animação.

``css
/* Definindo a animação */
@keyframes exemplo {
  0% { background-color: red; }
  50% { background-color: yellow; }
  100% { background-color: green; }
}

/* Aplicando a animação a um elemento */
.elemento-animado {
  animation-name: exemplo;
  animation-duration: 4s;
  animation-iteration-count: infinite;
}
Grid Layout
O Grid Layout do CSS é uma poderosa ferramenta para criar layouts complexos de forma simples e intuitiva. Utilizamos a propriedade display: grid para ativar o modo grid e definir linhas e colunas com grid-template-rows e grid-template-columns.

css
Copiar código
/* Definindo o container grid */
.container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 10px;
}

/* Estilizando os itens do grid */
.item {
  background-color: lightblue;
  padding: 20px;
  text-align: center;
}
Transições
Transições em CSS permitem alterar suavemente uma propriedade CSS de um valor para outro ao longo do tempo. Utilizamos a propriedade transition para definir a duração e as propriedades a serem animadas.

css
Copiar código
/* Definindo a transição */
.elemento-transicao {
  background-color: blue;
  transition: background-color 0.5s ease;
}

/* Estado do elemento ao passar o mouse */
.elemento-transicao:hover {
  background-color: green;
}
Variáveis CSS
As variáveis CSS (ou custom properties) permitem a reutilização de valores CSS em todo o documento, tornando o código mais limpo e fácil de manter. Definimos variáveis com --nome-da-variavel e acessamos com var(--nome-da-variavel).

css
Copiar código
/* Definindo variáveis no :root */
:root {
  --cor-principal: #3498db;
  --cor-secundaria: #2ecc71;
}

/* Utilizando variáveis nos estilos */
.elemento-variavel {
  color: var(--cor-principal);
  background-color: var(--cor-secundaria);
}
Tags Semânticas em HTML
As tags semânticas do HTML melhoram a acessibilidade e o SEO do site, descrevendo claramente o conteúdo e a estrutura do documento. Algumas das tags semânticas que usamos neste projeto incluem <header>, <nav>, <main>, <section>, <article>, <footer>.

html
Copiar código
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Meu Projeto Web</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <header>
    <h1>Bem-vindo ao Meu Projeto</h1>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">Sobre</a></li>
        <li><a href="#contact">Contato</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="home">
      <h2>Home</h2>
      <p>Conteúdo da seção Home.</p>
    </section>
    <section id="about">
      <h2>Sobre</h2>
      <p>Conteúdo da seção Sobre.</p>
    </section>
    <section id="contact">
      <h2>Contato</h2>
      <p>Conteúdo da seção Contato.</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2024 Meu Projeto Web</p>
  </footer>

</body>
</html>
