---
title: VbaModuleCollection Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 20
url: /de/aspose.cells.vba/vbamodulecollection/
is_root: false
---
##  VbaModuleCollection Klasse
Stellt die Liste der [`VbaModule`](/cells/python-net/de/aspose.cells.vba/vbamodule) dar



Der Typ VbaModuleCollection macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [capacity](/cells/python-net/de/aspose.cells.vba/vbamodulecollection/capacity) | Ruft die Anzahl der Elemente ab, die die Array-Liste enthalten kann, oder legt diese fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`add(self, sheet)`](/cells/python-net/de/aspose.cells.vba/vbamodulecollection/add/#aspose.cells.worksheet) | Fügt ein Modul für ein Arbeitsblatt hinzu.|
| [`add(self, type, name)`](/cells/python-net/de/aspose.cells.vba/vbamodulecollection/add/#aspose.cells.vba.vbamoduletype-str) | Fügt Modul hinzu.|
| [`get(self, index)`](/cells/python-net/de/aspose.cells.vba/vbamodulecollection/get/#int) | Ruft [`VbaModule`](/cells/python-net/de/aspose.cells.vba/vbamodule) in der Liste über den Index ab.|
| [`get(self, name)`](/cells/python-net/de/aspose.cells.vba/vbamodulecollection/get/#str) | Ruft [`VbaModule`](/cells/python-net/de/aspose.cells.vba/vbamodule) in der Liste anhand des Namens ab.|
| [`copy_to(self, array)`](/cells/python-net/de/aspose.cells.vba/vbamodulecollection/copy_to/#list) |Kopiert die gesamte Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am Anfang der Ziel-Array-Liste.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/de/aspose.cells.vba/vbamodulecollection/copy_to/#int-list-int-int) | Kopiert einen Bereich von Elementen aus der Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am angegebenen Index der Ziel-Array-Liste.|
| [`index_of(self, item, index)`](/cells/python-net/de/aspose.cells.vba/vbamodulecollection/index_of/#aspose.cells.vba.vbamodule-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der sich vom angegebenen Index bis zum letzten Element erstreckt.|
| [`index_of(self, item, index, count)`](/cells/python-net/de/aspose.cells.vba/vbamodulecollection/index_of/#aspose.cells.vba.vbamodule-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der am angegebenen Index beginnt und die angegebene Anzahl von Elementen enthält.|
| [`last_index_of(self, item)`](/cells/python-net/de/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.vbamodule) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb der gesamten Arrayliste zurück.|
| [`last_index_of(self, item, index)`](/cells/python-net/de/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.vbamodule-int) |Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der sich vom ersten Element bis zum angegebenen Index erstreckt.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/de/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.vbamodule-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der die angegebene Anzahl von Elementen enthält und am angegebenen Index endet.|
| [`add_designer_storage(self, name, data)`](/cells/python-net/de/aspose.cells.vba/vbamodulecollection/add_designer_storage/#str-bytes) |  |
| [`get_designer_storage(self, name)`](/cells/python-net/de/aspose.cells.vba/vbamodulecollection/get_designer_storage/#str) | Stellt die Daten des Designers dar.|
| [`add_user_form(self, name, codes, designer_storage)`](/cells/python-net/de/aspose.cells.vba/vbamodulecollection/add_user_form/#str-str-bytes) | Benutzerformular in VBA-Projekt einfügen.|
| [`remove_by_worksheet(self, sheet)`](/cells/python-net/de/aspose.cells.vba/vbamodulecollection/remove_by_worksheet/#aspose.cells.worksheet) | Entfernt das Modul für ein Arbeitsblatt.|
| [`remove_by_name(self, name)`](/cells/python-net/de/aspose.cells.vba/vbamodulecollection/remove_by_name/#str) | Entfernen Sie das Modul anhand des Namens|
| [`binary_search(self, item)`](/cells/python-net/de/aspose.cells.vba/vbamodulecollection/binary_search/#aspose.cells.vba.vbamodule) | Durchsucht die gesamte sortierte Array-Liste mithilfe des Standardvergleichers nach einem Element und gibt den nullbasierten Index des Elements zurück.|



###  Beispiel

```python
from aspose.cells import Workbook
from aspose.cells.vba import VbaModuleType

# Instantiating a Workbook object
workbook = Workbook()
#  Init VBA project.
vbaProject = workbook.vba_project
#  Add a new module.
vbaProject.modules.add(VbaModuleType.CLASS, "test")
# Saving the Excel file
workbook.save("book1.xlsm")

```

###  Siehe auch
* Modul [`aspose.cells.vba`](..)
* Klasse [`VbaModule`](/cells/python-net/de/aspose.cells.vba/vbamodule)
