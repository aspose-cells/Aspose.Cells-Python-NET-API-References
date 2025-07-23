---
title: ConnectionParameter класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 10
url: /ru/aspose.cells.externalconnections/connectionparameter/
is_root: false
---
##  ConnectionParameter класс
Указывает свойства любых параметров, используемых с внешними подключениями к данным.
Параметры действительны для ODBC и веб-запросов.



Тип ConnectionParameter предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [sql_type](/cells/python-net/ru/aspose.cells.externalconnections/connectionparameter/sql_type) | Тип данных SQL параметра. Действительно только для источников ODBC.|
| [refresh_on_change](/cells/python-net/ru/aspose.cells.externalconnections/connectionparameter/refresh_on_change) | Флаг, указывающий, должен ли запрос автоматически обновляться при обновлении содержимого<br/> Ячейка, в которой изменяется значение параметра. Если значение равно true, внешние данные обновляются.<br/> Используя новое значение параметра при каждом изменении. Если значение равно false, то внешние данные<br/> обновляется только по запросу пользователя или при возникновении какого-либо другого события, вызывающего обновление (например, открытие рабочей книги).|
| [prompt](/cells/python-net/ru/aspose.cells.externalconnections/connectionparameter/prompt) | Строка запроса для параметра. Отображается пользователю электронной таблицы вместе с интерфейсом ввода.<br/> для сбора значения параметра перед обновлением внешних данных. Используется только в тех случаях, когда<br/>параметрТип = подсказка.|
| [type](/cells/python-net/ru/aspose.cells.externalconnections/connectionparameter/type) | Тип используемого параметра.<br/> Если параметрType=value, то значение может быть логическим, double, целым,<br/> или строка будет использоваться. В этом случае ожидается, что только один из<br/> Будет указано {boolean, double, integer или string}.|
| [name](/cells/python-net/ru/aspose.cells.externalconnections/connectionparameter/name) | Имя параметра.|
| [cell_reference](/cells/python-net/ru/aspose.cells.externalconnections/connectionparameter/cell_reference) | Ссылка Cell, указывающая, значение какой ячейки использовать для параметра запроса. Используется только в том случае, если параметр типа_параметра — ячейка.|
| [value](/cells/python-net/ru/aspose.cells.externalconnections/connectionparameter/value) | Нецелое числовое значение, Целое значение, Строковое значение или Логическое значение<br/> для использования в качестве параметра запроса. Используется только в том случае, если параметр parameterType равен значению.|



###  Смотрите также
* модуль [`aspose.cells.externalconnections`](..)
