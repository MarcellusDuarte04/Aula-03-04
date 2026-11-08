 <!-- Tag Semântica header -->
<header class="header">
  <h1>Eu sou o header</h1>
  <div class="01"></div>
  <div class="02"></div>
  <div class="03"></div>
</header>

<!-- Estas são Divs encadeadas ou Pai e Filhos -->
<div class="main">
  <div class="main esquerda">
    <h1>Aula 03 e 04 de HTML</h1>
  </div>
  <div class="main direita">
    <h2>Início das aulas de DIV</h2>
  </div>
</div>

<!-- Tag semântica main -->
<main class="mainDiv">
  <h1>Eu sou a tag main</h1>
</main>

<!-- Tag semântica footer -->
<footer class="footer">
  <h1>Eu sou o footer</h1>
</footer> 

<div class="marcellus">
  <h1>Aula 03-04</h1>
</div>

<!-- Tag img aula 03-04 -->
<!-- Imagem externa -->
<img
  src="https://static.escolakids.uol.com.br/2025/01/1-sol-visto-do-universo.jpg"
  alt="Imagem do sol"
/>
<!-- Imagem interna -->
<img src="/sol.jpg" alt="Imagem do sol" />

<!-- Tag iframe Incorpora vídeos. -->
<iframe
  width="701"
  height="440"
  src="https://www.youtube.com/embed/ld90ZQgNTX8"
  title="Como instalar o Office 365 Grátis e Completo SEM ERRO"
  frameborder="0"
  allow="
    accelerometer;
    autoplay;
    clipboard-write;
    encrypted-media;
    gyroscope;
    picture-in-picture;
    web-share;
  "
  referrerpolicy="strict-origin-when-cross-origin"
  allowfullscreen
></iframe> css .header{
    min-height: 15vh;
}
.main{
    background-color: rgba(231, 0, 0, 0.795);
}
.esquerda{
    background-color: green;
    font-size: 5rem;
}
.direita{
    background-color: yellow;
}
.mainDiv{
    min-height: 35vh;
    background-color: rgba(0, 0, 0, 0.795);
}
.footer{
    min-height: 35vh;
    background-color: rgba(0, 0, 231, 0.795);
}
.marcellus{
    background-color: blue;
}
