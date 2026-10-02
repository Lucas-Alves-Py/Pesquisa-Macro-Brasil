# Dados públicos e reproduzíveis

Esta pasta contém somente recortes pequenos usados nas análises. O arquivo `2026-08-eventos-macro.csv` registra resultados, consensos e surpresas. Ele não substitui as bases originais.

## Fontes primárias

- **Selic e comunicados:** Banco Central do Brasil — histórico e comunicados do Copom.
- **IPCA:** IBGE — release do IPCA de julho de 2026.
- **IBC-Br:** BCB/Depec — série SGS 24364, com ajuste sazonal.
- **Emprego formal:** Ministério do Trabalho e Emprego — Novo Caged de julho de 2026.
- **Desemprego:** IBGE — PNAD Contínua, trimestre encerrado em julho de 2026.

## Reprodução do IBC-Br

A série pode ser consultada em JSON pela API do Banco Central:

```text
https://api.bcb.gov.br/dados/serie/bcdata.sgs.24364/dados?formato=json&dataInicial=01/01/2026&dataFinal=30/06/2026
```

O valor do índice passou de **110,93102 em maio** para **110,22154 em junho de 2026**, variação aproximada de **-0,64%** após ajuste sazonal.

## Observação metodológica

O consenso de mercado não é um dado oficial. Ele foi obtido das pesquisas da Reuters citadas nos respectivos `fontes.md`. Revisões de séries, especialmente IBC-Br e Caged, devem ser registradas sem apagar o valor conhecido na data original da análise.

