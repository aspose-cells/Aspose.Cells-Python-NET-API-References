---
title: add_identify yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 20
url: /tr/aspose.cells.pivot/pivotpagefields/add_identify/
is_root: false
---
##  add_identify(self, range_index, page_item_index) {#int-list}
Veri aralığını tanımlamak için her sayfa alanındaki hangi öğe etiketinin kullanılacağını ayarlar.
pageItemIndex.Length değeri PageFieldCount değerine eşit olmalıdır, bu nedenle lütfen önce sayfa alanını ekleyin.



```python

def add_identify(self, range_index, page_item_index):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| range_index | int | Konsolidasyon veri aralığı endeksi.|
| page_item_index | list | Her sayfa alanındaki sayfa öğesi dizini.<br/>pageItemIndex[2] = 1, bu aralığı tanımlamak için kullanılacak üçüncü alandaki ikinci öğe anlamına gelir.<br/> pageItemIndex[1] = -1, bu aralığı tanımlamak için kullanılacak ikinci alanda hiçbir öğe olmadığı anlamına gelir<br/> ve MS bu aralığı tanımlamak için ikinci alanda otomatik olarak "boş" bir öğe oluşturacaktır.|



###  Ayrıca bakınız
* modül [`aspose.cells.pivot`](../../)
* sınıf [`PivotPageFields`](/cells/python-net/tr/aspose.cells.pivot/pivotpagefields)
