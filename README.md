# Macro Research Brazil

Repositório de treino semanal de análise macroeconômica aplicada ao Brasil. O objetivo é transformar dados, notícias e decisões de política econômica em hipóteses condicionais, cadeias causais, cenários e implicações para os mercados.

## Gabarito de agosto de 2026

| Data | Caso | Questão central | Status em 03/09/2026 |
| --- | --- | --- | --- |
| 07/08 | Copom reduz a Selic para 14,00% | A comunicação foi mais importante que o corte esperado? | Em acompanhamento |
| 14/08 | IPCA de julho + ata do Copom | A desinflação é disseminada e persistente? | Em acompanhamento |
| 21/08 | IBC-Br de junho | A atividade está desacelerando o suficiente para aliviar a inflação? | Parcialmente confirmado |
| 28/08 | Novo Caged de julho | O emprego formal confirma a desaceleração da demanda? | Inconclusivo |

As quatro análises são **respostas-modelo**. Apenas a hipótese da primeira semana havia sido redigida anteriormente pelo assistente “como se fosse o aluno”; nas demais semanas não houve resposta original de Lucas. Por isso, nenhum trecho deste gabarito deve ser apresentado como raciocínio autoral sem ser refeito, discutido e validado por ele.

## Estrutura

```text
macro-research-brazil/
├── README.md
├── template/
│   └── analise-semanal.md
├── analises/
│   └── 2026/
│       ├── 2026-08-07-copom-selic-14-comunicacao/
│       ├── 2026-08-14-ipca-desinflacao-copom-cautela/
│       ├── 2026-08-21-ibc-br-desaceleracao-atividade/
│       └── 2026-08-28-caged-desaceleracao-emprego/
├── revisoes/
│   └── acompanhamento-de-cenarios.md
└── dados/
    ├── README.md
    └── 2026-08-eventos-macro.csv
```

Cada pasta semanal contém:

- `analise.md`: gabarito completo com hipótese, mecanismos, modelos, cenários, ativos, riscos e controle da previsão;
- `fontes.md`: fontes oficiais e jornalísticas utilizadas, com a função de cada uma.

## Método de estudo

1. Leia somente o contexto e os dados observados.
2. Responda, em até 15 minutos: choque, classificação, persistência e hipótese inicial.
3. Construa a cadeia causal e os três cenários em até 15 minutos.
4. Compare sua resposta com o gabarito, procurando variáveis esquecidas e elos frágeis.
5. Reescreva a conclusão em linguagem condicional e atualize o controle da previsão.

Tempo-alvo: **30 a 45 minutos** por análise. O gabarito deve servir como régua de qualidade, não como texto para memorização.

## Convenções

- **Fato:** dado observado ou informação documentada.
- **Hipótese:** interpretação ainda sujeita a teste.
- **Mecanismo:** canal que liga causa e efeito.
- **Previsão:** resultado esperado sob condições explícitas.
- **Risco:** evento que pode invalidar a hipótese.
- **Opinião:** julgamento não demonstrado pelos dados.

## Política de dados e fontes

São usados apenas dados públicos, rastreáveis e reproduzíveis. Fontes oficiais têm prioridade para fatos; a Reuters é usada principalmente para expectativas de consenso, reação de economistas e contexto de mercado. A data de corte desta versão é **3 de setembro de 2026**.

## Uso em portfólio

Uma análise só deve migrar do gabarito para o portfólio autoral depois que Lucas:

1. refizer a hipótese inicial sem consultar a resposta-modelo;
2. justificar pelo menos dois elos da cadeia causal;
3. escolher indicadores que possam invalidar sua tese;
4. atualizar o cenário com dados posteriores;
5. escrever a conclusão final com suas próprias palavras.


