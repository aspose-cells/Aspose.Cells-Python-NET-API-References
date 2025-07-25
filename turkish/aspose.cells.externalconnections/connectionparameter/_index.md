---
title: ConnectionParameter sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 10
url: /tr/aspose.cells.externalconnections/connectionparameter/
is_root: false
---
##  ConnectionParameter sınıfı
Harici veri bağlantılarıyla kullanılan tüm parametreler hakkında özellikleri belirtir
Parametreler ODBC ve web sorguları için geçerlidir.



ConnectionParameter türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [sql_type](/cells/python-net/tr/aspose.cells.externalconnections/connectionparameter/sql_type) | Parametrenin SQL veri türü. Yalnızca ODBC kaynakları için geçerlidir.|
| [refresh_on_change](/cells/python-net/tr/aspose.cells.externalconnections/connectionparameter/refresh_on_change) | Bir sorgunun içeriği güncellendiğinde otomatik olarak yenilenip yenilenmeyeceğini belirten bayrak<br/> Parametre değerini sağlayan hücre değişir. Doğruysa, harici veriler yenilenir.<br/> Her değişiklik olduğunda yeni parametre değeri kullanılır. Yanlış ise, harici veriler<br/> yalnızca kullanıcı tarafından istendiğinde veya başka bir olay yenilemeyi tetiklediğinde (örneğin, çalışma kitabı açıldığında) yenilenir.|
| [prompt](/cells/python-net/tr/aspose.cells.externalconnections/connectionparameter/prompt) | Parametre için istem dizesi. Giriş kullanıcı arayüzüyle birlikte elektronik tablo kullanıcısına sunulur.<br/> Harici verileri yenilemeden önce parametre değerini toplamak için kullanılır. Yalnızca şu durumlarda kullanılır:<br/>parametreTürü = istem.|
| [type](/cells/python-net/tr/aspose.cells.externalconnections/connectionparameter/type) | Kullanılan parametrenin türü.<br/> Eğer parameterType=value ise, boolean, double, integer değerlerinden biri<br/> veya dizesi kullanılacaktır. Bu durumda, yalnızca birinin kullanılması beklenir.<br/> {boolean, double, integer veya string} belirtilecektir.|
| [name](/cells/python-net/tr/aspose.cells.externalconnections/connectionparameter/name) | Parametrenin adı.|
| [cell_reference](/cells/python-net/tr/aspose.cells.externalconnections/connectionparameter/cell_reference) | Cell, sorgu parametresi için hangi hücrenin değerinin kullanılacağını belirten referanstır. Yalnızca parameterType hücre olduğunda kullanılır.|
| [value](/cells/python-net/tr/aspose.cells.externalconnections/connectionparameter/value) | Tam sayı olmayan sayısal değer, Tam sayı değeri, Dize değeri veya Boole değeri<br/> Sorgu parametresi olarak kullanılacak. Yalnızca parameterType değeri değer olduğunda kullanılır.|



###  Ayrıca bakınız
* modül [`aspose.cells.externalconnections`](..)
