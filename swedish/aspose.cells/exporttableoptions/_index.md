---
title: ExportTableOptions klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 560
url: /sv/aspose.cells/exporttableoptions/
is_root: false
---
##  ExportTableOptions klass
Representerar alla exporttabellalternativ.



Typen ExportTableOptions avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [`__init__(self)`](/cells/python-net/sv/aspose.cells/exporttableoptions/__init__/#) | Konstruerar en ny instans av ExportTableOptions|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [export_column_name](/cells/python-net/sv/aspose.cells/exporttableoptions/export_column_name) | Anger om data i den första raden exporteras till kolumnnamnet i datatabellen.<br/> Standardvärdet är falskt.|
| [skip_error_value](/cells/python-net/sv/aspose.cells/exporttableoptions/skip_error_value) | Anger om ett ogiltigt värde för kolumnen hoppas över.<br/> Om till exempel kolumntypen är decimal är värdet större än decimal.MaxValue<br/>och den här egenskapen är sann, kommer vi inte att kasta undantag igen.<br/> Standardvärdet är falskt.|
| [plot_visible_cells](/cells/python-net/sv/aspose.cells/exporttableoptions/plot_visible_cells) | Exporterar endast synliga celler.|
| [plot_visible_rows](/cells/python-net/sv/aspose.cells/exporttableoptions/plot_visible_rows) | Exporterar endast synliga rader.|
| [plot_visible_columns](/cells/python-net/sv/aspose.cells/exporttableoptions/plot_visible_columns) | Exporterar endast synliga kolumner.|
| [export_as_string](/cells/python-net/sv/aspose.cells/exporttableoptions/export_as_string) | Exporterar strängvärdet för cellerna till datatabellen.|
| [export_as_html_string](/cells/python-net/sv/aspose.cells/exporttableoptions/export_as_html_string) | Exporterar cellernas HTML-strängvärde till datatabellen.|
| [format_strategy](/cells/python-net/sv/aspose.cells/exporttableoptions/format_strategy) | Hämtar och anger formatstrategin vid export av värdet som strängvärde.|
| [check_mixed_value_type](/cells/python-net/sv/aspose.cells/exporttableoptions/check_mixed_value_type) | Falskt, Aspose.Cells kommer att ställa in DataColumn-typen efter värdetypen för den första raden för prestanda.<br/> Sant, Aspose.Cells kontrollerar om värdetyperna i kolumnen är blandade innan DataColumn-typen anges.<br/> Och värdetyperna är blandade, DataColumns typ kommer att vara en sträng.|
| [allow_db_null](/cells/python-net/sv/aspose.cells/exporttableoptions/allow_db_null) |Det här värdet anger om DBNulls är tillåtna i den här tabellen.|
| [is_vertical](/cells/python-net/sv/aspose.cells/exporttableoptions/is_vertical) | Sant om en rad i arbetsboksfilen representerar en rad i datatabellen. Falskt om en kolumn i arbetsboksfilen representerar en rad i datatabellen.|
| [indexes](/cells/python-net/sv/aspose.cells/exporttableoptions/indexes) | Index för kolumner/rader som ska exporteras ut.|
| [rename_strategy](/cells/python-net/sv/aspose.cells/exporttableoptions/rename_strategy) | Strategi för dubbletter av kolumnnamn.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`preprocess_exported_value(self, cell_row, cell_column, value)`](/cells/python-net/sv/aspose.cells/exporttableoptions/preprocess_exported_value/#int-int-aspose.cells.cellvalue) | Förbearbeta värdet för den aktuella cellen som ska exporteras.|



###  Anmärkningar

Om det finns några speciella krav gällande exporten, som att ignorera felvärden, kan användaren utöka den här klassen
att skriva över motsvarande API:er för att uppnå målet.

###  Se även
* modul [`aspose.cells`](..)
