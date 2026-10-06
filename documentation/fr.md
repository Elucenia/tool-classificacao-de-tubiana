<!-- ELUCENIA technical documentation · classificacao-de-tubiana · fr · no clinical/professional/rights approval -->

# Classification de Tubiana (Dupuytren)

[conditions, sources et autorisations](https://elucenia.org/fr/outils/classificacao-de-tubiana)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Déficit d’extension de la métacarpophalangienne

`mcf`

degrés · intervalle: 0–120

### Déficit d’extension de l’interphalangienne proximale

`ifp`

degrés · intervalle: 0–130

### Déficit d’extension de l’interphalangienne distale (ou hyperextension)

`ifd`

degrés · intervalle: 0–100

### Existe-t-il un nodule ou un cordon palpable ?

`nodulo`

- `0` — Non
- `1` — Oui

## Édition de la méthode

Tubiana 1986 : déficit total d’extension, classes 0/N/I–IV, seuils 45/90/135 degrés

## Formule documentée

Déficit total du rayon = déficit d’extension MCP + IPP + IPD (l’hyperextension IPD compte comme déficit). Stades : 0 sans lésion; N nodule sans contracture; 1 jusqu’à 45°; 2 45–90°; 3 90–135°; 4 au-delà de 135°.

## Limites et population

La classification Tubiana 1986 décrit les déformations de Dupuytren par rayon et prévoit des informations complémentaires sur le pouce, le premier espace interdigital, la peau et la raideur postopératoire. Le déficit total d’extension seul ne reproduit pas cette évaluation complète. Les seuils et conventions de la version utilisée doivent être vérifiés dans l’article intégral.

## Références

- [Tubiana R. Evaluation des déformations dans la maladie de Dupuytren (Evaluation of deformities in Dupuytren disease). Ann Chir Main, 1986.](https://doi.org/10.1016/s0753-9053(86)80043-6)

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

Stade 1 : déficit total de 0 à 45°

| Détails du résultat | |
| --- | --- |
| Déficit total d’extension | 30° |

Contracture de la MCF ≥ 30° ou toute contracture de l’IPP : indication classique de traitement (critère de Hueston).


### 2

Stade 2 : déficit total de 45 à 90°

| Détails du résultat | |
| --- | --- |
| Déficit total d’extension | 90° |

Contracture de la MCF ≥ 30° ou toute contracture de l’IPP : indication classique de traitement (critère de Hueston).


### 3

Stade 4 : déficit total supérieur à 135°

| Détails du résultat | |
| --- | --- |
| Déficit total d’extension | 150° |

Contracture de la MCF ≥ 30° ou toute contracture de l’IPP : indication classique de traitement (critère de Hueston).


### 4

Stade N : nodule ou corde sans contracture

| Détails du résultat | |
| --- | --- |
| Déficit total d’extension | 0° |

