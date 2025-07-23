---
title: set_footer metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 180
url: /sv/aspose.cells/pagesetup/set_footer/
is_root: false
---
##  set_footer(self, section, footer_script) {#int-str}
Ställer in ett skript som formaterar sidfoten i en Excel-fil.



```python

def set_footer(self, section, footer_script):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| section | int |0: Vänster sektion, 1: Mittsektion, 2: Höger sektion.|
| footer_script | str | Skript för sidfotsformat.|
###  Anmärkningar

Skriptkommandon:

| Kommando| Beskrivning|
| :- | :- |
| &P| Nuvarande sidnummer|
| &N| Sidantal|
| &D| Aktuellt datum|
| &T| Aktuell tid|
| &A| Arknamn|
| &F| Filnamn utan sökväg|
| &"<FontName>"|Typsnittsnamn, till exempel: &"Arial"|
| &"<FontName>, <FontStyle>"| Typsnittsnamn och typsnittsstil, till exempel: &"Arial,Bold"|
| &<FontSize>| Teckenstorlek. Om detta kommando följs av ett vanligt nummer som ska skrivas ut i rubriken, kommer det att separeras från teckenhöjden med ett mellanslag.|
| &K<RRGGBB>| Teckenfärg, till exempel (RÖD): &KFF0000|
| &G| Bildskript|

Till exempel: "&Arial,Fetstil&8 sidfotsanteckning"


###  Se även
* modul [`aspose.cells`](../../)
* klass [`PageSetup`](/cells/python-net/sv/aspose.cells/pagesetup)
