---
layout: ebook
title: "Título do E-book"
subtitle: "Subtítulo opcional"
author: "Seu Nome"
date: "2025"
description: "Descrição curta (opcional)"
cover_image: "/assets/img/sua-capa-a4.jpg"   # só informativo; a capa é inserida no HTML abaixo
---

<!-- CAPA (A4, pode ser IMG ou SVG) -->
<div class="cover-page">
  <!-- IMG direto (mais simples) -->
  <img src="{{ '/assets/img/sua-capa-a4.jpg' | relative_url }}" alt="Capa do e-book">
  <!-- Ou SVG em tamanho A4:
  <svg class="cover-svg" width="210mm" height="297mm" viewBox="0 0 210 297" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Capa">
    <image href="{{ '/assets/img/sua-capa-a4.jpg' | relative_url }}" x="0" y="0" width="210" height="297" preserveAspectRatio="xMidYMid meet"/>
  </svg>
  -->
</div>

<div class="page-break"></div>

# Sumário
<ol class="sumario">
  <li>Capítulo 1</li>
  <li>Capítulo 2</li>
  <li>Capítulo 3</li>
  <li>Capítulo 4</li>
  <li>Capítulo 5</li>
  <li>Capítulo 6</li>
  <li>Capítulo 7</li>
  <li>Sobre o Autor</li>
</ol>

<hr class="divider-gold">

<div class="page-break"></div>

# Capítulo 1 — Título do capítulo
Parágrafos do capítulo…

<hr class="divider-gold">
<div class="page-break"></div>

# Capítulo 2 — Título do capítulo
Parágrafos…

<!-- …repita estrutura para os demais capítulos... -->

<hr class="divider-gold">
<div class="page-break"></div>

<!-- SOBRE O AUTOR -->
<div class="author-page">
  <img class="author-avatar" src="{{ '/assets/img/autor.jpg' | relative_url }}" alt="Autor(a)">
  <h1>Seu Nome</h1>
  <h3>Sua credencial</h3>
  <p class="author-intro">
    Mini-bio justificada com recuo da primeira linha, etc.
  </p>
  <div class="about-box about-narrow">
    <h3>Missão</h3>
    <ul class="author-highlights">
      <li>Item 1</li>
      <li>Item 2</li>
    </ul>
  </div>
  <div class="about-box about-narrow">
    <h3>Como eu trabalho</h3>
    <ul class="author-highlights">
      <li>Item 1</li>
      <li>Item 2</li>
    </ul>
  </div>
  <p class="author-cta">
    <strong>Próximo passo:</strong> CTA/Link principal.
  </p>
</div>