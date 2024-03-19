---
title: Row sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1340
url: /tr/aspose.cells/row/
is_root: false
---
##  Row sınıfı
Çalışma sayfasındaki tek bir satırı temsil eder.



Row türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [is_blank](/cells/python-net/tr/aspose.cells/row/is_blank) | Satırın herhangi bir veri içerip içermediğini belirtir|
| [is_collapsed](/cells/python-net/tr/aspose.cells/row/is_collapsed) | satırın daraltılıp daraltılmadığı|
| [height](/cells/python-net/tr/aspose.cells/row/height) | Satır yüksekliğini Puan birimi cinsinden alır ve ayarlar.|
| [is_hidden](/cells/python-net/tr/aspose.cells/row/is_hidden) | Satırın gizli olup olmadığını belirtir.|
| [index](/cells/python-net/tr/aspose.cells/row/index) | Bu satırın indeksini alır.|
| [group_level](/cells/python-net/tr/aspose.cells/row/group_level) | Satırın grup düzeyini alır.|
| [is_height_matched](/cells/python-net/tr/aspose.cells/row/is_height_matched) | Satır yüksekliğinin çalışma kitabının geçerli varsayılan yazı tipi ayarıyla eşleşip eşleşmediğini belirtir.<br/>Bu özelliğin doğruluğu aynı zamanda satır yüksekliğinin kullanıcı tarafından ayarlanan özel yükseklik değeri olmadan "otomatik" olduğunu da belirtir.|
| [has_custom_style](/cells/python-net/tr/aspose.cells/row/has_custom_style) | Bu satırın özel stil ayarlarına (çalışma kitabından devralınan varsayılan ayardan farklı) sahip olup olmadığını belirtir.|
| [first_cell](/cells/python-net/tr/aspose.cells/row/first_cell) | Satırdaki ilk hücre nesnesini alır.|
| [first_data_cell](/cells/python-net/tr/aspose.cells/row/first_data_cell) | Satırdaki ilk boş olmayan hücreyi alır.|
| [last_cell](/cells/python-net/tr/aspose.cells/row/last_cell) | Satırdaki son hücre nesnesini alır.|
| [last_data_cell](/cells/python-net/tr/aspose.cells/row/last_data_cell) | Satırdaki boş olmayan son hücreyi alır.|



Hücreyi alır.
###  Dizin oluşturucu
| İsim| Tanım|
| :- | :- |
| [index] | Sütun dizini|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [get_cell_by_index](/cells/python-net/tr/aspose.cells/row/get_cell_by_index/#int) | Bu satırın hücre koleksiyonundaki hücreyi belirli bir dizine göre alın.|
| [get_enumerator](/cells/python-net/tr/aspose.cells/row/get_enumerator/#bool-bool) | Bu satır boyunca hücreleri yineleyen bir numaralandırıcı alır.|
| [get_cell_or_null](/cells/python-net/tr/aspose.cells/row/get_cell_or_null/#int) | Belirli bir dizindeki hücreyi veya null değerini alır.|
| [get_style](/cells/python-net/tr/aspose.cells/row/get_style/#) | Bu satırın stilini alır.|
| [set_style](/cells/python-net/tr/aspose.cells/row/set_style/#aspose.cells.Style) | Bu satırın stilini ayarlar.|
| [copy_settings](/cells/python-net/tr/aspose.cells/row/copy_settings/#aspose.cells.Row-bool) | Stil, yükseklik, görünürlük vb. gibi satır ayarlarını kopyalayın.|
| [apply_style](/cells/python-net/tr/aspose.cells/row/apply_style/#aspose.cells.Style-aspose.cells.StyleFlag) | Tüm satırın formatlarını uygular.|
| [equals](/cells/python-net/tr/aspose.cells/row/equals/#aspose.cells.Row) | Bu nesnenin başka bir satır nesnesiyle aynı satıra başvurup başvurmadığını kontrol eder.|



###  Örnek

```python
from aspose.cells import BackgroundType, StyleFlag, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
style = workbook.create_style()
# Setting the background color to Blue
style.background_color = Color.blue
# Setting the foreground color to Red
style.foreground_color = Color.red
# setting Background Pattern
style.pattern = BackgroundType.DIAGONAL_STRIPE
# New Style Flag
styleFlag = StyleFlag()
# Set All Styles
styleFlag.all = True
# Get first row
row = worksheet.cells.rows[0]
# Apply Style to first row
row.apply_style(style, styleFlag)
# Saving the Excel file
workbook.save("book1.xls")

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
