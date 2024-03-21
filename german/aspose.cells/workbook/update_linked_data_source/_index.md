---
title: update_linked_data_source Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 420
url: /de/aspose.cells/workbook/update_linked_data_source/
is_root: false
---
##  update_linked_data_source {#list}
Wenn diese Arbeitsmappe externe Links zu anderen Datenquellen enthält,
Aspose.Cells wird versuchen, die neuesten Daten aus den angegebenen Quellen abzurufen.



```python
def update_linked_data_source(self, external_workbooks):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| external_workbooks | list | Arbeitsmappen, die zum Aktualisieren von Daten externer Links verwendet werden, auf die in dieser Arbeitsmappe verwiesen wird.<br/>Die Übereinstimmung dieser Arbeitsmappen mit externen Links wird durch [`Workbook.file_name`](/cells/python-net/de/aspose.cells/workbook#file_name) bestimmt<br/>und [`ExternalLink.data_source`](/cells/python-net/de/aspose.cells/externallink#data_source). Bitte stellen Sie daher sicher, dass [`Workbook.file_name`](/cells/python-net/de/aspose.cells/workbook#file_name) vorhanden ist<br/> Für jede Arbeitsmappe wurde der richtige Wert angegeben, damit sie mit dem entsprechenden externen Link verknüpft werden können.|
###  Bemerkungen

Wenn für eine Arbeitsmappe kein entsprechender externer Link gefunden werden kann, wird diese Arbeitsmappe ignoriert.
Wenn Sie also später eine Formel mit einem neuen externen Link festlegen, möchten Sie die Arbeitsmappe ignorieren
damit verknüpft werden soll, kann die Verknüpfung erst ausgeführt werden, wenn Sie diese Methode mit diesen Arbeitsmappen erneut aufrufen.


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Workbook`](/cells/python-net/de/aspose.cells/workbook)
