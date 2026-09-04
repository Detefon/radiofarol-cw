
# Simulador de CW - Radiofarol DX - PWA

Simulador de telegrafia CW com fila de transmissão precisa, modo manipulador, modo prova e bancos de treino.

## Como publicar no GitHub Pages

1. Crie um repositório novo no GitHub: `radiofarol-cw` (público)
2. Faça upload de TODOS os arquivos desta pasta para a branch `main` na raiz:
   - index.html
   - manifest.json
   - sw.js
   - icon-192.png
   - icon-512.png
   - icon-180.png

3. No GitHub, vá em Settings > Pages
   - Source: Deploy from a branch
   - Branch: main / root
   - Salve

4. Seu app estará em: https://SEU-USUARIO.github.io/radiofarol-cw/

5. Para domínio personalizado radiofaroledx.com.br:
   - Em Settings > Pages > Custom domain, coloque: cw.radiofaroledx.com.br
   - Crie um arquivo CNAME com esse domínio
   - No seu provedor DNS, crie CNAME cw apontando para SEU-USUARIO.github.io

## Funcionalidades PWA
- Instalável em Android, iOS e Desktop
- Funciona 100% offline após primeira visita
- Ícone oficial amarelo #FFC300
- Service Worker com cache

73 de PY3TR / Radiofarol DX Group
