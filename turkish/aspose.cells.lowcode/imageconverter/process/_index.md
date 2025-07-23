---
title: process yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 20
url: /tr/aspose.cells.lowcode/imageconverter/process/
is_root: false
---
##  process(, şablon_dosyası, sonuç_dosyası){#str-str}
Şablon dosyasını resimlere dönüştürür.



```python

@staticmethod
def process(template_file, result_file):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| template_file | str | Görüntülere dönüştürülecek şablon dosyası.|
| result_file | str | Üretilen görsellere ait sonuç dosyası (isim deseni).|
###  Notlar

Çıktı dosyaları belirtilen sonuç dosyasından oluşturulacaktır
Sayfanın ve bölünmüş parçanın sıra numarası eklenerek.
Örneğin, belirtilen çıktı dosyası Image.png ise, oluşturulan görüntü
dosyalar Image_0_0.png, Image_0_1.png, ..., Image_1_0.png, ... olacaktır.

##  process(, yükleme_seçenekleri, kaydetme_seçenekleri){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions}
Şablon dosyasını resimlere dönüştürür



```python

@staticmethod
def process(load_options, save_options):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/tr/aspose.cells.lowcode/lowcodeloadoptions) | Giriş ve yükleme seçenekleri|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptions) | Çıktı ve kaydetme seçenekleri|
###  Notlar

Birden fazla sayfayı destekleyen formattaki görüntüye (örneğin tiff) dönüştürürken,
belirtilen [`LowCodeSaveOptions.output_file`](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptions#output_file)
veya [`LowCodeSaveOptions.output_stream`](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptions#output_stream) doğrudan elde edilen görüntü için kullanılacaktır.


Diğer görüntü türleri için, kaydetme seçeneklerinde çıktı olarak Akış belirtilmişse,
daha sonra ortaya çıkan tüm görüntüler aynı Akışa kaydedilecektir.
Aksi takdirde, çıktı dosyaları belirtilen çıktı dosyasından oluşturulacaktır
Sayfanın sıra numarasını ve bölünmüş parçayı ekleyerek kaydetme seçeneklerinden birini seçin.
Örneğin, belirtilen çıktı dosyası Image.png ise, oluşturulan görüntü
dosyalar Image_0_0.png, Image_0_1.png, ..., Image_1_0.png, ... olacaktır.

##  process(, yükleme_seçenekleri, kaydetme_seçenekleri, sağlayıcı){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-AbstractLowCodeSaveOptionsProvider}




```python

@staticmethod
def process(load_options, save_options, provider):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/tr/aspose.cells.lowcode/lowcodeloadoptions) |  |
| save_options | [`LowCodeSaveOptions`](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptions) |  |
| provider | AbstractLowCodeSaveOptionsProvider |  |



###  Ayrıca bakınız
* modül [`aspose.cells.lowcode`](../../)
* sınıf [`ImageConverter`](/cells/python-net/tr/aspose.cells.lowcode/imageconverter)
