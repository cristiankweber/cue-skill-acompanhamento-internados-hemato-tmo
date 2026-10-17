# Organização de Exames — Padrão de Linha Única

## Formato

Apresente os exames em **uma única linha por data**, precedida da data:

```
# [DD/MM/AAAA]: Hb X | Ht X | Leu X (XS | XM | XL | XEo | XB) | Plaq X | Ret X% (valor/mm³) | Ur X | Cr X (DCE: Y) | Na X | K X | Mg X | P X | BT X | BD X | BI X | TGO X | TGP X | FA X | GGT X | LDH X | PCR X | Ferritina X - FeS X - TIBC X - TSAT X | CT X - HDL X - LDL X - Tg X | B12 X | Folato X | VitD X | TSH X | T4L X
```

## Regras obrigatórias

- Não incluir exames ausentes no laudo. Inclua apenas o que foi fornecido.
- Manter tudo em linha única sempre que possível, separando blocos por ` | `.
- Usar **Leu** para leucócitos totais; diferencial absoluto entre parênteses
  quando disponível: S (segmentados/neutrófilos), M (monócitos), L (linfócitos),
  Eo (eosinófilos), B (basófilos).
- **Reticulócitos** sempre como `Ret X% (valor/mm³)`. Calcular o absoluto quando
  houver % e contagem de hemácias/eritrócitos suficiente.
- **Creatinina** com filtração: `Cr X (DCE: Y)`.
- **Perfil de ferro** na ordem: `Ferritina - FeS - TIBC - TSAT`.
- **Perfil lipídico** na ordem: `CT - HDL - LDL - Tg`.
- Não inventar resultados nem unidades.

## Cálculos derivados

Faça apenas quando os insumos estiverem presentes nos dados fornecidos.

**Reticulócitos absolutos**
`Ret absoluto (/mm³) = Ret(%) / 100 × hemácias (/mm³)`
Apresentar como `Ret X% (valor/mm³)`.

**TSAT (saturação de transferrina)**
`TSAT (%) = (Ferro sérico ÷ TIBC) × 100`
Calcular quando FeS e TIBC estiverem disponíveis.

**LDL por Friedewald**
`LDL = CT − HDL − (Tg ÷ 5)` (mg/dL)
Calcular apenas se CT, HDL e Tg disponíveis **e Tg < 400 mg/dL**. Se Tg ≥ 400,
não calcular e sinalizar “LDL não calculável por Tg elevado”.

**eGFR / DCE**
Se a entrada já trouxer o DCE, reproduzir. Caso contrário, calcular por
**CKD-EPI 2021** (preferencial) usando creatinina, idade e sexo; registrar a
fórmula usada. Cockcroft-Gault pode ser citado se peso disponível e for o
padrão da instituição. Não calcular sem idade/sexo.

## Tendências a destacar (comparando datas)

Quando houver exames prévios, sinalize variações clinicamente relevantes em uma
seção `TENDÊNCIAS`:

- **Queda de Hb** com magnitude/velocidade (sugerir sangramento, hemólise,
  hemodiluição ou supressão medular conforme contexto).
- **Plaquetopenia** progressiva ou súbita; correlacionar com enxertia, consumo,
  microangiopatia (TMA), DECH, fármacos.
- **Neutrófilos:** documentar enxertia (≥ 500/mm³ por 3 dias) ou queda para
  faixa de neutropenia (< 500, < 100 = grave).
- **Ascensão de Cr / queda de eGFR** (nefrotoxicidade de calcineurínicos,
  anfotericina, contraste, SOS/VOD, pré-renal).
- **LDH** em elevação (hemólise, TMA, lise, atividade de doença).
- **PCR / ferritina** em ascensão (infecção, inflamação, SAM/HLH).
- **Bilirrubinas / transaminases / FA-GGT** (DECH hepática, SOS/VOD, toxicidade,
  colestase, sepse).
- **Eletrólitos** críticos (K, Mg, P) — relevante em síndrome de lise e
  refeeding.

Apresente a tendência de forma objetiva: parâmetro, sentido, magnitude e
hipótese(s) a considerar — sem afirmar causalidade quando os dados não permitem.
