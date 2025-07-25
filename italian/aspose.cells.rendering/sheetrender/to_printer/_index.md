---
title: Metodo to_printer
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 60
url: /it/aspose.cells.rendering/sheetrender/to_printer/
is_root: false
---
##  to_printer(self, printer_name) {#str}
Esegui il rendering del foglio di lavoro sulla stampante



```python

def to_printer(self, printer_name):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| printer_name | str | il nome della stampante, ad esempio: "Microsoft Office Document Image Writer"|


##  to_printer(self, printer_settings) {#aspose.pydrawing.printing.PrinterSettings}
Esegui il rendering del foglio di lavoro sulla stampante



```python

def to_printer(self, printer_settings):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| printer_settings | aspose.pydrawing.printing.PrinterSettings | le impostazioni della stampante, ad esempio PrinterName, Duplex|


##  to_printer(self, printer_name, job_name) {#str-str}
Esegui il rendering del foglio di lavoro sulla stampante



```python

def to_printer(self, printer_name, job_name):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| printer_name | str | il nome della stampante, ad esempio: "Microsoft Office Document Image Writer"|
| job_name | str | imposta il nome del processo di stampa|


##  to_printer(self, printer_settings, job_name) {#aspose.pydrawing.printing.PrinterSettings-str}
Esegui il rendering del foglio di lavoro sulla stampante



```python

def to_printer(self, printer_settings, job_name):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| printer_settings | aspose.pydrawing.printing.PrinterSettings | le impostazioni della stampante, ad esempio PrinterName, Duplex|
| job_name | str | imposta il nome del processo di stampa|


##  to_printer(self, printer_name, print_page_index, print_page_count) {#str-int-int}
Esegui il rendering del foglio di lavoro sulla stampante



```python

def to_printer(self, printer_name, print_page_index, print_page_count):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| printer_name | str | il nome della stampante, ad esempio: "Microsoft Office Document Image Writer"|
| print_page_index | int | l'indice basato su 0 della prima pagina da stampare, deve essere compreso nell'intervallo [0, SheetRender.PageCount-1]|
| print_page_count | int | il numero di pagine da stampare, deve essere maggiore di zero|
###  Osservazioni

NOTA: questo metodo è ormai obsoleto.
In alternativa, utilizzare ToPrinter(string PrinterName) e ImageOrPrintOptions.PageIndex, PageCount per impostare la prima pagina e il numero di pagine da stampare.
 Questa proprietà verrà rimossa 12 mesi dopo, a partire da dicembre 2021.
Aspose si scusa per ogni eventuale disagio arrecato.


###  Guarda anche
* modulo [`aspose.cells.rendering`](../../)
* classe [`SheetRender`](/cells/python-net/it/aspose.cells.rendering/sheetrender)
