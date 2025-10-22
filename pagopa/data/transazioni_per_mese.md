# Numero di transazioni per mese ed anno

Il file riporta il numero di transazioni registrate sulla piattaforma pagoPA, per anno e mese degli ultimi 3 anni. I dati sono disponibili per ciascuna categoria di ente creditore e complessivamente per tutte le categorie ("Tutte"). Vengono mostrati casi in cui il numero di transazioni registrate superi le 5 transazioni.

## Aggiornamento dati

- Quotidiano, alle 8:30 (UTC).

## Formato dati

**Reference file:**

- transazioni_per_mese.csv<br>

| Campo               | Tipo di dati  | Descrizione                     | Formato |
| ------------------- | ------------  | ----------------------------    | ------- |
| anno_mese           | string        | Anno e mese delle transazioni   | YYYY-MM |
| categoria           | string        | Categoria di ente creditore     |         |
| numero_transazioni  | integer       | Numero di transazioni           |         |

Questi dati sono disponibili anche in formato json.