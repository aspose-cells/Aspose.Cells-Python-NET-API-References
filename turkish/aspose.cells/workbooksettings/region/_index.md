---
title: region mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 400
url: /tr/aspose.cells/workbooksettings/region/
is_root: false
---
##  region mülk

Çalışma kitabının bölgesel ayarlarını alır veya ayarlar.

###  Notlar

1. Şablon dosyasından yüklenen bir çalışma kitabı için Aspose.Cells bileşeni tarafından kullanılan bölgesel ayarlar:
Ben). XLS dosyası için bölgesel ayarlar için tanımlanmış alanlar vardır ve MS Excel, XLS dosyasını kaydederken bölgesel ayar verilerini dosyaya kaydeder.
Bu nedenle, çalışma kitabının şablon dosyasında kayıtlı region'i kullanıyoruz.
XLS dosyasına kaydedilen region'i kullanmak istemiyorsanız, lütfen şablon dosyasını yükledikten sonra onu beklenen değere (CodeCode.Default gibi) sıfırlayın.
Ve XLS dosyasını kaydederken kullanıcının belirlediği değeri de (bu yöntemle) dosyaya kaydediyoruz.
ii). XLSX, XLSB...vb. gibi diğer dosya formatları için, dosya formatı spesifikasyonunda bölgesel ayarlar için tanımlanmış bir alan yoktur.
Bu nedenle çalışma kitabı için uygulama ortamının bölgesel ayarlarını kullanıyoruz.
Ve bu dosya formatlarıyla oluşturulan dosyalar için kullanıcının belirlediği değer (bu yöntemle) saklanamaz.
2. MS Excel'deki görünüm efekti için:
Burada uygulanan bölgesel ayarlar, yalnızca Aspose.Cells bileşeniyle çalışma zamanında etkili olabilir, oluşturulan dosya MS Excel ile görüntülenirken etkili olamaz.
Belirtilen bölgesel ayar verilerinin kaydedildiği oluşturulan XLS dosyası için bile MS Excel ile görüntülenirken/düzenlenirken,
MS Excel tarafından biçimlendirmeyi gerçekleştirmek için kullanılan region her zaman MS Excel'in çalıştığı ortamın varsayılan bölgesel ayarlarıdır,
dosyaya kaydedilen değil. Bu MS Excel'in davranışıdır ve kodla değiştirilemez.
###  Tanım:
```python
@property
def region(self):
    ...
@region.setter
def region(self, value):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`CountryCode`](/cells/python-net/tr/aspose.cells/countrycode)
* sınıf [`WorkbookSettings`](/cells/python-net/tr/aspose.cells/workbooksettings)
