---
title: set_license метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 20
url: /ru/aspose.cells/license/set_license/
is_root: false
---
##  set_license(self, license_name) {#str}
Лицензирует компонент.



```python

def set_license(self, license_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| license_name | str |  |
###  Примечания

Пытается найти лицензию в следующих местах:


1. Явный путь.


2. Папка, содержащая сборку компонента Aspose.


3. Папка, содержащая вызывающую сборку клиента.


4. Папка, содержащая начальную (стартовую) сборку.


5. Встроенный ресурс в вызывающую сборку клиента.


**Примечание:**На Compact Framework .NET пытается найти лицензию только в этих местах:


1. Явный путь.


2. Встроенный ресурс в вызывающую сборку клиента.
###  Пример


В этом примере будет предпринята попытка найти файл лицензии с именем MyLicense.lic.
 в папке, которая содержит


компонент в папке, содержащей вызывающую сборку,
в папке входной сборки, а затем во встроенных ресурсах вызывающей сборки.

```python
from aspose.cells import License

license = License()
license.set_license("MyLicense.lic")

```
Может быть полным или коротким именем файла или именем встроенного ресурса.
Для переключения в режим оценки используйте пустую строку.


##  set_license(self, stream) {#io.RawIOBase}
Лицензирует компонент.



```python

def set_license(self, stream):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| stream | io.RawIOBase |Поток, содержащий лицензию.|
###  Примечания

Используйте этот метод для загрузки лицензии из потока.
###  Пример


```python
from aspose.cells import License

license = License()
license.set_license(myStream)

```



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`License`](/cells/python-net/ru/aspose.cells/license)
