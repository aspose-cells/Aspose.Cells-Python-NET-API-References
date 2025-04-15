---
title: finish method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 20
url: /aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/finish/
is_root: false
---

## finish(self, part) {#aspose.cells.lowcode.LowCodeSaveOptions}

Releases resources after processing currently split part.



```python

def finish(self, part):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| part | [`LowCodeSaveOptions`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptions) | the save options used for currently split part. |
### Remarks

By default this method just closes the stream specified by the
[`LowCodeSaveOptions.output_stream`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptions#output_stream) directly(if the save options
specified a Stream as destination).
User may overwrite this method to control how to release resources
according to their requirement and the implementation of
[`AbstractLowCodeSaveOptionsProvider.get_save_options`](/cells/python-net/aspose.cells.lowcode/abstractlowcodesaveoptionsprovider/get_save_options).


### See Also
* module [`aspose.cells.lowcode`](../../)
* class [`LowCodeSaveOptionsProviderOfPlaceHolders`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders)
