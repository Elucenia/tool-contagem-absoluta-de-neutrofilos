<!-- ELUCENIA technical documentation · contagem-absoluta-de-neutrofilos · pt-BR · no clinical/professional/rights approval -->

# Contagem absoluta de neutrófilos

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/contagem-absoluta-de-neutrofilos)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Leucócitos totais

`leuco`

/µL · intervalo: 10–500000

### Segmentados

`seg`

% · intervalo: 0–100

### Bastões (opcional)

`bast`

% · opcional · intervalo: 0–100

## Edição do método

CAN:leucócitos×(segmentados+bastões)/100; contexto IDSA atualização 2010/publicação 2011

## Fórmula documentada

CAN = leucócitos (/µL) × (segmentados % + bastões %) ÷ 100.

## Limites e população

A referência IDSA 2010/2011 aborda febre e neutropenia induzida por quimioterapia em pacientes com câncer, com estratificação dependente de sinais/sintomas, câncer, terapia e comorbidades. O valor calculado da contagem absoluta não substitui essa avaliação. Os limiares e unidades da definição devem ser conferidos no guideline integral; o resumo lido não os apresenta.

## Referências

- [Freifeld AG et al. Clinical practice guideline for the use of antimicrobial agents in neutropenic patients with cancer: 2010 update by the Infectious Diseases Society of America. Clin Infect Dis, 2011.](https://doi.org/10.1093/cid/cir073)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
