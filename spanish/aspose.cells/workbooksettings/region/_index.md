---
title: region propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 440
url: /es/aspose.cells/workbooksettings/region/
is_root: false
---
##  region propiedad

Obtiene o establece la configuración regional para el libro de trabajo.

###  Observaciones

1. Configuración regional utilizada por el componente Aspose.Cells para un libro de trabajo cargado desde un archivo de plantilla:
i). Para un archivo XLS, hay campos definidos para configuraciones regionales y MS Excel guarda los datos de configuración regional en el archivo al guardar el archivo XLS.
Entonces, usamos el region guardado en el archivo de plantilla para el libro de trabajo.
Si no desea utilizar el region guardado en el archivo XLS, restablézcalo al esperado (por ejemplo, CountryCode.Default) después de cargar el archivo de plantilla.
Además, también guardamos el valor especificado por el usuario (mediante este método) en el archivo al guardar un archivo XLS.
ii). Para otros formatos de archivo, como XLSX, XLSB, etc., no hay ningún campo definido para configuraciones regionales en la especificación del formato de archivo.
Entonces, utilizamos la configuración regional del entorno de la aplicación para el libro de trabajo.
Además, el valor especificado por el usuario (mediante este método) no se puede conservar para los archivos generados con esos formatos de archivo.
2. Para el efecto de vista en MS Excel:
La configuración regional aplicada aquí solo puede tener efecto en tiempo de ejecución con el componente Aspose.Cells y no al visualizar el archivo generado con MS Excel.
Incluso para el archivo generado XLS en el que se han guardado los datos de configuración regional especificados, al verlo/editarlo con MS Excel,
El número region utilizado para realizar el formateo por MS Excel es siempre la configuración regional predeterminada del entorno donde se ejecuta MS Excel.
No es el que está guardado en el archivo. Es un comportamiento de MS Excel y no se puede cambiar mediante código.
###  Definición:
```python
@property
def region(self):
    ...
@region.setter
def region(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`CountryCode`](/cells/python-net/es/aspose.cells/countrycode)
* clase [`WorkbookSettings`](/cells/python-net/es/aspose.cells/workbooksettings)
