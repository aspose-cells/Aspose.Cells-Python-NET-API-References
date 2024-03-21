---
title: to_printer metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 60
url: /sv/aspose.cells.rendering/sheetrender/to_printer/
is_root: false
---
##  to_printer {#str}
Återge arbetsbladet till skrivaren



```python
def to_printer(self, printer_name):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| printer_name | str | namnet på skrivaren , till exempel: "Microsoft Office Document Image Writer"|


##  to_printer {#aspose.pydrawing.printing.PrinterSettings}
Återge arbetsbladet till skrivaren



```python
def to_printer(self, printer_settings):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| printer_settings | aspose.pydrawing.printing.PrinterSettings | skrivarens inställningar, t.ex. Skrivarnamn, Duplex|


##  to_printer {#str-str}
Återge arbetsbladet till skrivaren



```python
def to_printer(self, printer_name, job_name):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| printer_name | str | namnet på skrivaren , till exempel: "Microsoft Office Document Image Writer"|
| job_name | str | ställ in utskriftsjobbets namn|


##  to_printer {#aspose.pydrawing.printing.PrinterSettings-str}
Återge arbetsbladet till skrivaren



```python
def to_printer(self, printer_settings, job_name):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| printer_settings | aspose.pydrawing.printing.PrinterSettings | skrivarens inställningar, t.ex. Skrivarnamn, Duplex|
| job_name | str | ställ in utskriftsjobbets namn|


##  to_printer {#str-int-int}
Återge arbetsbladet till skrivaren



```python
def to_printer(self, printer_name, print_page_index, print_page_count):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| printer_name | str | namnet på skrivaren , till exempel: "Microsoft Office Document Image Writer"|
| print_page_index | int | det 0-baserade indexet för den första sidan som ska skrivas ut, det måste vara inom området [0, SheetRender.PageCount-1]|
| print_page_count | int | antalet sidor som ska skrivas ut måste det vara större än noll|
###  Anmärkningar

OBS: Denna metod är nu föråldrad.
Använd istället ToPrinter(string PrinterName) och ImageOrPrintOptions.PageIndex, PageCount för att ställa in den första sidan och antalet sidor som ska skrivas ut.
 Den här egenskapen kommer att tas bort 12 månader senare sedan december 2021.
Aspose ber om ursäkt för eventuella besvär du kan ha upplevt.


###  Se även
* modul [`aspose.cells.rendering`](../../)
* klass [`SheetRender`](/cells/python-net/sv/aspose.cells.rendering/sheetrender)
