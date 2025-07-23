---
title: LowCodeSaveOptionsProviderOfPlaceHolders classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 120
url: /it/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/
is_root: false
---
##  LowCodeSaveOptionsProviderOfPlaceHolders classe
Implementazione per fornire opzioni di salvataggio che salvano le parti divise nei file
e il percorso del file risultante sono definiti con segnaposto.



**Eredità:** [`LowCodeSaveOptionsProviderOfPlaceHolders`](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders)



Il tipo LowCodeSaveOptionsProviderOfPlaceHolders espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [`__init__(self, path_template)`](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/__init__/#str) |Crea un'istanza per fornire opzioni di salvataggio in base ai modelli specificati.|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [sheet_index_offset](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/sheet_index_offset) | Scostamento dell'indice del foglio rispetto a quanto utilizzato nel percorso del file<br/> e il suo valore effettivo ([`SplitPartInfo.sheet_index`](/cells/python-net/it/aspose.cells.lowcode/splitpartinfo#sheet_index)).|
| [split_part_index_offset](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/split_part_index_offset) | Scostamento dell'indice della parte divisa rispetto a quanto utilizzato nel percorso del file<br/> e il suo valore effettivo ([`SplitPartInfo.part_index`](/cells/python-net/it/aspose.cells.lowcode/splitpartinfo#part_index)).|
| [build_path_with_sheet_always](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/build_path_with_sheet_always) | Se aggiungere sempre l'indice del foglio o il nome al percorso del file.<br/>Il valore predefinito è falso, ovvero quando è presente un solo foglio,<br/>l'indice del foglio e il nome e il prefisso corrispondente ([`LowCodeSaveOptionsProviderOfPlaceHolders.sheet_name_prefix`](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders#sheet_name_prefix))<br/> non verrà aggiunto al percorso del file.|
| [build_path_with_split_part_always](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/build_path_with_split_part_always) | Se aggiungere sempre l'indice della parte divisa al percorso del file.<br/>Il valore predefinito è falso, ovvero quando c'è una sola parte divisa,<br/>l'indice della parte divisa e il prefisso corrispondente ([`LowCodeSaveOptionsProviderOfPlaceHolders.split_part_prefix`](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders#split_part_prefix))<br/> non verrà aggiunto al percorso del file.|
| [sheet_name_prefix](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/sheet_name_prefix) |Prefisso per l'indice del foglio di lavoro.|
| [sheet_index_prefix](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/sheet_index_prefix) |Prefisso per l'indice del foglio di lavoro.|
| [split_part_prefix](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/split_part_prefix) | Prefisso per l'indice della parte divisa.|
| [save_options_template](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/save_options_template) | Modello per la creazione di istanze di opzioni di salvataggio in [`LowCodeSaveOptionsProviderOfPlaceHolders.get_save_options`](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/get_save_options).|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`get_save_options(self, part)`](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/get_save_options/#aspose.cells.lowcode.splitpartinfo) | Ottiene le opzioni di salvataggio da cui ottenere le impostazioni di output per la parte attualmente divisa.|
| [`finish(self, part)`](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/finish/#aspose.cells.lowcode.lowcodesaveoptions) |  |



###  Guarda anche
* modulo [`aspose.cells.lowcode`](..)
* classe [`LowCodeSaveOptionsProviderOfPlaceHolders`](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders)
