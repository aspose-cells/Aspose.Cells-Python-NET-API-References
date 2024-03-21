---
title: AccessCacheOptions numaralandırma
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1810
url: /tr/aspose.cells/accesscacheoptions/
is_root: false
---
##  AccessCacheOptions numaralandırma
Veri erişimi için önbellek seçenekleri. ile birleştirilebilir | birden fazla seçeneğin birlikte işlenebilmesini sağlar.



AccessCacheOptions türü aşağıdaki üyeleri ortaya çıkarır:

###  Alanlar
| Alan| Tanım|
| :- | :- |
| NONE | Herhangi bir veri erişimi için önbellek yok.|
| ALL | Çalışma kitabındaki her türlü veri erişimi için mümkün olan tüm optimizasyonları uygulayın.<br/> Optimize edilmiş erişim sırasında tüm ayarlar ve veriler değiştirilmemelidir.|
| POSITION_AND_SIZE |Nesnenin (Şekil gibi) konumunu ve boyutunu elde etmek için olası optimizasyonu uygulayın.<br/> Optimize edilmiş erişim sırasında satır yüksekliği ve sütun genişliği ayarları değiştirilmemelidir.|
| CELLS_DATA | Hücrelerin değerlerini almak için olası optimizasyonu uygulayın.<br/>Cells data(Cell, Row verileri ve ayarları) sırasında değiştirilmemelidir.<br/>optimize edilmiş erişim için yeni Cell/Row nesneleri de oluşturulmamalıdır (örneğin<br/> [dizin oluşturucu] tarafından).|
| CELL_DISPLAY | Ekranla ilgili sonuçları elde etmek için olası optimizasyonu uygulayın<br/>hücreler ([`Cell.display_string_value`](/cells/python-net/tr/aspose.cells/cell#display_string_value), [`Cell.get_style`](/cells/python-net/tr/aspose.cells/cell/get_style), [`Cell.get_display_style`](/cells/python-net/tr/aspose.cells/cell/get_display_style), vb.).<br/>Cells veri ve stille ilgili nesneler (Cell/Satır/Sütun stilleri, sütun genişliği vb.) değiştirilmemelidir<br/> optimize edilmiş erişim sırasında.|
| GET_FORMULA | Formül almak için olası optimizasyonu uygulayın.<br/>Formül ifadesini etkileyebilecek tüm veriler ve ayarlar (Çalışma Sayfasının adı, Adın metni,<br/> optimize edilmiş erişim sırasında tablonun sütunu vb. değiştirilmemelidir.|
| SET_FORMULA |Formülleri ayarlamak için olası optimizasyonu uygulayın.<br/>Formül ifadesini etkileyebilecek tüm veriler ve ayarlar (Çalışma Sayfasının adı, Adın metni,<br/> optimize edilmiş erişim sırasında tablonun sütunu vb. değiştirilmemelidir.|
| CALCULATE_FORMULA | Formüllerin hesaplanması için olası optimizasyonu uygulayın.<br/>Cells veriler optimize edilmiş erişim sırasında değiştirilmemeli, yeni nesneler olmamalıdır (Cell, Row, vb.)<br/> ya da oluşturulmalıdır (örneğin [dizin oluşturucu] tarafından).|
| CONDITIONAL_FORMATTING | Koşullu biçimlendirmelerin biçimlendirme sonucunu elde etmek için olası optimizasyonu uygulayın.<br/>Koşullu biçimlendirmelerin sonucunu etkileyebilecek tüm veriler ve ayarlar (ayarlar)<br/> optimize edilmiş erişim sırasında koşullu biçimlendirmeler, bağımlı hücre değerleri vb. değiştirilmemelidir.|
| VALIDATION | Doğrulama sonucunu almak için olası optimizasyonu uygulayın.<br/>Doğrulama sonucunu etkileyebilecek tüm veriler ve ayarlar (doğrulama ayarları,<br/> bağımlı hücre değerleri vb.) optimize edilmiş erişim sırasında değiştirilmemelidir.|



###  Notlar

Bazı özellikler için büyük veri setine erişim, çok sayıda tekrarlanan ve karmaşık işlem gerektirir
Arama, hesaplama vb. gibi işlemler çok fazla zaman alacaktır.
Yaygın durumlarda, erişim sırasında tüm bağımlı veriler değişmeden kalır, böylece bazı önbellekler oluşturulabilir ve kullanılabilir.
erişim performansını iyileştirin.
Bu amaçla, kullanıcının ne tür veri erişim ihtiyacını belirtebilmesi için bu API'i sağlıyoruz.
olası önbellekleme mekanizmasıyla optimize edilecek.


Farklı seçenekler için farklı veri setlerinin "salt okunur" olması gerekebileceğini lütfen unutmayın.
Verilere erişim performansı ise birçok hususa, önbellekleme mekanizmasının kullanımına bağlıdır.
performansın artacağını garanti etmez. Bazı durumlar için,
Erişilecek veri kümesinin küçük olması gibi önbellek kullanımı daha da fazla zamana neden olabilir çünkü
önbelleğe almanın da belirli bir ekstra süreye ihtiyacı vardır.

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
