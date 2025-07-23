---
title: ImageOrPrintOptions classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 30
url: /fr/aspose.cells.rendering/imageorprintoptions/
is_root: false
---
##  ImageOrPrintOptions classe
Permet de spécifier des options lors du rendu d'une feuille de calcul en images, de l'impression d'une feuille de calcul ou du rendu d'un graphique en image.



Le type ImageOrPrintOptions expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [`__init__(self)`](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/__init__/#) | Cteur.|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [save_format](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/save_format) | Obtient ou définit le type de format de fichier de sortie<br/> Assistance Tiff/XPS|
| [print_with_status_dialog](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/print_with_status_dialog) | Si PrintWithStatusDialog = true, une boîte de dialogue s'affichera indiquant l'état d'impression actuel.<br/> sinon aucune boîte de dialogue de ce type ne s'affichera.|
| [horizontal_resolution](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/horizontal_resolution) | Obtient ou définit la résolution horizontale des images générées, en points par pouce.|
| [vertical_resolution](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/vertical_resolution) | Obtient ou définit la résolution verticale des images générées, en points par pouce.|
| [tiff_compression](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/tiff_compression) | Obtient ou définit le type de compression à appliquer uniquement lors de l'enregistrement de pages au format `Tiff`.|
| [tiff_color_depth](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/tiff_color_depth) | Obtient ou définit la profondeur de bits à appliquer uniquement lors de l'enregistrement des pages au format `Tiff`.|
| [tiff_binarization_method](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/tiff_binarization_method) | Obtient ou définit la méthode utilisée lors de la conversion des images au format 1 bpp<br/>lorsque [`ImageOrPrintOptions.image_type`](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions#image_type) est Tiff et [`ImageOrPrintOptions.tiff_compression`](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions#tiff_compression) est égal à Ccitt3 ou Ccitt4.|
| [printing_page](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/printing_page) | Indique quelles pages ne seront pas imprimées.|
| [quality](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/quality) | Obtient ou définit une valeur déterminant la qualité des images générées<br/> à appliquer uniquement lors de l'enregistrement de pages au format `Jpeg`. La valeur par défaut est 100.|
| [image_type](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/image_type) | Obtient ou définit le format des images générées.<br/> valeur par défaut : PNG.|
| [is_cell_auto_fit](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/is_cell_auto_fit) | Indique si la largeur et la hauteur des cellules sont automatiquement ajustées par la valeur de la cellule.<br/> La valeur par défaut est false.|
| [one_page_per_sheet](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/one_page_per_sheet) | Si OnePagePerSheet est vrai, tout le contenu d'une feuille sera affiché sur une seule page dans le résultat.<br/> Le format de papier de la mise en page sera invalide, ainsi que les autres paramètres de la mise en page.<br/> prendra toujours effet.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/all_columns_in_one_page_per_sheet) | Si AllColumnsInOnePagePerSheet est vrai, tout le contenu des colonnes d'une feuille sera affiché sur une seule page dans le résultat.<br/> La largeur du format de papier de la mise en page sera invalide, ainsi que les autres paramètres de la mise en page.<br/> prendra toujours effet.|
| [chart_image_type](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/chart_image_type) | Indiquez le type d'image du graphique lors de la conversion.<br/> valeur par défaut : PNG.|
| [embeded_image_name_in_svg](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/embeded_image_name_in_svg) | Indiquez le nom de fichier de l'image intégrée dans svg.<br/> Cela devrait être un chemin complet avec un répertoire comme « c:\\xpsEmbedded »|
| [svg_fit_to_view_port](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/svg_fit_to_view_port) | si cette propriété est vraie, le svg généré s'adaptera au port d'affichage.|
| [svg_css_prefix](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/svg_css_prefix) |Obtient et définit le préfixe du nom CSS en svg, la valeur par défaut est une chaîne vide.|
| [only_area](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/only_area) | Si cette propriété est vraie, une zone sera générée et aucune échelle ne prendra effet.|
| [text_rendering_hint](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/text_rendering_hint) | Spécifie la qualité du rendu du texte.<br/> La valeur par défaut est TextRenderingHint.SystemDefault|
| [smoothing_mode](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/smoothing_mode) | Spécifie si le lissage (anticrénelage) est appliqué aux lignes et aux courbes ainsi qu'aux bords des zones remplies.<br/> La valeur par défaut est SmoothingMode.None|
| [transparent](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/transparent) | Indique si l'arrière-plan de l'image générée doit être transparent.|
| [pixel_format](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/pixel_format) | Obtient ou définit le format de pixel pour les images générées.|
| [is_font_substitution_char_granularity](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/is_font_substitution_char_granularity) | Indique s'il faut uniquement remplacer la police de caractère lorsque la police de la cellule n'est pas compatible avec celle-ci.|
| [page_index](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/page_index) | Obtient ou définit l'index de base 0 de la première page à enregistrer.|
| [page_count](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/page_count) | Obtient ou définit le nombre de pages à enregistrer.|
| [is_optimized](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/is_optimized) | Indique s'il faut optimiser les éléments de sortie.|
| [default_font](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/default_font) | Lorsque les caractères dans Excel sont Unicode et ne sont pas définis avec la police correcte dans le style de cellule,<br/>Ils peuvent apparaître sous forme de bloc dans un PDF, une image.<br/>Définissez la police par défaut telle que MingLiu ou MS Gothic pour afficher ces caractères.<br/>Si cette propriété n'est pas définie, Aspose.Cells utilisera la police par défaut du système pour afficher ces caractères Unicode.|
| [check_workbook_default_font](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/check_workbook_default_font) | Lorsque les caractères dans Excel sont Unicode et ne sont pas définis avec la police correcte dans le style de cellule,<br/>Ils peuvent apparaître sous forme de bloc dans un PDF, une image.<br/> Définissez cette option sur vrai pour essayer d'utiliser la police par défaut du classeur pour afficher ces caractères en premier.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/output_blank_page_when_nothing_to_print) | Indique s'il faut sortir une page vierge lorsqu'il n'y a rien à imprimer.|
| [gridline_type](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/gridline_type) | Obtient ou définit le type de grille.|
| [gridline_color](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/gridline_color) | Obtient ou définit la couleur de la grille.|
| [text_cross_type](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/text_cross_type) | Obtient ou définit le type de texte affiché lorsque la largeur du texte est supérieure à la largeur de la cellule.|
| [emf_type](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/emf_type) | Obtient ou définit un EmfType qui spécifie le format du métafichier.<br/> La valeur par défaut est EmfPlusDual.|
| [default_edit_language](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/default_edit_language) | Obtient ou définit la langue d'édition par défaut.|
| [sheet_set](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/sheet_set) | Obtient ou définit les feuilles à afficher. Par défaut, toutes les feuilles du classeur sont visibles : [`SheetSet.visible`](/cells/python-net/fr/aspose.cells.rendering/sheetset#visible).|
| [emf_render_setting](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/emf_render_setting) | Paramètre pour le rendu des métafichiers Emf dans le fichier source.|
| [custom_render_settings](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/custom_render_settings) | Obtient ou définit des paramètres personnalisés pendant le rendu.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`set_desired_size(self, desired_width, desired_height)`](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/set_desired_size/#int-int) | Définit la largeur et la hauteur souhaitées de l'image.|
| [`set_desired_size(self, desired_width, desired_height, keep_aspect_ratio)`](/cells/python-net/fr/aspose.cells.rendering/imageorprintoptions/set_desired_size/#int-int-bool) | Définit la largeur et la hauteur souhaitées de l'image.|



###  Exemple

```python
from aspose.cells import Workbook
from aspose.cells.drawing import ImageType
from aspose.cells.rendering import ImageOrPrintOptions

# Set Image Or Print Options
options = ImageOrPrintOptions()
# Set output image format
options.image_type = ImageType.PNG
# Set Horizontal resolution
options.horizontal_resolution = 300
# Set Vertical Resolution
options.vertical_resolution = 300
# Instantiate Workbook
book = Workbook("test.xls")
# Save chart as Image using ImageOrPrint Options
book.worksheets[0].charts[0].to_image("chart.png", options)

```

###  Voir également
* module [`aspose.cells.rendering`](..)
