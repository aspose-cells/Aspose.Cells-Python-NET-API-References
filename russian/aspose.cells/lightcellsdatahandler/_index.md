---
title: LightCellsDataHandler класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 1030
url: /ru/aspose.cells/lightcellsdatahandler/
is_root: false
---
##  LightCellsDataHandler класс
Представляет обработчик данных ячеек для чтения больших файлов электронных таблиц в облегченном режиме.



Тип LightCellsDataHandler предоставляет следующие элементы:

###  Методы
| Метод| Описание|
| :- | :- |
| [start_sheet](/cells/python-net/ru/aspose.cells/lightcellsdatahandler/start_sheet/#aspose.cells.Worksheet) | Начинает обрабатывать рабочий лист.|
| [start_row](/cells/python-net/ru/aspose.cells/lightcellsdatahandler/start_row/#int) | Готовится к обработке строки.|
| [process_row](/cells/python-net/ru/aspose.cells/lightcellsdatahandler/process_row/#aspose.cells.Row) | Начинает обрабатывать одну строку.|
| [start_cell](/cells/python-net/ru/aspose.cells/lightcellsdatahandler/start_cell/#int) | Готовится к обработке ячейки.|
| [process_cell](/cells/python-net/ru/aspose.cells/lightcellsdatahandler/process_cell/#aspose.cells.Cell) | Начинает обрабатывать одну ячейку.|



###  Примечания

При чтении книги в этом режиме [`LightCellsDataHandler.start_sheet`](/cells/python-net/ru/aspose.cells/lightcellsdatahandler/start_sheet) будет проверяться при чтении каждого листа в книге.
Для одного листа, если [`LightCellsDataHandler.start_sheet`](/cells/python-net/ru/aspose.cells/lightcellsdatahandler/start_sheet) выдает true, то будут проверены все данные и свойства строк/ячейок этого листа.
и обрабатывается реализацией этого интерфейса. Для каждой строки будет вызываться [`LightCellsDataHandler.start_row`](/cells/python-net/ru/aspose.cells/lightcellsdatahandler/start_row), чтобы проверить, нужно ли ее обрабатывать.
Если строку необходимо обработать, сначала будут прочитаны свойства этой строки, и пользователь сможет получить доступ к ее свойствам по номеру [`LightCellsDataHandler.process_row`](/cells/python-net/ru/aspose.cells/lightcellsdatahandler/process_row).
если ячейки строки также необходимо обработать, то [`LightCellsDataHandler.process_row`](/cells/python-net/ru/aspose.cells/lightcellsdatahandler/process_row) должно вернуть true, а затем [`LightCellsDataHandler.start_cell`](/cells/python-net/ru/aspose.cells/lightcellsdatahandler/start_cell) будет
вызывается для каждой существующей ячейки в этой строке, чтобы проверить, нужно ли обрабатывать одну ячейку. Если необходимо обработать одну ячейку,
затем будет вызван [`LightCellsDataHandler.process_cell`](/cells/python-net/ru/aspose.cells/lightcellsdatahandler/process_cell) для обработки ячейки посредством реализации этого интерфейса.


Обратите внимание, что пользователь должен работать только со значениями и свойствами текущего объекта Row/Cell, предоставленными соответствующим методом.
Поскольку данные ячеек считываются из файла шаблона в потоковом режиме, большинство других объектов могут быть сброшены/обновлены позже.
после загрузки данных ячеек. Поэтому, когда пользователь управляет другими объектами в этой реализации,
эти операции могут не повлиять на объекты, существующие в книге. Или, что еще хуже, эти операции могут
привести к противоречивым данным в книге, а затем вызвать непредвиденную проблему или исключение позже.
Итак, для всех других объектов, таких как фигуры, ширина и стили столбцов, условное форматирование и т. д.,
пожалуйста, не используйте их ни в каких методах этой реализации.
Вместо этого управляйте ими после создания книги.

###  Смотрите также
* модуль [`aspose.cells`](..)
