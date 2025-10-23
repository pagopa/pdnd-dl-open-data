# pdnd-dl-open-data
Questa repository raccoglie i dati open delle dashboard pubbliche dei prodotti di PagoPA S.p.A., organizzati per prodotto.

## Struttura della repository

La repository è suddivisa in directory principali, ciascuna relativa a un prodotto:

- **io/**  
	Dati e metadati relativi all’App IO.
- **pagopa/**  
	Dati e metadati relativi alla piattaforma pagoPA.
- **send/**  
	Dati e metadati relativi al Servizio Notifiche Digitali (SEND).

All’interno di ciascuna directory prodotto sono presenti le seguenti sottocartelle:

- **data/**  
	Contiene i file di dati in formato CSV, JSON e la relativa documentazione in Markdown (`.md`).

- **metadata/**  
	Contiene i metadati utile alla costruzione del catalogo, in formato RDF.

- **CHANGELOG.md**  
	File che traccia le modifiche apportate ai dati e alla documentazione.

## Esempio di struttura

```
io/
	CHANGELOG.md
	data/
		...
	metadata/
		opendata.rdf
pagopa/
	CHANGELOG.md
	data/
		...
	metadata/
        opendata.rdf
send/
	CHANGELOG.md
	data/
		...
	metadata/
        opendata.rdf
LICENSE
README.md
```

## Licenza

I dati sono rilasciati con licenza [CC0 1.0 Universal](LICENSE), che ne consente il libero utilizzo.

---
Per maggiori informazioni sui singoli dataset, consultare la documentazione `.md` presente in ciascuna cartella `data/`.
