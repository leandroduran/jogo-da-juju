# Jogo da Juju

Jogo de plataforma em HTML/Canvas, feito para a Juju. Dois heróis (Juju e Papai) e o Side (um ajudante diferente em cada episódio) exploram uma ilha, acham um tesouro, são capturados por piratas e tomam o navio.

**Jogar:** abra `index.html` no navegador — ou, publicado no GitHub Pages, acesse pelo link do repositório (funciona em tablet e celular, com botões na tela).

## Controles
| Tecla | Ação |
|---|---|
| ← → ou A D | andar |
| ↑ / W / espaço | pular · agarrar e subir na corda |
| ↓ / S | descer na corda |
| Z | jogar coco |
| X | agir: cavar, abrir, pegar, golpear com a espada |
| C | trocar o herói que lidera |

No toque (tablet/celular) os botões aparecem sozinhos; o 🎮 no topo liga/desliga; 🔊 controla a música.

**Tela cheia no iPhone/iPad:** abra o link no Safari → Compartilhar → *Adicionar à Tela de Início*. O jogo vira um ícone e abre sem a barra do navegador.

## Episódios
1. **Ilha dos Náufragos** — tábuas → ponte, cipó, caranguejos, tesouro enterrado.
2. **O Navio Pirata** — cela, barris, cordas do mastro, espada, capitão.

## Imagens
Ver [`assets/README.md`](assets/README.md). Sem imagens o jogo usa desenhos próprios.

## Fluxo de trabalho
- `dev` — branch de trabalho; toda mudança entra aqui primeiro.
- `main` — produção; recebe `dev` só depois de testado. GitHub Pages publica a partir de `main`.

```bash
# promover dev → produção
git checkout main && git merge dev && git push
```

Sem áudio ou arte de terceiros: música gerada em tempo real (Web Audio), personagens originais ou desenhados por quem joga.
