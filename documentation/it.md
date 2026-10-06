<!-- ELUCENIA technical documentation · contagem-absoluta-de-neutrofilos · it · no clinical/professional/rights approval -->

# Conta assoluta dei neutrofili

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/contagem-absoluta-de-neutrofilos)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Conta totale dei leucociti

`leuco`

/µL · intervallo: 10–500000

### Neutrofili segmentati

`seg`

% · intervallo: 0–100

### Neutrofili a banda (facoltativo)

`bast`

% · facoltativo · intervallo: 0–100

## Edizione del metodo

ANC: leucociti×(segmentati+bande)/100; contesto IDSA aggiornamento 2010/pubblicazione 2011

## Formula documentata

Conta assoluta dei neutrofili = leucociti (/µL) × (neutrofili segmentati % + neutrofili a banda %) ÷ 100.

## Limiti e popolazione

La fonte IDSA 2010/2011 tratta febbre e neutropenia indotta da chemioterapia nei pazienti con tumore, con stratificazione dipendente da segni/sintomi, tumore, terapia e comorbilità. Il valore calcolato della conta assoluta non sostituisce questa valutazione. Le soglie e le unità della definizione devono essere verificate nella linea guida completa; l’abstract letto non le riporta.

## Riferimenti

- [Freifeld AG et al. Clinical practice guideline for the use of antimicrobial agents in neutropenic patients with cancer: 2010 update by the Infectious Diseases Society of America. Clin Infect Dis, 2011.](https://doi.org/10.1093/cid/cir073)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Risultati documentati

Le informazioni seguenti conservano gli output del metodo per esempi sintetici. Non costituiscono una validazione clinica indipendente.

### 1

Senza neutropenia

| Dettagli del risultato | |
| --- | --- |
| Neutrofili (segmentati + bastoncelli) | 60,0% |


### 2

Neutropenia moderata (500 a 999/µL)

| Dettagli del risultato | |
| --- | --- |
| Neutrofili (segmentati + bastoncelli) | 45,0% |


### 3

Neutropenia moderata (500 a 999/µL)

| Dettagli del risultato | |
| --- | --- |
| Neutrofili (segmentati + bastoncelli) | 25,0% |


### 4

Neutropenia profonda (< 100/µL)

| Dettagli del risultato | |
| --- | --- |
| Neutrofili (segmentati + bastoncelli) | 10,0% |

Con febbre (≥ 38,3 °C o ≥ 38,0 °C per 1 h), è neutropenia febbrile: antibiotico empirico entro 1 ora.

