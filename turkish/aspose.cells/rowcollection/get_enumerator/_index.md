---
title: get_enumerator yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 30
url: /tr/aspose.cells/rowcollection/get_enumerator/
is_root: false
---
##  get_enumerator(self, reversed, sync) {#bool-bool}
Bu koleksiyondaki satırları yineleyen bir numaralandırıcı alır


###  İadeler

Satır numaralandırıcı


```python

def get_enumerator(self, reversed, sync):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| reversed | bool | satırları ters sırada numaralandırın|
| sync | bool | döndürülen numaralandırıcının satır koleksiyonunun değişikliğini kontrol edip etmemesi gerektiği<br/> ve onunla senkronize kalın.|
###  Notlar

Satır koleksiyonu değiştirilecekse (yeni Satırın örneklenmesine neden olabilecek işlemlerle veya
Mevcut Satır (numaralandırıcı ile yapılan geçiş sırasında kaldırılabilir),
geçişin devam edebilmesi için normal numaralandırıcı yerine senkronize numaralandırıcı kullanılmalıdır
son MoveNext() tarafından geçilen konumdan hemen sonraki konumdan.
Ancak, hiçbir öğenin atlanmaması veya tekrar tekrar geçilmemesi avantajının yanı sıra,
Eşzamanlı numaralandırıcının dezavantajı, performansın biraz düşmesidir
normal sayım cihazıyla karşılaştırıldığında.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`RowCollection`](/cells/python-net/tr/aspose.cells/rowcollection)
