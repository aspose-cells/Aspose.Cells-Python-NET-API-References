﻿---
title: set_license method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 20
url: /aspose.cells/license/set_license/
is_root: false
---

## set_license {#str}

Licenses the component.



```python
def set_license(self, license_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| license_name | str |  |
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
### Example 


In this example, an attempt will be made to find a license file named MyLicense.lic
in the folder that contains 


the component, in the folder that contains the calling assembly,
in the folder of the entry assembly and then in the embedded resources of the calling assembly.

```python
from aspose.cells import License

license = License()
license.set_license("MyLicense.lic")

```
Can be a full or short file name or name of an embedded resource.
Use an empty string to switch to evaluation mode.


## set_license {#io.RawIOBase}

Licenses the component.



```python
def set_license(self, stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | io.RawIOBase | A stream that contains the license. |
### Remarks

Use this method to load a license from a stream.
### Example 


```python
from aspose.cells import License

license = License()
license.set_license(myStream)

```



### See Also
* module [`aspose.cells`](../../)
* class [`License`](/cells/python-net/aspose.cells/license)
