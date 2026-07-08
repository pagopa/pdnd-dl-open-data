
# Categorie di enti su SEND che inviano notifiche

Il file riporta il numero di notifiche SEND (Servizio Notifiche Digitali) inviate per categorie di enti. Il dato è sugli ultimi 3 anni, e con un valore complessivo su tutto lo storico.

## Aggiornamento dati

- Quotidiano, alle 11:00 (UTC).

## Formato dati

**Reference file:**

- notifiche_per_categoria.csv<br>

| Campo                 | Tipo di dati | Descrizione                               | Formato |
| -----------------     | ------------ | ----------------------------------------- | ------- |
| anno                  | string       | Anno di notifica                          | YYYY    |
| categoria             | string       | Categoria ente mittente                   |         |
| notifiche_inviate     | integer      | Numero di notifiche totali inviate        |         |
| ranking               | integer      | Ranking                                   | [1;10]  |

Questi dati sono disponibili anche in formato json.