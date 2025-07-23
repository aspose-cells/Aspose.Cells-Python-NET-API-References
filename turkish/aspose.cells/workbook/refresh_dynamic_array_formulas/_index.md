---
title: refresh_dynamic_array_formulas yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 290
url: /tr/aspose.cells/workbook/refresh_dynamic_array_formulas/
is_root: false
---
##  refresh_dynamic_array_formulas(self, calculate) {#bool}
Dinamik dizi formüllerini yeniler (geçerli verilere göre komşu hücrelerin yeni aralığına taşır)
Çalışma kitabındaki diğer formüller, dinamik dizi formülleri tarafından kullanılsalar bile yinelemeli olarak hesaplanmayacaktır.



```python

def refresh_dynamic_array_formulas(self, calculate):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| calculate | bool | Bu dinamik dizi formülleri için hücre değerlerini hesaplar ve günceller mi?|


##  refresh_dynamic_array_formulas(self, calculate, copts) {#bool-aspose.cells.CalculationOptions}
Dinamik dizi formüllerini yeniler (geçerli verilere göre komşu hücrelerin yeni aralığına taşır)



```python

def refresh_dynamic_array_formulas(self, calculate, copts):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| calculate | bool | Bu dinamik dizi formülleri için hücre değerlerini hesaplar ve günceller mi?|
| copts | [`CalculationOptions`](/cells/python-net/tr/aspose.cells/calculationoptions) | Formülleri hesaplama seçenekleri|
###  Notlar

Performans değerlendirmesi için tüm dinamik dizi formüllerini otomatik olarak yenilemiyoruz
Formülün kendisi veya başvurduğu veriler değiştiğinde.
Bu nedenle, kullanıcının dinamik dizi formüllerini etkileyebilecek işlemlerden sonra bu yöntemi manuel olarak çağırması gerekir.
hücre değerlerini içe aktarmak/ayarlamak, satır/sütun/aralık eklemek/silmek, ...vb. gibi.

Fonksiyonlu formüllerin çoğu için, dökülme aralığının hesaplanması aynı zamanda formülün hesaplanmasını da gerektirir.
bu nedenle genel olarak "hesapla" bayrağı için gerçek değer tercih edilir.
Formül basit ise, örneğin bir aralık başvurusu veya dizi ise (örneğin "=C1:E5", "={1,2;3,4}", ...),
bir aralık veya dizi üzerinde basit bir fonksiyon (örneğin "=ABS(C1:E5)", "=1+{1,2;3,4}", ...),
ve tüm formüller daha sonra hesaplanacaktır (örneğin [`Workbook.calculate_formula`](/cells/python-net/tr/aspose.cells/workbook/calculate_formula)),
o zaman "hesapla" bayrağı için false değerini kullanmak, performans açısından tekrarlanan hesaplamanın önüne geçebilir.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Workbook`](/cells/python-net/tr/aspose.cells/workbook)
