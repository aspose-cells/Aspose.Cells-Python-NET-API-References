---
title: get_display_style metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 110
url: /sv/aspose.cells/cell/get_display_style/
is_root: false
---
##  get_display_style(self) {#}
Hämtar visningsstilen för den här cellen.


###  Returnerar

visningsstil för den här cellen


```python

def get_display_style(self):
    ...
```


###  Anmärkningar

Samma sak gäller för att använda [`BorderType.SIDE_BORDERS`](/cells/python-net/sv/aspose.cells/bordertype#SIDE_BORDERS)
för [`Cell.get_display_style`](/cells/python-net/sv/aspose.cells/cell/get_display_style).
Det vill säga, den här metoden kommer att kontrollera och justera övre/nedre/vänstra/högra kanterna för den här cellen
enligt stilen ([`Cell.get_style`](/cells/python-net/sv/aspose.cells/cell/get_style)) för dess intilliggande celler,
men kontrollera inte de sammanslagna cellerna och kontrollera inte visningsstilen för intilliggande celler.

##  get_display_style(self, include_merged_borders) {#bool}
Hämtar visningsstilen för den här cellen.


###  Returnerar

visningsstil för den här cellen


```python

def get_display_style(self, include_merged_borders):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| include_merged_borders | bool | Anger om kontroll av kantlinjer för sammanslagna celler ska göras.|
###  Anmärkningar

Om den angivna flaggan är falsk, är det samma sak med [`Cell.get_display_style`](/cells/python-net/sv/aspose.cells/cell/get_display_style).
Annars är det samma sak med att använda
[`BorderType.SIDE_BORDERS`](/cells/python-net/aspose.cells/bordertype#SIDE_BORDERS)|[`BorderType.DYNAMIC_STYLE_BORDERS`](/cells/python-net/aspose.cells/bordertype#DYNAMIC_STYLE_BORDERS)
för [`Cell.get_display_style`](/cells/python-net/sv/aspose.cells/cell/get_display_style).

##  get_display_style(self, adjacent_borders) {#aspose.cells.BorderType}
Hämtar visningsstilen för den här cellen.


###  Returnerar

visningsstil för den här cellen


```python

def get_display_style(self, adjacent_borders):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| adjacent_borders | [`BorderType`](/cells/python-net/sv/aspose.cells/bordertype) | Anger vilka gränser som behöver kontrolleras och justeras<br/> enligt gränserna för intilliggande celler.|
###  Anmärkningar

Om den här cellen också påverkas av andra inställningar, såsom villkorsstyrd formatering, listobjekt etc.
då kan visningsstilen skilja sig från [`Cell.get_style`](/cells/python-net/sv/aspose.cells/cell/get_style).

För flaggor för att justera gränser enligt angränsande celler,
[`BorderType.TOP_BORDER`](/cells/python-net/aspose.cells/bordertype#TOP_BORDER)/[`BorderType.BOTTOM_BORDER`](/cells/python-net/aspose.cells/bordertype#BOTTOM_BORDER)
/[`BorderType.LEFT_BORDER`](/cells/python-net/aspose.cells/bordertype#LEFT_BORDER)/[`BorderType.RIGHT_BORDER`](/cells/python-net/aspose.cells/bordertype#RIGHT_BORDER)
ange om markering och kombination av nedre/övre/höger/vänster gränser
de vänstra/högra/övre/nedre cellerna intill denna.

För prestanda och kompatibilitet,
vissa enums används för att beteckna vissa specialoperationer:

[`BorderType.HORIZONTAL`](/cells/python-net/aspose.cells/bordertype#HORIZONTAL)/[`BorderType.VERTICAL`](/cells/python-net/aspose.cells/bordertype#VERTICAL)
anger om den ska markeras och kombineras med den nedre/högra kanten av de sammanslagna cellerna.

[`BorderType.DIAGONAL`](/cells/python-net/sv/aspose.cells/bordertype#DIAGONAL) (det vill säga både [`StyleModifyFlag.DIAGONAL_UP_BORDER`](/cells/python-net/sv/aspose.cells/stylemodifyflag#DIAGONAL_UP_BORDER) och
[`StyleModifyFlag.DIAGONAL_DOWN_BORDER`](/cells/python-net/sv/aspose.cells/stylemodifyflag#DIAGONAL_DOWN_BORDER) har ställts in) anger att gränser kontrolleras och kombineras
från visningsstilen för intilliggande celler.

Observera att du bör kontrollera kantlinjer/stilar för intilliggande celler, särskilt visningsstilarna,
är en tidskrävande process. Om det inte finns något behov av att hämta kantlinjerna för den returnerade stilen,
använder [`BorderType.NONE`](/cells/python-net/sv/aspose.cells/bordertype#NONE) för att inaktivera processen för intilliggande celler
kommer att ge bättre prestanda.
När man hämtar kantlinjer för angränsande celler från stilar som definierats endast för dessa celler (utan att ställa in
[`BorderType.DIAGONAL`](/cells/python-net/sv/aspose.cells/bordertype#DIAGONAL)), prestandan kan också vara bättre eftersom kontrollen
Visningsstilen för en cell är också tidskrävande.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`Cell`](/cells/python-net/sv/aspose.cells/cell)
