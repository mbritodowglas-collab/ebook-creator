# Bella Prime – E-book Oficial

Este diretório faz parte do repositório `ebook-creator`.

## Como editar
Abra o arquivo `index.md` e atualize o conteúdo conforme desejar.  
Você pode editar o texto, adicionar citações, imagens e dividir trechos em colunas usando `<div class="two-columns">`.

## Como exportar para PDF
Você pode gerar o e-book em PDF de três maneiras:

1. **Via Pandoc (recomendado):**
   ```bash
   pandoc index.md -o "Bella Prime.pdf" --css style.css --pdf-engine=weasyprint