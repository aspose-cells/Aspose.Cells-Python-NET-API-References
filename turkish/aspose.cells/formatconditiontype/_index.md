---
title: FormatConditionType numaralandırma
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 2110
url: /tr/aspose.cells/formatconditiontype/
is_root: false
---
##  FormatConditionType numaralandırma
Koşullu biçimlendirme kural türü.



FormatConditionType türü aşağıdaki üyeleri ortaya çıkarır:

###  Alanlar
| Alan| Tanım|
| :- | :- |
| CELL_VALUE | Bu koşullu biçimlendirme kuralı bir hücre değerini karşılaştırır<br/> Bir operatör kullanılarak hesaplanan bir formüle göre sonuç.|
| EXPRESSION | Bu koşullu biçimlendirme kuralı, bir formül içerir<br/>değerlendir. Formül sonucu doğru olduğunda, hücre<br/> vurgulanmıştır.|
| TOP10 | Bu koşullu biçimlendirme kuralı, hangi hücrelerin vurgulandığını belirtir.<br/>değerler en üst N veya en alt N parantezine düşer,<br/> belirtilen.|
| UNIQUE_VALUES | Bu koşullu biçimlendirme kuralı benzersiz öğeleri vurgular<br/> aralıktaki değerler.|
| DUPLICATE_VALUES | Bu koşullu biçimlendirme kuralı, yinelenenleri vurgular<br/> değerler.|
| CONTAINS_TEXT | Bu koşullu biçimlendirme kuralı hücreleri vurgular<br/>Verilen metni içeren. SEARCH() kullanmaya eşdeğerdir<br/>hücrenin içerip içermediğini belirlemek için sayfa işlevi<br/> metin.|
| NOT_CONTAINS_TEXT | Bu koşullu biçimlendirme kuralı, hücreleri vurgular<br/>Verilen metni içermiyor. SEARCH() kullanmaya eşdeğerdir<br/>hücrenin içerip içermediğini belirlemek için sayfa işlevi<br/> metin olsun ya da olmasın.|
| BEGINS_WITH | Bu koşullu biçimlendirme kuralı, hücreleri vurgular<br/>Verilen metinle başlayan aralık. Şuna eşdeğerdir<br/> LEFT() sayfa fonksiyonunu kullanarak değerleri karşılaştırıyoruz.|
| ENDS_WITH | Bu koşullu biçimlendirme kuralı, şu şekilde biten hücreleri vurgular:<br/>Verilen metinle. RIGHT() sayfasını kullanmaya eşdeğerdir<br/> fonksiyon ve değerlerin karşılaştırılması.|
| CONTAINS_BLANKS | Bu koşullu biçimlendirme kuralı, hücreleri vurgular<br/>tamamen boştur. LEN(TRIM()) kullanımına eşdeğerdir.<br/>Bu, hücrenin yalnızca karakterler içermesi durumunda<br/>TRIM()'in kaldıracağı değer, boş olarak değerlendirilir.<br/> Boş bir hücre de boş kabul edilir.|
| NOT_CONTAINS_BLANKS | Bu koşullu biçimlendirme kuralı, hücreleri vurgular<br/>boş değil. LEN(TRIM()) kullanımına eşdeğerdir. Bu<br/>hücrenin yalnızca şu karakterleri içermesi anlamına gelir:<br/>TRIM() kaldırılırsa, boş kabul edilir.<br/> boş hücre de boş kabul edilir.|
| CONTAINS_ERRORS | Bu koşullu biçimlendirme kuralı, hücreleri vurgular<br/>formül hataları. ISERROR() sayfasını kullanmaya eşdeğerdir<br/> Formül hatası olup olmadığını belirleme fonksiyonu.|
| NOT_CONTAINS_ERRORS | Bu koşullu biçimlendirme kuralı hücreleri vurgular<br/>formül hataları olmadan. ISERROR() kullanmaya eşdeğerdir<br/> Formül hatası olup olmadığını belirlemek için sayfa işlevi.|
| TIME_PERIOD | Bu koşullu biçimlendirme kuralı hücreleri vurgular<br/>belirtilen zaman dilimindeki tarihleri içeren<br/>hücrenin temel değeri değerlendirilir, bu nedenle<br/>hücrenin tarih olarak biçimlendirilmesine gerek yoktur<br/>değerlendirildi. Örneğin, içeren bir hücre ile<br/>değer 38913 koşullu format aşağıdaki durumlarda uygulanır:<br/> kural 7/14/2006 değerini gerektiriyor.|
| ABOVE_AVERAGE | Bu koşullu biçimlendirme kuralı, hücreleri vurgular<br/>tüm değerler için ortalamanın üstünde veya altında<br/> menzil.|
| COLOR_SCALE | Bu koşullu biçimlendirme kuralı, derecelendirilmiş bir biçimlendirme oluşturur<br/> hücrelerdeki renk skalası.|
| DATA_BAR | Bu koşullu biçimlendirme kuralı, derecelendirilmiş bir biçimlendirme görüntüler<br/> hücre aralığındaki veri çubuğu.|
| ICON_SET |Bu koşullu biçimlendirme kuralı, simgelere hücrelere uygulanır<br/> değerlerine göre.|



###  Ayrıca bakınız
* modül [`aspose.cells`](..)
