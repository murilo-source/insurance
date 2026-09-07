# Template — Post Institucional MG

**Editar visualmente:** https://claude.ai/code/artifact/6ba774b5-1d8f-4f9b-a54d-0ce588dd02e9

Modelo pronto para qualquer data institucional/civica (7 de Setembro, Dia da Bandeira, Consciência Negra, Natal, Ano Novo, aniversário da empresa etc). Validado no post de 7 de Setembro de 2026.

## Quando usar este modelo

Registro **institucional**: datas civis, comemorativas, sem venda. Zero CTA, zero produto, zero pílula de ação — só marca e a data. Para posts de produto/nicho (agro, auto, garantia...), siga o sistema do Thaner descrito no [DNA Visual MG](https://claude.ai/code/artifact/57e01ba5-f06f-484e-8dcc-344f1f5b60eb), não este modelo.

## Como editar

Abra o link acima e mexa direto pelos chips de ajuste no topo do artboard (não precisa editar código):

| Campo | O que é | Exemplo |
|---|---|---|
| `eyebrowLabel` | Selo pequeno no topo do texto | "7 DE SETEMBRO" |
| `headlineSetup` | Linha fina de contexto | "Feliz Dia da" |
| `headlineMain` | Palavra de impacto, grande | "Independência" |
| `subtitle` | Uma frase curta, sem venda | "Liberdade que a gente ajuda a proteger, todos os dias." |
| `colorMid` / `colorAccent` | As duas cores do losango (a de baixo é sempre o azul-marinho da marca) | verde/dourado para datas ligadas ao Brasil; troque para outra dupla harmônica em outras datas |

Depois de editar, exporte PNG pelo botão Export do canvas.

## Regra do ícone

O arquivo usa `logo_icon_flag.png` (ícone MG recolorido nas cores da bandeira) — correto para datas ligadas ao Brasil. Para datas sem relação com a bandeira (Natal, aniversário da empresa etc.), troque a referência da imagem no `Main.dc.html` para `logo_icon_navy.png` (incluso nesta pasta, é o ícone original da marca).

## Fórmula de legenda (Instagram)

Mesmo registro contido da arte — sem hashtag, sem CTA, sem link:

```
[Data]. [Saudação curta].

[Uma frase que liga o sentimento da data ao que a MG faz — sem vender].

MG Gestão de Riscos [emoji da data, se fizer sentido]
```

**Exemplo (7 de Setembro):**
```
7 de Setembro. Feliz Dia da Independência.

Liberdade que a gente ajuda a proteger, todos os dias.

MG Gestão de Riscos 🇧🇷
```

## Arquivos

- `Main.dc.html` — a peça, com os campos acima como props editáveis
- `canvas.json` — layout do canvas (1080×1080)
- `logo_icon_flag.png` — ícone MG nas cores da bandeira (default)
- `logo_icon_navy.png` — ícone MG original, para datas sem tema Brasil
