---
title: WorkbookRender classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 150
url: /fr/aspose.cells.rendering/workbookrender/
is_root: false
---
##  WorkbookRender classe
 Représente un rendu de classeur.
Le constructeur de cette classe, doit être utilisé après modification de la mise en page, du style de cellule.



Le type WorkbookRender expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [`__init__(self, workbook, options)`](/cells/python-net/fr/aspose.cells.rendering/workbookrender/__init__/#aspose.cells.workbook-aspose.cells.rendering.imageorprintoptions) | La construction de WorkbookRender|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [page_count](/cells/python-net/fr/aspose.cells.rendering/workbookrender/page_count) | Obtient le nombre total de pages du classeur.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`to_image(self, stream)`](/cells/python-net/fr/aspose.cells.rendering/workbookrender/to_image/#io.rawiobase) | Rendre l'intégralité du classeur sous forme d'image Tiff à diffuser.|
| [`to_image(self, filename)`](/cells/python-net/fr/aspose.cells.rendering/workbookrender/to_image/#str) | Rendre l'intégralité du classeur sous forme d'image Tiff dans un fichier.|
| [`to_image(self, page_index, file_name)`](/cells/python-net/fr/aspose.cells.rendering/workbookrender/to_image/#int-str) | Rendre une certaine page dans un fichier.|
| [`to_image(self, page_index, stream)`](/cells/python-net/fr/aspose.cells.rendering/workbookrender/to_image/#int-io.rawiobase) | Rendre une certaine page dans un flux.|
| [`to_printer(self, printer_name)`](/cells/python-net/fr/aspose.cells.rendering/workbookrender/to_printer/#str) | Rendre le classeur sur l'imprimante|
| [`to_printer(self, printer_name, job_name)`](/cells/python-net/fr/aspose.cells.rendering/workbookrender/to_printer/#str-str) | Rendre le classeur sur l'imprimante|
| [`to_printer(self, printer_settings)`](/cells/python-net/fr/aspose.cells.rendering/workbookrender/to_printer/#aspose.pydrawing.printing.printersettings) | Rendre le classeur sur l'imprimante|
| [`to_printer(self, printer_settings, job_name)`](/cells/python-net/fr/aspose.cells.rendering/workbookrender/to_printer/#aspose.pydrawing.printing.printersettings-str) | Rendre le classeur sur l'imprimante|
| [`to_printer(self, printer_name, print_page_index, print_page_count)`](/cells/python-net/fr/aspose.cells.rendering/workbookrender/to_printer/#str-int-int) | Rendre le classeur sur l'imprimante|
| [`get_page_size_inch(self, page_index)`](/cells/python-net/fr/aspose.cells.rendering/workbookrender/get_page_size_inch/#int) | Obtenir la taille de la page en pouces de l'image de sortie.|
| [`custom_print(self, next_page_after_print, print_page_event_args)`](/cells/python-net/fr/aspose.cells.rendering/workbookrender/custom_print/#bool-aspose.pydrawing.printing.printpageeventargs) | Le client peut contrôler le réglage de la page de l'imprimante lors de l'impression de chaque page à l'aide de cette fonction.|
| [`dispose(self)`](/cells/python-net/fr/aspose.cells.rendering/workbookrender/dispose/#) | Libère les ressources créées et utilisées pour le rendu.|



###  Remarques



###  Voir également
* module [`aspose.cells.rendering`](..)
