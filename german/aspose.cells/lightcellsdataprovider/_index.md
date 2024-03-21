---
title: LightCellsDataProvider Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1040
url: /de/aspose.cells/lightcellsdataprovider/
is_root: false
---
##  LightCellsDataProvider Klasse
Stellt einen Datenanbieter zum Speichern großer Tabellenkalkulationsdateien im Light-Weight-Modus dar.



Der Typ LightCellsDataProvider macht die folgenden Member verfügbar:

###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [start_sheet](/cells/python-net/de/aspose.cells/lightcellsdataprovider/start_sheet/#int) | Beginnt mit dem Speichern eines Arbeitsblatts.|
| [next_row](/cells/python-net/de/aspose.cells/lightcellsdataprovider/next_row/#) | Ruft die nächste zu speichernde Zeile ab.|
| [start_row](/cells/python-net/de/aspose.cells/lightcellsdataprovider/start_row/#aspose.cells.Row) | Beginnt mit dem Speichern der Daten einer Zeile.|
| [next_cell](/cells/python-net/de/aspose.cells/lightcellsdataprovider/next_cell/#) | Ruft die nächste zu speichernde Zelle ab.|
| [start_cell](/cells/python-net/de/aspose.cells/lightcellsdataprovider/start_cell/#aspose.cells.Cell) | Beginnt mit dem Speichern der Daten einer Zelle.|
| [is_gather_string](/cells/python-net/de/aspose.cells/lightcellsdataprovider/is_gather_string/#) |Überprüft, ob der aktuelle Zeichenfolgenwert der Zelle in einem globalen Pool gesammelt werden muss.|



###  Bemerkungen

Wenn Sie eine Arbeitsmappe in diesem Modus speichern, wird [`LightCellsDataProvider.start_sheet`](/cells/python-net/de/aspose.cells/lightcellsdataprovider/start_sheet) beim Speichern jedes Arbeitsblatts in der Arbeitsmappe überprüft.
Wenn [`LightCellsDataProvider.start_sheet`](/cells/python-net/de/aspose.cells/lightcellsdataprovider/start_sheet) für ein Blatt „true“ ergibt, werden alle Daten und Eigenschaften für Zeilen/Zellen dieses Blattes gespeichert
wird durch die Implementierung dieser Schnittstelle bereitgestellt.
Zunächst wird [`LightCellsDataProvider.next_row`](/cells/python-net/de/aspose.cells/lightcellsdataprovider/next_row) aufgerufen, um den nächsten zu speichernden Zeilenindex abzurufen.
Wenn ein gültiger Zeilenindex zurückgegeben wird (der Zeilenindex muss in aufsteigender Reihenfolge vorliegen, damit die Zeilen gespeichert werden),
dann wird von [`LightCellsDataProvider.start_row`](/cells/python-net/de/aspose.cells/lightcellsdataprovider/start_row) ein Row-Objekt bereitgestellt, das diese Zeile darstellt, damit die Implementierung ihre Eigenschaften festlegen kann.
Für eine Zeile wird zunächst [`LightCellsDataProvider.next_cell`](/cells/python-net/de/aspose.cells/lightcellsdataprovider/next_cell) überprüft.
Wenn ein gültiger Spaltenindex zurückgegeben wird (der Spaltenindex muss für alle Zellen der aktuellen Zeile in aufsteigender Reihenfolge sein),
dann wird von [`LightCellsDataProvider.start_cell`](/cells/python-net/de/aspose.cells/lightcellsdataprovider/start_cell) ein Cell-Objekt bereitgestellt, das diese Zelle darstellt, zur Implementierung, um ihre Daten und Eigenschaften festzulegen.
Nach [`LightCellsDataProvider.start_cell`](/cells/python-net/de/aspose.cells/lightcellsdataprovider/start_cell) wird die Zelle direkt in der resultierenden Tabellenkalkulationsdatei gespeichert.
Dann wird die nächste Zelle überprüft und verarbeitet.


Bitte beachten Sie, dass der Benutzer nur Werte und Eigenschaften für das aktuelle Row/Cell-Objekt aktualisieren sollte, das von der entsprechenden Methode bereitgestellt wird.
Da die Zelldaten im Streaming-Verfahren in die resultierende Datei geschrieben werden, wurden möglicherweise die meisten anderen Objekte geschrieben
in die resultierende Datei hinzugefügt oder es wurden einige globale Daten für sie gesammelt und geschrieben. Wenn der Benutzer also andere Objekte aktualisiert
Beim Speichern von Zelldaten haben diese Vorgänge möglicherweise keinen Einfluss auf die gespeicherten Daten. Oder noch schlimmer, diese Operationen könnten es sein
Dies führt dazu, dass inkonsistente Daten in der resultierenden Datei gespeichert werden und die Datei schließlich beschädigt wird.
Also für alle anderen Objekte wie Formen, Spaltenbreite und -stile, bedingte Formatierungen usw.
Bitte betreiben Sie sie nicht in einer der Methoden dieser Implementierung.
Bitte verwalten Sie sie stattdessen und passen Sie sie an den endgültigen Zustand an, bevor Sie die Methode „Speichern“ der Arbeitsmappe aufrufen.

###  Siehe auch
* Modul [`aspose.cells`](..)
