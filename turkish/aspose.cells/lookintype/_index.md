---
title: LookInType numaralandırma
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 2270
url: /tr/aspose.cells/lookintype/
is_root: false
---
##  LookInType numaralandırma
Tip olarak görünümü temsil eder.



LookInType türü aşağıdaki üyeleri ortaya çıkarır:

###  Alanlar
| Alan| Tanım|
| :- | :- |
| FORMULAS | Hücre formül ise, formül([`Cell.formula`](/cells/python-net/tr/aspose.cells/cell#formula))'den aranan nesneyi bulur,<br/>Aksi takdirde hücrenin orijinal değerinden bulunur ([`LookInType.ORIGINAL_VALUES`](/cells/python-net/tr/aspose.cells/lookintype#ORIGINAL_VALUES) ile aynıdır).|
| VALUES | Hücrenin orijinal değerinden nesneyi bulur ([`Cell.value`](/cells/python-net/tr/aspose.cells/cell#value))<br/> ve biçimlendirilmiş değer([`Cell.string_value`](/cells/python-net/tr/aspose.cells/cell#string_value)).|
| VALUES_EXCLUDE_FORMULA_CELL | Formül içeren hücreleri yok sayar. Formül içermeyen hücreler için,<br/> [`LookInType.VALUES`](/cells/python-net/tr/aspose.cells/lookintype#VALUES)'de de durum aynıdır.|
| COMMENTS | Nesneyi yalnızca hücrenin yorumundan bulur. Yorumu olmayan hücreleri yok sayar.|
| ONLY_FORMULAS | Formül olmayan hücreleri yok sayar. Formül olan hücreler için,<br/> ([`Cell.formula`](/cells/python-net/tr/aspose.cells/cell#formula)) formülünden aranan nesneyi bulur.|
| ORIGINAL_VALUES | Nesneyi yalnızca hücrenin orijinal değerinden bul.|
| FORMATTED_VALUES | Nesneyi yalnızca hücrenin biçimlendirilmiş değerinden ([`Cell.string_value`](/cells/python-net/tr/aspose.cells/cell#string_value)) bul.|



###  Ayrıca bakınız
* modül [`aspose.cells`](..)
