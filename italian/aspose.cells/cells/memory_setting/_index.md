---
title: memory_setting proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 1160
url: /it/aspose.cells/cells/memory_setting/
is_root: false
---
##  memory_setting proprietà

Ottiene o imposta l'opzione di utilizzo della memoria per queste celle.

###  Osservazioni

Limiti notevoli e operazioni consigliate per alcune modalità:
| Modalità| Osservazioni| Supportato|
| :- | :- | :- |
|
 per ridurre il costo della memoria. D'altra parte, i dati compatti possono anche
 causare un aumento dei costi di tempo, soprattutto durante l'aggiornamento dei dati delle celle,
 o accedere a celle/righe in modo casuale | v8.0.0 |
|
 Quando questa modalità viene utilizzata per qualsiasi foglio di lavoro in una cartella di lavoro, |
 dovrebbe essere chiamato alla fine del lavoro per rilasciare tutte le risorse come i file temporanei.
            | 
 L'accesso casuale alle celle fornirà scarse prestazioni perché i dati necessitano
 da leggere/aggiornare in modo casuale e ripetuto (quindi il puntatore nel file sarà
modificato di conseguenza e le operazioni di I/O saranno richieste ripetutamente).
 Se possibile, accedi sempre ai dati in sequenza (riga per riga).
            | 
 Quando i dati di una riga/cella vengono modificati, i dati delle altre celle/righe
 può anche essere influenzato (ad esempio i dati possono essere spostati/spostati in altri luoghi)
 per allocare spazi sufficienti per i dati modificati).
 Quindi ogni modifica di ogni dato richiede la sincronizzazione di altri oggetti esistenti (
 come Riga o oggetto Cell).
 Quindi, per ottenere prestazioni migliori, non mantenere più righe/Cells
 allo stesso tempo. Elaborarli uno per uno ridurrà la sincronizzazione dei dati
 per loro in modo che le prestazioni possano essere migliorate un po'.
 | versione 25.7 |
###  Definizione:
```python
@property
def memory_setting(self):
    ...
@memory_setting.setter
def memory_setting(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Cells`](/cells/python-net/it/aspose.cells/cells)
* classe [`MemorySetting`](/cells/python-net/it/aspose.cells/memorysetting)
