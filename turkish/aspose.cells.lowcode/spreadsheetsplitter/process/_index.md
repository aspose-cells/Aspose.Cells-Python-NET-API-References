---
title: process yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 20
url: /tr/aspose.cells.lowcode/spreadsheetsplitter/process/
is_root: false
---
##  process(, seçenekler){#aspose.cells.lowcode.LowCodeSplitOptions}
E-tablo dosyasını birden fazla parçaya böler.



```python

@staticmethod
def process(options):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| options | [`LowCodeSplitOptions`](/cells/python-net/tr/aspose.cells.lowcode/lowcodesplitoptions) | Elektronik tabloyu bölme seçenekleri|


##  process(, şablon_dosyası, sonuç_dosyası){#str-str}
Verilen şablon dosyasını birden fazla parçaya böler.



```python

@staticmethod
def process(template_file, result_file):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| template_file | str | Bölünecek şablon dosyası|
| result_file | str | Sonuçta ortaya çıkan dosya (isim deseni)|
###  Notlar

Çıktı dosyaları belirtilen sonuç dosyasından oluşturulacaktır.
sayfanın ve bölünmüş parçanın sıra numarasının eklenmesi.
Örneğin, belirtilen çıktı dosyası Split.xlsx ise, oluşturulan
dosyalar Split_0_0.xlsx, Split_0_1.xlsx, ..., Split_1_0.xlsx, ... olacaktır.


###  Ayrıca bakınız
* modül [`aspose.cells.lowcode`](../../)
* sınıf [`SpreadsheetSplitter`](/cells/python-net/tr/aspose.cells.lowcode/spreadsheetsplitter)
