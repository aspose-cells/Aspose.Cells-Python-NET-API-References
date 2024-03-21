---
title: SheetRender Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 120
url: /de/aspose.cells.rendering/sheetrender/
is_root: false
---
##  SheetRender Klasse
Stellt ein Arbeitsblatt-Rendering dar, das das Arbeitsblatt in verschiedene Bilder rendern kann, z. B. (BMP, PNG, JPEG, TIFF..)
Der Konstruktor dieser Klasse muss nach der Änderung des Seiten-Setups und des Zellenstils verwendet werden.



Der Typ SheetRender macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [__init__](/cells/python-net/de/aspose.cells.rendering/sheetrender/__init__/#aspose.cells.Worksheet-aspose.cells.rendering.ImageOrPrintOptions) | Das Konstrukt von SheetRender benötigt Arbeitsblatt und ImageOrPrintOptions als Parameter|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [page_count](/cells/python-net/de/aspose.cells.rendering/sheetrender/page_count) | Ruft die Gesamtseitenzahl des aktuellen Arbeitsblatts ab.|
| [page_scale](/cells/python-net/de/aspose.cells.rendering/sheetrender/page_scale) | Ruft den berechneten Seitenmaßstab des Blattes ab.<br/> Gibt den eingestellten Maßstab zurück, wenn [`PageSetup.zoom`](/cells/python-net/de/aspose.cells/pagesetup#zoom) gesetzt ist. Andernfalls wird der berechnete Maßstab gemäß [`PageSetup.fit_to_pages_wide`](/cells/python-net/de/aspose.cells/pagesetup#fit_to_pages_wide) und [`PageSetup.fit_to_pages_tall`](/cells/python-net/de/aspose.cells/pagesetup#fit_to_pages_tall) zurückgegeben.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [to_image](/cells/python-net/de/aspose.cells.rendering/sheetrender/to_image/#int-str) |Rendern Sie eine bestimmte Seite in eine Datei.|
| [to_image](/cells/python-net/de/aspose.cells.rendering/sheetrender/to_image/#int-io.RawIOBase) | Rendern Sie eine bestimmte Seite in einen Stream.|
| [to_tiff](/cells/python-net/de/aspose.cells.rendering/sheetrender/to_tiff/#io.RawIOBase) | Rendern Sie das gesamte Arbeitsblatt als TIFF-Bild zum Streamen.|
| [to_tiff](/cells/python-net/de/aspose.cells.rendering/sheetrender/to_tiff/#str) | Rendern Sie das gesamte Arbeitsblatt als TIFF-Bild in eine Datei.|
| [to_printer](/cells/python-net/de/aspose.cells.rendering/sheetrender/to_printer/#str) | Arbeitsblatt auf Drucker übertragen|
| [to_printer](/cells/python-net/de/aspose.cells.rendering/sheetrender/to_printer/#str-str) | Arbeitsblatt auf Drucker übertragen|
| [to_printer](/cells/python-net/de/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.PrinterSettings) | Arbeitsblatt auf Drucker übertragen|
| [to_printer](/cells/python-net/de/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.PrinterSettings-str) | Arbeitsblatt auf Drucker übertragen|
| [to_printer](/cells/python-net/de/aspose.cells.rendering/sheetrender/to_printer/#str-int-int) | Arbeitsblatt auf Drucker übertragen|
| [get_page_size_inch](/cells/python-net/de/aspose.cells.rendering/sheetrender/get_page_size_inch/#int) | Ermitteln Sie die Seitengröße des Ausgabebilds in Zoll.|
| [custom_print](/cells/python-net/de/aspose.cells.rendering/sheetrender/custom_print/#bool-aspose.pydrawing.printing.PrintPageEventArgs) | Mit dieser Funktion kann der Client die Seiteneinstellungen des Druckers beim Drucken jeder Seite steuern.|
| [dispose](/cells/python-net/de/aspose.cells.rendering/sheetrender/dispose/#) | Gibt Ressourcen frei, die für das Rendern erstellt und verwendet wurden.|



###  Siehe auch
* Modul [`aspose.cells.rendering`](..)
