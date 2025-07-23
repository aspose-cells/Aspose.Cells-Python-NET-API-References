---
title: License класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 930
url: /ru/aspose.cells/license/
is_root: false
---
##  License класс
Предоставляет методы лицензирования компонента.



Тип License предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ru/aspose.cells/license/__init__/#) | Инициализирует новый экземпляр этого класса.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`set_license(self, license_name)`](/cells/python-net/ru/aspose.cells/license/set_license/#str) | Лицензирует компонент.|
| [`set_license(self, stream)`](/cells/python-net/ru/aspose.cells/license/set_license/#io.rawiobase) | Лицензирует компонент.|



###  Пример

В этом примере будет предпринята попытка найти файл лицензии с именем MyLicense.lic.
 в папке, которая содержит


компонент в папке, содержащей вызывающую сборку,
в папке входной сборки, а затем во встроенных ресурсах вызывающей сборки.

```python
from aspose.cells import License

license = License()
license.set_license("MyLicense.lic")

```

###  Смотрите также
* модуль [`aspose.cells`](..)
