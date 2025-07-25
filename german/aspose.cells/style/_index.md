---
title: Style Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1350
url: /de/aspose.cells/style/
is_root: false
---
##  Style Klasse
Stellt den Anzeigestil des Excel-Dokuments dar, z. B. Schriftart, Farbe, Ausrichtung, Rahmen usw.
Das Objekt Style enthält alle Stilattribute (Schriftart, Zahlenformat, Ausrichtung usw.) als Eigenschaften.



Der Typ Style macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [`__init__(self)`](/cells/python-net/de/aspose.cells/style/__init__/#) | Initialisiert eine neue Instanz der Klasse [`Style`](/cells/python-net/de/aspose.cells/style).|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [background_theme_color](/cells/python-net/de/aspose.cells/style/background_theme_color) | Ruft die Hintergrunddesignfarbe ab und legt sie fest.|
| [foreground_theme_color](/cells/python-net/de/aspose.cells/style/foreground_theme_color) | Ruft die Vordergrunddesignfarbe ab und legt sie fest.|
| [name](/cells/python-net/de/aspose.cells/style/name) | Ruft den Namen des Stils ab oder legt ihn fest.|
| [pattern](/cells/python-net/de/aspose.cells/style/pattern) | Ruft den Mustertyp des Zellenhintergrunds ab oder legt ihn fest.|
| [borders](/cells/python-net/de/aspose.cells/style/borders) | Ruft die [`BorderCollection`](/cells/python-net/de/aspose.cells/bordercollection) des Stils ab.|
| [background_color](/cells/python-net/de/aspose.cells/style/background_color) | Ruft die Hintergrundfarbe eines Stils ab oder legt sie fest.|
| [background_argb_color](/cells/python-net/de/aspose.cells/style/background_argb_color) | Ruft die Hintergrundfarbe mit einem 32-Bit-ARGB-Wert ab und legt sie fest.|
| [foreground_color](/cells/python-net/de/aspose.cells/style/foreground_color) | Ruft die Vordergrundfarbe eines Stils ab oder legt sie fest.|
| [foreground_argb_color](/cells/python-net/de/aspose.cells/style/foreground_argb_color) | Ruft die Vordergrundfarbe mit einem 32-Bit-ARGB-Wert ab und legt sie fest.|
| [has_borders](/cells/python-net/de/aspose.cells/style/has_borders) | Überprüft, ob für den Stil Rahmen festgelegt wurden.|
| [parent_style](/cells/python-net/de/aspose.cells/style/parent_style) | Ruft den übergeordneten Stil dieses Stils ab.|
| [is_number_format_applied](/cells/python-net/de/aspose.cells/style/is_number_format_applied) | Geben Sie an, ob die Zahlenformatierung angewendet werden soll.|
| [is_font_applied](/cells/python-net/de/aspose.cells/style/is_font_applied) |Geben Sie an, ob die Schriftformatierung angewendet werden soll.|
| [is_alignment_applied](/cells/python-net/de/aspose.cells/style/is_alignment_applied) | Geben Sie an, ob die Ausrichtungsformatierung angewendet werden soll.|
| [is_border_applied](/cells/python-net/de/aspose.cells/style/is_border_applied) | Geben Sie an, ob die Rahmenformatierung angewendet werden soll.|
| [is_fill_applied](/cells/python-net/de/aspose.cells/style/is_fill_applied) | Geben Sie an, ob die Füllformatierung angewendet werden soll.|
| [is_protection_applied](/cells/python-net/de/aspose.cells/style/is_protection_applied) | Geben Sie an, ob die Schutzformatierung angewendet werden soll.|
| [indent_level](/cells/python-net/de/aspose.cells/style/indent_level) | Stellt die Einzugsebene für die Zelle oder den Bereich dar. Kann nur eine Ganzzahl zwischen 0 und 250 sein.|
| [font](/cells/python-net/de/aspose.cells/style/font) | Ruft ein [`Style.font`](/cells/python-net/de/aspose.cells/style#font)-Objekt ab.|
| [rotation_angle](/cells/python-net/de/aspose.cells/style/rotation_angle) | Stellt den Textdrehwinkel dar.|
| [horizontal_alignment](/cells/python-net/de/aspose.cells/style/horizontal_alignment) | Ruft den horizontalen Ausrichtungstyp des Texts in einer Zelle ab oder legt ihn fest.|
| [vertical_alignment](/cells/python-net/de/aspose.cells/style/vertical_alignment) | Ruft den vertikalen Ausrichtungstyp des Texts in einer Zelle ab oder legt ihn fest.|
| [is_text_wrapped](/cells/python-net/de/aspose.cells/style/is_text_wrapped) | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob der Text innerhalb einer Zelle umbrochen wird.|
| [number](/cells/python-net/de/aspose.cells/style/number) | Ruft das Anzeigeformat für Zahlen und Datumsangaben ab oder legt es fest. Die Formatierungsmuster sind je nach Region unterschiedlich.|
| [is_locked](/cells/python-net/de/aspose.cells/style/is_locked) | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob eine Zelle geändert werden kann oder nicht.|
| [custom](/cells/python-net/de/aspose.cells/style/custom) | Stellt die benutzerdefinierte Zahlenformatzeichenfolge dieses Stilobjekts dar.<br/>Wenn das benutzerdefinierte Zahlenformat nicht festgelegt ist (z. B. wenn das Zahlenformat integriert ist), wird "" zurückgegeben.|
| [culture_custom](/cells/python-net/de/aspose.cells/style/culture_custom) | Ruft die kulturabhängige Musterzeichenfolge für das Zahlenformat ab und legt sie fest.<br/>Wenn für dieses Objekt kein Zahlenformat festgelegt wurde, wird null zurückgegeben.<br/> Wenn das Zahlenformat integriert ist, wird die Musterzeichenfolge zurückgegeben, die der integrierten Zahl entspricht.|
| [invariant_custom](/cells/python-net/de/aspose.cells/style/invariant_custom) | Ruft die kulturunabhängige Musterzeichenfolge für das Zahlenformat ab.<br/>Wenn für dieses Objekt kein Zahlenformat festgelegt wurde, wird null zurückgegeben.<br/> Wenn das Zahlenformat integriert ist, wird die Musterzeichenfolge zurückgegeben, die der integrierten Zahl entspricht.|
| [is_formula_hidden](/cells/python-net/de/aspose.cells/style/is_formula_hidden) | Gibt an, ob die Formel ausgeblendet wird, wenn das Arbeitsblatt geschützt ist.|
| [shrink_to_fit](/cells/python-net/de/aspose.cells/style/shrink_to_fit) | Gibt an, ob der Text automatisch verkleinert wird, um in die verfügbare Spaltenbreite zu passen.|
| [text_direction](/cells/python-net/de/aspose.cells/style/text_direction) | Stellt die Lesereihenfolge des Textes dar.|
| [is_justify_distributed](/cells/python-net/de/aspose.cells/style/is_justify_distributed) | Gibt an, ob in der letzten Textzeile die Blocksatz- oder die verteilte Ausrichtung der Zellen verwendet werden soll.|
| [quote_prefix](/cells/python-net/de/aspose.cells/style/quote_prefix) | Gibt an, ob der Wert der Zelle mit einem einfachen Anführungszeichen beginnt.|
| [is_gradient](/cells/python-net/de/aspose.cells/style/is_gradient) | Gibt an, ob es sich bei der Zellenschattierung um ein Verlaufsmuster handelt.|
| [is_percent](/cells/python-net/de/aspose.cells/style/is_percent) | Gibt an, ob das Zahlenformat ein Prozentformat ist.|
| [is_date_time](/cells/python-net/de/aspose.cells/style/is_date_time) | Gibt an, ob es sich bei dem Zahlenformat um ein Datumsformat handelt.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`set_border(self, border_type, border_style, border_color)`](/cells/python-net/de/aspose.cells/style/set_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.pydrawing.color) | Legt die Grenzen des Stils fest.|
| [`set_border(self, border_type, border_style, border_color)`](/cells/python-net/de/aspose.cells/style/set_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.cells.cellscolor) | Legt die Grenzen des Stils fest.|
| [`set_pattern_color(self, pattern, color1, color2)`](/cells/python-net/de/aspose.cells/style/set_pattern_color/#aspose.cells.backgroundtype-aspose.pydrawing.color-aspose.pydrawing.color) |Legt die Hintergrundfarbe fest.|
| [`copy(self, style)`](/cells/python-net/de/aspose.cells/style/copy/#aspose.cells.style) | Kopiert Daten aus einem anderen Stilobjekt|
| [`update(self)`](/cells/python-net/de/aspose.cells/style/update/#) | Wenden Sie den benannten Stil auf die Stile der Zellen an, die diesen benannten Stil verwenden.<br/>Es funktioniert wie das Klicken auf die Schaltfläche „OK“, nachdem Sie die Stiländerung abgeschlossen haben.<br/> Gilt nur für benannten Stil.|
| [`is_modified(self, modify_flag)`](/cells/python-net/de/aspose.cells/style/is_modified/#aspose.cells.stylemodifyflag) | Überprüft, ob die angegebenen Eigenschaften des Stils geändert wurden.<br/> Wird für den Stil von bedingten Formatierungen verwendet, um zu überprüfen, ob die angegebenen Eigenschaften dieses Stils beim Anwenden der bedingten Formatierungen auf eine Zelle verwendet werden sollen.|
| [`set_custom(self, custom, builtin_preference)`](/cells/python-net/de/aspose.cells/style/set_custom/#str-bool) | Legt die Zeichenfolge für das benutzerdefinierte Zahlenformat einer Zelle fest.|
| [`set_two_color_gradient(self, color1, color2, gradient_style_type, variant)`](/cells/python-net/de/aspose.cells/style/set_two_color_gradient/#aspose.pydrawing.color-aspose.pydrawing.color-aspose.cells.drawing.gradientstyletype-int) | Legt die angegebene Füllung auf einen zweifarbigen Farbverlauf fest.|
| [`get_two_color_gradient(self, color1, color2, gradient_style_type, variant)`](/cells/python-net/de/aspose.cells/style/get_two_color_gradient/#aspose.pydrawing.color&-aspose.pydrawing.color&-any-any) | Holen Sie sich die Einstellung für den zweifarbigen Farbverlauf.|
| [`get_two_color_gradient_setting(self)`](/cells/python-net/de/aspose.cells/style/get_two_color_gradient_setting/#) | Holen Sie sich die Einstellung für den zweifarbigen Farbverlauf.|
| [`to_json(self)`](/cells/python-net/de/aspose.cells/style/to_json/#) | Konvertieren Sie [`Style`](/cells/python-net/de/aspose.cells/style) in JSON Strukturdaten.|



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
