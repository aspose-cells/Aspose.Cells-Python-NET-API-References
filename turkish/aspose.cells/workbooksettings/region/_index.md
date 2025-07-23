---
title: region mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 440
url: /tr/aspose.cells/workbooksettings/region/
is_root: false
---
##  region mülk

Çalışma kitabının bölgesel ayarlarını alır veya ayarlar.

###  Notlar

1. Şablon dosyasından yüklenen bir çalışma kitabı için Aspose.Cells bileşeni tarafından kullanılan bölgesel ayarlar:
i). XLS dosyası için bölgesel ayarlara yönelik tanımlanmış alanlar vardır ve MS Excel, XLS dosyasını kaydederken bölgesel ayar verilerini dosyaya kaydeder.
Bu yüzden çalışma kitabının şablon dosyasında kayıtlı region'i kullanıyoruz.
XLS dosyasında kayıtlı region'i kullanmak istemiyorsanız, şablon dosyasını yükledikten sonra dosyayı beklenen değere (örneğin, CountryCode.Default) sıfırlayın.
Ve XLS dosyasını kaydederken kullanıcı tarafından belirtilen değeri de (bu yöntemle) dosyaya kaydediyoruz.
ii). XLSX, XLSB...vb. gibi diğer dosya biçimleri için, dosya biçimi belirtiminde bölgesel ayarlar için tanımlanmış bir alan yoktur.
Yani çalışma kitabı için uygulamanın ortamının bölgesel ayarlarını kullanıyoruz.
Ve, kullanıcı tarafından belirtilen değer (bu yöntemle) bu dosya formatlarına sahip oluşturulan dosyalar için saklanamaz.
2. MS Excel'deki görünüm efekti için:
Burada uygulanan bölgesel ayarlar yalnızca Aspose.Cells bileşeniyle çalışma zamanında etkili olabilir ve oluşturulan dosya MS Excel ile görüntülenirken etkili olamaz.
Belirtilen bölgesel ayar verilerinin kaydedildiği XLS numaralı oluşturulan dosya için bile, MS Excel ile görüntülendiğinde/düzenlendiğinde,
MS Excel tarafından biçimlendirme yapmak için kullanılan region, her zaman MS Excel'in çalıştığı ortamın varsayılan bölgesel ayarlarıdır,
Dosyada kayıtlı olan değil. Bu, MS Excel'in davranışıdır ve kodla değiştirilemez.
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
