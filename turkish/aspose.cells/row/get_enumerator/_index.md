---
title: get_enumerator yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 70
url: /tr/aspose.cells/row/get_enumerator/
is_root: false
---
##  get_enumerator(self, reversed, sync) {#bool-bool}
Bu satırdaki hücreleri yineleyen bir numaralandırıcı alır.


###  İadeler

Hücre sayımcısı


```python

def get_enumerator(self, reversed, sync):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| reversed | bool |hücreleri ters sırada numaralandırın|
| sync | bool | döndürülen numaralandırıcının bu satırdaki hücrelerin değişikliğini kontrol edip etmemesi<br/> ve onunla senkronize kalın.|
###  Notlar

Satır değiştirilecekse (yeni Cell'in örneklenmesine neden olabilecek işlemlerle veya
mevcut Cell numaranın numaralandırıcı ile geçiş sırasında kaldırılması,
geçişin devam edebilmesi için normal numaralandırıcı yerine senkronize numaralandırıcı kullanılmalıdır
son MoveNext() tarafından geçilen konumdan hemen sonraki konumdan.
Ancak, hiçbir öğenin atlanmaması veya tekrar tekrar geçilmemesi avantajının yanı sıra,
Eşzamanlı numaralandırıcının dezavantajı, performansın biraz düşmesidir
normal sayım cihazıyla karşılaştırıldığında.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Row`](/cells/python-net/tr/aspose.cells/row)
