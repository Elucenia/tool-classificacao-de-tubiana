<!-- ELUCENIA technical documentation · classificacao-de-tubiana · pt-BR · no clinical/professional/rights approval -->

# Classificação de Tubiana (Dupuytren)

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/classificacao-de-tubiana)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Déficit de extensão da MCF (metacarpofalângica)

`mcf`

graus · intervalo: 0–120

### Déficit de extensão da IFP (interfalângica proximal)

`ifp`

graus · intervalo: 0–130

### Déficit de extensão da IFD (ou hiperextensão)

`ifd`

graus · intervalo: 0–100

### Há nódulo ou corda palpável?

`nodulo`

- `0` — Não
- `1` — Sim

## Edição do método

Tubiana 1986:déficit total deextensão, classes 0/N/I–IV, cortes 45/90/135 graus

## Fórmula documentada

Déficit total do raio = déficit de extensão da MCF + IFP + IFD (a hiperextensão da IFD entra como déficit). Estádios: 0 sem lesão; N nódulo sem contratura; 1 até 45°; 2 de 45 a 90°; 3 de 90 a 135°; 4 acima de 135°.

## Limites e população

A classificação Tubiana 1986 descreve deformidades de Dupuytren por raio e prevê informações complementares sobre polegar, primeiro espaço interdigital, pele e rigidez pós-operatória. O total de déficit de extensão isolado não reproduz essa avaliação completa. Cortes e convenções da versão usada precisam ser conferidos no artigo integral.

## Referências

- [Tubiana R. Evaluation des déformations dans la maladie de Dupuytren (Evaluation of deformities in Dupuytren disease). Ann Chir Main, 1986.](https://doi.org/10.1016/s0753-9053(86)80043-6)

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

## Resultados documentados

As informações abaixo preservam as saídas do método para exemplos sintéticos. Não constituem validação clínica independente.

### 1

Estádio 1: déficit total de 0 a 45°

| Detalhes do resultado | |
| --- | --- |
| Déficit total de extensão | 30° |

Contratura da MCF ≥ 30° ou qualquer contratura da IFP: indicação clássica de tratamento (critério de Hueston).


### 2

Estádio 2: déficit total de 45 a 90°

| Detalhes do resultado | |
| --- | --- |
| Déficit total de extensão | 90° |

Contratura da MCF ≥ 30° ou qualquer contratura da IFP: indicação clássica de tratamento (critério de Hueston).


### 3

Estádio 4: déficit total acima de 135°

| Detalhes do resultado | |
| --- | --- |
| Déficit total de extensão | 150° |

Contratura da MCF ≥ 30° ou qualquer contratura da IFP: indicação clássica de tratamento (critério de Hueston).


### 4

Estádio N: nódulo ou corda sem contratura

| Detalhes do resultado | |
| --- | --- |
| Déficit total de extensão | 0° |

