---
title: GridWorkbookSettings Klasse
second_title: Aspose.Cells.GridJs for Python via .NET API Referenzen
description:
type: docs
weight: 80
url: /de/aspose.cellsgridjs/gridworkbooksettings/
is_root: false
---
##  GridWorkbookSettings Klasse

Stellt die Einstellungen der Arbeitsmappe dar.



Der Typ GridWorkbookSettings macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [__init__](/cells/python-net/de/aspose.cellsgridjs/gridworkbooksettings/__init__/#) | Konstruiert eine neue Instanz von GridWorkbookSettings|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [max_iteration](/cells/python-net/de/aspose.cellsgridjs/gridworkbooksettings/max_iteration) | Gibt die maximale Anzahl von Iterationen zum Auflösen eines Zirkelverweises zurück oder legt sie fest. Der Standardwert ist 100.|
| [iteration](/cells/python-net/de/aspose.cellsgridjs/gridworkbooksettings/iteration) | Gibt an, ob Iteration zum Auflösen von Zirkelverweisen verwendet wird.|
| [force_full_calculate](/cells/python-net/de/aspose.cellsgridjs/gridworkbooksettings/force_full_calculate) | Gibt an, ob die Berechnung jedes Mal vollständig durchgeführt wird, wenn eine Berechnung ausgelöst wird.|
| [create_calc_chain](/cells/python-net/de/aspose.cellsgridjs/gridworkbooksettings/create_calc_chain) | Gibt an, ob eine Kette berechneter Formeln erstellt wird. Der Standardwert ist falsch.|
| [re_calculate_on_open](/cells/python-net/de/aspose.cellsgridjs/gridworkbooksettings/re_calculate_on_open) | Gibt an, ob alle Formeln beim Öffnen der Datei neu berechnet werden.|
| [precision_as_displayed](/cells/python-net/de/aspose.cellsgridjs/gridworkbooksettings/precision_as_displayed) | True, wenn Berechnungen in dieser Arbeitsmappe nur mit der Genauigkeit der angezeigten Zahlen durchgeführt werden|
| [date1904](/cells/python-net/de/aspose.cellsgridjs/gridworkbooksettings/date1904) |Ruft einen Wert ab oder legt diesen fest, der angibt, ob die Arbeitsmappe das Datumssystem 1904 verwendet.|
| [enable_macros](/cells/python-net/de/aspose.cellsgridjs/gridworkbooksettings/enable_macros) | Makros aktivieren; Jetzt funktioniert es nur, wenn ein Arbeitsblatt in ein anderes Arbeitsblatt in einer Arbeitsmappe kopiert wird.|
| [check_custom_number_format](/cells/python-net/de/aspose.cellsgridjs/gridworkbooksettings/check_custom_number_format) | Gibt an, ob beim Festlegen von Style.Custom das benutzerdefinierte Zahlenformat überprüft wird.|
| [author](/cells/python-net/de/aspose.cellsgridjs/gridworkbooksettings/author) | Ruft den Autor der Datei ab bzw. legt ihn fest.|



###  Beispiel


```python
from aspose.cellsgridjs import GridJsWorkbook, GridWorkbookSettings

g = GridJsWorkbook()
gsettings = GridWorkbookSettings()
g.settings = gsettings

```

###  Siehe auch
* Modul [`aspose.cellsgridjs`](..)
