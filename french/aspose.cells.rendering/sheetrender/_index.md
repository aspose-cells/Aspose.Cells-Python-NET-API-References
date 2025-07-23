---
title: SheetRender classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 110
url: /fr/aspose.cells.rendering/sheetrender/
is_root: false
---
##  SheetRender classe
Représente un rendu de feuille de calcul qui peut rendre la feuille de calcul dans diverses images telles que (BMP, PNG, JPEG, TIFF..)
Le constructeur de cette classe, doit être utilisé après modification de la mise en page, du style de cellule.



Le type SheetRender expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [`__init__(self, worksheet, options)`](/cells/python-net/fr/aspose.cells.rendering/sheetrender/__init__/#aspose.cells.worksheet-aspose.cells.rendering.imageorprintoptions) | la construction de SheetRender, nécessite worksheet et ImageOrPrintOptions comme paramètres|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [page_count](/cells/python-net/fr/aspose.cells.rendering/sheetrender/page_count) | Obtient le nombre total de pages de la feuille de calcul actuelle.|
| [page_scale](/cells/python-net/fr/aspose.cells.rendering/sheetrender/page_scale) | Obtient l'échelle de page calculée de la feuille.<br/> Renvoie l'échelle définie si [`PageSetup.zoom`](/cells/python-net/fr/aspose.cells/pagesetup#zoom) est défini. Sinon, renvoie l'échelle calculée selon [`PageSetup.fit_to_pages_wide`](/cells/python-net/fr/aspose.cells/pagesetup#fit_to_pages_wide) et [`PageSetup.fit_to_pages_tall`](/cells/python-net/fr/aspose.cells/pagesetup#fit_to_pages_tall).|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`to_image(self, page_index, file_name)`](/cells/python-net/fr/aspose.cells.rendering/sheetrender/to_image/#int-str) | Rendre une certaine page dans un fichier.|
| [`to_image(self, page_index, stream)`](/cells/python-net/fr/aspose.cells.rendering/sheetrender/to_image/#int-io.rawiobase) | Rendre une certaine page dans un flux.|
| [`to_tiff(self, stream)`](/cells/python-net/fr/aspose.cells.rendering/sheetrender/to_tiff/#io.rawiobase) | Rendre la feuille de calcul entière sous forme d'image Tiff à diffuser.|
| [`to_tiff(self, filename)`](/cells/python-net/fr/aspose.cells.rendering/sheetrender/to_tiff/#str) | Rendre la feuille de calcul entière sous forme d'image Tiff dans un fichier.|
| [`to_printer(self, printer_name)`](/cells/python-net/fr/aspose.cells.rendering/sheetrender/to_printer/#str) | Rendre la feuille de calcul à l'imprimante|
| [`to_printer(self, printer_name, job_name)`](/cells/python-net/fr/aspose.cells.rendering/sheetrender/to_printer/#str-str) | Rendre la feuille de calcul à l'imprimante|
| [`to_printer(self, printer_settings)`](/cells/python-net/fr/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.printersettings) | Rendre la feuille de calcul à l'imprimante|
| [`to_printer(self, printer_settings, job_name)`](/cells/python-net/fr/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.printersettings-str) | Rendre la feuille de calcul à l'imprimante|
| [`to_printer(self, printer_name, print_page_index, print_page_count)`](/cells/python-net/fr/aspose.cells.rendering/sheetrender/to_printer/#str-int-int) | Rendre la feuille de calcul à l'imprimante|
| [`get_page_size_inch(self, page_index)`](/cells/python-net/fr/aspose.cells.rendering/sheetrender/get_page_size_inch/#int) | Obtenir la taille de la page en pouces de l'image de sortie.|
| [`custom_print(self, next_page_after_print, print_page_event_args)`](/cells/python-net/fr/aspose.cells.rendering/sheetrender/custom_print/#bool-aspose.pydrawing.printing.printpageeventargs) | Le client peut contrôler le réglage de la page de l'imprimante lors de l'impression de chaque page à l'aide de cette fonction.|
| [`dispose(self)`](/cells/python-net/fr/aspose.cells.rendering/sheetrender/dispose/#) | Libère les ressources créées et utilisées pour le rendu.|



###  Voir également
* module [`aspose.cells.rendering`](..)
