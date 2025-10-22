# Transazioni, valore economico ed enti creditori 

Il file riporta il numero di transazioni registrate sulla piattaforma pagoPA, per anno (ultimi 3 anni) e dall'inizio di attività della piattaforma ("Complessivo"), ovvero l'anno 2016. Oltre al numero di transazioni si riporta il valore economico ad esse associato e il numero di enti creditori che hanno ricevuto tali transazioni. 

## Aggiornamento dati

- Quotidiano, alle 8:30 (UTC).

## Formato dati

**Reference file:**

- transazioni_riepilogo.csv<br>

| Campo               | Tipo di dati  | Descrizione               | Formato |
| ------------------- | ------------  | ------------------------  | ------- |
| anno                | string        | Anno delle transazioni    | YYYY    |
| numero_transazioni  | integer       | Numero di transazioni     |         |
| importo_totale      | decimal       | Valore economico in euro  |         |
| numero_enti         | integer       | Numero di enti creditori  |         |

Questi dati sono disponibili anche in formato json.