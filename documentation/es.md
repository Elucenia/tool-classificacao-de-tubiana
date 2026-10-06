<!-- ELUCENIA technical documentation · classificacao-de-tubiana · es · no clinical/professional/rights approval -->

# Clasificación de Tubiana (Dupuytren)

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/classificacao-de-tubiana)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Déficit de extensión de la metacarpofalángica

`mcf`

grados · intervalo: 0–120

### Déficit de extensión de la interfalángica proximal

`ifp`

grados · intervalo: 0–130

### Déficit de extensión de la interfalángica distal (o hiperextensión)

`ifd`

grados · intervalo: 0–100

### ¿Hay un nódulo o cordón palpable?

`nodulo`

- `0` — No
- `1` — Sí

## Edición del método

Tubiana 1986: déficit total de extensión, clases 0/N/I–IV, cortes 45/90/135 grados

## Fórmula documentada

Déficit total del rayo = déficit de extensión MCF + IFP + IFD (la hiperextensión IFD cuenta como déficit). Estadios: 0 sin lesión; N nódulo sin contractura; 1 hasta 45°; 2 45–90°; 3 90–135°; 4 más de 135°.

## Límites y población

La clasificación Tubiana 1986 describe las deformidades de Dupuytren por rayo y contempla información complementaria sobre el pulgar, el primer espacio interdigital, la piel y la rigidez posoperatoria. El déficit total de extensión aislado no reproduce esta evaluación completa. Los puntos de corte y las convenciones de la versión utilizada deben comprobarse en el artículo completo.

## Referencias

- [Tubiana R. Evaluation des déformations dans la maladie de Dupuytren (Evaluation of deformities in Dupuytren disease). Ann Chir Main, 1986.](https://doi.org/10.1016/s0753-9053(86)80043-6)

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

## Resultados documentados

La información siguiente conserva las salidas del método para ejemplos sintéticos. No constituye una validación clínica independiente.

### 1

Estadio 1: déficit total de 0 a 45°

| Detalles del resultado | |
| --- | --- |
| Déficit total de extensión | 30° |

Contractura de la MCF ≥ 30° o cualquier contractura de la IFP: indicación clásica de tratamiento (criterio de Hueston).


### 2

Estadio 2: déficit total de 45 a 90°

| Detalles del resultado | |
| --- | --- |
| Déficit total de extensión | 90° |

Contractura de la MCF ≥ 30° o cualquier contractura de la IFP: indicación clásica de tratamiento (criterio de Hueston).


### 3

Estadio 4: déficit total por encima de 135°

| Detalles del resultado | |
| --- | --- |
| Déficit total de extensión | 150° |

Contractura de la MCF ≥ 30° o cualquier contractura de la IFP: indicación clásica de tratamiento (criterio de Hueston).


### 4

Estadio N: nódulo o cuerda sin contractura

| Detalles del resultado | |
| --- | --- |
| Déficit total de extensión | 0° |

