# Hackerspace Blumenau

## Setup

- Instale o [RVM](https://rvm.io/)
- Instale o Ruby 2+ no RVM (`rvm install 2.3.0`)
- Instale a gema do jekyll (`gem install jekyll`)

## Executando

Execute o comando `jekyll serve` e acesse [http://127.0.0.1:4000/](http://127.0.0.1:4000/).

## Contribua

Ajude-nos a melhorar este projeto, ele é seu também.

Faça um fork e envie sua sugestão (aka Pull Request).

## Gerando conteúdo

### Páginas

Páginas ficam no menu principal (Sobre, Contato, ...).

Para adicionar uma nova página crie um arquivo chamado `minha-pagina.md` na pasta `_sitepages`.

A página deve possuir o seguinte formato:

```
---
layout: page
title: Minha Página
permalink: /minha-pagina/
---

Conteúdo da minha página.
```

### Artigos do Blog

Artigos ficam dentro do menu Blog.

Para adicionar um novo artigo crie um arquivo chamado `YYYY-MM-DD-meu-artigo.md` na pasta `_posts`.

O artigo deve possuir o seguinte formato:

```
---
layout: post
title: "Meu Artigo"
date: 2016-04-02 13:00:00 -0300
categories: categoria-1, categoria-2
---

Conteúdo do meu artigo.
```

### Projetos

Projetos ficam dentro do menu Projetos.

Para adicionar um novo projeto crie um arquivo chamado `meu-projeto.md` na pasta `_projects`.

O projeto deve possuir o seguinte formato:

```
---
layout: project
title: Meu Projeto
---

Conteúdo do meu projeto.
```

### Inserindo imagens

Para inserir uma imagem em um artigo, projeto ou página, você deve colocar a imagem na pasta `images`. E no local desejado você deve inserir a seguinte marcação `![Minha Imagem](/images/minha-imagem.png)`

## Licença

MIT para o código fonte do site.

Creative Commons Attribution-ShareAlike 4.0 International para o conteúdo do site.
