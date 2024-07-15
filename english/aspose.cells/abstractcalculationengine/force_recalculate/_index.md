---
title: force_recalculate method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 30
url: /aspose.cells/abstractcalculationengine/force_recalculate/
is_root: false
---

## force_recalculate {#str}

Whether force given function to be recalculated always when calculating shared formulas.


### Returns 


true if the specified function needs to be recalculated always.


```python
def force_recalculate(self, function_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| function_name | str | name of the function. Generally it is custom function's name.<br/>If [`AbstractCalculationEngine.process_built_in_functions`](/cells/python-net/aspose.cells/abstractcalculationengine#process_built_in_functions) is true, then built-in functions will also be checked here. |
### Remarks

For shared formulas, multiple cells share the same function.
If the function's parameters keep same for those cells too, then generally this function needs to be calculated only once.
So for performance consideration we only calculate such kind of function once too([`AbstractCalculationEngine.calculate`](/cells/python-net/aspose.cells/abstractcalculationengine/calculate)
is called only once, instead of being called repeatedly for every cell).
However, for user's custom implementation, maybe the function, especially the custom function,
needs to be calculated differently for different cells.
If so, user needs to override this method to make it return true for the function.
And for [`AbstractCalculationEngine.calculate`](/cells/python-net/aspose.cells/abstractcalculationengine/calculate), the given [`CalculationData.calculated_value`](/cells/python-net/aspose.cells/calculationdata#calculated_value)
may have been initialized with the cached value of previous calculation.


### See Also
* module [`aspose.cells`](../../)
* class [`AbstractCalculationEngine`](/cells/python-net/aspose.cells/abstractcalculationengine)
