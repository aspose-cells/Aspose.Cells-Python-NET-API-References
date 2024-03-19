---
title: is_param_literal_required недвижимость
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 50
url: /ru/aspose.cells/abstractcalculationengine/is_param_literal_required/
is_root: false
---
##  is_param_literal_required недвижимость

Указывает, нужен ли этому механизму буквальный текст параметра при выполнении вычислений. Значение по умолчанию — ложь.

###  Примечания

Если этому пользовательскому механизму вычислений требуется буквальный текст параметра,
для кэширования буквального текста для параметров потребуется больше стеков
и метод Calculate() можно вызывать рекурсивно для вычисления значения параметра.
Обычно для расчета формул не требуется буквенный текст.
и это свойство должно оставаться ложным для большинства реализаций, чтобы повысить производительность.
###  Определение:
```python
@property
def is_param_literal_required(self):
    ...
```

###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`AbstractCalculationEngine`](/cells/python-net/ru/aspose.cells/abstractcalculationengine)
