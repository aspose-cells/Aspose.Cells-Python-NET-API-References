---
title: Cell Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 110
url: /de/aspose.cells/cell/
is_root: false
---
##  Cell Klasse
Kapselt das Objekt, das eine einzelne Arbeitsmappenzelle darstellt.



Der Typ Cell macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [worksheet](/cells/python-net/de/aspose.cells/cell/worksheet) | Ruft das übergeordnete Arbeitsblatt ab.|
| [date_time_value](/cells/python-net/de/aspose.cells/cell/date_time_value) | Ruft den in der Zelle enthaltenen DateTime-Wert ab.|
| [row](/cells/python-net/de/aspose.cells/cell/row) | Ruft die Zeilennummer (nullbasiert) der Zelle ab.|
| [column](/cells/python-net/de/aspose.cells/cell/column) | Ruft die Spaltennummer (nullbasiert) der Zelle ab.|
| [is_formula](/cells/python-net/de/aspose.cells/cell/is_formula) | Gibt an, ob die angegebene Zelle eine Formel enthält.|
| [has_custom_function](/cells/python-net/de/aspose.cells/cell/has_custom_function) |Überprüft, ob die Formel dieser Zelle eine benutzerdefinierte Funktion (nicht unterstützte Funktion) enthält.|
| [type](/cells/python-net/de/aspose.cells/cell/type) | Stellt den Zellenwerttyp dar.|
| [name](/cells/python-net/de/aspose.cells/cell/name) | Ruft den Namen der Zelle ab.|
| [is_error_value](/cells/python-net/de/aspose.cells/cell/is_error_value) | Überprüft, ob der Wert dieser Zelle ein Fehler ist.|
| [is_numeric_value](/cells/python-net/de/aspose.cells/cell/is_numeric_value) | Gibt an, ob der Wert dieser Zelle numerisch ist (int, double und datetime)|
| [string_value](/cells/python-net/de/aspose.cells/cell/string_value) | Ruft den in der Zelle enthaltenen Zeichenfolgenwert ab. Wenn der Zellentyp Zeichenfolge ist, wird der Zeichenfolgenwert selbst zurückgegeben.<br/>Für andere Zelltypen wird der formatierte Zeichenfolgenwert (formatiert mit dem angegebenen Stil dieser Zelle) zurückgegeben.<br/>Der formatierte Zellenwert ist derselbe wie der, den Sie in Excel erhalten, wenn Sie eine Zelle als Text kopieren (z. B.<br/> Zelle in Texteditor kopieren oder in CSV exportieren).|
| [string_value_without_format](/cells/python-net/de/aspose.cells/cell/string_value_without_format) | Ruft den Zellenwert als Zeichenfolge ohne Format ab.|
| [number_category_type](/cells/python-net/de/aspose.cells/cell/number_category_type) | Stellt den Kategorietyp der Zahlenformatierung dieser Zelle dar.|
| [display_string_value](/cells/python-net/de/aspose.cells/cell/display_string_value) | Ruft den formatierten Zeichenfolgenwert dieser Zelle anhand des Anzeigestils der Zelle ab.|
| [int_value](/cells/python-net/de/aspose.cells/cell/int_value) | Ruft den in der Zelle enthaltenen Ganzzahlwert ab.|
| [double_value](/cells/python-net/de/aspose.cells/cell/double_value) | Ruft den in der Zelle enthaltenen Double-Wert ab.|
| [float_value](/cells/python-net/de/aspose.cells/cell/float_value) | Ruft den in der Zelle enthaltenen Gleitkommawert ab.|
| [bool_value](/cells/python-net/de/aspose.cells/cell/bool_value) | Ruft den in der Zelle enthaltenen Booleschen Wert ab.|
| [has_custom_style](/cells/python-net/de/aspose.cells/cell/has_custom_style) | Gibt an, ob diese Zelle benutzerdefinierte Stileinstellungen hat (anders als die übernommenen Standardeinstellungen).<br/>aus der entsprechenden Zeile, Spalte oder Arbeitsmappe).|
| [shared_style_index](/cells/python-net/de/aspose.cells/cell/shared_style_index) | Ruft den gemeinsamen Stilindex der Zelle im Stilpool ab.|
| [formula](/cells/python-net/de/aspose.cells/cell/formula) | Ruft eine Formel vom Typ [`Cell`](/cells/python-net/de/aspose.cells/cell) ab oder legt diese fest.|
| [formula_local](/cells/python-net/de/aspose.cells/cell/formula_local) | Ruft die lokal formatierte Formel der Zelle ab.|
| [r1c1_formula](/cells/python-net/de/aspose.cells/cell/r1c1_formula) | Ruft eine R1C1-Formel des [`Cell`](/cells/python-net/de/aspose.cells/cell) ab oder legt diese fest.|
| [contains_external_link](/cells/python-net/de/aspose.cells/cell/contains_external_link) | Gibt an, ob diese Zelle einen externen Link enthält.<br/> Gilt nur, wenn die Zelle eine Formelzelle ist.|
| [is_array_header](/cells/python-net/de/aspose.cells/cell/is_array_header) | Gibt an, dass die Formel der Zelle eine Array-Formel ist<br/> und es ist die erste Zelle des Arrays.|
| [is_dynamic_array_formula](/cells/python-net/de/aspose.cells/cell/is_dynamic_array_formula) | Gibt an, ob es sich bei der Formel der Zelle um eine dynamische Arrayformel (true) oder eine herkömmliche Arrayformel (false) handelt.|
| [is_array_formula](/cells/python-net/de/aspose.cells/cell/is_array_formula) | Gibt an, ob es sich bei der Zellenformel um eine Arrayformel handelt.|
| [is_in_array](/cells/python-net/de/aspose.cells/cell/is_in_array) | Gibt an, ob es sich bei der Zellenformel um eine Arrayformel handelt.|
| [is_shared_formula](/cells/python-net/de/aspose.cells/cell/is_shared_formula) | Gibt an, ob die Zellformel Teil einer gemeinsam genutzten Formel ist.|
| [is_table_formula](/cells/python-net/de/aspose.cells/cell/is_table_formula) | Gibt an, ob diese Zelle Teil einer Tabellenformel ist.|
| [is_in_table](/cells/python-net/de/aspose.cells/cell/is_in_table) | Gibt an, ob diese Zelle Teil einer Tabellenformel ist.|
| [value](/cells/python-net/de/aspose.cells/cell/value) | Ruft den in dieser Zelle enthaltenen Wert ab/legt ihn fest.|
| [is_style_set](/cells/python-net/de/aspose.cells/cell/is_style_set) | Gibt an, ob der Stil der Zelle festgelegt ist. Wenn „false“ zurückgegeben wird, bedeutet dies, dass diese Zelle ein Standardzellenformat hat.|
| [is_merged](/cells/python-net/de/aspose.cells/cell/is_merged) | Überprüft, ob eine Zelle Teil eines zusammengeführten Bereichs ist oder nicht.|
| [comment](/cells/python-net/de/aspose.cells/cell/comment) |Ruft den Kommentar dieser Zelle ab.|
| [html_string](/cells/python-net/de/aspose.cells/cell/html_string) | Ruft die HTML-Zeichenfolge ab und legt sie fest, die Daten und einige Formate in dieser Zelle enthält.|
| [is_check_box_style](/cells/python-net/de/aspose.cells/cell/is_check_box_style) | Gibt an, ob diese Zelle als Kontrollkästchen festgelegt werden soll.|
| [embedded_image](/cells/python-net/de/aspose.cells/cell/embedded_image) | Ruft das eingebettete Bild in der Zelle ab und legt es fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`put_value(self, bool_value)`](/cells/python-net/de/aspose.cells/cell/put_value/#bool) | Fügt einen Booleschen Wert in die Zelle ein.|
| [`put_value(self, int_value)`](/cells/python-net/de/aspose.cells/cell/put_value/#int) | Fügt einen ganzzahligen Wert in die Zelle ein.|
| [`put_value(self, double_value)`](/cells/python-net/de/aspose.cells/cell/put_value/#float) | Fügt einen doppelten Wert in die Zelle ein.|
| [`put_value(self, string_value, is_converted, set_style)`](/cells/python-net/de/aspose.cells/cell/put_value/#str-bool-bool) | Fügt einen Wert in die Zelle ein. Gegebenenfalls wird der Wert in einen anderen Datentyp konvertiert und das Zahlenformat der Zelle wird zurückgesetzt.|
| [`put_value(self, string_value, is_converted)`](/cells/python-net/de/aspose.cells/cell/put_value/#str-bool) | Fügt einen Zeichenfolgenwert in die Zelle ein und konvertiert den Wert gegebenenfalls in einen anderen Datentyp.|
| [`put_value(self, string_value)`](/cells/python-net/de/aspose.cells/cell/put_value/#str) | Fügt einen Zeichenfolgenwert in die Zelle ein.|
| [`put_value(self, date_time)`](/cells/python-net/de/aspose.cells/cell/put_value/#datetime) | Fügt einen DateTime-Wert in die Zelle ein.|
| [`put_value(self, object_value)`](/cells/python-net/de/aspose.cells/cell/put_value/#any) | Fügt einen Objektwert in die Zelle ein.|
| [`get_display_style(self)`](/cells/python-net/de/aspose.cells/cell/get_display_style/#) | Ruft den Anzeigestil dieser Zelle ab.|
| [`get_display_style(self, include_merged_borders)`](/cells/python-net/de/aspose.cells/cell/get_display_style/#bool) | Ruft den Anzeigestil dieser Zelle ab.|
| [`get_display_style(self, adjacent_borders)`](/cells/python-net/de/aspose.cells/cell/get_display_style/#aspose.cells.bordertype) | Ruft den Anzeigestil dieser Zelle ab.|
| [`get_style(self)`](/cells/python-net/de/aspose.cells/cell/get_style/#) | Ruft den Zellenstil ab.|
| [`get_style(self, check_borders)`](/cells/python-net/de/aspose.cells/cell/get_style/#bool) | Wenn checkBorders wahr ist, prüfen Sie, ob die Ränder anderer Zellen den Stil dieser Zelle beeinflussen.|
| [`set_style(self, style)`](/cells/python-net/de/aspose.cells/cell/set_style/#aspose.cells.style) | Legt den Zellenstil fest.|
| [`set_style(self, style, explicit_flag)`](/cells/python-net/de/aspose.cells/cell/set_style/#aspose.cells.style-bool) | Wenden Sie die geänderte Stileigenschaft auf die Zelle an.|
| [`set_style(self, style, flag)`](/cells/python-net/de/aspose.cells/cell/set_style/#aspose.cells.style-aspose.cells.styleflag) |Wenden Sie den Zellenstil basierend auf Flaggen an.|
| [`set_formula(self, formula, value)`](/cells/python-net/de/aspose.cells/cell/set_formula/#str-any) | Legen Sie die Formel und den Wert (berechnetes Ergebnis) der Formel fest.|
| [`set_formula(self, formula, options)`](/cells/python-net/de/aspose.cells/cell/set_formula/#str-aspose.cells.formulaparseoptions) | Legen Sie die Formel und den Wert (berechnetes Ergebnis) der Formel fest.|
| [`set_formula(self, formula, is_r1c1, is_local, value)`](/cells/python-net/de/aspose.cells/cell/set_formula/#str-bool-bool-any) | Legen Sie die Formel und den Wert der Formel fest.|
| [`set_formula(self, formula, options, value)`](/cells/python-net/de/aspose.cells/cell/set_formula/#str-aspose.cells.formulaparseoptions-any) | Legen Sie die Formel und den Wert (berechnetes Ergebnis) der Formel fest.|
| [`set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local)`](/cells/python-net/de/aspose.cells/cell/set_array_formula/#str-int-int-bool-bool) | Legt eine Matrixformel für einen Zellbereich fest.|
| [`set_array_formula(self, array_formula, row_number, column_number)`](/cells/python-net/de/aspose.cells/cell/set_array_formula/#str-int-int) | Legt eine Arrayformel (alte Arrayformel, die in MS Excel über STRG+UMSCHALT+EINGABE eingegeben wurde) für einen Zellbereich fest.|
| [`set_array_formula(self, array_formula, row_number, column_number, options)`](/cells/python-net/de/aspose.cells/cell/set_array_formula/#str-int-int-aspose.cells.formulaparseoptions) | Legt eine Matrixformel für einen Zellbereich fest.|
| [`set_array_formula(self, array_formula, row_number, column_number, options, values)`](/cells/python-net/de/aspose.cells/cell/set_array_formula/#str-int-int-aspose.cells.formulaparseoptions-list) | Legt eine Matrixformel für einen Zellbereich fest.|
| [`set_shared_formula(self, shared_formula, row_number, column_number, is_r1c1, is_local)`](/cells/python-net/de/aspose.cells/cell/set_shared_formula/#str-int-int-bool-bool) | Legt eine Formel für einen Zellbereich fest.|
| [`set_shared_formula(self, shared_formula, row_number, column_number)`](/cells/python-net/de/aspose.cells/cell/set_shared_formula/#str-int-int) | Legt gemeinsame Formeln für einen Zellbereich fest.|
| [`set_shared_formula(self, shared_formula, row_number, column_number, options)`](/cells/python-net/de/aspose.cells/cell/set_shared_formula/#str-int-int-aspose.cells.formulaparseoptions) | Legt gemeinsame Formeln für einen Zellbereich fest.|
| [`set_shared_formula(self, shared_formula, row_number, column_number, options, values)`](/cells/python-net/de/aspose.cells/cell/set_shared_formula/#str-int-int-aspose.cells.formulaparseoptions-list) | Legt gemeinsame Formeln für einen Zellbereich fest.|
| [`get_leafs(self)`](/cells/python-net/de/aspose.cells/cell/get_leafs/#) | Rufen Sie alle Zellen ab, die direkt auf diese Zelle verweisen und aktualisiert werden müssen, wenn diese Zelle geändert wird.|
| [`get_leafs(self, recursive)`](/cells/python-net/de/aspose.cells/cell/get_leafs/#bool) | Ruft alle Zellen ab, die aktualisiert werden, wenn diese Zelle geändert wird.|
| [`set_dynamic_array_formula(self, array_formula, options, calculate_value)`](/cells/python-net/de/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.formulaparseoptions-bool) | Legt eine dynamische Array-Formel fest und sorgt dafür, dass die Formel, wenn möglich, in benachbarte Zellen überläuft.|
| [`set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value)`](/cells/python-net/de/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.formulaparseoptions-list-bool-bool) | Legt eine dynamische Array-Formel fest und sorgt dafür, dass die Formel, wenn möglich, in benachbarte Zellen überläuft.|
| [`set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts)`](/cells/python-net/de/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.formulaparseoptions-list-bool-bool-aspose.cells.calculationoptions) | Legt eine dynamische Array-Formel fest und sorgt dafür, dass die Formel, wenn möglich, in benachbarte Zellen überläuft.|
| [`set_table_formula(self, row_number, column_number, row_input_cell, column_input_cell, values)`](/cells/python-net/de/aspose.cells/cell/set_table_formula/#int-int-str-str-list) | Erstellen Sie ausgehend von dieser Zelle eine Datentabelle mit zwei Variablen für den angegebenen Bereich.|
| [`set_table_formula(self, row_number, column_number, input_cell, is_row_input, values)`](/cells/python-net/de/aspose.cells/cell/set_table_formula/#int-int-str-bool-list) | Erstellen Sie eine Datentabelle mit einer Variable für einen bestimmten Bereich, beginnend mit dieser Zelle.|
| [`set_table_formula(self, row_number, column_number, row_index_of_row_input_cell, column_index_of_row_input_cell, row_index_of_column_input_cell, column_index_of_column_input_cell, values)`](/cells/python-net/de/aspose.cells/cell/set_table_formula/#int-int-int-int-int-int-list) | Erstellen Sie ausgehend von dieser Zelle eine Datentabelle mit zwei Variablen für den angegebenen Bereich.|
| [`set_table_formula(self, row_number, column_number, row_index_of_input_cell, column_index_of_input_cell, is_row_input, values)`](/cells/python-net/de/aspose.cells/cell/set_table_formula/#int-int-int-int-bool-list) | Erstellen Sie eine Datentabelle mit einer Variable für einen bestimmten Bereich, beginnend mit dieser Zelle.|
| [`get_characters(self)`](/cells/python-net/de/aspose.cells/cell/get_characters/#) | Gibt alle Characters-Objekte zurück<br/> das einen Zeichenbereich innerhalb des Zellentextes darstellt.|
| [`get_characters(self, flag)`](/cells/python-net/de/aspose.cells/cell/get_characters/#bool) | Gibt alle Characters-Objekte zurück<br/> das einen Zeichenbereich innerhalb des Zellentextes darstellt.|
| [`calculate(self, options)`](/cells/python-net/de/aspose.cells/cell/calculate/#aspose.cells.calculationoptions) | Berechnet die Formel der Zelle.|
| [`get_string_value(self, format_strategy)`](/cells/python-net/de/aspose.cells/cell/get_string_value/#aspose.cells.cellvalueformatstrategy) |Ruft den Zeichenfolgenwert anhand einer bestimmten Formatierungsstrategie ab.|
| [`get_width_of_value(self)`](/cells/python-net/de/aspose.cells/cell/get_width_of_value/#) | Ruft die Breite des Werts in Pixeln ab.|
| [`get_height_of_value(self)`](/cells/python-net/de/aspose.cells/cell/get_height_of_value/#) | Ruft die Höhe des Werts in Pixeln ab.|
| [`get_format_conditions(self)`](/cells/python-net/de/aspose.cells/cell/get_format_conditions/#) | Ruft die Formatierungsbedingungen ab, die für diese Zelle gelten.|
| [`get_formula(self, is_r1c1, is_local)`](/cells/python-net/de/aspose.cells/cell/get_formula/#bool-bool) | Holen Sie sich die Formel dieser Zelle.|
| [`get_precedents(self)`](/cells/python-net/de/aspose.cells/cell/get_precedents/#) | Ruft alle Referenzen ab, die in der Formel dieser Zelle vorkommen.|
| [`get_dependents(self, is_all)`](/cells/python-net/de/aspose.cells/cell/get_dependents/#bool) | Holen Sie sich alle Zellen, deren Formel direkt auf diese Zelle verweist.|
| [`get_precedents_in_calculation(self)`](/cells/python-net/de/aspose.cells/cell/get_precedents_in_calculation/#) | Ruft alle Präzedenzfälle (Verweise auf Zellen in der aktuellen Arbeitsmappe) ab, die von der Formel dieser Zelle während der Berechnung verwendet werden.|
| [`get_dependents_in_calculation(self, recursive)`](/cells/python-net/de/aspose.cells/cell/get_dependents_in_calculation/#bool) | Ruft alle Zellen ab, deren Berechnungsergebnis von dieser Zelle abhängt.|
| [`get_array_range(self)`](/cells/python-net/de/aspose.cells/cell/get_array_range/#) | Ruft den Arraybereich ab, wenn die Formel der Zelle eine Arrayformel ist.|
| [`remove_array_formula(self, leave_normal_formula)`](/cells/python-net/de/aspose.cells/cell/remove_array_formula/#bool) | Array-Formel entfernen.|
| [`copy(self, cell)`](/cells/python-net/de/aspose.cells/cell/copy/#aspose.cells.cell) | Kopiert Daten aus einer Quellzelle.|
| [`characters(self, start_index, length)`](/cells/python-net/de/aspose.cells/cell/characters/#int-int) | Gibt ein Zeichenobjekt zurück, das einen Zeichenbereich innerhalb des Zellentextes darstellt.|
| [`replace(self, place_holder, new_value, options)`](/cells/python-net/de/aspose.cells/cell/replace/#str-str-aspose.cells.replaceoptions) | Ersetzen Sie den Text der Zelle durch Optionen.|
| [`insert_text(self, index, text)`](/cells/python-net/de/aspose.cells/cell/insert_text/#int-str) | Fügen Sie einige Zeichen in die Zelle ein.<br/> Wenn die Zelle reich formatiert ist, kann mit dieser Methode die ursprüngliche Formatierung beibehalten werden.|
| [`is_rich_text(self)`](/cells/python-net/de/aspose.cells/cell/is_rich_text/#) |Gibt an, ob der Zeichenfolgenwert dieser Zelle ein Rich-Format-Text ist.|
| [`set_characters(self, characters)`](/cells/python-net/de/aspose.cells/cell/set_characters/#list) | Legt das Rich-Text-Format der Zelle fest.|
| [`get_merged_range(self)`](/cells/python-net/de/aspose.cells/cell/get_merged_range/#) | Gibt ein [`Range`](/cells/python-net/de/aspose.cells/range)-Objekt zurück, das einen zusammengeführte Bereich darstellt.|
| [`get_html_string(self, html5)`](/cells/python-net/de/aspose.cells/cell/get_html_string/#bool) | Ruft die HTML-Zeichenfolge ab, die Daten und einige Formate in dieser Zelle enthält.|
| [`to_json(self)`](/cells/python-net/de/aspose.cells/cell/to_json/#) | Konvertieren Sie [`Cell`](/cells/python-net/de/aspose.cells/cell) in JSON Strukturdaten.|
| [`equals(self, cell)`](/cells/python-net/de/aspose.cells/cell/equals/#aspose.cells.cell) | Überprüft, ob dieses Objekt mit einem anderen Zellobjekt auf dieselbe Zelle verweist.|
| [`get_conditional_formatting_result(self)`](/cells/python-net/de/aspose.cells/cell/get_conditional_formatting_result/#) | Holen Sie sich das Ergebnis der bedingten Formatierung.|
| [`get_validation(self)`](/cells/python-net/de/aspose.cells/cell/get_validation/#) | Ruft die auf diese Zelle angewendete Validierung ab.|
| [`get_validation_value(self)`](/cells/python-net/de/aspose.cells/cell/get_validation_value/#) | Ruft den Wert der Validierung ab, die auf diese Zelle angewendet wurde.|
| [`get_table(self)`](/cells/python-net/de/aspose.cells/cell/get_table/#) | Ruft die Tabelle ab, die diese Zelle enthält.|
| [`get_rich_value(self)`](/cells/python-net/de/aspose.cells/cell/get_rich_value/#) | Ruft den Gesamtwert der Zelle ab.|



###  Beispiel

```python
from aspose.cells import TextAlignmentType, Workbook
from aspose.pydrawing import Color

excel = Workbook()
cells = excel.worksheets[0].cells
# Put a string into a cell
cell = cells.get(0, 0)
cell.put_value("Hello")
first = cell.string_value
# Put an integer into a cell
cell = cells.get("B1")
cell.put_value(12)
second = cell.int_value
# Put a double into a cell
cell = cells.get(0, 2)
cell.put_value(-1.234)
third = cell.double_value
# Put a formula into a cell
cell = cells.get("D1")
cell.formula = "=B1 + C1"
# Put a combined formula: "sum(average(b1,c1), b1)" to cell at b2
cell = cells.get("b2")
cell.formula = "=sum(average(b1,c1), b1)"
# Set style of a cell
style = cell.get_style()
# Set background color
style.background_color = Color.yellow
# Set format of a cell
style.font.name = "Courier New"
style.vertical_alignment = TextAlignmentType.TOP
cell.set_style(style)

```

###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`Cell`](/cells/python-net/de/aspose.cells/cell)
* Klasse [`Range`](/cells/python-net/de/aspose.cells/range)
