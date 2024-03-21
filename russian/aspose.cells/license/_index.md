---
title: License класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 1020
url: /ru/aspose.cells/license/
is_root: false
---
##  License класс
Предоставляет методы для лицензирования компонента.



Тип License предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [__init__](/cells/python-net/ru/aspose.cells/license/__init__/#) | Инициализирует новый экземпляр этого класса.|


###  Методы
| Метод| Описание|
| :- | :- |
| [set_license](/cells/python-net/ru/aspose.cells/license/set_license/#str) | Лицензирует компонент.|
| [set_license](/cells/python-net/ru/aspose.cells/license/set_license/#io.RawIOBase) | Лицензирует компонент.|



###  Пример

В этом примере будет предпринята попытка найти файл лицензии с именем MyLicense.lic.
 в папке, содержащей


компонент в папке, содержащей вызывающую сборку,
в папке входной сборки, а затем во внедренных ресурсах вызывающей сборки.

```python
from aspose.cells import License

license = License()
license.set_license("MyLicense.lic")

```

###  Смотрите также
* модуль [`aspose.cells`](..)
