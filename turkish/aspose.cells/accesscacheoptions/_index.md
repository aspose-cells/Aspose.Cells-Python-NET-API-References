---
title: AccessCacheOptions numaralandırma
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1710
url: /tr/aspose.cells/accesscacheoptions/
is_root: false
---
##  AccessCacheOptions numaralandırma
Veri erişimi için önbellek seçenekleri. Birden fazla seçeneğin bir arada kullanılabilmesi için | operatörüyle birleştirilebilir.



AccessCacheOptions türü aşağıdaki üyeleri ortaya çıkarır:

###  Alanlar
| Alan| Tanım|
| :- | :- |
| NONE | Hiçbir veri erişimi için önbellek yok.|
| ALL | Çalışma kitabındaki her türlü veri erişimi için mümkün olan tüm iyileştirmeleri uygulayın.<br/> Optimize edilmiş erişim sırasında hiçbir ayar ve verinin değiştirilmemesi gerekmektedir.|
| POSITION_AND_SIZE | Nesnenin (örneğin Şekil) konumunu ve boyutunu elde etmek için olası optimizasyonu uygulayın.<br/> Optimize edilmiş erişim sırasında satır yüksekliği ve sütun genişliği ayarları değiştirilmemelidir.|
| CELLS_DATA | Hücrelerin değerlerini elde etmek için olası optimizasyonu uygulayın.<br/>Cells verileri (Cell Satırının verileri ve ayarları) sırasında değiştirilmemelidir.<br/>optimize edilmiş erişim için, yeni Cell/Satır nesneleri de oluşturulmamalıdır (örneğin<br/> [indeksleyici] tarafından).|
| CELL_DISPLAY | Görüntülemeyle ilgili sonuçları elde etmek için olası optimizasyonu uygulayın<br/>hücreler([`Cell.display_string_value`](/cells/python-net/tr/aspose.cells/cell#display_string_value), [`Cell.get_style`](/cells/python-net/tr/aspose.cells/cell/get_style), [`Cell.get_display_style`](/cells/python-net/tr/aspose.cells/cell/get_display_style), vb.).<br/>Cells veri ve stil ile ilgili nesneler (Cell/Satır/Sütun stilleri, sütun genişliği, vb.) değiştirilmemelidir<br/> optimize edilmiş erişim sırasında.|
| GET_FORMULA | Formülleri elde etmek için olası optimizasyonu uygulayın.<br/>Formül ifadesini etkileyebilecek tüm veriler ve ayarlar (Çalışma Sayfasının adı, Adın metni,<br/> Optimize edilmiş erişim sırasında tablonun sütunu vb. değiştirilmemelidir.|
| SET_FORMULA | Ayar formülleri için olası optimizasyonları uygulayın.<br/>Formül ifadesini etkileyebilecek tüm veriler ve ayarlar (Çalışma Sayfasının adı, Adın metni,<br/> Optimize edilmiş erişim sırasında tablonun sütunu vb. değiştirilmemelidir.|
| CALCULATE_FORMULA | Formüllerin hesaplanmasında olası optimizasyonları uygulayın.<br/>Cells verileri optimize edilmiş erişim sırasında değiştirilmemeli, yeni nesne (Cell, Satır, vb.) eklenmemeli.<br/> (örneğin [indeksleyici] tarafından) oluşturulmalıdır.|
| CONDITIONAL_FORMATTING | Koşullu biçimlendirmelerin biçimlendirme sonucunu elde etmek için olası optimizasyonu uygulayın.<br/>Koşullu biçimlendirmelerin sonucunu etkileyebilecek tüm veriler ve ayarlar (koşullu biçimlendirme ayarları)<br/> (koşullu biçimlendirmeler, bağımlı hücre değerleri vb.) optimize edilmiş erişim sırasında değiştirilmemelidir.|
| VALIDATION | Doğrulama sonucunu elde etmek için olası optimizasyonu uygulayın.<br/>Doğrulamanın sonucunu etkileyebilecek tüm veriler ve ayarlar (doğrulama ayarları,<br/> Bağımlı hücre değerleri vb.) optimize edilmiş erişim sırasında değiştirilmemelidir.|



###  Notlar

Bazı özellikler için büyük veri kümelerine erişim çok sayıda tekrarlanan ve karmaşık işlem gerektirir
arama, hesaplama, ...vb. gibi işlemler çok fazla ekstra zaman alacaktır.
Yaygın durumlar için, tüm bağımlı veriler erişim sırasında değişmeden kalır, bu nedenle bazı önbellekler oluşturulabilir ve kullanılabilir
erişim performansını iyileştirin.
Bu amaçla, kullanıcının hangi tür veri erişim ihtiyaçlarını belirleyebilmesi için API'i sağlıyoruz.
olası önbellekleme mekanizmasıyla optimize edilecek.


Lütfen, farklı seçenekler için farklı veri kümelerinin "salt okunur" olması gerekebileceğini unutmayın.
Ve verilere erişim performansı birçok unsura bağlıdır, önbelleğe alma mekanizmasının kullanımı
performansın iyileştirileceğini garanti etmez. Bazı durumlarda,
örneğin erişilecek veri kümesi küçükse, önbelleği kullanmak daha da fazla zamana neden olabilir çünkü
önbelleğe alma işleminin kendisi de belirli bir ekstra zamana ihtiyaç duyar.

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
