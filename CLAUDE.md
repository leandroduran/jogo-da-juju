# Jogo da Juju
Jogo de plataforma HTML/Canvas num único arquivo (index.html), feito pelo Leandro para a filha Juju.
Publicado via GitHub Pages: https://leandroduran.github.io/jogo-da-juju/

## Fluxo
- `dev` = trabalho; `main` = produção (Pages). Toda mudança entra em dev; só vai pra main por merge, após teste.
- Antes de commitar, confira a sintaxe do JS do index.html (ex.: node -e com new Function no conteúdo do <script>).
- Atualize o CHANGELOG.md a cada versão.

## Jogo
- Heróis: Juju (herói 1) e Papai (herói 2), iguais; a liderança alterna em "gates" e com a tecla C. No episódio 3 entra um terceiro herói (`CFG.heroC`, nome provisório "Herói 3").
- Ajudante chama-se sempre **Side**; é um personagem diferente por episódio (assets/epN/ajudante_sheet.png).
- Sem vidas nem game over; cair = volta ao checkpoint. Público: criança pequena, autista; mensagens curtas e gentis.
- Episódio 1: Ilha dos Náufragos (tábuas→ponte, cipó, caranguejos, tesouro). Episódio 2: Navio Pirata (cela, barris, cordas, espada, capitão). Episódio 3: O Coração da Floresta (habilidades em `CFG.skills`: força = Papai, cipós = Juju, ouvido = Herói 3; a minhoca Sherman, `CFG.worm`, segue o líder até a família). Próximos: viking, velho oeste, praia do Tiki.
- Toda configuração editável fica no bloco `const CFG` no topo do script.
- Imagens em assets/: heróis na raiz (heroi1, heroi2, heroi3); por episódio em assets/ep1, assets/ep2, assets/ep3. Ver assets/README.md para o formato das folhas. Sem imagem, o jogo usa desenhos próprios.
- Música e efeitos são gerados por Web Audio (sem arquivos de áudio).

## Regras
- Código, desenhos padrão e trilhas são originais. Não incluir músicas protegidas.
- As folhas de sprite em assets/ podem ser versionadas por decisão do Leandro, inclusive as que usam personagens de terceiros (ex.: heroi3_sheet.png, ep3/ajudante_sheet.png).
- Não versionar austin.png, pablo.png, uniqua.png, Sprite_personagem.png (já no .gitignore).
