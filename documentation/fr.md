<!-- ELUCENIA technical documentation · contagem-absoluta-de-neutrofilos · fr · no clinical/professional/rights approval -->

# Nombre absolu de neutrophiles

[conditions, sources et autorisations](https://elucenia.org/fr/outils/contagem-absoluta-de-neutrofilos)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Numération totale des leucocytes

`leuco`

/µL · intervalle: 10–500000

### Neutrophiles segmentés

`seg`

% · intervalle: 0–100

### Neutrophiles non segmentés (facultatif)

`bast`

% · facultatif · intervalle: 0–100

## Édition de la méthode

PNN absolus : leucocytes×(segmentés+bandes)/100 ; contexte IDSA mise à jour 2010/publication 2011

## Formule documentée

PNN absolus = leucocytes (/µL) × (neutrophiles segmentés % + neutrophiles non segmentés %) ÷ 100.

## Limites et population

La référence IDSA 2010/2011 traite de la fièvre et de la neutropénie induite par la chimiothérapie chez les patients atteints de cancer, avec une stratification dépendant des signes et symptômes, du cancer, du traitement et des comorbidités. La valeur calculée du compte absolu ne remplace pas cette évaluation. Les seuils et unités de la définition doivent être vérifiés dans la recommandation intégrale ; le résumé lu ne les présente pas.

## Références

- [Freifeld AG et al. Clinical practice guideline for the use of antimicrobial agents in neutropenic patients with cancer: 2010 update by the Infectious Diseases Society of America. Clin Infect Dis, 2011.](https://doi.org/10.1093/cid/cir073)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Résultats documentés

Les informations ci-dessous conservent les sorties de la méthode pour des exemples synthétiques. Elles ne constituent pas une validation clinique indépendante.

### 1

Sans neutropénie

| Détails du résultat | |
| --- | --- |
| Neutrophiles (segmentés + bâtonnets) | 60,0% |


### 2

Neutropénie modérée (500 à 999/µL)

| Détails du résultat | |
| --- | --- |
| Neutrophiles (segmentés + bâtonnets) | 45,0% |


### 3

Neutropénie modérée (500 à 999/µL)

| Détails du résultat | |
| --- | --- |
| Neutrophiles (segmentés + bâtonnets) | 25,0% |


### 4

Neutropénie profonde (< 100/µL)

| Détails du résultat | |
| --- | --- |
| Neutrophiles (segmentés + bâtonnets) | 10,0% |

En cas de fièvre (≥ 38,3 °C ou ≥ 38,0 °C pendant 1 h), il s’agit d’une neutropénie fébrile : antibiotique empirique dans un délai d’1 heure.

