# PampaTec na China — Slideshow

Repositório do slideshow **PampaTec na China**, com as mídias (fotos e vídeos) da missão da PampaTec na China, organizadas na mesma sequência apresentada no slideshow interativo.

## 🎯 Propósito

Este repositório publica, via **GitHub Pages**, um slideshow interativo (navegação por teclado/setas ou cliques nas laterais da tela) com as fotos e vídeos da missão PampaTec na China. Também disponibiliza um vídeo compilado com a mesma sequência do slideshow, para compartilhamento e reprodução offline.

## 📂 Conteúdo

- `index.html` — slideshow interativo (HTML/CSS/JS) com a sequência de mídias.
- `slideshow.html` — versão alternativa do slideshow.
- `media/` — fotos (`.jpg`) e vídeos (`.mp4`) utilizados no slideshow.
- `Logo PampaTec.png` — logo exibida sobreposta no slideshow.
- `PampaTec_na_China.mp4` — vídeo compilado (fotos com 10 s cada, vídeos com duração original), publicado como asset da Release `v1.0`.

## 🔗 Links

- **Slideshow interativo (GitHub Pages):** https://pampatec.github.io/pampatec-na-china-slideshow/
- **Vídeo para assistir no navegador (GitHub Pages):** https://pampatec.github.io/pampatec-na-china-slideshow/video.html
- **Vídeo completo para download (alta qualidade):** https://github.com/PampaTec/pampatec-na-china-slideshow/releases/download/v1.0/PampaTec_na_China.mp4
- **Página da Release:** https://github.com/PampaTec/pampatec-na-china-slideshow/releases/tag/v1.0

## 🚀 Publicação

A publicação é feita pelo script `git_push.sh`, que sincroniza o repositório local com o GitHub e publica no GitHub Pages (branch `main`).

## 📝 Observações

- O GitHub Pages exibe o slideshow diretamente a partir dos arquivos da branch `main`.
- O vídeo compilado excede 100 MB, por isso é distribuído como asset de uma Release (e não como arquivo comum do repositório).