---
title: process metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 20
url: /sv/aspose.cells.lowcode/spreadsheetlocker/process/
is_root: false
---
##  process(, load_options, save_options, provider){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-aspose.cells.lowcode.AbstractLowCodeProtectionProvider}
Låser kalkylbladsfilen med angivna inställningar.



```python

@staticmethod
def process(load_options, save_options, provider):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/sv/aspose.cells.lowcode/lowcodeloadoptions) | Alternativ för inmatning och laddning|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptions) | Alternativ för utdata och sparande|
| provider | [`AbstractLowCodeProtectionProvider`](/cells/python-net/sv/aspose.cells.lowcode/abstractlowcodeprotectionprovider) | Implementering för att tillhandahålla skyddsinställningar|


##  process(, mallfil, resultatfil, öppna_lösenord, skriv_lösenord){#str-str-str-str}
Låser kalkylbladsfilen med angivna inställningar.



```python

@staticmethod
def process(template_file, result_file, open_password, write_password):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| template_file | str | Mallfilen som ska låsas|
| result_file | str | Den resulterande filen|
| open_password | str | Lösenord för filkryptering|
| write_password | str |Lösenord för skydd av ändringar i kalkylblad|


##  process(, ladda_alternativ, spara_alternativ, öppna_lösenord, skriv_lösenord){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-str-str}
Låser kalkylbladsfilen med angivna inställningar.



```python

@staticmethod
def process(load_options, save_options, open_password, write_password):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/sv/aspose.cells.lowcode/lowcodeloadoptions) | Alternativ för inmatning och laddning|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptions) | Alternativ för utdata och sparande|
| open_password | str | Lösenord för filkryptering|
| write_password | str |Lösenord för skydd av ändringar i kalkylblad|


##  process(, load_options, save_options, open_password, write_password, workbook_lösenord, workbook_typ){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-str-str-str-aspose.cells.ProtectionType}
Låser kalkylbladsfilen med angivna inställningar.



```python

@staticmethod
def process(load_options, save_options, open_password, write_password, workbook_password, workbook_type):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/sv/aspose.cells.lowcode/lowcodeloadoptions) | Alternativ för inmatning och laddning|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptions) | Alternativ för utdata och sparande|
| open_password | str | Lösenord för filkryptering|
| write_password | str |Lösenord för skydd av ändringar i kalkylblad|
| workbook_password | str | Lösenord för skydd av arbetsboken|
| workbook_type | [`ProtectionType`](/cells/python-net/sv/aspose.cells/protectiontype) | Skyddstyp för att skydda arbetsboken|



###  Se även
* modul [`aspose.cells.lowcode`](../../)
* klass [`SpreadsheetLocker`](/cells/python-net/sv/aspose.cells.lowcode/spreadsheetlocker)
