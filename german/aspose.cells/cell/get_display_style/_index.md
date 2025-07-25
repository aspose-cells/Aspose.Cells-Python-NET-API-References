---
title: get_display_style Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 110
url: /de/aspose.cells/cell/get_display_style/
is_root: false
---
##  get_display_style(self) {#}
Ruft den Anzeigestil dieser Zelle ab.


###  Kehrt zurück

Anzeigestil dieser Zelle


```python

def get_display_style(self):
    ...
```


###  Bemerkungen

Dasselbe gilt für die Verwendung von [`BorderType.SIDE_BORDERS`](/cells/python-net/de/aspose.cells/bordertype#SIDE_BORDERS)
für [`Cell.get_display_style`](/cells/python-net/de/aspose.cells/cell/get_display_style).
Das heißt, diese Methode prüft und passt die oberen/unteren/linken/rechten Grenzen dieser Zelle an
entsprechend dem Stil ([`Cell.get_style`](/cells/python-net/de/aspose.cells/cell/get_style)) seiner benachbarten Zellen,
Überprüfen Sie jedoch nicht die verbundenen Zellen und überprüfen Sie nicht den Anzeigestil benachbarter Zellen.

##  get_display_style(self, include_merged_borders) {#bool}
Ruft den Anzeigestil dieser Zelle ab.


###  Kehrt zurück

Anzeigestil dieser Zelle


```python

def get_display_style(self, include_merged_borders):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| include_merged_borders | bool | Gibt an, ob die Grenzen verbundener Zellen überprüft werden.|
###  Bemerkungen

Wenn das angegebene Flag falsch ist, ist es dasselbe wie [`Cell.get_display_style`](/cells/python-net/de/aspose.cells/cell/get_display_style).
Ansonsten ist es dasselbe wie bei der Verwendung
[`BorderType.SIDE_BORDERS`](/cells/python-net/aspose.cells/bordertype#SIDE_BORDERS)|[`BorderType.DYNAMIC_STYLE_BORDERS`](/cells/python-net/aspose.cells/bordertype#DYNAMIC_STYLE_BORDERS)
für [`Cell.get_display_style`](/cells/python-net/de/aspose.cells/cell/get_display_style).

##  get_display_style(self, adjacent_borders) {#aspose.cells.BorderType}
Ruft den Anzeigestil dieser Zelle ab.


###  Kehrt zurück

Anzeigestil dieser Zelle


```python

def get_display_style(self, adjacent_borders):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| adjacent_borders | [`BorderType`](/cells/python-net/de/aspose.cells/bordertype) | Gibt an, welche Grenzen überprüft und angepasst werden müssen<br/> entsprechend den Grenzen benachbarter Zellen.|
###  Bemerkungen

Wenn diese Zelle auch von anderen Einstellungen wie bedingter Formatierung, Listenobjekten usw. betroffen ist,
dann kann der Anzeigestil von [`Cell.get_style`](/cells/python-net/de/aspose.cells/cell/get_style) abweichen.

Für Flags zum Anpassen von Grenzen entsprechend benachbarter Zellen,
[`BorderType.TOP_BORDER`](/cells/python-net/aspose.cells/bordertype#TOP_BORDER)/[`BorderType.BOTTOM_BORDER`](/cells/python-net/aspose.cells/bordertype#BOTTOM_BORDER)
/[`BorderType.LEFT_BORDER`](/cells/python-net/aspose.cells/bordertype#LEFT_BORDER)/[`BorderType.RIGHT_BORDER`](/cells/python-net/aspose.cells/bordertype#RIGHT_BORDER)
geben Sie an, ob die unteren/oberen/rechten/linken Grenzen von
die links/rechts/oben/unten angrenzenden Zellen.

Aus Leistungs- und Kompatibilitätsgründen
Einige Enumerationen werden verwendet, um spezielle Operationen zu kennzeichnen:

[`BorderType.HORIZONTAL`](/cells/python-net/aspose.cells/bordertype#HORIZONTAL)/[`BorderType.VERTICAL`](/cells/python-net/aspose.cells/bordertype#VERTICAL)
Geben Sie an, ob die untere/rechte Grenze der zusammengeführten Zellen mit dieser hierüber kombiniert werden soll.

[`BorderType.DIAGONAL`](/cells/python-net/de/aspose.cells/bordertype#DIAGONAL)(das heißt, sowohl [`StyleModifyFlag.DIAGONAL_UP_BORDER`](/cells/python-net/de/aspose.cells/stylemodifyflag#DIAGONAL_UP_BORDER) als auch
[`StyleModifyFlag.DIAGONAL_DOWN_BORDER`](/cells/python-net/de/aspose.cells/stylemodifyflag#DIAGONAL_DOWN_BORDER) wurden gesetzt) bezeichnet Grenzen prüfen und kombinieren
vom Anzeigestil benachbarter Zellen.

Bitte beachten Sie, dass beim Überprüfen der Grenzen/Stile benachbarter Zellen, insbesondere der Anzeigestile,
ist ein zeitaufwändiger Prozess. Wenn es nicht notwendig ist, die Ränder für den zurückgegebenen Stil abzurufen,
Verwenden Sie [`BorderType.NONE`](/cells/python-net/de/aspose.cells/bordertype#NONE), um den Prozess benachbarter Zellen zu deaktivieren
wird eine bessere Leistung bringen.
Wenn Sie die Grenzen benachbarter Zellen nur aus den Stilen erhalten, die für diese Zellen definiert sind (ohne
[`BorderType.DIAGONAL`](/cells/python-net/de/aspose.cells/bordertype#DIAGONAL)), kann die Leistung auch besser sein, weil die Überprüfung
Auch die Anzeige einer Zelle ist zeitaufwendig.


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Cell`](/cells/python-net/de/aspose.cells/cell)
