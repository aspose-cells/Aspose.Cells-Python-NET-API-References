---
title: finish method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 20
url: /aspose.cells.lowcode/abstractlowcodeloadoptionsprovider/finish/
is_root: false
---

## finish(self, part) {#aspose.cells.lowcode.LowCodeLoadOptions}

Releases resources after processing currently part of input.



```python

def finish(self, part):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| part | [`LowCodeLoadOptions`](/cells/python-net/aspose.cells.lowcode/lowcodeloadoptions) | the load options used for currently split part. |
### Remarks

By default this method just closes the stream specified by the
[`LowCodeLoadOptions.input_stream`](/cells/python-net/aspose.cells.lowcode/lowcodeloadoptions#input_stream) directly(if the load options
specified a Stream as source).
User may overwrite this method to control how to release resources
according to their requirement and the implementation of
[`AbstractLowCodeLoadOptionsProvider.current`](/cells/python-net/aspose.cells.lowcode/abstractlowcodeloadoptionsprovider#current).


### See Also
* module [`aspose.cells.lowcode`](../../)
* class [`AbstractLowCodeLoadOptionsProvider`](/cells/python-net/aspose.cells.lowcode/abstractlowcodeloadoptionsprovider)
