# Jogo da Juju
Jogo de plataforma HTML/Canvas num único arquivo (index.html), feito pelo Leandro para a filha Juju.
Publicado via GitHub Pages: https://leandroduran.github.io/jogo-da-juju/

## Fluxo
- `dev` = trabalho; `main` = produção (Pages). Toda mudança entra em dev; só vai pra main por merge, após teste.
- Antes de commitar, confira a sintaxe do JS do index.html (ex.: node -e com new Function no conteúdo do <script>).
- Atualize o CHANGELOG.md a cada versão.

## Jogo
- Heróis: Juju (herói 1) e Papai (herói 2), iguais; a liderança alterna em "gates" e com a tecla C.
- Ajudante chama-se sempre **Side**; é um personagem diferente por episódio (assets/epN/ajudante_sheet.png).
- Sem vidas nem game over; cair = volta ao checkpoint. Público: criança pequena, autista; mensagens curtas e gentis.
- Episódio 1: Ilha dos Náufragos (tábuas→ponte, cipó, caranguejos, tesouro). Episódio 2: Navio Pirata (cela, barris, cordas, espada, capitão). Próximos: viking, velho oeste, praia do Tiki.
- Toda configuração editável fica no bloco `const CFG` no topo do script.
- Imagens em assets/: heróis na raiz; por episódio em assets/ep1, assets/ep2. Ver assets/README.md para o formato das folhas.
- Música e efeitos são gerados por Web Audio (sem arquivos de áudio).

## Regras
- Não incluir personagens, imagens ou músicas protegidas (ex.: Backyardigans). Personagens e trilhas são originais.
- Não versionar austin.png, pablo.png, uniqua.png (já no .gitignore).
