---
title: built_in_document_properties mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 470
url: /tr/aspose.cells/workbook/built_in_document_properties/
is_root: false
---
##  built_in_document_properties mülk

E-tablonun tüm yerleşik belge özelliklerini temsil eden [`DocumentProperty`](/cells/python-net/tr/aspose.cells.properties/documentproperty) koleksiyonunu döndürür.

###  Notlar

Yerleşik belge özellikleri listesine yeni bir özellik eklenemez. Yalnızca yerleşik bir özelliği alabilir ve değerini değiştirebilirsiniz.
Aşağıda yerleşik özellik adları listesi yer almaktadır:

Başlık


Ders


Yazar


Anahtar kelimeler


Yorumlar


Şablon


Son Yazar


Revizyon Numarası


Uygulama Adı


Son Baskı Tarihi


Oluşturulma Tarihi


Son Kaydetme Zamanı


Toplam Düzenleme Süresi


Sayfa Sayısı


Kelime Sayısı


Karakter Sayısı


Güvenlik


Kategori


Biçim


Müdür


Şirket


Bayt Sayısı


Satır Sayısı


Paragraf Sayısı


Slayt Sayısı


Not Sayısı


Gizli Slayt Sayısı


Multimedya Klip Sayısı

###  Örnek

```python
from aspose.cells import Workbook

workbook = Workbook()
doc = workbook.built_in_document_properties.get("Author")
doc.value = "John Smith"

```
###  Tanım:
```python
@property
def built_in_document_properties(self):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`BuiltInDocumentPropertyCollection`](/cells/python-net/tr/aspose.cells.properties/builtindocumentpropertycollection)
* sınıf [`DocumentProperty`](/cells/python-net/tr/aspose.cells.properties/documentproperty)
* sınıf [`Workbook`](/cells/python-net/tr/aspose.cells/workbook)
