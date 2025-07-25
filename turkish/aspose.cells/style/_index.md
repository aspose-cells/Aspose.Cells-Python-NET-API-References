---
title: Style sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1350
url: /tr/aspose.cells/style/
is_root: false
---
##  Style sınıfı
Excel belgesinin yazı tipi, rengi, hizalaması, kenarlığı vb. gibi görüntüleme stilini temsil eder.
Style nesnesi tüm stil niteliklerini (yazı tipi, sayı biçimi, hizalama vb.) özellik olarak içerir.



Style türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self)`](/cells/python-net/tr/aspose.cells/style/__init__/#) | [`Style`](/cells/python-net/tr/aspose.cells/style) sınıfının yeni bir örneğini başlatır.|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [background_theme_color](/cells/python-net/tr/aspose.cells/style/background_theme_color) | Arka plan tema rengini alır ve ayarlar.|
| [foreground_theme_color](/cells/python-net/tr/aspose.cells/style/foreground_theme_color) | Ön plan tema rengini alır ve ayarlar.|
| [name](/cells/python-net/tr/aspose.cells/style/name) | Stilin adını alır veya ayarlar.|
| [pattern](/cells/python-net/tr/aspose.cells/style/pattern) | Hücre arka plan deseninin türünü alır veya ayarlar.|
| [borders](/cells/python-net/tr/aspose.cells/style/borders) | Stilin [`BorderCollection`](/cells/python-net/tr/aspose.cells/bordercollection)'ini alır.|
| [background_color](/cells/python-net/tr/aspose.cells/style/background_color) | Bir stilin arka plan rengini alır veya ayarlar.|
| [background_argb_color](/cells/python-net/tr/aspose.cells/style/background_argb_color) | Arka plan rengini 32-bit ARGB değeriyle alır ve ayarlar.|
| [foreground_color](/cells/python-net/tr/aspose.cells/style/foreground_color) | Bir stilin ön plan rengini alır veya ayarlar.|
| [foreground_argb_color](/cells/python-net/tr/aspose.cells/style/foreground_argb_color) | Ön plan rengini 32-bit ARGB değeriyle alır ve ayarlar.|
| [has_borders](/cells/python-net/tr/aspose.cells/style/has_borders) | Stil için sınırların ayarlanıp ayarlanmadığını kontrol eder.|
| [parent_style](/cells/python-net/tr/aspose.cells/style/parent_style) | Bu stilin üst stilini alır.|
| [is_number_format_applied](/cells/python-net/tr/aspose.cells/style/is_number_format_applied) | Sayı biçimlendirmesinin uygulanıp uygulanmayacağını belirtin.|
| [is_font_applied](/cells/python-net/tr/aspose.cells/style/is_font_applied) |Yazı tipi biçimlendirmesinin uygulanıp uygulanmayacağını belirtin.|
| [is_alignment_applied](/cells/python-net/tr/aspose.cells/style/is_alignment_applied) | Hizalama biçimlendirmesinin uygulanıp uygulanmayacağını belirtin.|
| [is_border_applied](/cells/python-net/tr/aspose.cells/style/is_border_applied) | Sınır biçimlendirmesinin uygulanıp uygulanmayacağını belirtin.|
| [is_fill_applied](/cells/python-net/tr/aspose.cells/style/is_fill_applied) | Dolgu biçimlendirmesinin uygulanıp uygulanmayacağını belirtin.|
| [is_protection_applied](/cells/python-net/tr/aspose.cells/style/is_protection_applied) | Koruma biçimlendirmesinin uygulanıp uygulanmayacağını belirtin.|
| [indent_level](/cells/python-net/tr/aspose.cells/style/indent_level) | Hücre veya aralık için girinti düzeyini temsil eder. Yalnızca 0 ile 250 arasında bir tam sayı olabilir.|
| [font](/cells/python-net/tr/aspose.cells/style/font) | [`Style.font`](/cells/python-net/tr/aspose.cells/style#font) nesnesini alır.|
| [rotation_angle](/cells/python-net/tr/aspose.cells/style/rotation_angle) | Metnin dönüş açısını temsil eder.|
| [horizontal_alignment](/cells/python-net/tr/aspose.cells/style/horizontal_alignment) | Bir hücredeki metnin yatay hizalama türünü alır veya ayarlar.|
| [vertical_alignment](/cells/python-net/tr/aspose.cells/style/vertical_alignment) | Bir hücredeki metnin dikey hizalama türünü alır veya ayarlar.|
| [is_text_wrapped](/cells/python-net/tr/aspose.cells/style/is_text_wrapped) | Bir hücrenin içindeki metnin sarılıp sarılmadığını gösteren bir değer alır veya ayarlar.|
| [number](/cells/python-net/tr/aspose.cells/style/number) | Sayıların ve tarihlerin görüntülenme biçimini alır veya ayarlar. Biçimlendirme kalıpları bölgelere göre farklılık gösterir.|
| [is_locked](/cells/python-net/tr/aspose.cells/style/is_locked) | Bir hücrenin değiştirilip değiştirilemeyeceğini belirten bir değer alır veya ayarlar.|
| [custom](/cells/python-net/tr/aspose.cells/style/custom) | Bu stil nesnesinin özel sayı biçimi dizesini temsil eder.<br/>Özel sayı biçimi ayarlanmamışsa (Örneğin, sayı biçimi yerleşikse), "" döndürülür.|
| [culture_custom](/cells/python-net/tr/aspose.cells/style/culture_custom) | Sayı biçimi için kültüre bağlı desen dizesini alır ve ayarlar.<br/>Bu nesne için herhangi bir sayı biçimi ayarlanmamışsa, null döndürülür.<br/> Sayı biçimi yerleşik ise yerleşik sayıya karşılık gelen desen dizesi döndürülecektir.|
| [invariant_custom](/cells/python-net/tr/aspose.cells/style/invariant_custom) | Sayı biçimi için kültürden bağımsız desen dizesini alır.<br/>Bu nesne için herhangi bir sayı biçimi ayarlanmamışsa, null döndürülür.<br/> Sayı biçimi yerleşik ise yerleşik sayıya karşılık gelen desen dizesi döndürülecektir.|
| [is_formula_hidden](/cells/python-net/tr/aspose.cells/style/is_formula_hidden) | Çalışma sayfası korunduğunda formülün gizlenip gizlenmeyeceğini gösterir.|
| [shrink_to_fit](/cells/python-net/tr/aspose.cells/style/shrink_to_fit) | Metnin mevcut sütun genişliğine sığacak şekilde otomatik olarak küçülüp küçülmediğini gösterir.|
| [text_direction](/cells/python-net/tr/aspose.cells/style/text_direction) | Metnin okuma sırasını gösterir.|
| [is_justify_distributed](/cells/python-net/tr/aspose.cells/style/is_justify_distributed) | Metnin son satırında hücrelerin hizalanmış mı yoksa dağıtılmış mı hizalanması gerektiğini belirtir.|
| [quote_prefix](/cells/python-net/tr/aspose.cells/style/quote_prefix) | Hücre değerinin tek tırnak işaretiyle başlayıp başlamadığını belirtir.|
| [is_gradient](/cells/python-net/tr/aspose.cells/style/is_gradient) | Hücre gölgelendirmesinin bir degrade deseni olup olmadığını gösterir.|
| [is_percent](/cells/python-net/tr/aspose.cells/style/is_percent) | Sayı biçiminin yüzde biçimi olup olmadığını belirtir.|
| [is_date_time](/cells/python-net/tr/aspose.cells/style/is_date_time) | Sayı biçiminin tarih biçimi olup olmadığını belirtir.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`set_border(self, border_type, border_style, border_color)`](/cells/python-net/tr/aspose.cells/style/set_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.pydrawing.color) | Stilin sınırlarını belirler.|
| [`set_border(self, border_type, border_style, border_color)`](/cells/python-net/tr/aspose.cells/style/set_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.cells.cellscolor) | Stilin sınırlarını belirler.|
| [`set_pattern_color(self, pattern, color1, color2)`](/cells/python-net/tr/aspose.cells/style/set_pattern_color/#aspose.cells.backgroundtype-aspose.pydrawing.color-aspose.pydrawing.color) |Arka plan rengini ayarlar.|
| [`copy(self, style)`](/cells/python-net/tr/aspose.cells/style/copy/#aspose.cells.style) | Başka bir stil nesnesinden veri kopyalar|
| [`update(self)`](/cells/python-net/tr/aspose.cells/style/update/#) | Adlandırılmış stili, bu adlandırılmış stili kullanan hücrelerin stillerine uygulayın.<br/>Bu, stili değiştirmeyi bitirdikten sonra "tamam" butonuna tıklamak gibi çalışır.<br/> Sadece adlandırılmış stil için geçerlidir.|
| [`is_modified(self, modify_flag)`](/cells/python-net/tr/aspose.cells/style/is_modified/#aspose.cells.stylemodifyflag) | Belirtilen stil özelliklerinin değiştirilip değiştirilmediğini kontrol eder.<br/> ConditionalFormattings stilinin belirtilen özelliklerinin bir hücreye ConditionalFormattings uygulanırken kullanılıp kullanılmayacağını kontrol etmek için kullanılır.|
| [`set_custom(self, custom, builtin_preference)`](/cells/python-net/tr/aspose.cells/style/set_custom/#str-bool) | Bir hücrenin Özel sayı biçimi dizesini ayarlar.|
| [`set_two_color_gradient(self, color1, color2, gradient_style_type, variant)`](/cells/python-net/tr/aspose.cells/style/set_two_color_gradient/#aspose.pydrawing.color-aspose.pydrawing.color-aspose.cells.drawing.gradientstyletype-int) | Belirtilen dolguyu iki renkli bir degradeye ayarlar.|
| [`get_two_color_gradient(self, color1, color2, gradient_style_type, variant)`](/cells/python-net/tr/aspose.cells/style/get_two_color_gradient/#aspose.pydrawing.color&-aspose.pydrawing.color&-any-any) | İki renkli degrade ayarını edinin.|
| [`get_two_color_gradient_setting(self)`](/cells/python-net/tr/aspose.cells/style/get_two_color_gradient_setting/#) | İki renkli degrade ayarını edinin.|
| [`to_json(self)`](/cells/python-net/tr/aspose.cells/style/to_json/#) | [`Style`](/cells/python-net/tr/aspose.cells/style) yapı verisini JSON yapı verisine dönüştürün.|



###  Örnek

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

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`BorderCollection`](/cells/python-net/tr/aspose.cells/bordercollection)
* sınıf [`Style`](/cells/python-net/tr/aspose.cells/style)
