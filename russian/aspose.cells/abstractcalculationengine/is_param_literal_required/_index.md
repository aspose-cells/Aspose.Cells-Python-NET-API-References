---
title: is_param_literal_required недвижимость
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 40
url: /ru/aspose.cells/abstractcalculationengine/is_param_literal_required/
is_root: false
---
##  is_param_literal_required недвижимость

Указывает, нужен ли этому движку буквальный текст параметра при выполнении вычислений. Значение по умолчанию — ложь.

###  Примечания

Если для этого пользовательского механизма вычислений требуется литеральный текст параметра, потребуется больше стеков для кэширования литерального текста для параметров, и метод Calculate() может вызываться рекурсивно для вычисления значения параметра.
Обычно литеральный текст не требуется для вычисления формул, и этот метод должен возвращать false для большинства реализаций, чтобы повысить производительность.
###  Определение:
```python
@property
def is_param_literal_required(self):
    ...
```

###  Смотрите также
* модуль [aspose.cells](../../)
* класс [AbstractCalculationEngine](/cells/python-net/ru/aspose.cells/abstractcalculationengine)
