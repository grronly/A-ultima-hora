# A Última Hora — demo (Rightdeath Game)

Jogo de terror em pixel art, pronto para virar app instalável (PWA) via GitHub Pages.

## Publicar no GitHub Pages
1. Crie um repositório novo no GitHub (público), por exemplo `a-ultima-hora`.
2. Envie **todo o conteúdo desta pasta** para a raiz do repositório (`index.html`, `sw.js`, `manifest.webmanifest`, pastas `fonts` e `icons`).
3. No repositório, vá em **Settings > Pages**. Em "Build and deployment", escolha **Deploy from a branch**, branch **main**, pasta **/ (root)**, e salve.
4. Em 1 ou 2 minutos o jogo estará em `https://SEU-USUARIO.github.io/a-ultima-hora/`.

## Instalar no celular (Android)
Abra o link no Chrome, toque no menu (três pontos) e escolha **Instalar app** ou **Adicionar à tela inicial**. Ele abre em tela cheia, deitado, e funciona offline depois da primeira visita.

## Atualizar o jogo
Depois de alterar o `index.html`, mude o número em `CACHE='ultima-hora-v1'` no `sw.js` (para `v2`, `v3`...). Sem isso, quem já instalou continua vendo a versão antiga.

## Gerar um APK depois
Com o jogo hospedado nesse endereço, ferramentas como o PWABuilder ou o Bubblewrap conseguem empacotar o PWA em APK.
