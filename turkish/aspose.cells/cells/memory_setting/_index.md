---
title: memory_setting mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1160
url: /tr/aspose.cells/cells/memory_setting/
is_root: false
---
##  memory_setting mülk

Bu hücreler için bellek kullanım seçeneğini alır veya ayarlar.

###  Notlar

Bazı modlar için dikkate değer sınırlamalar ve önerilen işlemler:
| Mod| Notlar| Desteklendi|
| :- | :- | :- |
|
 Bellek maliyetini azaltmak için. Öte yandan, sıkıştırılmış veriler de
 özellikle hücre verilerini güncellerken daha yüksek zaman maliyetine neden olur,
 veya hücrelere/satırlara rastgele erişim | v8.0.0 |
|
 Bu mod bir çalışma kitabındaki herhangi bir çalışma sayfası için kullanıldığında, |
 Geçici dosyalar gibi tüm kaynakların serbest bırakılması için işin sonunda çağrılması gerekir.
            | 
 Hücrelere rastgele erişim, verinin ihtiyaç duyması nedeniyle düşük performansa neden olur.
 rastgele ve tekrar tekrar okunacak/güncellenecek (bu nedenle dosyadaki işaretçi
(Buna göre değişecektir ve IO işlemleri tekrar tekrar gerekecektir).
 Mümkünse lütfen verilere her zaman sıralı (satır satır) olarak erişin.
            | 
 Bir satır/hücrenin verileri değiştirildiğinde, diğer hücrelerin/satırların verileri de değiştirilir.
 Ayrıca etkilenebilir (örneğin veriler başka yerlere kaydırılabilir/taşınabilir)
 (Değiştirilen veriler için yeterli alan ayırmak için).
 Yani her verinin her değişimi, var olan diğer nesnelerin senkronizasyonunu gerektirir.
 (örneğin Satır veya Cell nesnesi).
 Bu nedenle, daha iyi performans elde etmek için lütfen birden fazla Satır/Cells'i tutmayın
 Aynı zamanda. Bunları tek tek işlemek, veri senkronizasyonunu azaltacaktır.
 onlar için performans biraz daha iyileştirilebilir.
 | v25.7 |
###  Tanım:
```python
@property
def memory_setting(self):
    ...
@memory_setting.setter
def memory_setting(self, value):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Cells`](/cells/python-net/tr/aspose.cells/cells)
* sınıf [`MemorySetting`](/cells/python-net/tr/aspose.cells/memorysetting)
