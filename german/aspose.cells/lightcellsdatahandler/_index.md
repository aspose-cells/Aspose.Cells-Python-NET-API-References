---
title: LightCellsDataHandler Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1030
url: /de/aspose.cells/lightcellsdatahandler/
is_root: false
---
##  LightCellsDataHandler Klasse
Stellt den Zelldatenhandler zum Lesen großer Tabellenkalkulationsdateien im Light-Weight-Modus dar.



Der Typ LightCellsDataHandler macht die folgenden Member verfügbar:

###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [start_sheet](/cells/python-net/de/aspose.cells/lightcellsdatahandler/start_sheet/#aspose.cells.Worksheet) | Beginnt mit der Verarbeitung eines Arbeitsblatts.|
| [start_row](/cells/python-net/de/aspose.cells/lightcellsdatahandler/start_row/#int) | Bereitet die Verarbeitung einer Zeile vor.|
| [process_row](/cells/python-net/de/aspose.cells/lightcellsdatahandler/process_row/#aspose.cells.Row) | Beginnt mit der Verarbeitung einer Zeile.|
| [start_cell](/cells/python-net/de/aspose.cells/lightcellsdatahandler/start_cell/#int) | Bereitet die Verarbeitung einer Zelle vor.|
| [process_cell](/cells/python-net/de/aspose.cells/lightcellsdatahandler/process_cell/#aspose.cells.Cell) | Beginnt mit der Verarbeitung einer Zelle.|



###  Bemerkungen

Beim Lesen einer Arbeitsmappe in diesem Modus wird [`LightCellsDataHandler.start_sheet`](/cells/python-net/de/aspose.cells/lightcellsdatahandler/start_sheet) beim Lesen jedes Arbeitsblatts in der Arbeitsmappe überprüft.
Wenn [`LightCellsDataHandler.start_sheet`](/cells/python-net/de/aspose.cells/lightcellsdatahandler/start_sheet) für ein Blatt „true“ ergibt, werden alle Daten und Eigenschaften der Zeilen/Zellen dieses Blattes überprüft
und durch die Implementierung dieser Schnittstelle verarbeitet. Für jede Zeile wird [`LightCellsDataHandler.start_row`](/cells/python-net/de/aspose.cells/lightcellsdatahandler/start_row) aufgerufen, um zu prüfen, ob sie verarbeitet werden muss.
Wenn eine Zeile verarbeitet werden muss, werden zuerst die Eigenschaften dieser Zeile gelesen und der Benutzer kann bis [`LightCellsDataHandler.process_row`](/cells/python-net/de/aspose.cells/lightcellsdatahandler/process_row) auf ihre Eigenschaften zugreifen.
Wenn auch die Zellen der Zeile verarbeitet werden müssen, sollte [`LightCellsDataHandler.process_row`](/cells/python-net/de/aspose.cells/lightcellsdatahandler/process_row) „true“ zurückgeben und dann [`LightCellsDataHandler.start_cell`](/cells/python-net/de/aspose.cells/lightcellsdatahandler/start_cell)
Wird für jede vorhandene Zelle in dieser Zeile aufgerufen, um zu prüfen, ob eine Zelle verarbeitet werden muss. Wenn eine Zelle verarbeitet werden muss,
dann wird [`LightCellsDataHandler.process_cell`](/cells/python-net/de/aspose.cells/lightcellsdatahandler/process_cell) aufgerufen, um die Zelle durch die Implementierung dieser Schnittstelle zu verarbeiten.


Bitte beachten Sie, dass der Benutzer nur die Werte und Eigenschaften des aktuellen Row/Cell-Objekts bearbeiten sollte, das von der entsprechenden Methode bereitgestellt wird.
Da die Zelldaten im Streaming-Verfahren aus der Vorlagendatei gelesen werden, können die meisten anderen Objekte später zurückgesetzt/aktualisiert werden
nachdem die Zellendaten geladen wurden. Wenn der Benutzer also andere Objekte in dieser Implementierung bedient,
Diese Vorgänge können sich möglicherweise nicht auf die in der Arbeitsmappe vorhandenen Objekte auswirken. Oder noch schlimmer, diese Operationen könnten es sein
Dies führt zu inkonsistenten Daten in der Arbeitsmappe und später zu unerwarteten Problemen oder Ausnahmen.
Also für alle anderen Objekte wie Formen, Spaltenbreite und -stile, bedingte Formatierungen usw.
Bitte betreiben Sie sie nicht in einer der Methoden dieser Implementierung.
Bitte verwalten Sie sie stattdessen, nachdem die Arbeitsmappe erstellt wurde.

###  Siehe auch
* Modul [`aspose.cells`](..)
