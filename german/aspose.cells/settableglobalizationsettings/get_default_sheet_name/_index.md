---
title: get_default_sheet_name Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 80
url: /de/aspose.cells/settableglobalizationsettings/get_default_sheet_name/
is_root: false
---
##  get_default_sheet_name(self) {#}
Ruft den Standardblattnamen zum automatischen Hinzufügen eines Arbeitsblatts ab.
Der Standardwert ist „Blatt“.


###  Kehrt zurück

der Standardblattname zum automatischen Hinzufügen von Arbeitsblättern


```python

def get_default_sheet_name(self):
    ...
```


###  Bemerkungen

Die automatisch hinzugefügte(wie zum Beispiel von [`WorksheetCollection.add`](/cells/python-net/de/aspose.cells/worksheetcollection/add))
Der Name des Blattes besteht aus dem angegebenen Namen plus Sequenznummer.
 Beispielsweise möchte ein Benutzer in Deutschland möglicherweise, dass der Blattname „Tabellenblatt2“ statt „Sheet2“ lautet.
Anschließend kann der Benutzer diese Methode implementieren, um „Tabellenblatt“ zurückzugeben.


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`SettableGlobalizationSettings`](/cells/python-net/de/aspose.cells/settableglobalizationsettings)
