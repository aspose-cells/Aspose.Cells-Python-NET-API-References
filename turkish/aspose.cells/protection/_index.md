---
title: Protection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1150
url: /tr/aspose.cells/protection/
is_root: false
---
##  Protection sınıfı
Bir çalışma sayfası için mevcut çeşitli koruma seçeneklerini temsil eder.



Protection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [allow_deleting_column](/cells/python-net/tr/aspose.cells/protection/allow_deleting_column) | Korunan bir çalışma sayfasında sütunların silinmesine izin verilip verilmediğini gösterir.|
| [allow_deleting_row](/cells/python-net/tr/aspose.cells/protection/allow_deleting_row) | Korunan bir çalışma sayfasında satırların silinmesine izin verilip verilmediğini gösterir.|
| [allow_filtering](/cells/python-net/tr/aspose.cells/protection/allow_filtering) | Kullanıcının, sayfanın korunmasından önce oluşturulan bir Otomatik Filtreyi kullanmasına izin verilip verilmediğini gösterir.|
| [allow_formatting_cell](/cells/python-net/tr/aspose.cells/protection/allow_formatting_cell) | Korunan bir çalışma sayfasında hücrelerin biçimlendirilmesine izin verilip verilmediğini gösterir.|
| [allow_formatting_column](/cells/python-net/tr/aspose.cells/protection/allow_formatting_column) | Korunan bir çalışma sayfasında sütun biçimlendirmesine izin verilip verilmediğini gösterir|
| [allow_formatting_row](/cells/python-net/tr/aspose.cells/protection/allow_formatting_row) |Korunan bir çalışma sayfasında satırların biçimlendirilmesine izin verilip verilmediğini gösterir|
| [allow_inserting_column](/cells/python-net/tr/aspose.cells/protection/allow_inserting_column) | Korunan bir çalışma sayfasına sütun eklenmesine izin verilip verilmediğini gösterir|
| [allow_inserting_hyperlink](/cells/python-net/tr/aspose.cells/protection/allow_inserting_hyperlink) | Korunan bir çalışma sayfasına köprü metinlerinin eklenmesine izin verilip verilmediğini gösterir|
| [allow_inserting_row](/cells/python-net/tr/aspose.cells/protection/allow_inserting_row) | Korunan bir çalışma sayfasına satır eklenmesine izin verilip verilmediğini gösterir|
| [allow_sorting](/cells/python-net/tr/aspose.cells/protection/allow_sorting) | Korunan bir çalışma sayfasında sıralama seçeneğinin izin verilip verilmediğini gösterir.|
| [allow_using_pivot_table](/cells/python-net/tr/aspose.cells/protection/allow_using_pivot_table) | Kullanıcının korumalı bir çalışma sayfasındaki pivot tabloları değiştirmesine izin verilip verilmediğini gösterir.|
| [allow_editing_content](/cells/python-net/tr/aspose.cells/protection/allow_editing_content) | Kullanıcının korumalı bir çalışma sayfasındaki kilitli hücrelerin içeriğini düzenlemesine izin verilip verilmediğini gösterir.|
| [allow_editing_object](/cells/python-net/tr/aspose.cells/protection/allow_editing_object) | Kullanıcının korumalı bir çalışma sayfasındaki çizim nesnelerini değiştirmesine izin verilip verilmediğini gösterir.|
| [allow_editing_scenario](/cells/python-net/tr/aspose.cells/protection/allow_editing_scenario) | Kullanıcının korumalı bir çalışma sayfasındaki senaryoları düzenlemesine izin verilip verilmediğini gösterir.|
| [allow_selecting_locked_cell](/cells/python-net/tr/aspose.cells/protection/allow_selecting_locked_cell) | Kullanıcının korumalı bir çalışma sayfasındaki kilitli hücreleri seçmesine izin verilip verilmediğini gösterir.|
| [allow_selecting_unlocked_cell](/cells/python-net/tr/aspose.cells/protection/allow_selecting_unlocked_cell) | Kullanıcının korumalı bir çalışma sayfasındaki kilitsiz hücreleri seçmesine izin verilip verilmediğini gösterir.|
| [password](/cells/python-net/tr/aspose.cells/protection/password) | Çalışma sayfasını korumak için kullanılan şifreyi temsil eder.|
| [is_protected_with_password](/cells/python-net/tr/aspose.cells/protection/is_protected_with_password) | Çalışma sayfalarının parola ile korunup korunmadığını gösterir.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`copy(self, source)`](/cells/python-net/tr/aspose.cells/protection/copy/#aspose.cells.protection) |Kopyalama koruma bilgisi.|
| [`verify_password(self, password)`](/cells/python-net/tr/aspose.cells/protection/verify_password/#str) | Şifreyi doğrular.|
| [`get_password_hash(self)`](/cells/python-net/tr/aspose.cells/protection/get_password_hash/#) | Mevcut şifrenin özetini alır.|



###  Örnek

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
worksheet = workbook.worksheets[0]
# Allowing users to select locked cells of the worksheet
worksheet.protection.allow_selecting_locked_cell = True
# Allowing users to select unlocked cells of the worksheet
worksheet.protection.allow_selecting_unlocked_cell = True

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
