---
title: LowCodeSaveOptionsProviderOfPlaceHolders Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 120
url: /de/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/
is_root: false
---
##  LowCodeSaveOptionsProviderOfPlaceHolders Klasse
Implementierung zur Bereitstellung von Speicheroptionen, mit denen abgetrennte Teile in Dateien gespeichert werden
und der Pfad der resultierenden Datei werden mit Platzhaltern definiert.



**Nachlass:** [`LowCodeSaveOptionsProviderOfPlaceHolders`](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders)



Der Typ LowCodeSaveOptionsProviderOfPlaceHolders macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [`__init__(self, path_template)`](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/__init__/#str) |Instanziiert eine Instanz, um Speicheroptionen gemäß angegebenen Vorlagen bereitzustellen.|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [sheet_index_offset](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/sheet_index_offset) | Offset des Blattindex zwischen dem im Dateipfad verwendeten<br/> und sein tatsächlicher Wert ([`SplitPartInfo.sheet_index`](/cells/python-net/de/aspose.cells.lowcode/splitpartinfo#sheet_index)).|
| [split_part_index_offset](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/split_part_index_offset) | Offset des Index des geteilten Teils zwischen dem, was im Dateipfad verwendet wird<br/> und sein tatsächlicher Wert ([`SplitPartInfo.part_index`](/cells/python-net/de/aspose.cells.lowcode/splitpartinfo#part_index)).|
| [build_path_with_sheet_always](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/build_path_with_sheet_always) | Ob immer Blattindex oder Name zum Dateipfad hinzugefügt werden soll.<br/>Der Standardwert ist „false“, d. h. wenn nur ein Blatt vorhanden ist,<br/>den Blattindex und -namen und das entsprechende Präfix ([`LowCodeSaveOptionsProviderOfPlaceHolders.sheet_name_prefix`](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders#sheet_name_prefix))<br/> wird nicht zum Dateipfad hinzugefügt.|
| [build_path_with_split_part_always](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/build_path_with_split_part_always) | Ob dem Dateipfad immer ein geteilter Teilindex hinzugefügt wird.<br/>Der Standardwert ist „false“, d. h. wenn nur ein Teil geteilt ist,<br/>der Split-Part-Index und das entsprechende Präfix ([`LowCodeSaveOptionsProviderOfPlaceHolders.split_part_prefix`](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders#split_part_prefix))<br/> wird nicht zum Dateipfad hinzugefügt.|
| [sheet_name_prefix](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/sheet_name_prefix) |Präfix für den Index des Arbeitsblatts.|
| [sheet_index_prefix](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/sheet_index_prefix) |Präfix für den Index des Arbeitsblatts.|
| [split_part_prefix](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/split_part_prefix) | Präfix für den Index des geteilten Teils.|
| [save_options_template](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/save_options_template) | Die Vorlage zum Erstellen einer Instanz von Speicheroptionen in [`LowCodeSaveOptionsProviderOfPlaceHolders.get_save_options`](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/get_save_options).|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`get_save_options(self, part)`](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/get_save_options/#aspose.cells.lowcode.splitpartinfo) | Ruft die Speicheroptionen ab, aus denen die Ausgabeeinstellungen für den aktuell geteilten Teil abgerufen werden.|
| [`finish(self, part)`](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/finish/#aspose.cells.lowcode.lowcodesaveoptions) |  |



###  Siehe auch
* Modul [`aspose.cells.lowcode`](..)
* Klasse [`LowCodeSaveOptionsProviderOfPlaceHolders`](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders)
