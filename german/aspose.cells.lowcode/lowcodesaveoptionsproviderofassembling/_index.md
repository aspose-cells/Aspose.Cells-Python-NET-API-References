---
title: LowCodeSaveOptionsProviderOfAssembling Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 110
url: /de/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/
is_root: false
---
##  LowCodeSaveOptionsProviderOfAssembling Klasse
Implementierung zur Bereitstellung von Speicheroptionen, mit denen abgetrennte Teile in Dateien gespeichert werden
und der Pfad der resultierenden Datei lautet (sie kann Verzeichnisse enthalten):
[`LowCodeSaveOptionsProviderOfAssembling.path_header`](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#path_header)+[`LowCodeSaveOptionsProviderOfAssembling.sheet_prefix`](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#sheet_prefix)+Blattindex(oder Blattname)
+[`LowCodeSaveOptionsProviderOfAssembling.split_part_prefix`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#split_part_prefix)+SplitPartIndex+[`LowCodeSaveOptionsProviderOfAssembling.path_tail`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#path_tail).



**Nachlass:** [`LowCodeSaveOptionsProviderOfAssembling`](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling)



Der Typ LowCodeSaveOptionsProviderOfAssembling macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [`__init__(self)`](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/__init__/#) | Erstellt eine neue Instanz von LowCodeSaveOptionsProviderOfAssembling|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [path_header](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/path_header) | Kopfteil (vor dem Hinzufügen des Blattinhalts und dem geteilten Teil) des Dateipfads.|
| [path_tail](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/path_tail) | Letzter Teil (nach den Sequenznummern) des Dateipfads.<br/> Es sollte die Erweiterung des Dateinamens enthalten.|
| [use_sheet_name](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/use_sheet_name) | Gibt an, ob der Dateipfad mit dem Blattnamen statt dem Blattindex erstellt wird. Der Standardwert ist „false“.|
| [sheet_prefix](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/sheet_prefix) |Präfix für den Index des Arbeitsblatts.|
| [split_part_prefix](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/split_part_prefix) | Präfix für den Index des geteilten Teils.|
| [sheet_index_offset](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/sheet_index_offset) | Offset des Blattindex zwischen dem im Dateipfad verwendeten<br/> und sein tatsächlicher Wert ([`SplitPartInfo.sheet_index`](/cells/python-net/de/aspose.cells.lowcode/splitpartinfo#sheet_index)).|
| [split_part_index_offset](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/split_part_index_offset) | Offset des Index des geteilten Teils zwischen dem, was im Dateipfad verwendet wird<br/> und sein tatsächlicher Wert ([`SplitPartInfo.part_index`](/cells/python-net/de/aspose.cells.lowcode/splitpartinfo#part_index)).|
| [build_path_with_sheet_always](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/build_path_with_sheet_always) | Ob immer Blattindex oder Name zum Dateipfad hinzugefügt werden soll.<br/>Der Standardwert ist „false“, d. h. wenn nur ein Blatt vorhanden ist,<br/> Der Blattindex (oder Name) und das entsprechende Präfix werden dem Dateipfad nicht hinzugefügt.|
| [build_path_with_split_part_always](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/build_path_with_split_part_always) | Ob dem Dateipfad immer ein geteilter Teilindex hinzugefügt wird.<br/>Der Standardwert ist „false“, d. h. wenn nur ein Teil geteilt ist,<br/> Der Split-Part-Index und das entsprechende Präfix werden dem Dateipfad nicht hinzugefügt.|
| [save_options_template](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/save_options_template) | Die Vorlage zum Erstellen einer Instanz von Speicheroptionen in [`LowCodeSaveOptionsProviderOfAssembling.get_save_options`](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/get_save_options).|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`get_save_options(self, part)`](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/get_save_options/#aspose.cells.lowcode.splitpartinfo) | Ruft die Speicheroptionen ab, aus denen die Ausgabeeinstellungen für den aktuell geteilten Teil abgerufen werden.|
| [`finish(self, part)`](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/finish/#aspose.cells.lowcode.lowcodesaveoptions) |  |



###  Siehe auch
* Modul [`aspose.cells.lowcode`](..)
* Klasse [`LowCodeSaveOptionsProviderOfAssembling`](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling)
