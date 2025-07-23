---
title: create_safe_sheet_name metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 90
url: /sv/aspose.cells/cellshelper/create_safe_sheet_name/
is_root: false
---
##  create_safe_sheet_name(, namnförslag){#str}
Kontrollerar angivet arknamn och skapar ett giltigt namn vid behov.
Om det angivna arknamnet överensstämmer med reglerna för Excel-arknamn, returnera det.
Annars kommer strängen att avkortas om längden överskrider gränsen.
och ogiltiga tecken kommer att ersättas med ' ', och returnera sedan det ombyggda strängvärdet.


###  Returnerar




```python

@staticmethod
def create_safe_sheet_name(name_proposal):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| name_proposal | str | arknamn som ska användas|


##  create_safe_sheet_name(, namnförslag, ersätt_char){#str-char}
Kontrollerar angivet arknamn och skapar ett giltigt namn vid behov.
Om det angivna arknamnet överensstämmer med reglerna för Excel-arknamn, returnera det.
Annars kommer strängen att avkortas om längden överskrider gränsen.
och ogiltiga tecken kommer att ersättas med ett givet tecken, och returnera sedan det ombyggda strängvärdet.


###  Returnerar




```python

@staticmethod
def create_safe_sheet_name(name_proposal, replace_char):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| name_proposal | str | arknamn som ska användas|
| replace_char | char | tecken som kommer att användas för att ersätta ogiltiga tecken i angivet arknamn|



###  Se även
* modul [`aspose.cells`](../../)
* klass [`CellsHelper`](/cells/python-net/sv/aspose.cells/cellshelper)
