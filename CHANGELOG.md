# Changelog

## 0.3.4
- Tatu-bola lê folhas com linhas separadas por lado (`layout:'lr'` em `CFG.sheets.crab3`): parado/andando/enrolar à direita, andando/enrolar à esquerda. Enrola uma vez ao ser acertado, segura e desenrola antes de fugir.

## 0.3.3
- Família do Sherman: quatro minhocas, cada uma de uma cor (azul, laranja, verde, lilás), todas de bolinhas — e o Sherman também ganhou bolinhas.
- Ravina: ilhotas maiores (150 px) — cabem os três heróis e o Sherman.
- Cipós vão e voltam: ficam pendurados do lado em que foram largados; na ilhota com dois cipós, vai pro lado que o herói está olhando.
- Clareira: tronco oco com notinhas e "?" marca onde a família está; a escuta vale em toda a clareira e uma mata fechada no fim impede passar direto.
- Trocas de líder não acontecem no meio de um cipó nem em pontos já ultrapassados há muito.

## 0.3.2
- Tatus-bola na floresta (cinco): empurram ao encostar, castanha faz virar bolinha, depois fogem de costas. Folha opcional `assets/ep3/tatu_sheet.png` (mesmo esquema do caranguejo).

## 0.3.1
- Sherman anda de pé no chão, logo atrás de quem lidera (não vai mais na cabeça). `CFG.worm.offset` = distância atrás do líder.

## 0.3.0 — Episódio 3: O Coração da Floresta
- Terceiro herói (`CFG.heroC`, nome provisório "Herói 3") — o jogo passa a suportar três heróis, com dois seguidores que pulam junto e evitam buracos.
- Habilidades da selva em `CFG.skills`: força (empurrar a pedra pro lamaçal), cipós (cadeia de três cipós sobre a ravina), ouvido (escutar pra abrir a mata fechada e achar a família). O herói certo assume sozinho quando o desafio aparece.
- Sherman (`CFG.worm`) viaja na cabeça de quem lidera e reencontra a família na clareira. Cogumelos-trampolim, lamaçais, castanhas.
- Side do episódio 3 é a cientista (desenho padrão de jaleco; `assets/ep3/ajudante_sheet.png`).
- Opereta original (baixo "oom", pizzicato "pah", clarinete saltitante) em dó maior.
- Cartão de título ao começar cada episódio; botão "Ir direto à floresta"; fim do episódio 2 leva ao 3.

## 0.2.4
- Pulo mais longo (alcance ~270 px) e tolerante: vale apertar um pouco antes ou um pouco depois da beirada.
- O herói que vem atrás pula junto com o líder e também pula sozinho ao ver um buraco à frente.
- Troca de líder só acontece com os dois no chão e próximos; ponto de troca da ilha afastado do primeiro lago.

## 0.2.3
- Tablet: controles de toque numa faixa abaixo da tela. Celular deitado: botões translúcidos nos cantos, menores, sem encolher o jogo.
- Modo app: ao "Adicionar à Tela de Início" no iPhone/iPad, abre em tela cheia, deitado, com ícone próprio (`assets/icon.png`).

## 0.2.2
- Caranguejos de porão no convés do navio (dois), usando `assets/ep2/caranguejo_sheet.png`.

## 0.2.1
- Ajudante passa a se chamar **Side** em todas as fases, com um personagem diferente por episódio.
- Imagens reorganizadas por episódio: `assets/ep1/`, `assets/ep2/`; heróis continuam em `assets/`.

## 0.2.0 — Episódio 2: O Navio Pirata
- Cutscene de captura ao achar o tesouro (navio no horizonte, rede, título do episódio).
- Fase do navio: cela com chave trazida pela ajudante, piratas jogando barris, cordas de escalada nos mastros, escotilhas, espada pirata, capitão com 3 vidas, bandeira troca ao vencer.
- Canção de marinheiro original em 6/8 (sanfona, bumbo, pandeiro).
- Piratas desenhados em estilo redondinho/brilhoso; suporte a `pirata_sheet.png` e `capitao_sheet.png`.
- Botão "Ir direto ao navio pirata" na tela inicial.
- Heróis renomeados: Juju (1) e Papai (2).

## 0.1.0 — Episódio 1: Ilha dos Náufragos
- Dois heróis iguais com liderança alternando em pontos da fase e com C; ajudante no chão.
- Tábuas → ponte, cipó com X, caranguejos (coco → tonto → fogem), tesouro com pá.
- Paralaxe em 5 camadas, texturas geradas, bossa nova original por Web Audio.
- Sprite sheets opcionais para heróis, ajudante e caranguejo; controles de toque.
