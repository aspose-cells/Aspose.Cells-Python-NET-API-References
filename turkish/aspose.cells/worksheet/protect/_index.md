---
title: protect yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 200
url: /tr/aspose.cells/worksheet/protect/
is_root: false
---
##  protect {#aspose.cells.ProtectionType}
Çalışma sayfasını korur.



```python
def protect(self, type):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| type | [`ProtectionType`](/cells/python-net/tr/aspose.cells/protectiontype) | Koruma türü.|
###  Notlar

Bu yöntem çalışma sayfasını parola olmadan korur. Excel dosyasının tüm sürümlerinde protect çalışma sayfası olabilir.

##  protect {#aspose.cells.ProtectionType-str-str}

Çalışma sayfasını korur.



```python
def protect(self, type, password, old_password):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| type | [`ProtectionType`](/cells/python-net/tr/aspose.cells/protectiontype) | Koruma türü.|
| password | str | Şifre.|
| old_password | str | Çalışma sayfası zaten bir parolayla korunuyorsa lütfen eski parolayı girin.<br/> Aksi takdirde bu parametreye boş bir değer veya boş bir dize ayarlayabilirsiniz.|
###  Notlar

Bu yöntem, Excel dosyasının tüm sürümlerinde protect çalışma sayfasını çalıştırabilir.
###  Örnek


```python
from aspose.cells import ProtectionType, Workbook

# Instantiating a Workbook object
excel = Workbook("template.xlsx")
# Accessing the first worksheet in the Excel file
worksheet = excel.worksheets[0]
# Protecting the worksheet with a password
worksheet.protect(ProtectionType.ALL, "aspose", None)
# Saving the modified Excel file in default (that is Excel 20003) format
excel.save("output.xls")

```



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Worksheet`](/cells/python-net/tr/aspose.cells/worksheet)
