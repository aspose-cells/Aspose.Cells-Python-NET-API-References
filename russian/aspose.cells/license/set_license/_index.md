---
title: set_license метод
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 20
url: /ru/aspose.cells/license/set_license/
is_root: false
---
##  set_license(license_name) {#str}
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


4. Папка, содержащая входную (загрузочную) сборку.


5. Встроенный ресурс в вызывающей сборке клиента.


**Примечание:** В Compact Framework .NET пытается найти лицензию только в следующих местах:


1. Явный путь.


2. Встроенный ресурс в вызывающей сборке клиента.
###  Пример


В этом примере будет предпринята попытка найти файл лицензии с именем MyLicense.lic.
 в папке, содержащей


компонент в папке, содержащей вызывающую сборку,
в папке входной сборки, а затем во встроенных ресурсах вызывающей сборки.

```python
from aspose.cells import License

license = License()
license.set_license("MyLicense.lic")

```
Может быть полным или кратким именем файла или именем внедренного ресурса.
Используйте пустую строку для переключения в режим оценки.


##  set_license(stream) {#io.RawIOBase}
Лицензирует компонент.



```python
def set_license(self, stream):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| stream | io.RawIOBase | Поток, содержащий лицензию.|
###  Примечания

Используйте этот метод для загрузки лицензии из потока.
###  Пример


```python
from aspose.cells import License

license = License()
license.set_license(myStream)

```



###  Смотрите также
* модуль [aspose.cells](../../)
* класс [License](/cells/python-net/ru/aspose.cells/license)
