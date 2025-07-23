---
title: LowCodeSaveOptionsProviderOfPlaceHolders klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 120
url: /sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/
is_root: false
---
##  LowCodeSaveOptionsProviderOfPlaceHolders klass
Implementering för att tillhandahålla sparalternativ som sparar delade delar till filer
och sökvägen till den resulterande filen definieras med platshållare.



**Arv:** [`LowCodeSaveOptionsProviderOfPlaceHolders`](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders)



Typen LowCodeSaveOptionsProviderOfPlaceHolders avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [`__init__(self, path_template)`](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/__init__/#str) |Instansierar en instans för att tillhandahålla sparalternativ enligt angivna mallar.|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [sheet_index_offset](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/sheet_index_offset) | Förskjutning av arkets index mellan det som används i filsökvägen<br/> och dess faktiska värde ([`SplitPartInfo.sheet_index`](/cells/python-net/sv/aspose.cells.lowcode/splitpartinfo#sheet_index)).|
| [split_part_index_offset](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/split_part_index_offset) | Förskjutning av delad dels index mellan vad som används i filsökvägen<br/> och dess faktiska värde ([`SplitPartInfo.part_index`](/cells/python-net/sv/aspose.cells.lowcode/splitpartinfo#part_index)).|
| [build_path_with_sheet_always](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/build_path_with_sheet_always) | Om arkindex eller namn alltid ska läggas till i filsökvägen.<br/>Standardvärdet är falskt, det vill säga när det bara finns ett ark,<br/>arkindex och namn och motsvarande prefix ([`LowCodeSaveOptionsProviderOfPlaceHolders.sheet_name_prefix`](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders#sheet_name_prefix))<br/> kommer inte att läggas till i filsökvägen.|
| [build_path_with_split_part_always](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/build_path_with_split_part_always) | Om delat delindex alltid ska läggas till i filsökvägen.<br/>Standardvärdet är falskt, det vill säga när det bara finns en delad del,<br/>delindexet och motsvarande prefix ([`LowCodeSaveOptionsProviderOfPlaceHolders.split_part_prefix`](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders#split_part_prefix))<br/> kommer inte att läggas till i filsökvägen.|
| [sheet_name_prefix](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/sheet_name_prefix) |Prefix för kalkylbladets index.|
| [sheet_index_prefix](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/sheet_index_prefix) |Prefix för kalkylbladets index.|
| [split_part_prefix](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/split_part_prefix) | Prefix för indexet för den delade delen.|
| [save_options_template](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/save_options_template) | Mallen för att skapa en instans av sparalternativ i [`LowCodeSaveOptionsProviderOfPlaceHolders.get_save_options`](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/get_save_options).|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`get_save_options(self, part)`](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/get_save_options/#aspose.cells.lowcode.splitpartinfo) | Hämtar sparalternativen för att hämta utdatainställningarna för den aktuellt delade delen.|
| [`finish(self, part)`](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/finish/#aspose.cells.lowcode.lowcodesaveoptions) |  |



###  Se även
* modul [`aspose.cells.lowcode`](..)
* klass [`LowCodeSaveOptionsProviderOfPlaceHolders`](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders)
