# assets/

Coloque aqui os PNGs (fundo transparente). Nomes esperados — todos opcionais; sem eles o jogo usa os desenhos padrão:

| Arquivo | O quê | Grade |
|---|---|---|
| `heroi1_sheet.png` | Herói 1 (Juju) | 6 colunas × 8 linhas, quadros 128×128 |
| `heroi2_sheet.png` | Herói 2 (Papai) | idem |
| `ajudante_sheet.png` | Ajudante (Lili) | idem |
| `caranguejo_sheet.png` | Caranguejo | 6 × 6, quadros 512×512 |
| `pirata_sheet.png` | Capanga pirata (ep. 2) | 6 × 4 (ou 8) |
| `capitao_sheet.png` | Capitão pirata (ep. 2) | 6 × 4 (ou 8) |

Linhas das folhas de personagem: parado (2), andando (6), pulando (6), braços (6) — olhando pra direita; linhas 4–7 repetem olhando pra esquerda (se faltarem, o jogo espelha).
Linhas do caranguejo: parado frente, andando frente, garras frente, parado costas, andando costas, garras costas.

Também aceita imagem única: `heroi1.png`, `heroi2.png`, `ajudante.png`. Altura e margem dos pés se ajustam em `CFG.sprites` / `CFG.sheets` no `index.html`.
