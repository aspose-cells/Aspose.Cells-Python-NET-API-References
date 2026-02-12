---
title: detect_file_format method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 20
url: /aspose.cells/fileformatutil/detect_file_format/
is_root: false
---

## detect_file_format(, stream) {#io.RawIOBase}

Detects and returns the information about a format of an excel stored in a stream.


### Returns 


A [`FileFormatInfo`](/cells/python-net/aspose.cells/fileformatinfo) object that contains the detected information.


```python

@staticmethod
def detect_file_format(stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | io.RawIOBase |  |


## detect_file_format(, file_path) {#System.String}

Detects and returns the information about a format of an excel stored in a file.


### Returns 


A [`FileFormatInfo`](/cells/python-net/aspose.cells/fileformatinfo) object that contains the detected information.


```python

@staticmethod
def detect_file_format(file_path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | System.String | The file path. |
### Remarks

Only supports checking some files with magic signature.
If there is no magic signature, we can not precisely detect the file format.

## detect_file_format(, stream, password) {#io.RawIOBase-System.String}

Detects and returns the information about a format of an excel stored in a stream.


### Returns 


A [`FileFormatInfo`](/cells/python-net/aspose.cells/fileformatinfo) object that contains the detected information.


```python

@staticmethod
def detect_file_format(stream, password):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | io.RawIOBase |  |
| password | System.String | The password for encrypted ooxml files. |


## detect_file_format(, file_path, password) {#System.String-System.String}

Detects and returns the information about a format of an excel stored in a file.


### Returns 


A [`FileFormatInfo`](/cells/python-net/aspose.cells/fileformatinfo) object that contains the detected information.


```python

@staticmethod
def detect_file_format(file_path, password):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | System.String | The file path. |
| password | System.String | The password for encrypted ooxml files. |
### Remarks

Only supports checking some files with magic signature.
If there is no magic signature, we can not precisely detect the file format.


### See Also
* module [`aspose.cells`](../../)
* class [`FileFormatInfo`](/cells/python-net/aspose.cells/fileformatinfo)
* class [`FileFormatUtil`](/cells/python-net/aspose.cells/fileformatutil)
