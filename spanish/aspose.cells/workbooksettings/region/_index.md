---
title: region propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 400
url: /es/aspose.cells/workbooksettings/region/
is_root: false
---
##  region propiedad

Obtiene o establece la configuración regional del libro.

###  Observaciones

1. Configuración regional utilizada por el componente Aspose.Cells para un libro cargado desde un archivo de plantilla:
i). Para un archivo XLS, hay campos definidos para la configuración regional y MS Excel guarda los datos de la configuración regional en el archivo al guardar el archivo XLS.
Entonces, usamos el region guardado en el archivo de plantilla del libro.
Si no desea utilizar el region guardado en el archivo XLS, restablezcalo al esperado (como CountryCode.Default) después de cargar el archivo de plantilla.
Y también guardamos el valor especificado por el usuario (mediante este método) en el archivo al guardar un archivo XLS.
ii). Para otros formatos de archivo, como XLSX, XLSB...etc., no hay ningún campo definido para la configuración regional en la especificación del formato de archivo.
Entonces, utilizamos la configuración regional del entorno de la aplicación para el libro de trabajo.
Y el valor especificado por el usuario (mediante este método) no se puede conservar para los archivos generados con esos formatos de archivo.
2. Para el efecto de vista en MS Excel:
La configuración regional aplicada aquí solo puede tener efecto en tiempo de ejecución con el componente Aspose.Cells y no al visualizar el archivo generado con MS Excel.
Incluso para el archivo XLS generado en el que se guardaron los datos de configuración regional especificados, al verlo/editarlo con MS Excel,
el region utilizado para realizar el formateo con MS Excel es siempre la configuración regional predeterminada del entorno donde se ejecuta MS Excel,
no el guardado en el archivo. Es el comportamiento de MS Excel y no se puede cambiar mediante código.
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
