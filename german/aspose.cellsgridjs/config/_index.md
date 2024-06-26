---
title: Config Klasse
second_title: Aspose.Cells.GridJs for Python via .NET API Referenzen
description:
type: docs
weight: 10
url: /de/aspose.cellsgridjs/config/
is_root: false
---
##  Config Klasse

Stellt alle Einstellungen für GridJs dar



Der Typ Config macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [__init__](/cells/python-net/de/aspose.cellsgridjs/config/__init__/#) | Erstellt eine neue Instanz von Config|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [save_html_as_zip](/cells/python-net/de/aspose.cellsgridjs/config/save_html_as_zip) | Legt fest/ruft ab, ob die HTML-Datei als ZIP-Archiv gespeichert werden soll. Der Standardwert ist „false“.|
| [same_image_detecting](/cells/python-net/de/aspose.cellsgridjs/config/same_image_detecting) | Legt fest/ruft ab, ob überprüft werden soll, ob das Bild dieselbe Quelle hat. Der Standardwert ist „true“.<br/> Der Standardwert ist wahr.|
| [auto_optimize_for_large_cells](/cells/python-net/de/aspose.cellsgridjs/config/auto_optimize_for_large_cells) | Legt fest/ruft ab, ob die Ladeleistung für Arbeitsblätter mit großen Zellen automatisch optimiert werden soll<br/> Ignorieren Sie einige Stile/Rahmen, um die Ladezeit zu verkürzen<br/> Der Standardwert ist wahr.|
| [islimit_shape_or_image](/cells/python-net/de/aspose.cellsgridjs/config/islimit_shape_or_image) |Legt fest/ruft ab, ob die Gesamtzahl der angezeigten Formen/Bilder innerhalb eines Arbeitsblatts begrenzt werden soll, wenn auf „true“ gesetzt.<br/> GridJs begrenzt die gesamte Anzeigeform/Bildgröße innerhalb eines Arbeitsblatts auf MaxShapeOrImageCount<br/> Der Standardwert ist wahr.|
| [max_shape_or_image_count](/cells/python-net/de/aspose.cellsgridjs/config/max_shape_or_image_count) | Setzt/ruft die Gesamtzahl der Anzeigeformen/Bilder im aktiven Blatt ab. Dies wird wirksam, wenn IslimitShapes=true.<br/> Der Standardwert ist 100.|
| [max_total_shape_or_image_count](/cells/python-net/de/aspose.cellsgridjs/config/max_total_shape_or_image_count) | Setzt/ruft die Gesamtzahl der Anzeigeformen/Bilder in der gesamten Arbeitsmappe ab. Dies wird wirksam, wenn IslimitShapes=true.<br/> Der Standardwert ist 300.|
| [max_shape_or_image_width_or_height](/cells/python-net/de/aspose.cellsgridjs/config/max_shape_or_image_width_or_height) | Setzt/ruft die maximale Breite oder Höhe für eine Form/ein Bild ab. GridJs ignoriert die Form/das Bild mit einer größeren Breite oder Höhe. Dies wird wirksam, wenn IslimitShapes=true.<br/> Der Standardwert ist 10000.|
| [max_pdf_save_seconds](/cells/python-net/de/aspose.cellsgridjs/config/max_pdf_save_seconds) | Setzt/ruft die maximale Zeitüberschreitung in Sekunden beim Speichern als PDF ab.<br/> Der Standardwert ist 10.|
| [ignore_empty_content](/cells/python-net/de/aspose.cellsgridjs/config/ignore_empty_content) | Legt fest/ruft ab, ob der maximale Bereich angezeigt werden soll, der Daten, Stil, zusammengeführte Zellen und Formen umfasst.<br/> wenn die letzte Zeile oder Spalte Zellen ohne Wert und Formel enthält, aber über einen benutzerdefinierten Stil verfügt<br/>dann werden wir diese Zeile/Spalte nicht anzeigen, wenn dieser Wert wahr ist.<br/> Der Standardwert ist true .|
| [use_print_area](/cells/python-net/de/aspose.cellsgridjs/config/use_print_area) |Legt fest/ruft ab, ob PageSetup.PrintArea für den UI-Anzeigebereich verwendet werden soll, wenn das Arbeitsblatt über eine PageSetup-Einstellung für PrintArea verfügt.<br/> Der Standardwert ist false .|
| [load_time_out](/cells/python-net/de/aspose.cellsgridjs/config/load_time_out) | Setzt/ruft einen Timeout-Interrupt in Millisekunden beim Laden der Datei ab. Wenn die Ladezeit der Datei länger als erwartet ist, wird eine Ausnahme ausgelöst.<br/> Der Standardwert ist -1, was bedeutet, dass kein Timeout-Interrupt festgelegt ist.|
| [show_chart_sheet](/cells/python-net/de/aspose.cellsgridjs/config/show_chart_sheet) | Legt fest/ruft ab, ob das Diagrammarbeitsblatt angezeigt werden soll.<br/> Der Standardwert ist false .|
| [page_size](/cells/python-net/de/aspose.cellsgridjs/config/page_size) | Legt fest/ruft ab, ob eine Paginierung durchgeführt werden soll<br/> GridJs begrenzt die Zeilengröße basierend auf PageSize. Wenn PageSize -1 ist, wird keine Paginierung durchgeführt<br/> Der Standardwert ist -1|
| [empty_sheet_max_row](/cells/python-net/de/aspose.cellsgridjs/config/empty_sheet_max_row) | Legt die maximale Standardzeile für ein leeres Arbeitsblatt fest bzw. ruft diese ab.<br/> Der Standardwert ist 12.|
| [empty_sheet_max_col](/cells/python-net/de/aspose.cellsgridjs/config/empty_sheet_max_col) | Setzt/ruft die standardmäßige maximale Spalte für ein leeres Arbeitsblatt ab.<br/> Der Standardwert ist 15.|
| [picture_cache_directory](/cells/python-net/de/aspose.cellsgridjs/config/picture_cache_directory) | Setzt/ruft das Cache-Verzeichnis für Bilder ab. (Dies wird wirksam, wenn GridJsWorkbook.CacheImp null ist.)<br/> Der Standardpfad ist „_piccache“ im FileCacheDirectory.|
| [file_cache_directory](/cells/python-net/de/aspose.cellsgridjs/config/file_cache_directory) |Setzt/ruft das Cache-Verzeichnis für die Tabellenkalkulationsdatei ab.<br/> Wir müssen es auf einen bestimmten Pfad festlegen, bevor wir GridJs verwenden.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [set_license](/cells/python-net/de/aspose.cellsgridjs/config/set_license/#str) |  |
| [set_license](/cells/python-net/de/aspose.cellsgridjs/config/set_license/#io.RawIOBase) | Lizenziert die Komponente.|
| [set_font_folder](/cells/python-net/de/aspose.cellsgridjs/config/set_font_folder/#str-bool) | Legt den Schriftartenordner fest|
| [set_font_folders](/cells/python-net/de/aspose.cellsgridjs/config/set_font_folders/#list-bool) | Legt die Schriftartenordner fest|



###  Siehe auch
* Modul [`aspose.cellsgridjs`](..)
