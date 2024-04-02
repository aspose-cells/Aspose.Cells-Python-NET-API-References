---
title: insert_image Methode
second_title: Aspose.Cells.GridJs for Python via .NET API Referenzen
description:
type: docs
weight: 130
url: /de/aspose.cellsgridjs/gridjsworkbook/insert_image/
is_root: false
---
##  insert_image {#str-str-io.RawIOBase-str}

Fügt ein Bild aus dem Dateistream oder der URL in das Arbeitsblatt ein (es muss entweder der Dateistream oder die URL angegeben werden).
 oder
Fügt eine Form ein, wenn der p.type einer von AutoShapeType ist


###  Kehrt zurück


Die Formatzeichenfolge JSON des eingefügten Bildes


```python
def insert_image(self, uid, p, s, image_url):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| uid | str | Die eindeutige ID für den Dateicache|
| p | str | Die Formatzeichenfolge JSON für den Vorgang, die die Zellenposition, den Arbeitsblattnamen, die obere linke Zeile, die obere linke Spalte für das Bild usw. angibt {name:'sheet1',ri:1,ci:1} |
| s | io.RawIOBase | Der Dateistream der Bilddatei|
| image_url | str | Die URL der Bilddatei|



###  Siehe auch
* Modul [`aspose.cellsgridjs`](../../)
* Klasse [`GridJsWorkbook`](/cells/python-net/de/aspose.cellsgridjs/gridjsworkbook)
