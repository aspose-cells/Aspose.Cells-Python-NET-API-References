---
title: get_equation_paragraph метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 110
url: /ru/aspose.cells.drawing/textbox/get_equation_paragraph/
is_root: false
---
##  get_equation_paragraph(self) {#}
Получает первый математический абзац из свойства TextBody объекта TextBox.


###  Возврат

Если есть математический абзац, возвращает первый, в противном случае возвращает null.


```python

def get_equation_paragraph(self):
    ...
```




##  get_equation_paragraph(self, index) {#int}
Получить указанный математический абзац из свойства TextBody объекта TextBox.
Уведомление:
(1) Возвращает NULL, если индекс выходит за пределы или не найден.
(2) Также возвращает NULL, если указанная позиция индекса не является математическим абзацем.


###  Возврат

Возвращает математический абзац, указанный индексом.


```python

def get_equation_paragraph(self, index):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| index | int | Индекс позиции математического абзаца, начиная с 0.|



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`TextBox`](/cells/python-net/ru/aspose.cells.drawing/textbox)
