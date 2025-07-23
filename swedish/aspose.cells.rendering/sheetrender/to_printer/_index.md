---
title: to_printer metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 60
url: /sv/aspose.cells.rendering/sheetrender/to_printer/
is_root: false
---
##  to_printer(self, printer_name) {#str}
Rendera kalkylblad till skrivare



```python

def to_printer(self, printer_name):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| printer_name | str | skrivarens namn, till exempel: "Microsoft Office Document Image Writer"|


##  to_printer(self, printer_settings) {#aspose.pydrawing.printing.PrinterSettings}
Rendera kalkylblad till skrivare



```python

def to_printer(self, printer_settings):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| printer_settings | aspose.pydrawing.printing.PrinterSettings | skrivarens inställningar, t.ex. skrivarnamn, duplex|


##  to_printer(self, printer_name, job_name) {#str-str}
Rendera kalkylblad till skrivare



```python

def to_printer(self, printer_name, job_name):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| printer_name | str | skrivarens namn, till exempel: "Microsoft Office Document Image Writer"|
| job_name | str | ange utskriftsjobbets namn|


##  to_printer(self, printer_settings, job_name) {#aspose.pydrawing.printing.PrinterSettings-str}
Rendera kalkylblad till skrivare



```python

def to_printer(self, printer_settings, job_name):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| printer_settings | aspose.pydrawing.printing.PrinterSettings | skrivarens inställningar, t.ex. skrivarnamn, duplex|
| job_name | str | ange utskriftsjobbets namn|


##  to_printer(self, printer_name, print_page_index, print_page_count) {#str-int-int}
Rendera kalkylblad till skrivare



```python

def to_printer(self, printer_name, print_page_index, print_page_count):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| printer_name | str | skrivarens namn, till exempel: "Microsoft Office Document Image Writer"|
| print_page_index | int | det 0-baserade indexet för den första sidan som ska skrivas ut, det måste vara inom intervallet [0, SheetRender.PageCount-1]|
| print_page_count | int | antalet sidor som ska skrivas ut måste vara större än noll|
###  Anmärkningar

OBS: Den här metoden är nu föråldrad.
Använd istället ToPrinter(string PrinterName) och ImageOrPrintOptions.PageIndex, PageCount för att ange den första sidan och antalet sidor som ska skrivas ut.
 Den här egenskapen kommer att tas bort 12 månader senare från och med december 2021.
Aspose ber om ursäkt för eventuella besvär du kan ha upplevt.


###  Se även
* modul [`aspose.cells.rendering`](../../)
* klass [`SheetRender`](/cells/python-net/sv/aspose.cells.rendering/sheetrender)
