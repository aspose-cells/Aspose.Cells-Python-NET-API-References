---
title: import_excel_file metod
second_title: Aspose.Cells.GridJs for Python via .NET API Referenser
description:
type: docs
weight: 110
url: /sv/aspose.cellsgridjs/gridjsworkbook/import_excel_file/
is_root: false
---
##  import_excel_file {#str}

Importerar excel-filen från filsökvägen.



```python
def import_excel_file(self, file_name):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| file_name | str | Den fullständiga sökvägen till filen.|


##  import_excel_file {#str-str}

Importerar excel-filen från filsökvägen.



```python
def import_excel_file(self, uid, file_name):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| uid | str | Det unika ID:t för filcacheminnet, om satt till null, kommer det att genereras automatiskt.|
| file_name | str | Den fullständiga sökvägen till filen.|


##  import_excel_file {#io.RawIOBase-aspose.cellsgridjs.GridLoadFormat}

Importerar excel-filen från filström med laddningsformat.



```python
def import_excel_file(self, filestream, format):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| filestream | io.RawIOBase | Strömmen av excel-filen.|
| format | [`GridLoadFormat`](/cells/python-net/sv/aspose.cellsgridjs/gridloadformat) | Excel-filens LoadFormat.|


##  import_excel_file {#str-str-str}

Importerar excel-filen från filsökväg och öppet lösenord.



```python
def import_excel_file(self, uid, file_name, password):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| uid | str | Det unika ID:t för filcacheminnet, om satt till null, kommer det att genereras automatiskt.|
| file_name | str | Den fullständiga sökvägen till filen.|
| password | str | Det öppna lösenordet för excel-filen. Värdet kan vara null Om inget passowrd är inställt.|


##  import_excel_file {#str-io.RawIOBase-aspose.cellsgridjs.GridLoadFormat}

Importerar excel-filen från filström.



```python
def import_excel_file(self, uid, filestream, format):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| uid | str | Det unika ID:t för filcacheminnet, om satt till null, kommer det att genereras automatiskt.|
| filestream | io.RawIOBase | Strömmen av excel-filen.|
| format | [`GridLoadFormat`](/cells/python-net/sv/aspose.cellsgridjs/gridloadformat) | Excel-filens LoadFormat.|


##  import_excel_file {#io.RawIOBase-aspose.cellsgridjs.GridLoadFormat-str}

Importerar excel-filen från filströmmen med laddningsformat och öppet lösenord.



```python
def import_excel_file(self, filestream, format, password):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| filestream | io.RawIOBase | Strömmen av excel-filen.|
| format | [`GridLoadFormat`](/cells/python-net/sv/aspose.cellsgridjs/gridloadformat) | Excel-filens LoadFormat.|
| password | str | Det öppna lösenordet för excel-filen. Värdet kan vara null Om inget passowrd är inställt.|


##  import_excel_file {#str-io.RawIOBase-aspose.cellsgridjs.GridLoadFormat-str}

Importerar excel-filen från filströmmen med laddningsformat och öppet lösenord.



```python
def import_excel_file(self, uid, filestream, format, password):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| uid | str | Det unika ID:t för filcacheminnet, om satt till null, kommer det att genereras automatiskt.|
| filestream | io.RawIOBase | Strömmen av excel-filen.|
| format | [`GridLoadFormat`](/cells/python-net/sv/aspose.cellsgridjs/gridloadformat) | Excel-filens LoadFormat.|
| password | str | Det öppna lösenordet för excel-filen. Värdet kan vara null Om inget passowrd är inställt|



###  Se även
* modul [`aspose.cellsgridjs`](../../)
* klass [`GridJsWorkbook`](/cells/python-net/sv/aspose.cellsgridjs/gridjsworkbook)
