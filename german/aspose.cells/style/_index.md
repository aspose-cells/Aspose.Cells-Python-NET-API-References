---
title: Style Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1460
url: /de/aspose.cells/style/
is_root: false
---
##  Style Klasse
Stellt den Anzeigestil des Excel-Dokuments dar, z. B. Schriftart, Farbe, Ausrichtung, Rahmen usw.
Das Objekt Style enthält alle Stilattribute (Schriftart, Zahlenformat, Ausrichtung usw.) als Eigenschaften.



Der Typ Style macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [__init__](/cells/python-net/de/aspose.cells/style/__init__/#) | Initialisiert eine neue Instanz der Klasse [`Style`](/cells/python-net/de/aspose.cells/style).|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [background_theme_color](/cells/python-net/de/aspose.cells/style/background_theme_color) | Ruft die Hintergrunddesignfarbe ab und legt sie fest.|
| [foreground_theme_color](/cells/python-net/de/aspose.cells/style/foreground_theme_color) | Ruft die Vordergrund-Designfarbe ab und legt sie fest.|
| [name](/cells/python-net/de/aspose.cells/style/name) | Ruft den Namen des Stils ab oder legt ihn fest.|
| [pattern](/cells/python-net/de/aspose.cells/style/pattern) |Ruft den Hintergrundmustertyp der Zelle ab oder legt diesen fest.|
| [borders](/cells/python-net/de/aspose.cells/style/borders) | Ruft die [`BorderCollection`](/cells/python-net/de/aspose.cells/bordercollection) des Stils ab.|
| [background_color](/cells/python-net/de/aspose.cells/style/background_color) | Ruft die Hintergrundfarbe eines Stils ab oder legt diese fest.|
| [background_argb_color](/cells/python-net/de/aspose.cells/style/background_argb_color) | Ruft die Hintergrundfarbe mit einem 32-Bit-ARGB-Wert ab und legt sie fest.|
| [foreground_color](/cells/python-net/de/aspose.cells/style/foreground_color) | Ruft die Vordergrundfarbe eines Stils ab oder legt diese fest.|
| [foreground_argb_color](/cells/python-net/de/aspose.cells/style/foreground_argb_color) | Ruft die Vordergrundfarbe mit einem 32-Bit-ARGB-Wert ab und legt sie fest.|
| [has_borders](/cells/python-net/de/aspose.cells/style/has_borders) | Prüft, ob für den Stil Rahmen festgelegt wurden.|
| [parent_style](/cells/python-net/de/aspose.cells/style/parent_style) | Ruft den übergeordneten Stil dieses Stils ab.|
| [is_number_format_applied](/cells/python-net/de/aspose.cells/style/is_number_format_applied) | Geben Sie an, ob die Zahlenformatierung angewendet werden soll.|
| [is_font_applied](/cells/python-net/de/aspose.cells/style/is_font_applied) | Geben Sie an, ob die Schriftartformatierung angewendet werden soll.|
| [is_alignment_applied](/cells/python-net/de/aspose.cells/style/is_alignment_applied) | Geben Sie an, ob die Ausrichtungsformatierung angewendet werden soll.|
| [is_border_applied](/cells/python-net/de/aspose.cells/style/is_border_applied) | Geben Sie an, ob die Rahmenformatierung angewendet werden soll.|
| [is_fill_applied](/cells/python-net/de/aspose.cells/style/is_fill_applied) | Geben Sie an, ob die Füllformatierung angewendet werden soll.|
| [is_protection_applied](/cells/python-net/de/aspose.cells/style/is_protection_applied) | Geben Sie an, ob die Schutzformatierung angewendet werden soll.|
| [indent_level](/cells/python-net/de/aspose.cells/style/indent_level) | Stellt die Einzugsebene für die Zelle oder den Bereich dar. Kann nur eine ganze Zahl zwischen 0 und 250 sein.|
| [font](/cells/python-net/de/aspose.cells/style/font) | Ruft ein [`Style.font`](/cells/python-net/de/aspose.cells/style#font)-Objekt ab.|
| [rotation_angle](/cells/python-net/de/aspose.cells/style/rotation_angle) | Stellt den Textdrehwinkel dar.|
| [horizontal_alignment](/cells/python-net/de/aspose.cells/style/horizontal_alignment) |Ruft den horizontalen Ausrichtungstyp des Texts in einer Zelle ab oder legt diesen fest.|
| [vertical_alignment](/cells/python-net/de/aspose.cells/style/vertical_alignment) | Ruft den vertikalen Ausrichtungstyp des Texts in einer Zelle ab oder legt diesen fest.|
| [is_text_wrapped](/cells/python-net/de/aspose.cells/style/is_text_wrapped) | Ruft einen Wert ab, der angibt, ob der Text innerhalb einer Zelle umbrochen wird, oder legt diesen fest.|
| [number](/cells/python-net/de/aspose.cells/style/number) | Ruft das Anzeigeformat von Zahlen und Datumsangaben ab oder legt dieses fest. Die Formatierungsmuster sind je nach Region unterschiedlich.|
| [is_locked](/cells/python-net/de/aspose.cells/style/is_locked) | Ruft einen Wert ab, der angibt, ob eine Zelle geändert werden kann oder nicht, oder legt diesen fest.|
| [custom](/cells/python-net/de/aspose.cells/style/custom) | Stellt die benutzerdefinierte Zahlenformatzeichenfolge dieses Stilobjekts dar.<br/> Wenn das benutzerdefinierte Zahlenformat nicht festgelegt ist (z. B. das Zahlenformat ist integriert), wird „“ zurückgegeben.|
| [culture_custom](/cells/python-net/de/aspose.cells/style/culture_custom) | Ruft die kulturabhängige Musterzeichenfolge für das Zahlenformat ab und legt sie fest.<br/>Wenn für dieses Objekt kein Zahlenformat festgelegt wurde, wird null zurückgegeben.<br/> Wenn das Zahlenformat integriert ist, wird die Musterzeichenfolge zurückgegeben, die der integrierten Nummer entspricht.|
| [invariant_custom](/cells/python-net/de/aspose.cells/style/invariant_custom) | Ruft die kulturunabhängige Musterzeichenfolge für das Zahlenformat ab.<br/>Wenn für dieses Objekt kein Zahlenformat festgelegt wurde, wird null zurückgegeben.<br/> Wenn das Zahlenformat integriert ist, wird die Musterzeichenfolge zurückgegeben, die der integrierten Nummer entspricht.|
| [is_formula_hidden](/cells/python-net/de/aspose.cells/style/is_formula_hidden) |Gibt an, ob die Formel ausgeblendet wird, wenn das Arbeitsblatt geschützt ist.|
| [shrink_to_fit](/cells/python-net/de/aspose.cells/style/shrink_to_fit) | Stellt dar, ob der Text automatisch verkleinert wird, damit er in die verfügbare Spaltenbreite passt.|
| [text_direction](/cells/python-net/de/aspose.cells/style/text_direction) | Stellt die Lesereihenfolge des Textes dar.|
| [is_justify_distributed](/cells/python-net/de/aspose.cells/style/is_justify_distributed) | Gibt an, ob die Zellen im Blocksatz oder in der verteilten Ausrichtung in der letzten Textzeile verwendet werden sollen.|
| [quote_prefix](/cells/python-net/de/aspose.cells/style/quote_prefix) | Gibt an, ob der Wert der Zelle mit einem einfachen Anführungszeichen beginnt.|
| [is_gradient](/cells/python-net/de/aspose.cells/style/is_gradient) | Gibt an, ob die Zellschattierung ein Farbverlaufsmuster ist.|
| [is_percent](/cells/python-net/de/aspose.cells/style/is_percent) | Gibt an, ob das Zahlenformat ein Prozentformat ist.|
| [is_date_time](/cells/python-net/de/aspose.cells/style/is_date_time) | Gibt an, ob das Zahlenformat ein Datumsformat ist.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [set_border](/cells/python-net/de/aspose.cells/style/set_border/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.pydrawing.Color) | Legt die Grenzen des Stils fest.|
| [set_border](/cells/python-net/de/aspose.cells/style/set_border/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.cells.CellsColor) | Legt die Grenzen des Stils fest.|
| [set_pattern_color](/cells/python-net/de/aspose.cells/style/set_pattern_color/#aspose.cells.BackgroundType-aspose.pydrawing.Color-aspose.pydrawing.Color) | Legt die Hintergrundfarbe fest.|
| [copy](/cells/python-net/de/aspose.cells/style/copy/#aspose.cells.Style) | Kopiert Daten von einem anderen Stilobjekt|
| [update](/cells/python-net/de/aspose.cells/style/update/#) | Wenden Sie den benannten Stil auf die Stile der Zellen an, die diesen benannten Stil verwenden.<br/>Es funktioniert so, als ob Sie auf die Schaltfläche „OK“ klicken würden, nachdem Sie mit der Änderung des Stils fertig sind.<br/> Gilt nur für benannte Stile.|
| [is_modified](/cells/python-net/de/aspose.cells/style/is_modified/#aspose.cells.StyleModifyFlag) | Prüft, ob die angegebenen Eigenschaften des Stils geändert wurden.<br/>Wird für den Stil von ConditionalFormattings verwendet, um zu prüfen, ob die angegebenen Eigenschaften dieses Stils verwendet werden sollen, wenn die ConditionalFormattings auf eine Zelle angewendet werden.|
| [set_custom](/cells/python-net/de/aspose.cells/style/set_custom/#str-bool) | Legt die benutzerdefinierte Zahlenformatzeichenfolge einer Zelle fest.|
| [set_two_color_gradient](/cells/python-net/de/aspose.cells/style/set_two_color_gradient/#aspose.pydrawing.Color-aspose.pydrawing.Color-aspose.cells.drawing.GradientStyleType-int) | Legt die angegebene Füllung auf einen zweifarbigen Farbverlauf fest.|
| [get_two_color_gradient](/cells/python-net/de/aspose.cells/style/get_two_color_gradient/#aspose.pydrawing.Color&-aspose.pydrawing.Color&-any-any) | Holen Sie sich die Einstellung für den zweifarbigen Farbverlauf.|
| [get_two_color_gradient_setting](/cells/python-net/de/aspose.cells/style/get_two_color_gradient_setting/#) | Holen Sie sich die Einstellung für den zweifarbigen Farbverlauf.|
| [to_json](/cells/python-net/de/aspose.cells/style/to_json/#) | Konvertieren Sie Strukturdaten von [`Style`](/cells/python-net/de/aspose.cells/style) in JSON.|



###  Beispiel

```python
from aspose.cells import Workbook
from aspose.pydrawing import Color

workbook = Workbook()
sheets = workbook.worksheets
cell = sheets[0].cells.get("A1")
style = cell.get_style()
style.font.name = "Times New Roman"
style.font.color = Color.blue
cell.set_style(style)

```

###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`BorderCollection`](/cells/python-net/de/aspose.cells/bordercollection)
* Klasse [`Style`](/cells/python-net/de/aspose.cells/style)
