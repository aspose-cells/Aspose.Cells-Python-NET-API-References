---
title: Metered класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 1090
url: /ru/aspose.cells/metered/
is_root: false
---
##  Metered класс
Предоставляет методы для установки дозированного ключа.



Тип Metered предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [__init__](/cells/python-net/ru/aspose.cells/metered/__init__/#) | Инициализирует новый экземпляр этого класса.|


###  Методы
| Метод| Описание|
| :- | :- |
| [set_metered_key](/cells/python-net/ru/aspose.cells/metered/set_metered_key/#str-str) | Устанавливает измеренный открытый и закрытый ключ.<br/> Если вы приобретаете лимитную лицензию, при запуске приложения следует позвонить по этому номеру API, обычно этого достаточно.<br/> Однако, если данные о потреблении не загружаются и превышают 24 часа, лицензия будет переведена в оценочный статус.<br/> Чтобы избежать такого случая, вам следует регулярно проверять статус лицензии. Если это оценочный статус, позвоните еще раз по этому номеру API.|
| [get_consumption_quantity](/cells/python-net/ru/aspose.cells/metered/get_consumption_quantity/#) | Получает размер файла потребления|
| [get_consumption_credit](/cells/python-net/ru/aspose.cells/metered/get_consumption_credit/#) | Получает потребительский кредит|
| [get_product_name](/cells/python-net/ru/aspose.cells/metered/get_product_name/#) | Получает название продукта|
| [is_metered_licensed](/cells/python-net/ru/aspose.cells/metered/is_metered_licensed/#) | Проверьте, лицензирован ли счетчик|



###  Пример

В этом примере будет предпринята попытка установить дозированные открытый и закрытый ключи.


```python
from aspose.cells import Metered

matered = Metered()
matered.set_metered_key("PublicKey", "PrivateKey")

```

###  Смотрите также
* модуль [`aspose.cells`](..)
