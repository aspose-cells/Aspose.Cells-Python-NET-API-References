---
title: ReConnectionMethodType перечисление
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 130
url: /ru/aspose.cells.externalconnections/reconnectionmethodtype/
is_root: false
---
##  ReConnectionMethodType перечисление
Указывает, что должно делать приложение для работы с электронными таблицами при сбое подключения.



Тип ReConnectionMethodType предоставляет следующие члены:

###  Поля
| Поле| Описание|
| :- | :- |
| REQUIRED | При обновлении используйте существующую информацию о соединении, и если она окажется недействительной<br/> затем получите обновленную информацию о подключении, если она доступна, из файла внешнего подключения.|
| ALWAYS | При каждом обновлении получайте обновленную информацию о подключении из файла внешнего подключения,<br/> если доступно, и используйте его вместо существующей информации о соединении.<br/> В этом случае обновление данных завершится ошибкой, если файл внешнего подключения недоступен.|
| NEVER | Никогда не получать обновленную информацию о подключении из внешнего файла подключения<br/> даже если он доступен и даже если существующая информация о соединении недействительна|



###  Смотрите также
* модуль [aspose.cells.externalconnections](..)
