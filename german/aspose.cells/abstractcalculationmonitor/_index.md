---
title: AbstractCalculationMonitor Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 30
url: /de/aspose.cells/abstractcalculationmonitor/
is_root: false
---
##  AbstractCalculationMonitor Klasse
Überwachen Sie den Benutzer, um den Fortschritt der Formelberechnung zu verfolgen.



Der Typ AbstractCalculationMonitor macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [original_value](/cells/python-net/de/aspose.cells/abstractcalculationmonitor/original_value) | Ruft den alten Wert der berechneten Zelle ab.<br/> Sollte nur in [AbstractCalculationMonitor.before_calculate(sheet_index, row_index, col_index)](/cells/python-net/de/aspose.cells/abstractcalculationmonitor/before_calculate) und [AbstractCalculationMonitor.after_calculate(sheet_index, row_index, col_index)](/cells/python-net/de/aspose.cells/abstractcalculationmonitor/after_calculate) verwendet werden.|
| [value_changed](/cells/python-net/de/aspose.cells/abstractcalculationmonitor/value_changed) | Ob der Wert der Zelle nach der Berechnung geändert wurde.<br/> Sollte nur in [AbstractCalculationMonitor.after_calculate(sheet_index, row_index, col_index)](/cells/python-net/de/aspose.cells/abstractcalculationmonitor/after_calculate) verwendet werden.|
| [calculated_value](/cells/python-net/de/aspose.cells/abstractcalculationmonitor/calculated_value) | Ruft den neu berechneten Wert der Zelle ab.<br/> Sollte nur in [AbstractCalculationMonitor.after_calculate(sheet_index, row_index, col_index)](/cells/python-net/de/aspose.cells/abstractcalculationmonitor/after_calculate) verwendet werden.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [before_calculate(sheet_index, row_index, col_index)](/cells/python-net/de/aspose.cells/abstractcalculationmonitor/before_calculate/#int-int-int) | Implementieren Sie diese Methode, um Geschäfte zu machen, bevor Sie eine Zelle berechnen.|
| [after_calculate(sheet_index, row_index, col_index)](/cells/python-net/de/aspose.cells/abstractcalculationmonitor/after_calculate/#int-int-int) | Implementieren Sie diese Methode, um Geschäfte zu machen, nachdem eine Zelle berechnet wurde.|
| [on_circular(circular_cells_data)](/cells/python-net/de/aspose.cells/abstractcalculationmonitor/on_circular/#collections.abc.Iterator) | Implementieren Sie diese Methode, um Geschäfte zu machen, wenn Sie Formeln mit Zirkelbezügen berechnen.|



###  Siehe auch
* Modul [aspose.cells](..)
