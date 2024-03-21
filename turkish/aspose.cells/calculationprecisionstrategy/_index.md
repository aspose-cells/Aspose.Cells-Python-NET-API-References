---
title: CalculationPrecisionStrategy numaralandırma
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1890
url: /tr/aspose.cells/calculationprecisionstrategy/
is_root: false
---
##  CalculationPrecisionStrategy numaralandırma
Hesaplama hassasiyetini yönetmeye yönelik stratejileri sıralar.
IEEE 754 Kayan Nokta Aritmetiğinin kesinlik sorunu nedeniyle bazı "görünüşte basit" formüller beklenen sonuç olarak hesaplanamayabilir.
"=-0.45+0.43+0.02" formülü gibi, işlenenler doğrudan '+' operatörüyle hesaplanırken sonuç sıfır değildir. Bu tür hassas bir sorun için,
bazı özel stratejiler beklenen sonucu verebilir.



CalculationPrecisionStrategy türü aşağıdaki üyeleri ortaya çıkarır:

###  Alanlar
| Alan| Tanım|
| :- | :- |
| NONE | Hesaplamada herhangi bir strateji uygulanmadı.<br/>Hesaplarken yalnızca orijinal double değerini işlenen olarak kullanın ve sonucu doğrudan döndürün.<br/> Performans açısından en verimli ve çoğu durumda uygulanabilir.|
| ROUND | Hesaplama sonucunu anlamlı basamaklara göre yuvarlar.|
| DECIMAL |Mümkün olduğunda işlenen olarak ondalık sayıyı kullanır.<br/> Performans açısından en verimsiz.|



###  Ayrıca bakınız
* modül [`aspose.cells`](..)
