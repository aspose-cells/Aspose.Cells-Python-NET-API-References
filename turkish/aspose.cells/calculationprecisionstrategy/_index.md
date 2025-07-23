---
title: CalculationPrecisionStrategy numaralandırma
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1790
url: /tr/aspose.cells/calculationprecisionstrategy/
is_root: false
---
##  CalculationPrecisionStrategy numaralandırma
Hesaplama hassasiyetini ele almaya yönelik stratejileri sıralar.
IEEE 754 Kayan Nokta Aritmetiği'nin kesinlik sorunu nedeniyle, bazı "görünüşte basit" formüller beklenen sonuç olarak hesaplanmayabilir.
Örneğin "=-0,45+0,43+0,02" formülünde, işlenenler doğrudan '+' operatörüyle hesaplandığında sonuç sıfır olmaz. Bu tür bir hassasiyet sorunu için,
Bazı özel stratejiler beklenen sonucu verebilir.



CalculationPrecisionStrategy türü aşağıdaki üyeleri ortaya çıkarır:

###  Alanlar
| Alan| Tanım|
| :- | :- |
| NONE | Hesaplamada herhangi bir strateji uygulanmadı.<br/>Hesaplama yaparken sadece orijinal double değerini operand olarak kullanın ve sonucu doğrudan döndürün.<br/> Performans açısından en verimli ve çoğu durumda uygulanabilir.|
| ROUND | Hesaplama sonucunu anlamlı basamaklara göre yuvarlar.|
| DECIMAL | Mümkün olduğunda işlenen olarak ondalık sayı kullanılır.<br/> Performans açısından en verimsiz olanı.|



###  Ayrıca bakınız
* modül [`aspose.cells`](..)
