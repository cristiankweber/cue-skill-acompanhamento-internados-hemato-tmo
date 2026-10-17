# Modelo de Evolução Clínica (quando solicitado)

Use quando o usuário pedir evolução/resumo de internação completos. Omita campos
sem dados (escreva "não informado" apenas onde for clinicamente relevante).

```
HEMATOLOGIA E TRANSPLANTE DE MEDULA ÓSSEA

IDENTIFICAÇÃO / CONTEXTO DA INTERNAÇÃO:
[motivo da internação, dia de internação]

HISTÓRICO HEMATOLÓGICO:
Diagnóstico de base: [doença, data aproximada, risco]
Tratamentos prévios: [cronológico, com resposta quando disponível]
Status atual da doença: [remissão / ativa / recaída / refratária / investigação]

TRANSPLANTE (se aplicável):
Tipo: [autólogo / alo aparentado / não aparentado / haploidêntico]
Data: [DD/MM/AAAA]  | Dia pós-TMO: [D+X]
Condicionamento: [...]  | Fonte celular: [...]
Profilaxia de DECH: [...]  | Doador/compatibilidade: [...]

PRÉVIO:
Comorbidades / medicações de uso contínuo / alergias / histórico de
sangramento ou trombose.

SUBJETIVO:
[queixas, intercorrências, sintomas infecciosos/GI/cutâneos/respiratórios/
neurológicos, sinais de DECH]

EXAME FÍSICO:
[se fornecido; senão "não informado"]

EXAMES (organizados):
[laudo de linha única — ver organizacao_exames.md]

TENDÊNCIAS:
[variações relevantes entre datas]

⚠️ ALERTAS:
[gatilhos de gravidade, se houver — ver alertas_gravidade.md]

AVALIAÇÃO:
[problemas ativos + interpretação objetiva]

CONDUTAS SUGERIDAS:
[lista objetiva; decisão final do assistente]
```
