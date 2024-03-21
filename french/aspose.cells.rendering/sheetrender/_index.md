---
title: SheetRender classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 120
url: /fr/aspose.cells.rendering/sheetrender/
is_root: false
---
##  SheetRender classe
Représente un rendu de feuille de calcul qui peut restituer une feuille de calcul sur diverses images telles que (BMP, PNG, JPEG, TIFF..)
Le constructeur de cette classe, doit être utilisé après modification de la configuration de la page, du style de cellule.



Le type SheetRender expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [__init__](/cells/python-net/fr/aspose.cells.rendering/sheetrender/__init__/#aspose.cells.Worksheet-aspose.cells.rendering.ImageOrPrintOptions) | la construction de SheetRender, nécessite une feuille de calcul et ImageOrPrintOptions comme paramètres|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [page_count](/cells/python-net/fr/aspose.cells.rendering/sheetrender/page_count) | Obtient le nombre total de pages de la feuille de calcul actuelle.|
| [page_scale](/cells/python-net/fr/aspose.cells.rendering/sheetrender/page_scale) | Obtient l’échelle de page calculée de la feuille.<br/> Renvoie l'échelle définie si [`PageSetup.zoom`](/cells/python-net/fr/aspose.cells/pagesetup#zoom) est défini. Sinon, renvoie l'échelle calculée selon [`PageSetup.fit_to_pages_wide`](/cells/python-net/fr/aspose.cells/pagesetup#fit_to_pages_wide) et [`PageSetup.fit_to_pages_tall`](/cells/python-net/fr/aspose.cells/pagesetup#fit_to_pages_tall).|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [to_image](/cells/python-net/fr/aspose.cells.rendering/sheetrender/to_image/#int-str) |Rendre certaines pages dans un fichier.|
| [to_image](/cells/python-net/fr/aspose.cells.rendering/sheetrender/to_image/#int-io.RawIOBase) | Afficher certaines pages dans un flux.|
| [to_tiff](/cells/python-net/fr/aspose.cells.rendering/sheetrender/to_tiff/#io.RawIOBase) | Rendre la feuille de calcul entière sous forme d'image Tiff à diffuser.|
| [to_tiff](/cells/python-net/fr/aspose.cells.rendering/sheetrender/to_tiff/#str) | Rendre la feuille de calcul entière sous forme d'image Tiff dans un fichier.|
| [to_printer](/cells/python-net/fr/aspose.cells.rendering/sheetrender/to_printer/#str) | Rendre la feuille de calcul sur l'imprimante|
| [to_printer](/cells/python-net/fr/aspose.cells.rendering/sheetrender/to_printer/#str-str) | Rendre la feuille de calcul sur l'imprimante|
| [to_printer](/cells/python-net/fr/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.PrinterSettings) | Rendre la feuille de calcul sur l'imprimante|
| [to_printer](/cells/python-net/fr/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.PrinterSettings-str) | Rendre la feuille de calcul sur l'imprimante|
| [to_printer](/cells/python-net/fr/aspose.cells.rendering/sheetrender/to_printer/#str-int-int) | Rendre la feuille de calcul sur l'imprimante|
| [get_page_size_inch](/cells/python-net/fr/aspose.cells.rendering/sheetrender/get_page_size_inch/#int) | Obtenez la taille de la page en pouces de l’image de sortie.|
| [custom_print](/cells/python-net/fr/aspose.cells.rendering/sheetrender/custom_print/#bool-aspose.pydrawing.printing.PrintPageEventArgs) | Le client peut contrôler les paramètres de page de l'imprimante lors de l'impression de chaque page à l'aide de cette fonction.|
| [dispose](/cells/python-net/fr/aspose.cells.rendering/sheetrender/dispose/#) | Libère les ressources créées et utilisées pour le rendu.|



###  Voir également
* module [`aspose.cells.rendering`](..)
