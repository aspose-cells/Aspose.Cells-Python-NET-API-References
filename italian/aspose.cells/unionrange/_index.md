---
title: UnionRange classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 1510
url: /it/aspose.cells/unionrange/
is_root: false
---
##  UnionRange classe
Rappresenta l'intervallo dell'unione.



Il tipo UnionRange espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [first_row](/cells/python-net/it/aspose.cells/unionrange/first_row) | Ottiene l'indice della prima riga dell'intervallo.|
| [first_column](/cells/python-net/it/aspose.cells/unionrange/first_column) | Ottiene l'indice della prima colonna dell'intervallo.|
| [row_count](/cells/python-net/it/aspose.cells/unionrange/row_count) | Ottiene il conteggio delle righe nell'intervallo.|
| [column_count](/cells/python-net/it/aspose.cells/unionrange/column_count) | Ottiene il conteggio delle righe nell'intervallo.|
| [value](/cells/python-net/it/aspose.cells/unionrange/value) | Ottiene e imposta i valori dell'intervallo.|
| [name](/cells/python-net/it/aspose.cells/unionrange/name) | Ottiene o imposta il nome dell'intervallo.|
| [refers_to](/cells/python-net/it/aspose.cells/unionrange/refers_to) | Ottiene l'intervallo a cui si riferisce.|
| [has_range](/cells/python-net/it/aspose.cells/unionrange/has_range) | Indica se c'è un intervallo.|
| [hyperlinks](/cells/python-net/it/aspose.cells/unionrange/hyperlinks) | Ottiene tutti i collegamenti ipertestuali nell'intervallo.|
| [cell_count](/cells/python-net/it/aspose.cells/unionrange/cell_count) | Ottiene il conteggio di tutte le celle nell'intervallo.|
| [range_count](/cells/python-net/it/aspose.cells/unionrange/range_count) |Ottiene il conteggio degli intervalli.|
| [ranges](/cells/python-net/it/aspose.cells/unionrange/ranges) | Ottiene tutti gli intervalli di unione.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`set_outline_borders(self, border_styles, border_colors)`](/cells/python-net/it/aspose.cells/unionrange/set_outline_borders/#list-aspose.pydrawing.color[]) | Imposta i bordi delle linee attorno a un intervallo di celle.|
| [`set_outline_borders(self, border_style, border_color)`](/cells/python-net/it/aspose.cells/unionrange/set_outline_borders/#aspose.cells.cellbordertype-aspose.pydrawing.color) | Imposta i bordi del contorno attorno a un intervallo di celle con lo stesso stile e colore.|
| [`intersect(self, range)`](/cells/python-net/it/aspose.cells/unionrange/intersect/#str) | Interseca un altro intervallo.|
| [`intersect(self, union_range)`](/cells/python-net/it/aspose.cells/unionrange/intersect/#aspose.cells.unionrange) | Interseca un altro intervallo.|
| [`intersect(self, ranges)`](/cells/python-net/it/aspose.cells/unionrange/intersect/#list) | Interseca un altro intervallo.|
| [`union(self, range)`](/cells/python-net/it/aspose.cells/unionrange/union/#str) | Unione un'altra gamma.|
| [`union(self, union_range)`](/cells/python-net/it/aspose.cells/unionrange/union/#aspose.cells.unionrange) | Unione un'altra gamma.|
| [`union(self, ranges)`](/cells/python-net/it/aspose.cells/unionrange/union/#list) | Unisci gli intervalli.|
| [`merge(self)`](/cells/python-net/it/aspose.cells/unionrange/merge/#) |Combina un intervallo di celle in un'unica cella.|
| [`un_merge(self)`](/cells/python-net/it/aspose.cells/unionrange/un_merge/#) | Annulla l'unione delle celle unite di questo intervallo.|
| [`put_value(self, string_value, is_converted, set_style)`](/cells/python-net/it/aspose.cells/unionrange/put_value/#str-bool-bool) | Inserisce un valore nell'intervallo; se appropriato, il valore verrà convertito in un altro tipo di dati e il formato numerico della cella verrà reimpostato.|
| [`set_style(self, style)`](/cells/python-net/it/aspose.cells/unionrange/set_style/#aspose.cells.style) | Imposta lo stile dell'intervallo.|
| [`apply_style(self, style, flag)`](/cells/python-net/it/aspose.cells/unionrange/apply_style/#aspose.cells.style-aspose.cells.styleflag) | Applica formati per un intervallo intero.|
| [`copy(self, range, options)`](/cells/python-net/it/aspose.cells/unionrange/copy/#aspose.cells.unionrange-aspose.cells.pasteoptions) | Copia dell'intervallo con le opzioni Incolla speciale.|



###  Guarda anche
* modulo [`aspose.cells`](..)
