# assets/

PNGs com fundo transparente. Tudo opcional: sem a imagem, o jogo usa o desenho padrão.

```
assets/
├── heroi1_sheet.png      Juju   — vale pra todas as fases
├── heroi2_sheet.png      Papai  — vale pra todas as fases
├── ep1/                  Episódio 1 — Ilha dos Náufragos
│   ├── ajudante_sheet.png   o Side desta fase
│   └── caranguejo_sheet.png
└── ep2/                  Episódio 2 — O Navio Pirata
    ├── ajudante_sheet.png   o Side desta fase (outro personagem, mesmo nome)
    ├── pirata_sheet.png
    └── capitao_sheet.png
```

**Side** é o ajudante: o nome é sempre Side, mas cada episódio tem um personagem diferente — basta colocar o `ajudante_sheet.png` certo dentro de `epN/`.

| Folha | Grade |
|---|---|
| heróis e Side | 6 colunas × 8 linhas, quadros 128×128 — linhas: parado (2), andando (6), pulando (6), braços (6) olhando pra direita; linhas 4–7 as mesmas olhando pra esquerda (se faltarem, o jogo espelha) |
| caranguejo | 6 × 6, quadros 512×512 — parado frente, andando frente, garras frente, parado costas, andando costas, garras costas |
| pirata, capitão | 6 × 4 (ou 8), mesmas linhas dos heróis; "pulando" é usada quando está tonto, "braços" quando joga barril |

Também aceita imagem única (`heroi1.png`, `heroi2.png`, `epN/ajudante.png`). Altura e margem dos pés se ajustam em `CFG.sprites` / `CFG.sheets` no `index.html`.
