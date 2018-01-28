---
title: Como postar no 4hackers
date: 2018-01-27 21:05:11
tags:
---


### eae hackudo,

Este blog tem o intuito de permitir qualquer um de ensinar/compartilhar algo sobre tecnologia, está sendo mantido no github, o deploy e build está sendo feito pelo travis-ci e hospedado no github-pages. Totalmente aberto a novas ideias, contribuições e parcerias.

### Conhecimentos Nescessários
  
É importante que você tenha um conhecimento básico nessas tecnologias/ferramentas abaixo:
- Git e Github
- Hexo
- Markdown

É necessário que você tenha o Git, Node.js e Hexo instalados na sua máquina.

### Criando o post no blog
1. Antes de qualquer coisa você deve criar um fork do repositório principal.
2. Baixe o blog e crie o post:
```
  # Baixe o fork do repositório:
  git clone --recursive https://github.com/<username>/4hackers.git
  # Crie o post pelo hexo:
  hexo new post <titulo>
```
Para escrever é só abrir o arquivo que está na pasta `source/_posts/`, aconselho utilizar um editor de Markdown como Visual Code.
3. Depois basta criar um pull request para o repositório principal, assim que o PR for completado o post irá automaticamente para o site atráves do build e deploy do Travis-CI.