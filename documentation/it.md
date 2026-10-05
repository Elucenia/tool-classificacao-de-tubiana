<!-- ELUCENIA technical documentation · classificacao-de-tubiana · it · no clinical/professional/rights approval -->

# Classificazione di Tubiana (Dupuytren)

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/classificacao-de-tubiana)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Deficit di estensione della metacarpofalangea

`mcf`

gradi · intervallo: 0–120

### Deficit di estensione dell’interfalangea prossimale

`ifp`

gradi · intervallo: 0–130

### Deficit di estensione dell’interfalangea distale (o iperestensione)

`ifd`

gradi · intervallo: 0–100

### È presente un nodulo o cordone palpabile?

`nodulo`

- `0` — No
- `1` — Sì

## Edizione del metodo

Tubiana 1986: deficit totale di estensione, classi 0/N/I–IV, soglie 45/90/135 gradi

## Formula documentata

Deficit totale del raggio = deficit di estensione MCF + IFP + IFD (l’iperestensione IFD conta come deficit). Stadi: 0 nessuna lesione; N nodulo senza contrattura; 1 fino a 45°; 2 45–90°; 3 90–135°; 4 oltre 135°.

## Limiti e popolazione

La classificazione Tubiana 1986 descrive le deformità di Dupuytren per raggio e prevede informazioni complementari su pollice, primo spazio interdigitale, cute e rigidità postoperatoria. Il deficit totale di estensione da solo non riproduce la valutazione completa. Soglie e convenzioni della versione utilizzata devono essere verificate nell’articolo completo.

## Riferimenti

- [Tubiana R. Evaluation des déformations dans la maladie de Dupuytren (Evaluation of deformities in Dupuytren disease). Ann Chir Main, 1986.](https://doi.org/10.1016/s0753-9053(86)80043-6)

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
