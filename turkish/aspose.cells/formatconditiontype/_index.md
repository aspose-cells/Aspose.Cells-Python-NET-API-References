---
title: FormatConditionType numaralandırma
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 2170
url: /tr/aspose.cells/formatconditiontype/
is_root: false
---
##  FormatConditionType numaralandırma
Koşullu biçim kural türü.



FormatConditionType türü aşağıdaki üyeleri ortaya çıkarır:

###  Alanlar
| Alan| Tanım|
| :- | :- |
| CELL_VALUE | Bu koşullu biçimlendirme kuralı bir hücre değerini karşılaştırır<br/> bir operatör kullanılarak formülle hesaplanan sonuca.|
| EXPRESSION | Bu koşullu biçimlendirme kuralı aşağıdakileri yapacak bir formül içerir:<br/>değerlendirmek. Formül sonucu doğru olduğunda hücre<br/> vurgulanmıştır.|
| TOP10 | Bu koşullu biçimlendirme kuralı,<br/>değerler üst N veya alt N parantezinde yer alır, çünkü<br/> belirtildi.|
| UNIQUE_VALUES |Bu koşullu biçimlendirme kuralı benzersiz öğeleri vurgular<br/> aralıktaki değerler.|
| DUPLICATE_VALUES | Bu koşullu biçimlendirme kuralı yinelenenleri vurgular<br/> değerler.|
| CONTAINS_TEXT | Bu koşullu biçimlendirme kuralı hücreleri vurgular<br/>Verilen metni içeren. SEARCH() işlevini kullanmaya eşdeğerdir<br/>Hücrenin içerip içermediğini belirlemek için sayfa işlevi<br/> Metin.|
| NOT_CONTAINS_TEXT | Bu koşullu biçimlendirme kuralı, aşağıdaki hücreleri vurgular:<br/>verilen metni içermez. SEARCH() işlevini kullanmaya eşdeğer<br/>Hücrenin içerip içermediğini belirlemek için sayfa işlevi<br/> metin olsun ya da olmasın.|
| BEGINS_WITH | Bu koşullu biçimlendirme kuralı,<br/>Verilen metinle başlayan aralık. Eşittir<br/> LEFT() sayfa işlevini kullanma ve değerleri karşılaştırma.|
| ENDS_WITH | Bu koşullu biçimlendirme kuralı, biten hücreleri vurgular<br/>verilen metinle. RIGHT() sayfasını kullanmaya eşdeğerdir<br/> fonksiyon ve değerlerin karşılaştırılması.|
| CONTAINS_BLANKS | Bu koşullu biçimlendirme kuralı, aşağıdaki hücreleri vurgular:<br/>tamamen boştur. LEN(TRIM()) kullanımına eşdeğerdir.<br/>Bu, hücrenin yalnızca karakterler içermesi durumunda<br/>TRIM() öğesinin kaldırılacağı durumlarda boş kabul edilir.<br/> Boş bir hücre de boş kabul edilir.|
| NOT_CONTAINS_BLANKS | Bu koşullu biçimlendirme kuralı, aşağıdaki hücreleri vurgular:<br/>boş değiller. LEN(TRIM()) kullanımına eşdeğerdir. Bu<br/>hücrenin yalnızca karakterler içermesi durumunda anlamına gelir<br/>TRIM() kaldırılırsa boş kabul edilir. Bir<br/> boş hücre de boş kabul edilir.|
| CONTAINS_ERRORS | Bu koşullu biçimlendirme kuralı, hücreleri vurgular<br/>formül hataları. ISERROR() sayfasını kullanmaya eşdeğerdir<br/> Formül hatası olup olmadığını belirleme işlevi.|
| NOT_CONTAINS_ERRORS | Bu koşullu biçimlendirme kuralı hücreleri vurgular<br/>formül hatası olmadan. ISERROR() kullanmaya eşdeğerdir<br/> Formül hatası olup olmadığını belirlemek için sayfa işlevi.|
| TIME_PERIOD | Bu koşullu biçimlendirme kuralı hücreleri vurgular<br/>belirtilen zaman dilimindeki tarihleri içerir.<br/>hücrenin temel değeri değerlendirilir, dolayısıyla<br/>hücrenin tarih olarak biçimlendirilmesine gerek yoktur<br/>değerlendirildi. Örneğin, aşağıdakileri içeren bir hücreyle:<br/>değer 38913 ise koşullu format uygulanacaktır:<br/> kural 14.07.2006 değerini gerektirir.|
| ABOVE_AVERAGE | Bu koşullu biçimlendirme kuralı, aşağıdaki hücreleri vurgular:<br/>tüm değerler için ortalamanın üstünde veya altındadır.<br/> menzil.|
| COLOR_SCALE | Bu koşullu biçimlendirme kuralı, derecelendirilmiş bir<br/> Hücrelerdeki renk skalası.|
| DATA_BAR | Bu koşullu biçimlendirme kuralı, derecelendirilmiş bir<br/> hücre aralığındaki veri çubuğu.|
| ICON_SET | Bu koşullu biçimlendirme kuralı, simgeleri hücrelere uygular<br/> değerlerine göre.|



###  Ayrıca bakınız
* modül [`aspose.cells`](..)
