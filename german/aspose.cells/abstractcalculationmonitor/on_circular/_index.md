---
title: on_circular Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 40
url: /de/aspose.cells/abstractcalculationmonitor/on_circular/
is_root: false
---
##  on_circular {#collections.abc.Iterator}
Implementieren Sie diese Methode, um bei der Berechnung von Formeln mit Zirkelbezügen Geschäfte zu machen.


###  Kehrt zurück

Ob die Formel-Engine diese Zellen nach diesem Aufruf kreisförmig berechnen muss.
True, damit die Formel-Engine weiterhin Berechnungen für sie durchführen kann.
Falsch, damit die Formel-Engine diese Zellen einfach als berechnet markiert.


```python
def on_circular(self, circular_cells_data):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| circular_cells_data | collections.abc.Iterator | IEnumerator mit [`CalculationCell`](/cells/python-net/de/aspose.cells/calculationcell) Elementen, die Zellen darstellen, die<br/> hängen von Zirkelverweisen ab.|
###  Bemerkungen

In der Implementierung kann der Benutzer auch den erwarteten Wert als berechnetes Ergebnis festlegen
für einen Teil/alle dieser Zellen, damit die Formel-Engine sie nicht rekursiv berechnet.


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`AbstractCalculationMonitor`](/cells/python-net/de/aspose.cells/abstractcalculationmonitor)
* Klasse [`CalculationCell`](/cells/python-net/de/aspose.cells/calculationcell)
