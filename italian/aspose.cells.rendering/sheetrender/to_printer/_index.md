---
title: Metodo to_printer
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 60
url: /it/aspose.cells.rendering/sheetrender/to_printer/
is_root: false
---
##  to_printer {#str}
Rendering del foglio di lavoro sulla stampante



```python
def to_printer(self, printer_name):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| printer_name | str | il nome della stampante, ad esempio: "Microsoft Office Document Image Writer"|


##  to_printer {#aspose.pydrawing.printing.PrinterSettings}
Rendering del foglio di lavoro sulla stampante



```python
def to_printer(self, printer_settings):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| printer_settings | aspose.pydrawing.printing.PrinterSettings | le impostazioni della stampante, ad esempio NomeStampante, Duplex|


##  to_printer {#str-str}
Rendering del foglio di lavoro sulla stampante



```python
def to_printer(self, printer_name, job_name):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| printer_name | str | il nome della stampante, ad esempio: "Microsoft Office Document Image Writer"|
| job_name | str | impostare il nome del lavoro di stampa|


##  to_printer {#aspose.pydrawing.printing.PrinterSettings-str}
Rendering del foglio di lavoro sulla stampante



```python
def to_printer(self, printer_settings, job_name):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| printer_settings | aspose.pydrawing.printing.PrinterSettings | le impostazioni della stampante, ad esempio NomeStampante, Duplex|
| job_name | str | impostare il nome del lavoro di stampa|


##  to_printer {#str-int-int}
Rendering del foglio di lavoro sulla stampante



```python
def to_printer(self, printer_name, print_page_index, print_page_count):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| printer_name | str | il nome della stampante, ad esempio: "Microsoft Office Document Image Writer"|
| print_page_index | int | l'indice in base 0 della prima pagina da stampare, deve essere compreso nell'intervallo [0, SheetRender.PageCount-1]|
| print_page_count | int | il numero di pagine da stampare, deve essere maggiore di zero|
###  Osservazioni

NOTA: questo metodo è ormai obsoleto.
Utilizzare invece ToPrinter(string PrinterName) e ImageOrPrintOptions.PageIndex, PageCount per impostare la prima pagina e il numero di pagine da stampare.
 Questa proprietà verrà rimossa 12 mesi dopo a partire da dicembre 2021.
Aspose si scusa per eventuali disagi riscontrati.


###  Guarda anche
* modulo [`aspose.cells.rendering`](../../)
* classe [`SheetRender`](/cells/python-net/it/aspose.cells.rendering/sheetrender)
