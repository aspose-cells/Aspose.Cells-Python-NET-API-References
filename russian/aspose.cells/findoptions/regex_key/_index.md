---
title: regex_key недвижимость
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 110
url: /ru/aspose.cells/findoptions/regex_key/
is_root: false
---
##  regex_key недвижимость

Указывает, является ли искомый ключ регулярным выражением.
Если значение true, то искомый ключ будет принят за регулярное выражение и проанализирован.
В противном случае ключ будет обработан согласно правилам MS Excel.

###  Примечания

Несмотря на то, что ключ поиска был указан как регулярное выражение,
он может быть рефакторингован согласно указанному [`FindOptions.look_at_type`](/cells/python-net/ru/aspose.cells/findoptions#look_at_type).
Например, если тип — [`LookAtType.CONTAINS`](/cells/python-net/ru/aspose.cells/lookattype#CONTAINS) (это значение по умолчанию для этого параметра),
Подстановочные знаки будут автоматически добавлены в начало и конец поискового ключа, чтобы гарантировать совпадение.
Отмечено как «содержит». В этом случае регулярные выражения станут сложнее.
и производительность также снизится.
Итак, с точки зрения производительности, если пользователь указал точное правило для регулярного выражения, то нет необходимости
использовать [`FindOptions.look_at_type`](/cells/python-net/ru/aspose.cells/findoptions#look_at_type) как дополнительное ограничение, и пользователь может установить его как [`LookAtType.ENTIRE_CONTENT`](/cells/python-net/ru/aspose.cells/lookattype#ENTIRE_CONTENT)
для достижения более высокой производительности.
###  Определение:
```python
@property
def regex_key(self):
    ...
@regex_key.setter
def regex_key(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`FindOptions`](/cells/python-net/ru/aspose.cells/findoptions)
