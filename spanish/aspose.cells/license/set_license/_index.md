---
title: método set_license
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 20
url: /es/aspose.cells/license/set_license/
is_root: false
---
##  set_license(self, license_name) {#str}
Licencia el componente.



```python

def set_license(self, license_name):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| license_name | str |  |
###  Observaciones

Intenta encontrar la licencia en las siguientes ubicaciones:


1. Ruta explícita.


2. La carpeta que contiene el conjunto de componentes Aspose.


3. La carpeta que contiene el ensamblado de llamada del cliente.


4. La carpeta que contiene el ensamblaje de entrada (inicio).


5. Un recurso incrustado en el ensamblaje de llamada del cliente.


**Nota:**En el Compact Framework .NET, intenta encontrar la licencia solo en estas ubicaciones:


1. Ruta explícita.


2. Un recurso incrustado en el ensamblaje de llamada del cliente.
###  Ejemplo


En este ejemplo, se intentará encontrar un archivo de licencia llamado MyLicense.lic
 en la carpeta que contiene


el componente, en la carpeta que contiene el ensamblado que lo llama,
en la carpeta del ensamblaje de entrada y luego en los recursos integrados del ensamblaje que llama.

```python
from aspose.cells import License

license = License()
license.set_license("MyLicense.lic")

```
Puede ser un nombre de archivo completo o corto o el nombre de un recurso incrustado.
Utilice una cadena vacía para cambiar al modo de evaluación.


##  set_license(self, stream) {#io.RawIOBase}
Licencia el componente.



```python

def set_license(self, stream):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| stream | io.RawIOBase |Una secuencia que contiene la licencia.|
###  Observaciones

Utilice este método para cargar una licencia desde una transmisión.
###  Ejemplo


```python
from aspose.cells import License

license = License()
license.set_license(myStream)

```



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`License`](/cells/python-net/es/aspose.cells/license)
