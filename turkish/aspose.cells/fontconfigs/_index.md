---
title: FontConfigs sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 670
url: /tr/aspose.cells/fontconfigs/
is_root: false
---
##  FontConfigs sınıfı
Yazı tipi ayarlarını belirtir



FontConfigs türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self)`](/cells/python-net/tr/aspose.cells/fontconfigs/__init__/#) | FontConfigs'in yeni bir örneğini oluşturur|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [default_font_name](/cells/python-net/tr/aspose.cells/fontconfigs/default_font_name) | Varsayılan yazı tipi adını alır veya ayarlar.|
| [prefer_system_font_substitutes](/cells/python-net/tr/aspose.cells/fontconfigs/prefer_system_font_substitutes) | Bir yazı tipi sunulmadığında ve bu yazı tipinin yerine geçecek bir şey ayarlanmadığında, önce sistem yazı tipi ikamelerinin kullanılıp kullanılmayacağını belirtin.<br/>Örn: Ubuntu'da "Arial" fontu genelde "Liberation Sans" ile değiştirilir.<br/> Varsayılan değer false'tur.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`is_font_available(, font_name)`](/cells/python-net/tr/aspose.cells/fontconfigs/is_font_available/#str) | Yazı tipinin mevcut olup olmadığını belirtin.|
| [`get_font_file_data_info(, font_name, is_bold, is_italic, is_exact_style)`](/cells/python-net/tr/aspose.cells/fontconfigs/get_font_file_data_info/#str-bool-bool-bool) | Yazı tipi dosyası verilerinin veri bilgilerini alın.|
| [`set_font_substitutes(, original_font_name, substitute_font_names)`](/cells/python-net/tr/aspose.cells/fontconfigs/set_font_substitutes/#str-list) | Verilen orijinal yazı tipi adı yerine yazı tipi adları.|
| [`get_font_substitutes(, original_font_name)`](/cells/python-net/tr/aspose.cells/fontconfigs/get_font_substitutes/#str) |Orijinal yazı tipi sunulmamışsa kullanılacak yazı tipi ikame adlarını içeren diziyi döndürür.|
| [`set_font_folder(, font_folder, recursive)`](/cells/python-net/tr/aspose.cells/fontconfigs/set_font_folder/#str-bool) | Yazı tipleri klasörünü ayarlar|
| [`set_font_folders(, font_folders, recursive)`](/cells/python-net/tr/aspose.cells/fontconfigs/set_font_folders/#list-bool) | Yazı tipi klasörlerini ayarlar|
| [`set_font_sources(, sources)`](/cells/python-net/tr/aspose.cells/fontconfigs/set_font_sources/#list) |  |
| [`get_font_sources()`](/cells/python-net/tr/aspose.cells/fontconfigs/get_font_sources/#) | Kaynak listesini içeren dizinin bir kopyasını alır|



###  Ayrıca bakınız
* modül [`aspose.cells`](..)
