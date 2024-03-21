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
Stellt die Liste von [`VbaModule`](/cells/python-net/de/aspose.cells.vba/vbamodule) dar



Der Typ VbaModuleCollection macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [capacity](/cells/python-net/de/aspose.cells.vba/vbamodulecollection/capacity) | Ruft die Anzahl der Elemente ab, die die Array-Liste enthalten kann, oder legt diese fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [add](/cells/python-net/de/aspose.cells.vba/vbamodulecollection/add/#aspose.cells.Worksheet) | Fügt ein Modul für ein Arbeitsblatt hinzu.|
| [add](/cells/python-net/de/aspose.cells.vba/vbamodulecollection/add/#aspose.cells.vba.VbaModuleType-str) | Fügt Modul hinzu.|
| [copy_to](/cells/python-net/de/aspose.cells.vba/vbamodulecollection/copy_to/#list) | Kopiert die gesamte Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am Anfang der Ziel-Array-Liste.|
| [copy_to](/cells/python-net/de/aspose.cells.vba/vbamodulecollection/copy_to/#int-list-int-int) | Kopiert einen Bereich von Elementen aus der Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am angegebenen Index der Ziel-Array-Liste.|
| [index_of](/cells/python-net/de/aspose.cells.vba/vbamodulecollection/index_of/#aspose.cells.vba.VbaModule-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der vom angegebenen Index bis zum letzten Element reicht.|
| [index_of](/cells/python-net/de/aspose.cells.vba/vbamodulecollection/index_of/#aspose.cells.vba.VbaModule-int-int) |Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der beim angegebenen Index beginnt und die angegebene Anzahl von Elementen enthält.|
| [last_index_of](/cells/python-net/de/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.VbaModule) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens in der gesamten Array-Liste zurück.|
| [last_index_of](/cells/python-net/de/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.VbaModule-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der vom ersten Element bis zum angegebenen Index reicht.|
| [last_index_of](/cells/python-net/de/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.VbaModule-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der die angegebene Anzahl von Elementen enthält und beim angegebenen Index endet.|
| [add_designer_storage](/cells/python-net/de/aspose.cells.vba/vbamodulecollection/add_designer_storage/#str-bytes) |  |
| [get_designer_storage](/cells/python-net/de/aspose.cells.vba/vbamodulecollection/get_designer_storage/#str) | Stellt die Daten von Designer dar.|
| [add_user_form](/cells/python-net/de/aspose.cells.vba/vbamodulecollection/add_user_form/#str-str-bytes) | Benutzerformular in VBA-Projekt einfügen.|
| [binary_search](/cells/python-net/de/aspose.cells.vba/vbamodulecollection/binary_search/#aspose.cells.vba.VbaModule) | Durchsucht die gesamte sortierte Array-Liste mithilfe des Standardvergleichs nach einem Element und gibt den nullbasierten Index des Elements zurück.|



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
