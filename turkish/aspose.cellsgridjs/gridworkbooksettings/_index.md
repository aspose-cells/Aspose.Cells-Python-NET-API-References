---
title: GridWorkbookSettings sınıfı
second_title: Aspose.Cells.GridJs for Python via .NET API Referanslar
description:
type: docs
weight: 80
url: /tr/aspose.cellsgridjs/gridworkbooksettings/
is_root: false
---
##  GridWorkbookSettings sınıfı

Çalışma kitabının ayarlarını temsil eder.



GridWorkbookSettings türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [__init__](/cells/python-net/tr/aspose.cellsgridjs/gridworkbooksettings/__init__/#) | GridWorkbookSettings'in yeni bir örneğini oluşturur|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [max_iteration](/cells/python-net/tr/aspose.cellsgridjs/gridworkbooksettings/max_iteration) | Döngüsel bir referansı çözümlemek için maksimum yineleme sayısını döndürür veya ayarlar; varsayılan değer 100'dür.|
| [iteration](/cells/python-net/tr/aspose.cellsgridjs/gridworkbooksettings/iteration) | Döngüsel başvuruları çözümlemek için yinelemenin kullanılıp kullanılmayacağını belirtir.|
| [force_full_calculate](/cells/python-net/tr/aspose.cellsgridjs/gridworkbooksettings/force_full_calculate) | Bir hesaplama her tetiklendiğinde tam olarak hesaplama yapılıp yapılmadığını gösterir.|
| [create_calc_chain](/cells/python-net/tr/aspose.cellsgridjs/gridworkbooksettings/create_calc_chain) | Hesaplanan formüller zincirinin oluşturulup oluşturulmadığını belirtir. Varsayılan yanlıştır.|
| [re_calculate_on_open](/cells/python-net/tr/aspose.cellsgridjs/gridworkbooksettings/re_calculate_on_open) | Dosya açıldığında tüm formüllerin yeniden hesaplanıp hesaplanmayacağını belirtir.|
| [precision_as_displayed](/cells/python-net/tr/aspose.cellsgridjs/gridworkbooksettings/precision_as_displayed) | Bu çalışma kitabındaki hesaplamalar yalnızca görüntülenen sayıların kesinliği kullanılarak yapılacaksa doğrudur|
| [date1904](/cells/python-net/tr/aspose.cellsgridjs/gridworkbooksettings/date1904) |Çalışma kitabının 1904 tarih sistemini kullanıp kullanmadığını temsil eden bir değer alır veya ayarlar.|
| [enable_macros](/cells/python-net/tr/aspose.cellsgridjs/gridworkbooksettings/enable_macros) | Makroları etkinleştirin; Artık yalnızca bir çalışma sayfasını çalışma kitabındaki başka bir çalışma sayfasına kopyalarken çalışır.|
| [check_custom_number_format](/cells/python-net/tr/aspose.cellsgridjs/gridworkbooksettings/check_custom_number_format) | Style.Custom ayarlanırken özel sayı biçiminin kontrol edilip edilmeyeceğini belirtir.|
| [author](/cells/python-net/tr/aspose.cellsgridjs/gridworkbooksettings/author) | Dosyanın yazarını alır/ayarlar.|



###  Örnek


```python
from aspose.cellsgridjs import GridJsWorkbook, GridWorkbookSettings

g = GridJsWorkbook()
gsettings = GridWorkbookSettings()
g.settings = gsettings

```

###  Ayrıca bakınız
* modül [`aspose.cellsgridjs`](..)
