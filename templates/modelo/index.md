---
layout: ebook
title: "{{ Título do E-book }}"
subtitle: "{{ Subtítulo ou slogan opcional }}"
author: "{{ Nome do autor ou marca }}"
date: "2025"
---

<!-- =======================================================
     TEMPLATE UNIVERSAL DE E-BOOK · MD PERSONAL SYSTEM
     ======================================================= -->
<!-- Este arquivo serve como molde. Copie-o para /ebooks/ e edite as seções. -->

<div lang="pt-BR">

<!-- =========================
     CAPA (página 1)
     ========================= -->
<div class="cover-page" align="center">
  <img src="{{ '/assets/img/capa-exemplo.jpg' | relative_url }}" alt="Capa do E-book" />
</div>

<div class="page-break"></div>

<!-- =========================
     SUMÁRIO
     ========================= -->
# Sumário
1. Introdução  
2. Capítulo 1 – Nome do capítulo  
3. Capítulo 2 – Nome do capítulo  
4. Capítulo 3 – Nome do capítulo  
5. Conclusão  
6. Sobre o Autor  

---

<!-- =========================
     INTRODUÇÃO
     ========================= -->
# 1. Introdução

<div class="two-columns">

Aqui você inicia o diálogo com o leitor.  
Use uma linguagem natural e humana — como se estivesse conversando com uma amiga ou aluno.  
A introdução deve conectar emoção e propósito.

</div>

<div class="quote-center">
  <h3>“Frase de impacto ou citação para abrir o livro.”</h3>
</div>

---

# 2. Capítulo 1 – Nome do capítulo

<div class="two-columns">

Conte aqui a primeira parte da história, método ou reflexão.  
Recomenda-se misturar **conceito + exemplo + orientação prática**.

Use blocos `blockquote` para depoimentos, trechos reflexivos ou falas marcantes.

</div>

<blockquote>
“Texto exemplo de citação formatada no padrão editorial.”
</blockquote>

---

# 3. Capítulo 2 – Nome do capítulo

<div class="two-columns">

Continue o conteúdo mantendo ritmo e leveza.  
Destaque frases importantes com `<strong>` para reforçar ideias.  
Separe seções com `---` para melhorar a leitura.

</div>

---

# 4. Capítulo 3 – Nome do capítulo

<div class="two-columns">

Feche a parte principal com clareza.  
Resuma aprendizados e direcione o leitor para ação.

</div>

<div class="quote-center">
  <h3>“A transformação começa no pensamento.”</h3>
</div>

---

# 5. Conclusão

Encerre o e-book reforçando o propósito principal e incentivando a reflexão ou prática.

---

# 6. Sobre o Autor

<div class="author-card">
  <div class="author-photo">
    <img src="{{ '/assets/img/autor-exemplo.jpg' | relative_url }}" alt="Autor" loading="lazy" decoding="async">
  </div>

  <div class="author-bio">
    <h3><strong>{{ Nome do Autor }}</strong></h3>
    <p>
      Profissional de Educação Física e criador de métodos que unem treino, neurociência e comportamento.  
      Apaixonado por transformar conhecimento científico em ferramentas práticas de vida.
    </p>

    <div class="about-box">
      <h3>Missão</h3>
      <ul class="author-highlights">
        <li>Inspirar mudanças reais através da prática diária.</li>
        <li>Unir ciência, propósito e disciplina.</li>
        <li>Oferecer guias e programas transformadores.</li>
      </ul>
    </div>

    <div class="author-cta">
      <p><strong>Conecte-se:</strong></p>
      <p>Instagram: @seudominio · WhatsApp: (insira aqui)</p>
    </div>

    <p class="about-sign">— {{ Nome do Autor }}</p>
  </div>
</div>

</div> <!-- /lang -->
