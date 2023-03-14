---
title: ExportTableOptions klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 550
url: /sv/aspose.cells/exporttableoptions/
is_root: false
---
##  ExportTableOptions klass
Representerar alla exporttabellalternativ.



Typen ExportTableOptions avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [ExportTableOptions()](/cells/python-net/sv/aspose.cells/exporttableoptions/__init__/#) | Konstruerar en ny instans av ExportTableOptions|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [export_column_name](/cells/python-net/sv/aspose.cells/exporttableoptions/export_column_name) |Anger om data i den första raden exporteras till datatabellens kolumnnamn.<br/> Standardvärdet är falskt.|
| [skip_error_value](/cells/python-net/sv/aspose.cells/exporttableoptions/skip_error_value) | Anger om ett ogiltigt värde för kolumnen hoppar över.<br/> Till exempel, om kolumntypen är decimal , är värdet större än decimal.MaxValue<br/>och den här egenskapen är sann, vi kommer inte att kasta undantag igen.<br/> Standardvärdet är falskt.|
| [plot_visible_cells](/cells/python-net/sv/aspose.cells/exporttableoptions/plot_visible_cells) | Exporterar endast synliga celler.|
| [plot_visible_rows](/cells/python-net/sv/aspose.cells/exporttableoptions/plot_visible_rows) | Exporterar endast synliga rader.|
| [plot_visible_columns](/cells/python-net/sv/aspose.cells/exporttableoptions/plot_visible_columns) | Exporterar endast synliga kolumner.|
| [export_as_string](/cells/python-net/sv/aspose.cells/exporttableoptions/export_as_string) | Exporterar strängvärdet för cellerna till datatabellen.|
| [export_as_html_string](/cells/python-net/sv/aspose.cells/exporttableoptions/export_as_html_string) | Exporterar html-strängvärdet för cellerna till datatabellen.|
| [format_strategy](/cells/python-net/sv/aspose.cells/exporttableoptions/format_strategy) | Hämtar och ställer in formatstrategin när värdet exporteras som strängvärde.|
| [check_mixed_value_type](/cells/python-net/sv/aspose.cells/exporttableoptions/check_mixed_value_type) | False, Aspose.Cells kommer att ställa in DataColumns typ efter värdetypen för den första raden för prestanda.<br/> Sant, Aspose.Cells kommer att kontrollera om värdetypen i kolumnen är blandad innan du ställer in DataColumns typ<br/> Och värdetypen är blandad, DataColumns typ kommer att vara sträng.|
| [is_vertical](/cells/python-net/sv/aspose.cells/exporttableoptions/is_vertical) | Sant om en rad i arbetsboksfilen representerar en rad i DataTable. Falskt om en kolumn i arbetsboksfilen representerar en rad i DataTable.|
| [indexes](/cells/python-net/sv/aspose.cells/exporttableoptions/indexes) | Indexen för kolumner/rader som ska exporteras ut.|
| [rename_strategy](/cells/python-net/sv/aspose.cells/exporttableoptions/rename_strategy) | Strategi för dubbletter av namn på kolumner.|



###  Se även
* modul [aspose.cells](..)
