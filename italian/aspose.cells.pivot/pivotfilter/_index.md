---
title: PivotFilter classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 140
url: /it/aspose.cells.pivot/pivotfilter/
is_root: false
---
##  PivotFilter classe
Rappresenta un PivotFilter nella collezione PivotFilter.



Il tipo PivotFilter espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [use_whole_day](/cells/python-net/it/aspose.cells.pivot/pivotfilter/use_whole_day) | Indica se utilizza giorni interi nei suoi criteri di filtraggio.|
| [auto_filter](/cells/python-net/it/aspose.cells.pivot/pivotfilter/auto_filter) | Ottiene il filtro automatico del filtro pivot.|
| [filter_type](/cells/python-net/it/aspose.cells.pivot/pivotfilter/filter_type) | Ottiene il tipo di filtro automatico del filtro pivot.|
| [field_index](/cells/python-net/it/aspose.cells.pivot/pivotfilter/field_index) | Ottiene l'indice del campo sorgente a cui viene applicato questo filtro pivot.|
| [filter_category](/cells/python-net/it/aspose.cells.pivot/pivotfilter/filter_category) | Ottiene la categoria di questo filtro.|
| [value1](/cells/python-net/it/aspose.cells.pivot/pivotfilter/value1) | Ottiene il valore stringa 1 del filtro pivot dell'etichetta.|
| [value2](/cells/python-net/it/aspose.cells.pivot/pivotfilter/value2) | Ottiene il valore stringa2 del filtro pivot dell'etichetta.|
| [measure_fld_index](/cells/python-net/it/aspose.cells.pivot/pivotfilter/measure_fld_index) | Ottiene l'indice del campo di misura del filtro pivot.|
| [value_field_index](/cells/python-net/it/aspose.cells.pivot/pivotfilter/value_field_index) | Ottiene l'indice del campo valore nell'area valore.|
| [measure_cube_field_index](/cells/python-net/it/aspose.cells.pivot/pivotfilter/measure_cube_field_index) | Specifica l'indice del campo del cubo di misura.<br/>Questa proprietà viene utilizzata solo dai filtri nei pivot OLAP e specifica su quale misura deve essere applicato un filtro valore.|
| [member_property_field_index](/cells/python-net/it/aspose.cells.pivot/pivotfilter/member_property_field_index) | Ottiene l'indice del campo della proprietà membro del filtro pivot.|
| [name](/cells/python-net/it/aspose.cells.pivot/pivotfilter/name) | Ottiene il nome del filtro pivot.|
| [evaluation_order](/cells/python-net/it/aspose.cells.pivot/pivotfilter/evaluation_order) | Ottiene l'ordine di valutazione del filtro pivot.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`get_top_10_value(self)`](/cells/python-net/it/aspose.cells.pivot/pivotfilter/get_top_10_value/#) | Ottiene le prime 10 impostazioni del filtro.|
| [`get_labels(self)`](/cells/python-net/it/aspose.cells.pivot/pivotfilter/get_labels/#) | Ottiene le etichette del filtro didascalia.|
| [`get_number_values(self)`](/cells/python-net/it/aspose.cells.pivot/pivotfilter/get_number_values/#) | Ottiene i valori del filtro numerico.|
| [`get_date_time_values(self)`](/cells/python-net/it/aspose.cells.pivot/pivotfilter/get_date_time_values/#) | Ottiene i valori del filtro numerico.|



###  Esempio

```python
from aspose.cells import Workbook
from aspose.cells.pivot import PivotFieldType, PivotFilterType, PivotTableStyleType

book = Workbook()
sheet = book.worksheets[0]
cells = sheet.cells
cells.get(0, 0).value = "fruit"
cells.get(1, 0).value = "grape"
cells.get(2, 0).value = "blueberry"
cells.get(3, 0).value = "kiwi"
cells.get(4, 0).value = "cherry"
cells.get(5, 0).value = "grape"
cells.get(6, 0).value = "blueberry"
cells.get(7, 0).value = "kiwi"
cells.get(8, 0).value = "cherry"
cells.get(0, 1).value = "year"
cells.get(1, 1).value = 2020
cells.get(2, 1).value = 2020
cells.get(3, 1).value = 2020
cells.get(4, 1).value = 2020
cells.get(5, 1).value = 2021
cells.get(6, 1).value = 2021
cells.get(7, 1).value = 2021
cells.get(8, 1).value = 2021
cells.get(0, 2).value = "amount"
cells.get(1, 2).value = 50
cells.get(2, 2).value = 60
cells.get(3, 2).value = 70
cells.get(4, 2).value = 80
cells.get(5, 2).value = 90
cells.get(6, 2).value = 100
cells.get(7, 2).value = 110
cells.get(8, 2).value = 120
pivots = sheet.pivot_tables
pivotIndex = pivots.add("=Sheet1!A1:C9", "A12", "TestPivotTable")
pivot = pivots[pivotIndex]
pivot.add_field_to_area(PivotFieldType.ROW, "fruit")
pivot.add_field_to_area(PivotFieldType.COLUMN, "year")
pivot.add_field_to_area(PivotFieldType.DATA, "amount")
pivot.pivot_table_style_type = PivotTableStyleType.PIVOT_TABLE_STYLE_MEDIUM10
# Add top 10 filter
pivot.base_fields[0].filter_top10(0, PivotFilterType.COUNT, False, 2)
pivot.refresh_data()
pivot.calculate_data()
# do your business
book.save("out.xlsx")

```

###  Guarda anche
* modulo [`aspose.cells.pivot`](..)
