---
title: LightCellsDataProvider класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 1040
url: /ru/aspose.cells/lightcellsdataprovider/
is_root: false
---
##  LightCellsDataProvider класс
Представляет поставщика данных для сохранения больших файлов электронных таблиц в облегченном режиме.



Тип LightCellsDataProvider предоставляет следующие элементы:

###  Методы
| Метод| Описание|
| :- | :- |
| [start_sheet](/cells/python-net/ru/aspose.cells/lightcellsdataprovider/start_sheet/#int) | Начинает сохранять лист.|
| [next_row](/cells/python-net/ru/aspose.cells/lightcellsdataprovider/next_row/#) | Получает следующую сохраняемую строку.|
| [start_row](/cells/python-net/ru/aspose.cells/lightcellsdataprovider/start_row/#aspose.cells.Row) | Начинает сохранять данные одной строки.|
| [next_cell](/cells/python-net/ru/aspose.cells/lightcellsdataprovider/next_cell/#) | Получает следующую ячейку для сохранения.|
| [start_cell](/cells/python-net/ru/aspose.cells/lightcellsdataprovider/start_cell/#aspose.cells.Cell) | Начинает сохранять данные одной ячейки.|
| [is_gather_string](/cells/python-net/ru/aspose.cells/lightcellsdataprovider/is_gather_string/#) |Проверяет, нужно ли собирать текущее строковое значение ячейки в глобальный пул.|



###  Примечания

При сохранении книги в этом режиме [`LightCellsDataProvider.start_sheet`](/cells/python-net/ru/aspose.cells/lightcellsdataprovider/start_sheet) будет проверяться при сохранении каждого листа в книге.
Для одного листа, если [`LightCellsDataProvider.start_sheet`](/cells/python-net/ru/aspose.cells/lightcellsdataprovider/start_sheet) дает true, то все данные и свойства сохраняются для строк/ячейок этого листа.
будет обеспечена реализацией этого интерфейса.
В первую очередь будет вызван [`LightCellsDataProvider.next_row`](/cells/python-net/ru/aspose.cells/lightcellsdataprovider/next_row), чтобы получить индекс следующей строки, который нужно сохранить.
Если возвращается действительный индекс строки (индекс строки должен быть в порядке возрастания, чтобы строки могли быть сохранены),
тогда объект Row, представляющий эту строку, будет предоставлен [`LightCellsDataProvider.start_row`](/cells/python-net/ru/aspose.cells/lightcellsdataprovider/start_row) для реализации, чтобы установить его свойства.
Для одной строки в первую очередь будет проверяться [`LightCellsDataProvider.next_cell`](/cells/python-net/ru/aspose.cells/lightcellsdataprovider/next_cell).
Если возвращен действительный индекс столбца (индекс столбца должен быть в порядке возрастания для всех ячеек текущей строки),
тогда объект Cell, представляющий эту ячейку, будет предоставлен [`LightCellsDataProvider.start_cell`](/cells/python-net/ru/aspose.cells/lightcellsdataprovider/start_cell) для реализации для установки ее данных и свойств.
После [`LightCellsDataProvider.start_cell`](/cells/python-net/ru/aspose.cells/lightcellsdataprovider/start_cell) ячейка будет сохранена непосредственно в результирующий файл электронной таблицы.
Затем будет проверена и обработана следующая ячейка.


Обратите внимание: пользователю следует обновлять значения и свойства только для текущего объекта Row/Cell, предоставленного соответствующим методом.
Поскольку данные ячеек записываются в результирующий файл в потоковом режиме, большинство других объектов могли быть записаны
в результирующий файл или были собраны и записаны для них некоторые глобальные данные. Поэтому, когда пользователь обновляет другие объекты
при сохранении данных ячеек эти операции могут не повлиять на сохраненные данные. Или, что еще хуже, эти операции могут
привести к сохранению противоречивых данных в результирующем файле и, в конечном итоге, к повреждению файла.
Итак, для всех других объектов, таких как фигуры, ширина и стили столбцов, условное форматирование и т. д.,
пожалуйста, не используйте их ни в каких методах этой реализации.
Вместо этого управляйте ими и приведите их в окончательное состояние перед вызовом метода «Сохранить» в рабочей книге.

###  Смотрите также
* модуль [`aspose.cells`](..)
