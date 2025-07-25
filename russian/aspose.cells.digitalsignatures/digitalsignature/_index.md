---
title: DigitalSignature класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 10
url: /ru/aspose.cells.digitalsignatures/digitalsignature/
is_root: false
---
##  DigitalSignature класс
Подпись в деле.



Тип DigitalSignature предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self, certificate, comments, sign_time)`](/cells/python-net/ru/aspose.cells.digitalsignatures/digitalsignature/__init__/#system.security.cryptography.x509certificates.x509certificate2-str-datetime) | Конструктор digitalSignature. Использует реализацию .Net.|
| [`__init__(self, raw_data, password, comments, sign_time)`](/cells/python-net/ru/aspose.cells.digitalsignatures/digitalsignature/__init__/#bytes-str-str-datetime) |Конструктор digitalSignature. Использует реализацию Bouncy Castle.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [certificate](/cells/python-net/ru/aspose.cells.digitalsignatures/digitalsignature/certificate) | Объект сертификата, который был использован для подписи документа.|
| [comments](/cells/python-net/ru/aspose.cells.digitalsignatures/digitalsignature/comments) | Цель подписания.|
| [sign_time](/cells/python-net/ru/aspose.cells.digitalsignatures/digitalsignature/sign_time) | Время подписания документа.|
| [id](/cells/python-net/ru/aspose.cells.digitalsignatures/digitalsignature/id) | Указывает GUID, который может быть связан с GUID строки подписи, сохраненной в содержимом документа.<br/> Значение по умолчанию — пусто (все нули) Guid.|
| [text](/cells/python-net/ru/aspose.cells.digitalsignatures/digitalsignature/text) | Указывает текст фактической подписи в цифровой подписи.<br/> Значение по умолчанию — Пусто.|
| [image](/cells/python-net/ru/aspose.cells.digitalsignatures/digitalsignature/image) | Указывает изображение для цифровой подписи.<br/> Значение по умолчанию — ноль.|
| [provider_id](/cells/python-net/ru/aspose.cells.digitalsignatures/digitalsignature/provider_id) | Указывает идентификатор класса поставщика подписи.<br/> Значение по умолчанию — пусто (все нули) Guid.|
| [is_valid](/cells/python-net/ru/aspose.cells.digitalsignatures/digitalsignature/is_valid) | Если эта цифровая подпись действительна и документ не был подделан,<br/> это значение будет истинным.|
| [x_ad_es_type](/cells/python-net/ru/aspose.cells.digitalsignatures/digitalsignature/x_ad_es_type) | Тип XAdES.<br/> Значение по умолчанию — None (XAdES отключен).|



###  Смотрите также
* модуль [`aspose.cells.digitalsignatures`](..)
