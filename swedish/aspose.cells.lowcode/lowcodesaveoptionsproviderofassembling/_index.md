---
title: LowCodeSaveOptionsProviderOfAssembling klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 110
url: /sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/
is_root: false
---
##  LowCodeSaveOptionsProviderOfAssembling klass
Implementering för att tillhandahålla sparalternativ som sparar delade delar till filer
och sökvägen till den resulterande filen heter (den kan innehålla kataloger):
[`LowCodeSaveOptionsProviderOfAssembling.path_header`](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#path_header)+[`LowCodeSaveOptionsProviderOfAssembling.sheet_prefix`](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#sheet_prefix)+Arkindex (eller Arknamn)
+[`LowCodeSaveOptionsProviderOfAssembling.split_part_prefix`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#split_part_prefix)+SplitPartIndex+[`LowCodeSaveOptionsProviderOfAssembling.path_tail`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#path_tail).



**Arv:** [`LowCodeSaveOptionsProviderOfAssembling`](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling)



Typen LowCodeSaveOptionsProviderOfAssembling avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [`__init__(self)`](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/__init__/#) | Konstruerar en ny instans av LowCodeSaveOptionsProviderOfAssembling|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [path_header](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/path_header) | Rubrikdelen (före tillagt innehåll i arket och delad del) av filsökvägen.|
| [path_tail](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/path_tail) | Den efterföljande delen (efter sekvensnummer) av filsökvägen.<br/> Den bör innehålla filnamnstillägget.|
| [use_sheet_name](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/use_sheet_name) | Om filsökvägen ska byggas med arknamn istället för arkindex. Standardvärdet är falskt.|
| [sheet_prefix](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/sheet_prefix) |Prefix för kalkylbladets index.|
| [split_part_prefix](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/split_part_prefix) | Prefix för indexet för den delade delen.|
| [sheet_index_offset](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/sheet_index_offset) | Förskjutning av arkets index mellan det som används i filsökvägen<br/> och dess faktiska värde ([`SplitPartInfo.sheet_index`](/cells/python-net/sv/aspose.cells.lowcode/splitpartinfo#sheet_index)).|
| [split_part_index_offset](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/split_part_index_offset) | Förskjutning av delad dels index mellan vad som används i filsökvägen<br/> och dess faktiska värde ([`SplitPartInfo.part_index`](/cells/python-net/sv/aspose.cells.lowcode/splitpartinfo#part_index)).|
| [build_path_with_sheet_always](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/build_path_with_sheet_always) | Om arkindex eller namn alltid ska läggas till i filsökvägen.<br/>Standardvärdet är falskt, det vill säga när det bara finns ett ark,<br/> Arkindexet (eller namnet) och motsvarande prefix läggs inte till i filsökvägen.|
| [build_path_with_split_part_always](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/build_path_with_split_part_always) | Om delat delindex alltid ska läggas till i filsökvägen.<br/>Standardvärdet är falskt, det vill säga när det bara finns en delad del,<br/> Indexet för delad del och motsvarande prefix läggs inte till i filsökvägen.|
| [save_options_template](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/save_options_template) | Mallen för att skapa en instans av sparalternativ i [`LowCodeSaveOptionsProviderOfAssembling.get_save_options`](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/get_save_options).|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`get_save_options(self, part)`](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/get_save_options/#aspose.cells.lowcode.splitpartinfo) | Hämtar sparalternativen för att hämta utdatainställningarna för den aktuellt delade delen.|
| [`finish(self, part)`](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/finish/#aspose.cells.lowcode.lowcodesaveoptions) |  |



###  Se även
* modul [`aspose.cells.lowcode`](..)
* klass [`LowCodeSaveOptionsProviderOfAssembling`](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling)
