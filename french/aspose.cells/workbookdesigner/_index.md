---
title: WorkbookDesigner classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1580
url: /fr/aspose.cells/workbookdesigner/
is_root: false
---
##  WorkbookDesigner classe
Encapsule l'objet qui représente une feuille de calcul de concepteur.



Le type WorkbookDesigner expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [`__init__(self)`](/cells/python-net/fr/aspose.cells/workbookdesigner/__init__/#) | Initialise une nouvelle instance de la classe [`WorkbookDesigner`](/cells/python-net/fr/aspose.cells/workbookdesigner).|
| [`__init__(self, workbook)`](/cells/python-net/fr/aspose.cells/workbookdesigner/__init__/#aspose.cells.workbook) | Initialise une nouvelle instance de la classe [`WorkbookDesigner`](/cells/python-net/fr/aspose.cells/workbookdesigner).|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [workbook](/cells/python-net/fr/aspose.cells/workbookdesigner/workbook) | Obtient et définit l'objet [`WorkbookDesigner.workbook`](/cells/python-net/fr/aspose.cells/workbookdesigner#workbook).|
| [repeat_formulas_with_subtotal](/cells/python-net/fr/aspose.cells/workbookdesigner/repeat_formulas_with_subtotal) | Indique si les formules sont répétées avec une ligne de sous-total.|
| [update_empty_string_as_null](/cells/python-net/fr/aspose.cells/workbookdesigner/update_empty_string_as_null) |Si VRAI, Null sera inséré si la valeur est "";|
| [update_reference](/cells/python-net/fr/aspose.cells/workbookdesigner/update_reference) | Indique si les références dans d’autres feuilles de calcul seront mises à jour.|
| [calculate_formula](/cells/python-net/fr/aspose.cells/workbookdesigner/calculate_formula) | Indique si les formules doivent être calculées.|
| [line_by_line](/cells/python-net/fr/aspose.cells/workbookdesigner/line_by_line) | Indique si le traitement du marqueur intelligent est effectué ligne par ligne.|
| [contains_variables](/cells/python-net/fr/aspose.cells/workbookdesigner/contains_variables) | Indique si la première feuille de calcul contient des variables personnalisées.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`set_data_source(self, data_source, cells_data_table)`](/cells/python-net/fr/aspose.cells/workbookdesigner/set_data_source/#str-icellsdatatable) |  |
| [`set_data_source(self, variable, data)`](/cells/python-net/fr/aspose.cells/workbookdesigner/set_data_source/#str-any) | Définit la liaison de données à une variable.|
| [`process(self, range, is_preserved)`](/cells/python-net/fr/aspose.cells/workbookdesigner/process/#aspose.cells.range-bool) | Traite les marqueurs intelligents et remplit les valeurs de la source de données.|
| [`process(self)`](/cells/python-net/fr/aspose.cells/workbookdesigner/process/#) | Traite les marqueurs intelligents et remplit les valeurs de la source de données.|
| [`process(self, is_preserved)`](/cells/python-net/fr/aspose.cells/workbookdesigner/process/#bool) | Traite les marqueurs intelligents et remplit les valeurs de la source de données.|
| [`process(self, sheet_index, is_preserved)`](/cells/python-net/fr/aspose.cells/workbookdesigner/process/#int-bool) | Traite les marqueurs intelligents et remplit les valeurs de la source de données.|
| [`clear_data_source(self)`](/cells/python-net/fr/aspose.cells/workbookdesigner/clear_data_source/#) | Efface toutes les sources de données.|
| [`set_json_data_source(self, variable, data)`](/cells/python-net/fr/aspose.cells/workbookdesigner/set_json_data_source/#str-str) |  |
| [`get_smart_markers(self)`](/cells/python-net/fr/aspose.cells/workbookdesigner/get_smart_markers/#) | Renvoie une collection de marqueurs intelligents dans une feuille de calcul.|



###  Exemple

```python
from aspose.cells import Workbook, WorkbookDesigner

# Create WorkbookDesigner object.
wd = WorkbookDesigner()
# Open the template file (which contains smart markers).
wd.workbook = Workbook("SmartMarker_Designer.xls")
# Initialize your data from data source
# DataSet ds = new DataSet();
# ...
# Set the datatable as the data source.
# wd.SetDataSource(dt);
# Process the smart markers to fill the data into the worksheets.
wd.process(True)
# Save the excel file.
wd.workbook.save("outSmartMarker_Designer.xls")

```

###  Voir également
* module [`aspose.cells`](..)
* classe [`WorkbookDesigner`](/cells/python-net/fr/aspose.cells/workbookdesigner)
