---
title: Workbook yapıcı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 10
url: /tr/aspose.cells/workbook/__init__/
is_root: false
---
##  \_\_init\_\_(kendi){#}
[`Workbook`](/cells/python-net/tr/aspose.cells/workbook) sınıfının yeni bir örneğini başlatır.



```python

def __init__(self):
    ...
```


###  Notlar

Varsayılan dosya biçimi türü Xlsx'tir. Başka dosya türleri oluşturmak istiyorsanız lütfen Workbook(DosyaBiçimTürü) kullanın.
###  Örnek


Aşağıdaki kod, sınıfın yeni bir örneğini oluşturmak ve başlatmak için Workbook oluşturucusunun nasıl kullanılacağını gösterir.

```python
from aspose.cells import Workbook

workbook = Workbook()

```


##  \_\_init\_\_(self, dosya_biçim_türü){#aspose.cells.FileFormatType}
[`Workbook`](/cells/python-net/tr/aspose.cells/workbook) sınıfının yeni bir örneğini başlatır.



```python

def __init__(self, file_format_type):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| file_format_type | [`FileFormatType`](/cells/python-net/tr/aspose.cells/fileformattype) | Yeni dosya biçimi.|
###  Notlar

Varsayılan dosya biçimi türü Excel97To2003'tür.
###  Örnek


Aşağıdaki kod, Workbook oluşturucusunun çeşitli dosya biçimi türleriyle sınıfın yeni bir örneğini oluşturmak ve başlatmak için nasıl kullanılacağını gösterir.

```python
from aspose.cells import FileFormatType, Workbook

workbook = Workbook(FileFormatType.XLSX)

```


##  \_\_init\_\_(kendi, dosya){#str}
[`Workbook`](/cells/python-net/tr/aspose.cells/workbook) sınıfının yeni bir örneğini başlatır ve bir dosya açar.



```python

def __init__(self, file):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| file | str | Dosya adı.|


##  \_\_init\_\_(kendi, akış){#io.RawIOBase}
[`Workbook`](/cells/python-net/tr/aspose.cells/workbook) sınıfının yeni bir örneğini başlatır ve bir akış açar.



```python

def __init__(self, stream):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| stream | io.RawIOBase | Dere.|


##  \_\_init\_\_(self, dosya, yükleme_seçenekleri){#str-aspose.cells.LoadOptions}
[`Workbook`](/cells/python-net/tr/aspose.cells/workbook) sınıfının yeni bir örneğini başlatır ve bir dosya açar.



```python

def __init__(self, file, load_options):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| file | str | Dosya adı.|
| load_options | [`LoadOptions`](/cells/python-net/tr/aspose.cells/loadoptions) | Yükleme seçenekleri|


##  \_\_init\_\_(self, akış, yükleme_seçenekleri){#io.RawIOBase-aspose.cells.LoadOptions}
[`Workbook`](/cells/python-net/tr/aspose.cells/workbook) sınıfının yeni bir örneğini başlatır ve akışı açar.



```python

def __init__(self, stream, load_options):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| stream | io.RawIOBase | Dere.|
| load_options | [`LoadOptions`](/cells/python-net/tr/aspose.cells/loadoptions) | Yükleme seçenekleri|



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Workbook`](/cells/python-net/tr/aspose.cells/workbook)
