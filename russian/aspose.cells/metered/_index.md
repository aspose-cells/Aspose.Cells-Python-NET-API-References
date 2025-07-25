---
title: Metered класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 980
url: /ru/aspose.cells/metered/
is_root: false
---
##  Metered класс
Предоставляет методы установки измеренного ключа.



Тип Metered предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ru/aspose.cells/metered/__init__/#) | Инициализирует новый экземпляр этого класса.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`set_metered_key(self, public_key, private_key)`](/cells/python-net/ru/aspose.cells/metered/set_metered_key/#str-str) | Устанавливает контролируемые открытый и закрытый ключ.<br/>Если вы приобретаете лимитированную лицензию, то при запуске приложения необходимо вызвать API, обычно этого достаточно.<br/> Однако, если данные о потреблении не будут загружены и продолжительность загрузки превысит 24 часа, лицензия будет переведена в статус оценочной.<br/> Чтобы избежать подобных случаев, необходимо регулярно проверять статус лицензии. Если это статус оценки, позвоните по номеру API еще раз.|
| [`get_consumption_quantity()`](/cells/python-net/ru/aspose.cells/metered/get_consumption_quantity/#) | Получает размер файла потребления|
| [`get_consumption_credit()`](/cells/python-net/ru/aspose.cells/metered/get_consumption_credit/#) | Получает потребительский кредит|
| [`get_product_name(self)`](/cells/python-net/ru/aspose.cells/metered/get_product_name/#) | Получает название продукта|
| [`is_metered_licensed()`](/cells/python-net/ru/aspose.cells/metered/is_metered_licensed/#) | Проверьте, есть ли лицензия на счетчик|



###  Пример

В этом примере будет сделана попытка установить измеренный открытый и закрытый ключ.


```python
from aspose.cells import Metered

matered = Metered()
matered.set_metered_key("PublicKey", "PrivateKey")

```

###  Смотрите также
* модуль [`aspose.cells`](..)
