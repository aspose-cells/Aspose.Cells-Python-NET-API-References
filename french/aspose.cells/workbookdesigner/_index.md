---
title: WorkbookDesigner classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1670
url: /fr/aspose.cells/workbookdesigner/
is_root: false
---
##  WorkbookDesigner classe
Encapsule l'objet qui représente une feuille de calcul de concepteur.



Le type WorkbookDesigner expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [__init__](/cells/python-net/fr/aspose.cells/workbookdesigner/__init__/#) | Initialise une nouvelle instance de la classe [`WorkbookDesigner`](/cells/python-net/fr/aspose.cells/workbookdesigner).|
| [__init__](/cells/python-net/fr/aspose.cells/workbookdesigner/__init__/#aspose.cells.Workbook) | Initialise une nouvelle instance de la classe [`WorkbookDesigner`](/cells/python-net/fr/aspose.cells/workbookdesigner).|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [workbook](/cells/python-net/fr/aspose.cells/workbookdesigner/workbook) | Obtient et définit l'objet [`WorkbookDesigner.workbook`](/cells/python-net/fr/aspose.cells/workbookdesigner#workbook).|
| [repeat_formulas_with_subtotal](/cells/python-net/fr/aspose.cells/workbookdesigner/repeat_formulas_with_subtotal) | Indique si les formules sont répétitives avec une ligne de sous-total.|
| [update_empty_string_as_null](/cells/python-net/fr/aspose.cells/workbookdesigner/update_empty_string_as_null) | Si VRAI, Null sera inséré si la valeur est "" ;|
| [update_reference](/cells/python-net/fr/aspose.cells/workbookdesigner/update_reference) | Indique si les références dans d’autres feuilles de calcul seront mises à jour.|
| [calculate_formula](/cells/python-net/fr/aspose.cells/workbookdesigner/calculate_formula) | Indique si les formules doivent être calculées.|
| [call_back](/cells/python-net/fr/aspose.cells/workbookdesigner/call_back) | Obtient et définit l'interface de rappel du traitement du marqueur intelligent.|
| [line_by_line](/cells/python-net/fr/aspose.cells/workbookdesigner/line_by_line) | Indique si le marqueur intelligent est traité ligne par ligne.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [set_data_source](/cells/python-net/fr/aspose.cells/workbookdesigner/set_data_source/#str-aspose.cells.ICellsDataTable) | Définit la source de données d'un objet [`ICellsDataTable`](/cells/python-net/fr/aspose.cells/icellsdatatable).|
| [set_data_source](/cells/python-net/fr/aspose.cells/workbookdesigner/set_data_source/#str-any) | Définit la liaison des données à une variable.|
| [process](/cells/python-net/fr/aspose.cells/workbookdesigner/process/#) |Traite les marqueurs intelligents et remplit les valeurs de la source de données.|
| [process](/cells/python-net/fr/aspose.cells/workbookdesigner/process/#bool) |Traite les marqueurs intelligents et remplit les valeurs de la source de données.|
| [process](/cells/python-net/fr/aspose.cells/workbookdesigner/process/#int-bool) |Traite les marqueurs intelligents et remplit les valeurs de la source de données.|
| [clear_data_source](/cells/python-net/fr/aspose.cells/workbookdesigner/clear_data_source/#) | Efface toutes les sources de données.|
| [set_json_data_source](/cells/python-net/fr/aspose.cells/workbookdesigner/set_json_data_source/#str-str) |  |
| [get_smart_markers](/cells/python-net/fr/aspose.cells/workbookdesigner/get_smart_markers/#) | Renvoie une collection de marqueurs intelligents dans une feuille de calcul.|



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
* classe [`ICellsDataTable`](/cells/python-net/fr/aspose.cells/icellsdatatable)
* classe [`WorkbookDesigner`](/cells/python-net/fr/aspose.cells/workbookdesigner)
