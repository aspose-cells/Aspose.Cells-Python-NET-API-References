---
title: start_cell yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 40
url: /tr/aspose.cells/lightcellsdatahandler/start_cell/
is_root: false
---
##  start_cell(column_index) {#int}
Bir hücreyi işlemek için hazırlanır.


###  İadeler

bu hücrenin işlenmesi gerekip gerekmediği. false , hücreyi yok saymak ve geçerli satırın hücre verilerinin sonuna ulaşana kadar bir sonrakini kontrol etmek için


```python
def start_cell(self, column_index):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| column_index | int | işlenecek hücrenin sütun dizini|
###  Notlar

Geçerli satırdaki mevcut bir hücreye ulaşıldığında çağrılacaktır. Geçerli satır, [LightCellsDataHandler.process_row(row)](/cells/python-net/tr/aspose.cells/lightcellsdatahandler/process_row) numaralı son aramanın satırıdır.


###  Ayrıca bakınız

* modül [aspose.cells](../../)
* sınıf [LightCellsDataHandler](/cells/python-net/tr/aspose.cells/lightcellsdatahandler)
