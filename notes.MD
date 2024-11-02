# Starting in Bootstrap

## Import libraries with CDN

```
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
```

## Import libraries with DOWNLOAD FILES

> [Download files](https://getbootstrap.com/docs/5.3/getting-started/download/)

# CONTAINERS

> O que são?
- containers são elementos essenciais para organizar o layout e limitar a largura do conteúdo no site, criando um espaçamento horizontal nas laterais. Eles funcionam como "caixas" que centralizam e ajustam o conteúdo conforme o tamanho da tela.

> Tipos de containers: 
- .container: Centraliza o conteúdo e ajusta a largura automaticamente conforme o breakpoint (ponto de interrupção) do dispositivo. Em desktops maiores, a largura é fixa.
- .container-fluid: Sempre ocupa 100% da largura da tela, independentemente do tamanho do dispositivo.
- .container-{breakpoint} (ex.: .container-sm, .container-md, .container-lg, .container-xl, .container-xxl): Adapta a largura a partir de um breakpoint específico, ficando com largura fixa somente quando atinge aquele tamanho de tela ou maior.

```
sm: ≥ 576px
md: ≥ 768px
lg: ≥ 992px
xl: ≥ 1200px
xxl: ≥ 1400px
```