---
title: get_default_sheet_name method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 80
url: /aspose.cells/settableglobalizationsettings/get_default_sheet_name/
is_root: false
---

## get_default_sheet_name(self) {#}

Gets the default sheet name for adding worksheet automatically.
Default is "Sheet".


### Returns 


the default sheet name for adding worksheet automatically


```python

def get_default_sheet_name(self):
    ...
```


### Remarks

The automatically added(such as by [`WorksheetCollection.add`](/cells/python-net/aspose.cells/worksheetcollection/add))
sheet's name will be the specified name plus sequence number.
For example, for Germany user maybe wants the sheet name to be "Tabellenblatt2" instead of "Sheet2". 
Then user may implement this method to return "Tabellenblatt".


### See Also
* module [`aspose.cells`](../../)
* class [`SettableGlobalizationSettings`](/cells/python-net/aspose.cells/settableglobalizationsettings)
