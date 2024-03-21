---
title: check_font_compatibility недвижимость
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 60
url: /ru/aspose.cells/pptxsaveoptions/check_font_compatibility/
is_root: false
---
##  check_font_compatibility недвижимость

Указывает, следует ли проверять совместимость шрифтов для каждого символа в тексте.

###  Примечания

Значение по умолчанию верно.
Отключение этого свойства может повысить производительность.
Но когда для его отображения нельзя использовать шрифт по умолчанию или указанный шрифт текста/символа,
в сгенерированном PDF-файле могут встречаться нечитаемые символы (например, блоки).
В такой ситуации пользователь должен сохранить это свойство как истинное, чтобы
можно найти альтернативный шрифт и использовать его для отображения текста;
###  Определение:
```python
@property
def check_font_compatibility(self):
    ...
@check_font_compatibility.setter
def check_font_compatibility(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`PptxSaveOptions`](/cells/python-net/ru/aspose.cells/pptxsaveoptions)
