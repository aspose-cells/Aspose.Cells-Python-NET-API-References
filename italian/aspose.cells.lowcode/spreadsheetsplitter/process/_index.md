---
title: Metodo process
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 20
url: /it/aspose.cells.lowcode/spreadsheetsplitter/process/
is_root: false
---
##  process(, opzioni){#aspose.cells.lowcode.LowCodeSplitOptions}
Divide il file del foglio di calcolo in più parti.



```python

@staticmethod
def process(options):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| options | [`LowCodeSplitOptions`](/cells/python-net/it/aspose.cells.lowcode/lowcodesplitoptions) | Opzioni per la divisione del foglio di calcolo|


##  process(, file_modello, file_risultato){#str-str}
Divide il file modello specificato in più parti.



```python

@staticmethod
def process(template_file, result_file):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| template_file | str | Il file modello da dividere|
| result_file | str | Il file risultante (modello di nome)|
###  Osservazioni

file di output verranno creati dal file risultante specificato da
aggiungendo il numero di sequenza del foglio e della parte divisa.
Ad esempio, se il file di output specificato è Split.xlsx, il file generato
i file saranno Split_0_0.xlsx, Split_0_1.xlsx, ..., Split_1_0.xlsx, ...


###  Guarda anche
* modulo [`aspose.cells.lowcode`](../../)
* classe [`SpreadsheetSplitter`](/cells/python-net/it/aspose.cells.lowcode/spreadsheetsplitter)
