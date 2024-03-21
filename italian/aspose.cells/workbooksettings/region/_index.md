---
title: region proprietà
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 400
url: /it/aspose.cells/workbooksettings/region/
is_root: false
---
##  region proprietà

Ottiene o imposta le impostazioni internazionali per la cartella di lavoro.

###  Osservazioni

1. Impostazioni regionali utilizzate dal componente Aspose.Cells per una cartella di lavoro caricata dal file modello:
io). Per un file XLS, ci sono campi definiti per le impostazioni regionali e MS Excel salva i dati delle impostazioni regionali nel file quando si salva il file XLS.
Pertanto, utilizziamo lo region salvato nel file modello per la cartella di lavoro.
Se non desideri utilizzare region salvato nel file XLS, reimpostalo su quello previsto (ad esempio CountryCode.Default) dopo aver caricato il file modello.
Inoltre, salviamo nel file anche il valore specificato dall'utente (con questo metodo) quando salviamo un file XLS.
ii). Per altri formati di file, come XLSX, XLSB...ecc., non esiste un campo definito per le impostazioni regionali nella specifica del formato file.
Pertanto, utilizziamo le impostazioni regionali dell'ambiente dell'applicazione per la cartella di lavoro.
Inoltre, il valore specificato dall'utente (con questo metodo) non può essere mantenuto per i file generati con tali formati di file.
2. Per l'effetto vista in MS Excel:
Le impostazioni regionali applicate qui possono avere effetto solo in fase di runtime con il componente Aspose.Cells e non durante la visualizzazione del file generato con MS Excel.
Anche per il file XLS generato in cui sono stati salvati i dati delle impostazioni regionali specificate, quando lo si visualizza/modifica con MS Excel,
lo region utilizzato per eseguire la formattazione da MS Excel è sempre l'impostazione regionale predefinita dell'ambiente in cui è in esecuzione MS Excel,
non quello salvato nel file. È il comportamento di MS Excel e non può essere modificato dal codice.
###  Definizione:
```python
@property
def region(self):
    ...
@region.setter
def region(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`CountryCode`](/cells/python-net/it/aspose.cells/countrycode)
* classe [`WorkbookSettings`](/cells/python-net/it/aspose.cells/workbooksettings)
