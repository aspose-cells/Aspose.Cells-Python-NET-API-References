---
title: set_footer метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 180
url: /ru/aspose.cells/pagesetup/set_footer/
is_root: false
---
##  set_footer(self, section, footer_script) {#int-str}
Устанавливает скрипт форматирования нижнего колонтитула файла Excel.



```python

def set_footer(self, section, footer_script):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| section | int |0: Левая секция, 1: Центральная секция, 2: Правая секция.|
| footer_script | str | Скрипт форматирования нижнего колонтитула.|
###  Примечания

Команды скрипта:

| Команда| Описание|
| :- | :- |
| &П| Текущий номер страницы|
| &N| Количество страниц|
| &D| Текущая дата|
| &Т| Текущее время|
| &А| Имя листа|
| &Ф| Имя файла без пути|
| &"<FontName>"|Название шрифта, например: &"Arial"|
| &"<FontName>, <FontStyle>"| Название шрифта и начертание шрифта, например: &"Arial,Bold"|
| &<FontSize>| Размер шрифта. Если за этой командой следует число, которое должно быть выведено в заголовке, оно будет отделено от высоты шрифта пробелом.|
| &К<RRGGBB>| Цвет шрифта, например (КРАСНЫЙ): &KFF0000|
| &Г| Сценарий изображения|

Например: «&Arial,Bold&8Footer Note»


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`PageSetup`](/cells/python-net/ru/aspose.cells/pagesetup)
