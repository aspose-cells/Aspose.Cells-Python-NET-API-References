---
title: CopyOptions classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 340
url: /it/aspose.cells/copyoptions/
is_root: false
---
##  CopyOptions classe
Rappresenta le opzioni di copia.



Il tipo CopyOptions espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [`__init__(self)`](/cells/python-net/it/aspose.cells/copyoptions/__init__/#) | Costruttore CopyOptions.|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [keep_macros](/cells/python-net/it/aspose.cells/copyoptions/keep_macros) |Indica se mantenere le macro;|
| [extend_to_adjacent_range](/cells/python-net/it/aspose.cells/copyoptions/extend_to_adjacent_range) | Indica se estendere gli intervalli quando si copia l'intervallo nell'intervallo adiacente.|
| [copy_names](/cells/python-net/it/aspose.cells/copyoptions/copy_names) | Indica se copiare i nomi.|
| [copy_invalid_formulas_as_values](/cells/python-net/it/aspose.cells/copyoptions/copy_invalid_formulas_as_values) | Se la formula non è valida per la destinazione, copiare solo i valori.|
| [column_character_width](/cells/python-net/it/aspose.cells/copyoptions/column_character_width) | Indica se copiare la larghezza della colonna in unità di caratteri.|
| [refer_to_sheet_with_same_name](/cells/python-net/it/aspose.cells/copyoptions/refer_to_sheet_with_same_name) | In MS Excel, quando si copiano formule che fanno riferimento ad altri fogli di lavoro mentre si copia un foglio di lavoro in un altro,<br/>le formule copiate devono fare riferimento alla cartella di lavoro di origine.<br/>Tuttavia, in alcune situazioni l'utente potrebbe aver bisogno che le formule copiate facciano riferimento a fogli di lavoro con lo stesso nome<br/>nella stessa cartella di lavoro, ad esempio quando tali fogli di lavoro sono stati copiati prima di questa operazione di copia,<br/> allora questa proprietà dovrebbe essere mantenuta come vera.|
| [refer_to_destination_sheet](/cells/python-net/it/aspose.cells/copyoptions/refer_to_destination_sheet) | Quando si copia l'intervallo nello stesso file e il grafico fa riferimento al foglio di origine,<br/>Falso significa che l'origine dati del grafico copiato non verrà modificata.<br/> Vero significa che l'origine dati del grafico copiato fa riferimento al foglio di destinazione.|



###  Guarda anche
* modulo [`aspose.cells`](..)
