---
title: méthode to_printer
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 60
url: /fr/aspose.cells.rendering/sheetrender/to_printer/
is_root: false
---
##  to_printer(self, printer_name) {#str}
Rendre la feuille de calcul à l'imprimante



```python

def to_printer(self, printer_name):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| printer_name | str | le nom de l'imprimante, par exemple : « Microsoft Office Document Image Writer »|


##  to_printer(self, printer_settings) {#aspose.pydrawing.printing.PrinterSettings}
Rendre la feuille de calcul à l'imprimante



```python

def to_printer(self, printer_settings):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| printer_settings | aspose.pydrawing.printing.PrinterSettings | les paramètres de l'imprimante, par exemple PrinterName, Duplex|


##  to_printer(self, printer_name, job_name) {#str-str}
Rendre la feuille de calcul à l'imprimante



```python

def to_printer(self, printer_name, job_name):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| printer_name | str | le nom de l'imprimante, par exemple : « Microsoft Office Document Image Writer »|
| job_name | str | définir le nom du travail d'impression|


##  to_printer(self, printer_settings, job_name) {#aspose.pydrawing.printing.PrinterSettings-str}
Rendre la feuille de calcul à l'imprimante



```python

def to_printer(self, printer_settings, job_name):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| printer_settings | aspose.pydrawing.printing.PrinterSettings | les paramètres de l'imprimante, par exemple PrinterName, Duplex|
| job_name | str | définir le nom du travail d'impression|


##  to_printer(self, printer_name, print_page_index, print_page_count) {#str-int-int}
Rendre la feuille de calcul à l'imprimante



```python

def to_printer(self, printer_name, print_page_index, print_page_count):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| printer_name | str | le nom de l'imprimante, par exemple : « Microsoft Office Document Image Writer »|
| print_page_index | int | l'index de base 0 de la première page à imprimer, il doit être dans la plage [0, SheetRender.PageCount-1]|
| print_page_count | int | le nombre de pages à imprimer, il doit être supérieur à zéro|
###  Remarques

REMARQUE : cette méthode est désormais obsolète.
À la place, utilisez ToPrinter(string PrinterName) et ImageOrPrintOptions.PageIndex, PageCount pour définir la première page et le nombre de pages à imprimer.
 Cette propriété sera supprimée 12 mois plus tard soit décembre 2021.
Aspose s'excuse pour tout inconvénient que vous avez pu rencontrer.


###  Voir également
* module [`aspose.cells.rendering`](../../)
* classe [`SheetRender`](/cells/python-net/fr/aspose.cells.rendering/sheetrender)
