<!-- ELUCENIA technical documentation · contagem-absoluta-de-neutrofilos · es · no clinical/professional/rights approval -->

# Recuento absoluto de neutrófilos

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/contagem-absoluta-de-neutrofilos)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Recuento total de leucocitos

`leuco`

/µL · intervalo: 10–500000

### Neutrófilos segmentados

`seg`

% · intervalo: 0–100

### Neutrófilos en banda (opcional)

`bast`

% · opcional · intervalo: 0–100

## Edición del método

RAN: leucocitos×(segmentados+bandas)/100; contexto IDSA actualización 2010/publicación 2011

## Fórmula documentada

RAN = leucocitos (/µL) × (neutrófilos segmentados % + neutrófilos en banda %) ÷ 100.

## Límites y población

La referencia IDSA 2010/2011 aborda la fiebre y la neutropenia inducida por quimioterapia en pacientes con cáncer, con una estratificación dependiente de signos/síntomas, cáncer, tratamiento y comorbilidades. El valor calculado del recuento absoluto no sustituye esta evaluación. Los umbrales y las unidades de la definición deben comprobarse en la guía completa; el resumen leído no los presenta.

## Referencias

- [Freifeld AG et al. Clinical practice guideline for the use of antimicrobial agents in neutropenic patients with cancer: 2010 update by the Infectious Diseases Society of America. Clin Infect Dis, 2011.](https://doi.org/10.1093/cid/cir073)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
