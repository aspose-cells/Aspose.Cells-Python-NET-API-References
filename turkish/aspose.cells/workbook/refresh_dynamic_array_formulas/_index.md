---
title: refresh_dynamic_array_formulas yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 270
url: /tr/aspose.cells/workbook/refresh_dynamic_array_formulas/
is_root: false
---
##  refresh_dynamic_array_formulas {#bool}
Dinamik dizi formüllerini yeniler (mevcut verilere göre yeni komşu hücre aralığına yayılır)
Çalışma kitabındaki diğer formüller, dinamik dizi formülleri tarafından kullanılmış olsalar bile yinelemeli olarak hesaplanmayacaktır.



```python
def refresh_dynamic_array_formulas(self, calculate):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| calculate | bool | Bu dinamik dizi formülleri için hücre değerlerinin hesaplanıp güncellenmediği|


##  refresh_dynamic_array_formulas {#bool-aspose.cells.CalculationOptions}
Dinamik dizi formüllerini yeniler (mevcut verilere göre yeni komşu hücre aralığına yayılır)



```python
def refresh_dynamic_array_formulas(self, calculate, copts):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| calculate | bool | Bu dinamik dizi formülleri için hücre değerlerinin hesaplanıp güncellenmediği|
| copts | [`CalculationOptions`](/cells/python-net/tr/aspose.cells/calculationoptions) | Formülleri hesaplama seçenekleri|
###  Notlar

Performansı değerlendirmek amacıyla tüm dinamik dizi formüllerini otomatik olarak yenilemiyoruz
formülün kendisi veya başvurduğu veriler değiştiğinde.
Dolayısıyla kullanıcının dinamik dizi formüllerini etkileyebilecek işlemlerden sonra bu yöntemi manuel olarak çağırması gerekir.
hücre değerlerini içe aktarma/ayarlama, satır/sütun/aralık ekleme/silme vb. gibi.

Fonksiyonlara sahip çoğu formül için dökülme aralığının hesaplanması aynı zamanda formülün de hesaplanmasını gerektirir,
bu nedenle genel olarak "hesapla" bayrağı için gerçek değer tercih edilir.
Formül, aralık başvurusu veya dizi gibi basitse (örneğin "=C1:E5", "={1,2;3,4}", ...),
bir aralık veya dizideki basit işlev (örneğin "=ABS(C1:E5)", "=1+{1,2;3,4}", ...),
ve tüm formüller daha sonra hesaplanacaktır ([`Workbook.calculate_formula`](/cells/python-net/tr/aspose.cells/workbook/calculate_formula) gibi),
daha sonra "hesapla" bayrağı için yanlış değerin kullanılması, performans yararına yinelenen hesaplamayı önleyebilir.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Workbook`](/cells/python-net/tr/aspose.cells/workbook)
