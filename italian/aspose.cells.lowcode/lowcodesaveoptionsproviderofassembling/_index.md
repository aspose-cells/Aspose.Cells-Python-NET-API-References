---
title: LowCodeSaveOptionsProviderOfAssembling classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 110
url: /it/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/
is_root: false
---
##  LowCodeSaveOptionsProviderOfAssembling classe
Implementazione per fornire opzioni di salvataggio che salvano le parti divise nei file
e il percorso del file risultante è denominato (potrebbe contenere directory):
[`LowCodeSaveOptionsProviderOfAssembling.path_header`](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#path_header)+[`LowCodeSaveOptionsProviderOfAssembling.sheet_prefix`](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#sheet_prefix)+SheetIndex(o SheetName)
+[`LowCodeSaveOptionsProviderOfAssembling.split_part_prefix`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#split_part_prefix)+SplitPartIndex+[`LowCodeSaveOptionsProviderOfAssembling.path_tail`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#path_tail).



**Eredità:** [`LowCodeSaveOptionsProviderOfAssembling`](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling)



Il tipo LowCodeSaveOptionsProviderOfAssembling espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [`__init__(self)`](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/__init__/#) | Costruisce una nuova istanza di LowCodeSaveOptionsProviderOfAssembling|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [path_header](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/path_header) | Parte dell'intestazione (prima dell'aggiunta del contenuto del foglio e della parte divisa) del percorso del file.|
| [path_tail](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/path_tail) | Parte finale (dopo i numeri di sequenza) del percorso del file.<br/> Dovrebbe includere l'estensione del nome del file.|
| [use_sheet_name](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/use_sheet_name) | Specifica se il percorso del file viene creato con il nome del foglio anziché con l'indice del foglio. Il valore predefinito è "false".|
| [sheet_prefix](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/sheet_prefix) |Prefisso per l'indice del foglio di lavoro.|
| [split_part_prefix](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/split_part_prefix) | Prefisso per l'indice della parte divisa.|
| [sheet_index_offset](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/sheet_index_offset) | Scostamento dell'indice del foglio rispetto a quanto utilizzato nel percorso del file<br/> e il suo valore effettivo ([`SplitPartInfo.sheet_index`](/cells/python-net/it/aspose.cells.lowcode/splitpartinfo#sheet_index)).|
| [split_part_index_offset](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/split_part_index_offset) | Scostamento dell'indice della parte divisa rispetto a quanto utilizzato nel percorso del file<br/> e il suo valore effettivo ([`SplitPartInfo.part_index`](/cells/python-net/it/aspose.cells.lowcode/splitpartinfo#part_index)).|
| [build_path_with_sheet_always](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/build_path_with_sheet_always) | Se aggiungere sempre l'indice del foglio o il nome al percorso del file.<br/>Il valore predefinito è falso, ovvero quando è presente un solo foglio,<br/> l'indice del foglio (o nome) e il prefisso corrispondente non verranno aggiunti al percorso del file.|
| [build_path_with_split_part_always](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/build_path_with_split_part_always) | Se aggiungere sempre l'indice della parte divisa al percorso del file.<br/>Il valore predefinito è falso, ovvero quando c'è una sola parte divisa,<br/> l'indice della parte divisa e il prefisso corrispondente non verranno aggiunti al percorso del file.|
| [save_options_template](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/save_options_template) | Modello per la creazione di istanze di opzioni di salvataggio in [`LowCodeSaveOptionsProviderOfAssembling.get_save_options`](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/get_save_options).|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`get_save_options(self, part)`](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/get_save_options/#aspose.cells.lowcode.splitpartinfo) | Ottiene le opzioni di salvataggio da cui ottenere le impostazioni di output per la parte attualmente divisa.|
| [`finish(self, part)`](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/finish/#aspose.cells.lowcode.lowcodesaveoptions) |  |



###  Guarda anche
* modulo [`aspose.cells.lowcode`](..)
* classe [`LowCodeSaveOptionsProviderOfAssembling`](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling)
