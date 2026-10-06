<!-- ELUCENIA technical documentation · contagem-absoluta-de-neutrofilos · en · no clinical/professional/rights approval -->

# Absolute neutrophil count

[conditions, sources and permissions](https://elucenia.org/en/tools/contagem-absoluta-de-neutrofilos)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Total white blood cell count

`leuco`

/µL · range: 10–500000

### Segmented neutrophils

`seg`

% · range: 0–100

### Band neutrophils (optional)

`bast`

% · optional · range: 0–100

## Method edition

ANC: leukocytes×(segmented+bands)/100; IDSA 2010 update/published 2011 context

## Documented formula

ANC = leukocytes (/µL) × (segmented neutrophils % + band neutrophils %) ÷ 100.

## Limits and population

The IDSA 2010/2011 reference addresses fever and chemotherapy-induced neutropenia in patients with cancer, with stratification depending on signs/symptoms, cancer, therapy and comorbidities. The calculated absolute count does not replace that assessment. The definition’s thresholds and units must be checked in the full guideline; the abstract read does not provide them.

## References

- [Freifeld AG et al. Clinical practice guideline for the use of antimicrobial agents in neutropenic patients with cancer: 2010 update by the Infectious Diseases Society of America. Clin Infect Dis, 2011.](https://doi.org/10.1093/cid/cir073)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Documented results

The information below preserves the method outputs for synthetic examples. It does not constitute independent clinical validation.

### 1

No neutropenia

| Result details | |
| --- | --- |
| Neutrophils (segmented + bands) | 60.0% |


### 2

Moderate neutropenia (500 to 999/µL)

| Result details | |
| --- | --- |
| Neutrophils (segmented + bands) | 45.0% |


### 3

Moderate neutropenia (500 to 999/µL)

| Result details | |
| --- | --- |
| Neutrophils (segmented + bands) | 25.0% |


### 4

Profound neutropenia (< 100/µL)

| Result details | |
| --- | --- |
| Neutrophils (segmented + bands) | 10.0% |

With fever (≥ 38,3 °C or ≥ 38,0 °C for 1 h), it is febrile neutropenia: empirical antibiotic within 1 hour.

