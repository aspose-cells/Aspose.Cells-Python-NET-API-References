---
title: OoxmlSaveOptions Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1050
url: /de/aspose.cells/ooxmlsaveoptions/
is_root: false
---
##  OoxmlSaveOptions Klasse
Stellt die Optionen zum Speichern einer Office Open XML-Datei dar.



**Nachlass:** [`OoxmlSaveOptions`](/cells/python-net/aspose.cells/ooxmlsaveoptions) → 
[`SaveOptions`](/cells/python-net/de/aspose.cells/saveoptions)



Der Typ OoxmlSaveOptions macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [`__init__(self)`](/cells/python-net/de/aspose.cells/ooxmlsaveoptions/__init__/#) | Erstellt die Optionen zum Speichern der Office Open XML-Datei.|
| [`__init__(self, save_format)`](/cells/python-net/de/aspose.cells/ooxmlsaveoptions/__init__/#aspose.cells.saveformat) | Erstellt die Optionen zum Speichern der Office Open XML-Datei.|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [save_format](/cells/python-net/de/aspose.cells/ooxmlsaveoptions/save_format) | Ruft das Format der gespeicherten Datei ab.|
| [clear_data](/cells/python-net/de/aspose.cells/ooxmlsaveoptions/clear_data) | Leeren Sie die Arbeitsmappe, nachdem Sie die Datei gespeichert haben.|
| [cached_file_folder](/cells/python-net/de/aspose.cells/ooxmlsaveoptions/cached_file_folder) | Der Ordner für temporäre Dateien, die als Datencache verwendet werden können.|
| [validate_merged_areas](/cells/python-net/de/aspose.cells/ooxmlsaveoptions/validate_merged_areas) | Gibt an, ob zusammengeführte Zellen vor dem Speichern der Datei validiert werden sollen.|
| [merge_areas](/cells/python-net/de/aspose.cells/ooxmlsaveoptions/merge_areas) | Gibt an, ob die Bereiche der bedingten Formatierung und Validierung vor dem Speichern der Datei zusammengeführt werden sollen.|
| [create_directory](/cells/python-net/de/aspose.cells/ooxmlsaveoptions/create_directory) | Wenn der Wert auf „true“ gesetzt ist und das Verzeichnis nicht existiert, wird das Verzeichnis vor dem Speichern der Datei automatisch erstellt.|
| [sort_names](/cells/python-net/de/aspose.cells/ooxmlsaveoptions/sort_names) |Gibt an, ob vor dem Speichern der Datei die definierten Namen sortiert werden sollen.|
| [sort_external_names](/cells/python-net/de/aspose.cells/ooxmlsaveoptions/sort_external_names) | Gibt an, ob extern definierte Namen vor dem Speichern der Datei sortiert werden sollen.|
| [refresh_chart_cache](/cells/python-net/de/aspose.cells/ooxmlsaveoptions/refresh_chart_cache) | Gibt an, ob die Aktualisierung der Diagramm-Cache-Daten|
| [check_excel_restriction](/cells/python-net/de/aspose.cells/ooxmlsaveoptions/check_excel_restriction) | Ob die Einschränkung der Excel-Datei überprüft wird, wenn der Benutzer zellenbezogene Objekte ändert.<br/>Beispielsweise erlaubt Excel nicht die Eingabe von Zeichenfolgenwerten, die länger als 32 KB sind.<br/> Wenn Sie einen Wert eingeben, der länger als 32 KB ist, wird er abgeschnitten.|
| [update_smart_art](/cells/python-net/de/aspose.cells/ooxmlsaveoptions/update_smart_art) | Gibt an, ob die SmartArt-Einstellung aktualisiert wird.<br/> Der Standardwert ist „false“.|
| [encrypt_document_properties](/cells/python-net/de/aspose.cells/ooxmlsaveoptions/encrypt_document_properties) | Gibt an, ob Dokumenteigenschaften beim Speichern als XLS-Datei verschlüsselt werden sollen.<br/> Der Standardwert ist „true“.|
| [export_cell_name](/cells/python-net/de/aspose.cells/ooxmlsaveoptions/export_cell_name) | Gibt an, ob der Zellenname in eine Excel2007-XLSX-Datei (.xlsm, .xltx, .xltm) exportiert wird.<br/>Wenn auf die Ausgabedatei von SQL Server DTS zugegriffen werden kann, muss dieser Wert „true“ sein.<br/>Wenn Sie den Wert auf „false“ setzen, wird die Leistung erheblich gesteigert und die Dateigröße beim Erstellen großer Dateien reduziert.<br/> Der Standardwert ist „true“.|
| [update_zoom](/cells/python-net/de/aspose.cells/ooxmlsaveoptions/update_zoom) | Gibt an, ob der Skalierungsfaktor vor dem Speichern der Datei aktualisiert werden soll<br/> wenn die Eigenschaften PageSetup.FitToPagesWide und PageSetup.FitToPagesTall steuern, wie das Arbeitsblatt skaliert wird.|
| [enable_zip64](/cells/python-net/de/aspose.cells/ooxmlsaveoptions/enable_zip64) | Verwenden Sie beim Schreiben von Zip-Archiven immer ZIP64-Erweiterungen, auch wenn dies nicht erforderlich ist.|
| [embed_ooxml_as_ole_object](/cells/python-net/de/aspose.cells/ooxmlsaveoptions/embed_ooxml_as_ole_object) | Gibt an, ob Ooxml-Dateien von OleObject als OLE-Objekt eingebettet werden.|
| [compression_type](/cells/python-net/de/aspose.cells/ooxmlsaveoptions/compression_type) | Ruft den Komprimierungstyp für die OOXML-Datei ab und legt ihn fest.|
| [wps_compatibility](/cells/python-net/de/aspose.cells/ooxmlsaveoptions/wps_compatibility) | Gibt an, ob die XLS-Datei mit WPS kompatibler gemacht werden soll.|



###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`OoxmlSaveOptions`](/cells/python-net/de/aspose.cells/ooxmlsaveoptions)
* Klasse [`SaveOptions`](/cells/python-net/de/aspose.cells/saveoptions)
