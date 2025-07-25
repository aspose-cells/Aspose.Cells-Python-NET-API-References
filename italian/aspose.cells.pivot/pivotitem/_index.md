---
title: PivotItem classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 180
url: /it/aspose.cells.pivot/pivotitem/
is_root: false
---
##  PivotItem classe
Rappresenta un elemento in un report PivotField.



Il tipo PivotItem espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [is_hidden](/cells/python-net/it/aspose.cells.pivot/pivotitem/is_hidden) | Ottiene e imposta se l'elemento pivot è nascosto.|
| [position](/cells/python-net/it/aspose.cells.pivot/pivotitem/position) | Specificare l'indice di posizione in tutti i PivotItems, non nei PivotItems sotto lo stesso nodo padre.|
| [position_in_same_parent_node](/cells/python-net/it/aspose.cells.pivot/pivotitem/position_in_same_parent_node) | Specificare l'indice di posizione nei PivotItems sotto lo stesso nodo padre.|
| [is_hide_detail](/cells/python-net/it/aspose.cells.pivot/pivotitem/is_hide_detail) | Ottiene e imposta se l'elemento pivot nasconde i dettagli.|
| [is_detail_hidden](/cells/python-net/it/aspose.cells.pivot/pivotitem/is_detail_hidden) |Ottiene e imposta se i dettagli di questo elemento pivot sono nascosti.|
| [is_calculated_item](/cells/python-net/it/aspose.cells.pivot/pivotitem/is_calculated_item) | Indica se questo elemento pivot è un elemento formula calcolato.|
| [is_formula](/cells/python-net/it/aspose.cells.pivot/pivotitem/is_formula) | Indica se questo elemento pivot è un elemento formula calcolato.|
| [is_missing](/cells/python-net/it/aspose.cells.pivot/pivotitem/is_missing) | Indica se l'elemento è stato rimosso dall'origine dati.|
| [value](/cells/python-net/it/aspose.cells.pivot/pivotitem/value) | Ottiene il valore dell'elemento pivot|
| [name](/cells/python-net/it/aspose.cells.pivot/pivotitem/name) | Ottiene il nome dell'elemento pivot.|
| [index](/cells/python-net/it/aspose.cells.pivot/pivotitem/index) | Ottiene l'indice dell'elemento pivot nel campo cache.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`move(self, count, is_same_parent)`](/cells/python-net/it/aspose.cells.pivot/pivotitem/move/#int-bool) | Sposta l'elemento verso l'alto o verso il basso|
| [`get_formula(self)`](/cells/python-net/it/aspose.cells.pivot/pivotitem/get_formula/#) | Ottiene la formula di questo elemento calcolato.<br/> Funziona solo se questo elemento è un elemento calcolato.|
| [`get_string_value(self)`](/cells/python-net/it/aspose.cells.pivot/pivotitem/get_string_value/#) | Ottiene il valore stringa dell'elemento pivot<br/> Se il valore è nullo, verrà restituito ""|
| [`get_double_value(self)`](/cells/python-net/it/aspose.cells.pivot/pivotitem/get_double_value/#) | Ottiene il valore double dell'elemento pivot<br/> Se il valore è nullo o non è un numero, restituirà 0|
| [`get_date_time_value(self)`](/cells/python-net/it/aspose.cells.pivot/pivotitem/get_date_time_value/#) | Ottiene il valore di data e ora dell'elemento pivot<br/> Se il valore è nullo, restituirà DateTime.MinValue|



###  Guarda anche
* modulo [`aspose.cells.pivot`](..)
