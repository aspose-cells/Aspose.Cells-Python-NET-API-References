---
title: process metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 20
url: /sv/aspose.cells.lowcode/spreadsheetsplitter/process/
is_root: false
---
##  process(, alternativ){#aspose.cells.lowcode.LowCodeSplitOptions}
Delar upp kalkylbladsfilen i flera delar.



```python

@staticmethod
def process(options):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| options | [`LowCodeSplitOptions`](/cells/python-net/sv/aspose.cells.lowcode/lowcodesplitoptions) | Alternativ för att dela kalkylblad|


##  process(, mallfil, resultatfil){#str-str}
Delar upp en given mallfil i flera delar.



```python

@staticmethod
def process(template_file, result_file):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| template_file | str | Mallfilen som ska delas|
| result_file | str | Den resulterande filen (namnmönster)|
###  Anmärkningar

Utdatafilerna kommer att byggas från den angivna resulterande filen av
tillägg av sekvensnummer för arket och den delade delen.
Om den angivna utdatafilen till exempel är Split.xlsx, så genereras den
filerna kommer att vara Split_0_0.xlsx, Split_0_1.xlsx, ..., Split_1_0.xlsx, ...


###  Se även
* modul [`aspose.cells.lowcode`](../../)
* klass [`SpreadsheetSplitter`](/cells/python-net/sv/aspose.cells.lowcode/spreadsheetsplitter)
