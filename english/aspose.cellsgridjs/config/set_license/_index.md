---
title: set_license method
second_title: Aspose.Cells.GridJs for Python via .NET API References
description: 
type: docs
weight: 40
url: /aspose.cellsgridjs/config/set_license/
is_root: false
---

## set_license(, license_name) {#System.String}

Licenses the component.



```python

@staticmethod
def set_license(license_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| license_name | System.String | Can be a full or short file name or name of an embedded resource.<br/>Use an empty string to switch to evaluation mode. |
### Remarks

Tries to find the license in the following locations:


1. Explicit path.


2. The folder that contains the Aspose component assembly.


3. The folder that contains the client's calling assembly.


4. The folder that contains the entry (startup) assembly.


5. An embedded resource in the client's calling assembly.


**Note:** On the .NET Compact Framework, tries to find the license only in these locations:


1. Explicit path.


2. An embedded resource in the client's calling assembly.

## set_license(, stream) {#io.RawIOBase}

Licenses the component.



```python

@staticmethod
def set_license(stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | io.RawIOBase | A stream that contains the license. |
### Remarks

Use this method to load a license from a stream.


### See Also
* module [`aspose.cellsgridjs`](../../)
* class [`Config`](/cells/python-net/aspose.cellsgridjs/config)
