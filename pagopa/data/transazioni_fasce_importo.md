# Transazioni per fascia di importo

Il file riporta il numero di transazioni registrate sulla piattaforma pagoPA, per anno (ultimi 3 anni) e dall'inizio di attività della piattaforma ("Complessivo"), ovvero l'anno 2016. Il numero di transazioni è suddiviso ciascuna categoria di ente creditore e complessivamente per tutte le categorie ("Tutte") e per fascia di importo:
* da 0€ a 25€
* da 26€ a 50€
* da 51 a 100€
* da 101€ a 200€
* da 201€ a 500€
* da 501€ a 1000€
* superiore a 1000€

Vengono mostrati casi in cui il numero di transazioni registrate superi le 5 transazioni.

## Aggiornamento dati

- Quotidiano, alle 8:30 (UTC).

## Formato dati

**Reference file:**

- transazioni_fasce_importo.csv<br>

| Campo               | Tipo di dati  | Descrizione                 | Formato |
| ------------------- | ------------  | ------------------------    | ------- |
| anno                | string        | Anno delle transazioni      | YYYY    |
| categoria           | string        | Categoria di ente creditore |         |
| fascia_importo      | string        | Fascia di importo in euro   |         |
| numero_transazioni  | integer       | Numero di transazioni       |         |

Questi dati sono disponibili anche in formato json.