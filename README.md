# Projeto de Layout Responsivo com CSS Grid

Este projeto demonstra como usar CSS Grid para criar um layout responsivo que organiza elementos em duas colunas quando a largura da tela está entre 360px e 414px. O projeto inclui cards que são organizados de forma a ficar um abaixo do outro em resoluções menores e em duas colunas em resoluções maiores.

## Estrutura do Projeto

### HTML

O arquivo HTML contém um contêiner pai (`.pai`) que contém um cabeçalho (`.header`) e vários cards (`.card`), cada um com um título (`.titulo`) e um subtítulo (`.sub-titulo`).

```html
<!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Layout Responsivo com CSS Grid</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <div class="pai">
      <div class="header">Header</div>
      <div class="card">
        <div class="titulo">Título 1</div>
        <div class="sub-titulo">Sub-título 1</div>
      </div>
      <div class="card">
        <div class="titulo">Título 2</div>
        <div class="sub-titulo">Sub-título 2</div>
      </div>
      <div class="card">
        <div class="titulo">Título 3</div>
        <div class="sub-titulo">Sub-título 3</div>
      </div>
      <div class="card">
        <div class="titulo">Título 4</div>
        <div class="sub-titulo">Sub-título 4</div>
      </div>
      <div class="card">
        <div class="titulo">Título 5</div>
        <div class="sub-título">Sub-título 5</div>
      </div>
      <div class="card">
        <div class="titulo">Título 6</div>
        <div class="sub-título">Sub-título 6</div>
      </div>
    </div>
  </body>
</html>
```
