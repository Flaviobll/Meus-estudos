# 📚 Minha Rotina de Estudos

Planejador de rotina de estudos feito em **HTML, CSS e JavaScript puro**: você cadastra módulos, marca os dias em que estudou e acompanha sua evolução.

Funciona como **PWA**: dá para instalar no celular ou no computador e usar offline.

## ✨ Funcionalidades

- Cadastro de módulos de estudo (ex.: Java, SQL, Inglês)
- Marcação dos dias estudados, com anotação opcional
- Acompanhamento da evolução
- Dados salvos no próprio navegador (`localStorage`), sem servidor e sem login
- Instalável como app (manifest + service worker) e com funcionamento offline

## 🛠️ Tecnologias

- HTML5, CSS3 e JavaScript (sem frameworks)
- Web App Manifest + Service Worker (PWA)
- LocalStorage para persistência

## ▶️ Como usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/Flaviobll/Meus-estudos.git
   ```
2. Abra o `index.html` no navegador. Para testar o modo offline/instalação, sirva a pasta com um servidor local:
   ```bash
   python -m http.server 8000
   ```
   e acesse `http://localhost:8000`.

## 📁 Estrutura

```
index.html      # app completo (HTML + CSS + JS)
manifest.json   # configuração do PWA
sw.js           # service worker (cache offline)
icon-512.png    # ícone do app
```

---
Feito por [Flávio Barbosa](https://www.linkedin.com/in/flaviobarbosaa) durante a transição para TI.
