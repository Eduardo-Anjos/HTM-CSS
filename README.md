# Projeto Galáxias Responsivo

Este projeto é uma aplicação web que fornece informações sobre galáxias. O design é responsivo para todos os dispositivos, e as cores foram cuidadosamente escolhidas para combinar com a temática das galáxias.

## Visão Geral

O projeto utiliza HTML, CSS e CSS Grid para criar um layout que se adapta a diferentes tamanhos de tela. A estética é inspirada nas cores e no visual das galáxias, criando uma experiência visual envolvente para os usuários.

## Estrutura do Projeto

### HTML

O arquivo HTML contém um cabeçalho (`.header`) com um menu de navegação e um título, seguido por várias seções de cards (`.card`). Cada card apresenta uma imagem, um título e uma descrição.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Galáxias</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <header class="header">
      <ul class="pai">
        <li class="topo"><a class="link" href="index.html">Home</a></li>
        <li class="topo"><a class="link" href="#">About</a></li>
        <li class="topo"><a class="link" href="#">Info</a></li>
        <li class="topo"><a class="link" href="#">Contact</a></li>
      </ul>
      <h1 class="titulo">
        <span class="THE-BIGGEST">THE BIGGEST</span>
        <span class="GALAXIES">GALAXIES</span>
      </h1>
      <p class="sub-titulo">And interesting facts about them</p>
    </header>
    <main class="principal">
      <div class="card-1 card">
        <img src="Imagens/img-1.jpg" />
        <h1 class="IC segunda-class mine-titulo">IC 1101</h1>
        <p class="paragrafos">
          IC 1101:IC 1101 is a supergiant elliptical galaxy at the center of the
          galaxy cluster Abell 2029. It is classified as a galaxy cD (is a type
          of elliptical galaxy characterized by its large halo of stars). It is
          1 billion light years away, in the constellation of Serpens. Lorem
          ipsum dolor sit amet consectetur adipisicing elit. Commodi quaerat sed
          atque eligendi dolores perspiciatis ea voluptas, aperiam doloremque
          dignissimos veritatis vitae eum tempora ut in, inventore modi dolorem!
          Numquam?
        </p>
      </div>
      <div class="card-2 card">
        <img src="Imagens/img-2.jpeg" />
        <h1 class="segunda-class mine-titulo">Phoenix Cluster</h1>
        <p class="nome-dentro paragrafos">
          Phoenix Cluster: The Phoenix Cluster is a huge cluster of Abell type I
          galaxies located in its namesake, the southern constellation of
          Phoenix. It was initially detected in 2010 during a 2,500 square
          degree survey of the southern sky using the Sunyaev-Zeldovich effect
          by collaboration with the South Pole. Lorem ipsum dolor sit amet
          consectetur, adipisicing elit. Fuga quae eos ea nostrum. Eaque, soluta
          dolores, asperiores autem delectus rerum deleniti aspernatur aliquam
          mollitia minima cum maiores, culpa ipsam quisquam.
        </p>
      </div>
      <div class="card-3 card">
        <img src="Imagens/img-3.jpeg" alt="" />
        <h1 class="NGC segunda-class mine-titulo">NGC 262</h1>
        <p class="paragrafos">
          NGC 262:NGC 262, also known as Markarian 348, is a galaxy spiral
          (S0-a) located in the direction of the constellation Andromeda. It has
          a declination of +31° 57' 27" and a right ascension of 0 hours, 48
          minutes and 47.1 seconds. Lorem ipsum dolor sit amet consectetur
          adipisicing elit. Aperiam corrupti unde magnam dolorum molestiae
          incidunt laudantium sint. Quisquam inventore ipsa voluptatem magnam
          autem rerum ratione soluta consequuntur temporibus saepe? Reiciendis.
        </p>
      </div>
      <div class="card-4 card">
        <img src="Imagens/img-4.jpeg" alt="" />
        <h1 class="outro-NGC segunda-class mine-titulo">NGC 4889</h1>
        <p class="paragrafos">
          NGC 4889:NGC 4884 (NGC 4889) is an elliptical galaxy (E) located in
          direction of the constellation of Coma Berenices. It has a declension
          of +27° 58' 35" and a right ascension of 13 hours, 00 minutes, 08.3
          seconds.
        </p>
      </div>
      <div class="card-5 card">
        <img src="Imagens/img-5.jpg" />
        <h1 class="outra-NGC segunda-class mine-titulo">NGC 4874</h1>
        <p class="paragrafos">
          NGC 4874:NGC 4874 is an elliptical galaxy (E) located in the direction
          of constellation of Coma Berenices. It has a declination of +27° 57'
          34" and a right ascension of 12 hours, 59 minutes and 35.8 seconds.
        </p>
      </div>
      <div class="card-6 card">
        <img src="Imagens/img-6.jpg" />
        <h1 class="BCG segunda-class mine-titulo">A2261-BCG</h1>
        <p class="outra-class paragrafos">
          A2261-BCG:The galaxy in question is the brightest in a cluster of
          galaxies called Abell 2261 — therefore, many refer to A2261-BCG with
          the name of the cluster itself. It is approximately 2.7 billion light
          years away from Earth, in the direction of the constellation Hercules,
          near the bright star Vega.
        </p>
      </div>
    </main>
  </body>
</html>
```
