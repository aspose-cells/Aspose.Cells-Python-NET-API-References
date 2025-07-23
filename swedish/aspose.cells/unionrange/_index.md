---
title: UnionRange klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1510
url: /sv/aspose.cells/unionrange/
is_root: false
---
##  UnionRange klass
Representerar unionsintervallet.



Typen UnionRange avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [first_row](/cells/python-net/sv/aspose.cells/unionrange/first_row) | Hämtar indexet för den första raden i intervallet.|
| [first_column](/cells/python-net/sv/aspose.cells/unionrange/first_column) | Hämtar indexet för den första kolumnen i intervallet.|
| [row_count](/cells/python-net/sv/aspose.cells/unionrange/row_count) | Hämtar antalet rader i intervallet.|
| [column_count](/cells/python-net/sv/aspose.cells/unionrange/column_count) | Hämtar antalet rader i intervallet.|
| [value](/cells/python-net/sv/aspose.cells/unionrange/value) | Hämtar och ställer in värdena för intervallet.|
| [name](/cells/python-net/sv/aspose.cells/unionrange/name) | Hämtar eller anger namnet på intervallet.|
| [refers_to](/cells/python-net/sv/aspose.cells/unionrange/refers_to) | Hämtar intervallet som refererar till.|
| [has_range](/cells/python-net/sv/aspose.cells/unionrange/has_range) | Anger om detta har ett räckvidd.|
| [hyperlinks](/cells/python-net/sv/aspose.cells/unionrange/hyperlinks) | Hämtar alla hyperlänkar inom intervallet.|
| [cell_count](/cells/python-net/sv/aspose.cells/unionrange/cell_count) | Hämtar allt cellantal inom intervallet.|
| [range_count](/cells/python-net/sv/aspose.cells/unionrange/range_count) |Hämtar antalet intervall.|
| [ranges](/cells/python-net/sv/aspose.cells/unionrange/ranges) | Hämtar alla unionsområden.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`set_outline_borders(self, border_styles, border_colors)`](/cells/python-net/sv/aspose.cells/unionrange/set_outline_borders/#list-aspose.pydrawing.color[]) | Anger linjekanter runt ett cellområde.|
| [`set_outline_borders(self, border_style, border_color)`](/cells/python-net/sv/aspose.cells/unionrange/set_outline_borders/#aspose.cells.cellbordertype-aspose.pydrawing.color) | Ställer in konturkanterna runt ett cellområde med samma kantstil och färg.|
| [`intersect(self, range)`](/cells/python-net/sv/aspose.cells/unionrange/intersect/#str) | Korsar ett annat intervall.|
| [`intersect(self, union_range)`](/cells/python-net/sv/aspose.cells/unionrange/intersect/#aspose.cells.unionrange) | Korsar ett annat intervall.|
| [`intersect(self, ranges)`](/cells/python-net/sv/aspose.cells/unionrange/intersect/#list) | Korsar ett annat intervall.|
| [`union(self, range)`](/cells/python-net/sv/aspose.cells/unionrange/union/#str) | Union ett annat intervall.|
| [`union(self, union_range)`](/cells/python-net/sv/aspose.cells/unionrange/union/#aspose.cells.unionrange) | Union ett annat intervall.|
| [`union(self, ranges)`](/cells/python-net/sv/aspose.cells/unionrange/union/#list) | Förena intervallen.|
| [`merge(self)`](/cells/python-net/sv/aspose.cells/unionrange/merge/#) |Kombinerar ett cellområde till en enda cell.|
| [`un_merge(self)`](/cells/python-net/sv/aspose.cells/unionrange/un_merge/#) | Avlägsnar sammanslagna celler i detta område.|
| [`put_value(self, string_value, is_converted, set_style)`](/cells/python-net/sv/aspose.cells/unionrange/put_value/#str-bool-bool) | Lägger in ett värde i intervallet. Om lämpligt konverteras värdet till en annan datatyp och cellens talformat återställs.|
| [`set_style(self, style)`](/cells/python-net/sv/aspose.cells/unionrange/set_style/#aspose.cells.style) | Anger stilen för intervallet.|
| [`apply_style(self, style, flag)`](/cells/python-net/sv/aspose.cells/unionrange/apply_style/#aspose.cells.style-aspose.cells.styleflag) | Tillämpar format för ett helt intervall.|
| [`copy(self, range, options)`](/cells/python-net/sv/aspose.cells/unionrange/copy/#aspose.cells.unionrange-aspose.cells.pasteoptions) | Kopiera intervallet med specialinställningar för klistra in.|



###  Se även
* modul [`aspose.cells`](..)
