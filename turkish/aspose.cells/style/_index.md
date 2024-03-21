---
title: Style sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1460
url: /tr/aspose.cells/style/
is_root: false
---
##  Style sınıfı
Yazı tipi, renk, hizalama, kenarlık vb. gibi Excel belgesinin görüntüleme stilini temsil eder.
Style nesnesi, özellik olarak tüm stil niteliklerini (yazı tipi, sayı biçimi, hizalama vb.) içerir.



Style türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [__init__](/cells/python-net/tr/aspose.cells/style/__init__/#) | [`Style`](/cells/python-net/tr/aspose.cells/style) sınıfının yeni bir örneğini başlatır.|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [background_theme_color](/cells/python-net/tr/aspose.cells/style/background_theme_color) | Arka plan tema rengini alır ve ayarlar.|
| [foreground_theme_color](/cells/python-net/tr/aspose.cells/style/foreground_theme_color) | Ön plan tema rengini alır ve ayarlar.|
| [name](/cells/python-net/tr/aspose.cells/style/name) | Stilin adını alır veya ayarlar.|
| [pattern](/cells/python-net/tr/aspose.cells/style/pattern) |Hücre arka plan desen türünü alır veya ayarlar.|
| [borders](/cells/python-net/tr/aspose.cells/style/borders) | Stilin [`BorderCollection`](/cells/python-net/tr/aspose.cells/bordercollection)'ini alır.|
| [background_color](/cells/python-net/tr/aspose.cells/style/background_color) | Bir stilin arka plan rengini alır veya ayarlar.|
| [background_argb_color](/cells/python-net/tr/aspose.cells/style/background_argb_color) | Arka plan rengini 32 bit ARGB değeriyle alır ve ayarlar.|
| [foreground_color](/cells/python-net/tr/aspose.cells/style/foreground_color) | Bir stilin ön plan rengini alır veya ayarlar.|
| [foreground_argb_color](/cells/python-net/tr/aspose.cells/style/foreground_argb_color) | Ön plan rengini 32 bit ARGB değeriyle alır ve ayarlar.|
| [has_borders](/cells/python-net/tr/aspose.cells/style/has_borders) | Stil için ayarlanan sınırların olup olmadığını kontrol eder.|
| [parent_style](/cells/python-net/tr/aspose.cells/style/parent_style) | Bu stilin ana stilini alır.|
| [is_number_format_applied](/cells/python-net/tr/aspose.cells/style/is_number_format_applied) | Sayı biçimlendirmesinin uygulanıp uygulanmayacağını belirtin.|
| [is_font_applied](/cells/python-net/tr/aspose.cells/style/is_font_applied) | Yazı tipi formatının uygulanması gerekip gerekmediğini belirtin.|
| [is_alignment_applied](/cells/python-net/tr/aspose.cells/style/is_alignment_applied) | Hizalama formatının uygulanması gerekip gerekmediğini belirtin.|
| [is_border_applied](/cells/python-net/tr/aspose.cells/style/is_border_applied) | Kenarlık biçimlendirmesinin uygulanıp uygulanmayacağını belirtin.|
| [is_fill_applied](/cells/python-net/tr/aspose.cells/style/is_fill_applied) | Dolgu formatının uygulanması gerekip gerekmediğini belirtin.|
| [is_protection_applied](/cells/python-net/tr/aspose.cells/style/is_protection_applied) | Koruma formatının uygulanması gerekip gerekmediğini belirtin.|
| [indent_level](/cells/python-net/tr/aspose.cells/style/indent_level) | Hücre veya aralığın girinti düzeyini temsil eder. Yalnızca 0 ile 250 arasında bir tam sayı olabilir.|
| [font](/cells/python-net/tr/aspose.cells/style/font) | [`Style.font`](/cells/python-net/tr/aspose.cells/style#font) nesnesini alır.|
| [rotation_angle](/cells/python-net/tr/aspose.cells/style/rotation_angle) | Metin döndürme açısını temsil eder.|
| [horizontal_alignment](/cells/python-net/tr/aspose.cells/style/horizontal_alignment) |Hücredeki metnin yatay hizalama türünü alır veya ayarlar.|
| [vertical_alignment](/cells/python-net/tr/aspose.cells/style/vertical_alignment) | Hücredeki metnin dikey hizalama türünü alır veya ayarlar.|
| [is_text_wrapped](/cells/python-net/tr/aspose.cells/style/is_text_wrapped) | Hücre içindeki metnin kaydırılıp kaydırılmadığını gösteren bir değer alır veya ayarlar.|
| [number](/cells/python-net/tr/aspose.cells/style/number) | Sayıların ve tarihlerin görüntülenme biçimini alır veya ayarlar. Biçimlendirme desenleri farklı bölgeler için farklıdır.|
| [is_locked](/cells/python-net/tr/aspose.cells/style/is_locked) | Bir hücrenin değiştirilip değiştirilemeyeceğini gösteren bir değer alır veya ayarlar.|
| [custom](/cells/python-net/tr/aspose.cells/style/custom) | Bu stil nesnesinin özel sayı biçimi dizesini temsil eder.<br/> Özel sayı formatı ayarlanmamışsa (Örneğin, sayı formatı yerleşiktir), "" döndürülür.|
| [culture_custom](/cells/python-net/tr/aspose.cells/style/culture_custom) | Sayı biçimi için kültüre bağlı desen dizesini alır ve ayarlar.<br/>Bu nesne için herhangi bir sayı biçimi ayarlanmamışsa null değeri döndürülür.<br/> Sayı formatı yerleşikse, yerleşik sayıya karşılık gelen kalıp dizisi döndürülür.|
| [invariant_custom](/cells/python-net/tr/aspose.cells/style/invariant_custom) | Sayı biçimi için kültürden bağımsız desen dizesini alır.<br/>Bu nesne için herhangi bir sayı biçimi ayarlanmamışsa null değeri döndürülür.<br/> Sayı formatı yerleşikse, yerleşik sayıya karşılık gelen kalıp dizisi döndürülür.|
| [is_formula_hidden](/cells/python-net/tr/aspose.cells/style/is_formula_hidden) |Çalışma sayfası korunurken formülün gizlenip gizlenmeyeceğini temsil eder.|
| [shrink_to_fit](/cells/python-net/tr/aspose.cells/style/shrink_to_fit) | Metnin mevcut sütun genişliğine sığacak şekilde otomatik olarak küçülüp küçülmediğini temsil eder.|
| [text_direction](/cells/python-net/tr/aspose.cells/style/text_direction) | Metin okuma sırasını temsil eder.|
| [is_justify_distributed](/cells/python-net/tr/aspose.cells/style/is_justify_distributed) | Metnin son satırında hücrelerin hizalı mı yoksa dağıtılmış hizalama mı kullanılması gerektiğini belirtir.|
| [quote_prefix](/cells/python-net/tr/aspose.cells/style/quote_prefix) | Hücrenin değerinin tek tırnak işaretiyle başlayıp başlamadığını belirtir.|
| [is_gradient](/cells/python-net/tr/aspose.cells/style/is_gradient) | Hücre gölgelemesinin degrade deseni olup olmadığını belirtir.|
| [is_percent](/cells/python-net/tr/aspose.cells/style/is_percent) | Sayı biçiminin yüzde biçimi olup olmadığını belirtir.|
| [is_date_time](/cells/python-net/tr/aspose.cells/style/is_date_time) | Sayı biçiminin tarih biçimi olup olmadığını belirtir.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [set_border](/cells/python-net/tr/aspose.cells/style/set_border/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.pydrawing.Color) | Stilin sınırlarını ayarlar.|
| [set_border](/cells/python-net/tr/aspose.cells/style/set_border/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.cells.CellsColor) | Stilin sınırlarını ayarlar.|
| [set_pattern_color](/cells/python-net/tr/aspose.cells/style/set_pattern_color/#aspose.cells.BackgroundType-aspose.pydrawing.Color-aspose.pydrawing.Color) | Arka plan rengini ayarlar.|
| [copy](/cells/python-net/tr/aspose.cells/style/copy/#aspose.cells.Style) | Başka bir stil nesnesinden veri kopyalar|
| [update](/cells/python-net/tr/aspose.cells/style/update/#) | Adlandırılmış stili, bu adlandırılmış stili kullanan hücrelerin stillerine uygulayın.<br/>Stili değiştirmeyi bitirdikten sonra "tamam" düğmesine tıklamak gibi çalışır.<br/> Yalnızca adlandırılmış stil için geçerlidir.|
| [is_modified](/cells/python-net/tr/aspose.cells/style/is_modified/#aspose.cells.StyleModifyFlag) | Stilin belirtilen özelliklerinin değiştirilip değiştirilmediğini kontrol eder.<br/>ConditionalFormattings stili için, bir hücreye ConditionalFormattings uygulanırken bu stilin belirtilen özelliklerinin kullanılması gerekip gerekmediğini kontrol etmek için kullanılır.|
| [set_custom](/cells/python-net/tr/aspose.cells/style/set_custom/#str-bool) | Bir hücrenin Özel sayı biçimi dizesini ayarlar.|
| [set_two_color_gradient](/cells/python-net/tr/aspose.cells/style/set_two_color_gradient/#aspose.pydrawing.Color-aspose.pydrawing.Color-aspose.cells.drawing.GradientStyleType-int) | Belirtilen dolguyu iki renkli bir degradeye ayarlar.|
| [get_two_color_gradient](/cells/python-net/tr/aspose.cells/style/get_two_color_gradient/#aspose.pydrawing.Color&-aspose.pydrawing.Color&-any-any) | İki renkli degrade ayarını edinin.|
| [get_two_color_gradient_setting](/cells/python-net/tr/aspose.cells/style/get_two_color_gradient_setting/#) | İki renkli degrade ayarını edinin.|
| [to_json](/cells/python-net/tr/aspose.cells/style/to_json/#) | [`Style`](/cells/python-net/tr/aspose.cells/style)'i JSON yapı verilerine dönüştürün.|



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
