---
title: LowCodeSaveOptionsProviderOfPlaceHolders classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 120
url: /fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/
is_root: false
---
##  LowCodeSaveOptionsProviderOfPlaceHolders classe
Mise en œuvre pour fournir des options de sauvegarde qui enregistrent les parties divisées dans des fichiers
et le chemin du fichier résultant sont définis avec des espaces réservés.



**Héritage:** [`LowCodeSaveOptionsProviderOfPlaceHolders`](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders)



Le type LowCodeSaveOptionsProviderOfPlaceHolders expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [`__init__(self, path_template)`](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/__init__/#str) |Instancie une instance pour fournir des options de sauvegarde selon des modèles spécifiés.|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [sheet_index_offset](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/sheet_index_offset) | Décalage de l'index de la feuille par rapport à celui utilisé dans le chemin du fichier<br/> et sa valeur réelle ([`SplitPartInfo.sheet_index`](/cells/python-net/fr/aspose.cells.lowcode/splitpartinfo#sheet_index)).|
| [split_part_index_offset](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/split_part_index_offset) | Décalage de l'index de la partie divisée par rapport à ce qui est utilisé dans le chemin du fichier<br/> et sa valeur réelle ([`SplitPartInfo.part_index`](/cells/python-net/fr/aspose.cells.lowcode/splitpartinfo#part_index)).|
| [build_path_with_sheet_always](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/build_path_with_sheet_always) | Ajoutez toujours un index de feuille ou un nom au chemin du fichier.<br/>La valeur par défaut est false, c'est-à-dire lorsqu'il n'y a qu'une seule feuille,<br/>l'index de la feuille et le nom et le préfixe correspondant ([`LowCodeSaveOptionsProviderOfPlaceHolders.sheet_name_prefix`](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders#sheet_name_prefix))<br/> ne sera pas ajouté au chemin du fichier.|
| [build_path_with_split_part_always](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/build_path_with_split_part_always) | Ajoutez-vous toujours un index de partie fractionnée au chemin du fichier ?<br/>La valeur par défaut est false, c'est-à-dire lorsqu'il n'y a qu'une seule partie divisée,<br/>l'index de la partie divisée et le préfixe correspondant ([`LowCodeSaveOptionsProviderOfPlaceHolders.split_part_prefix`](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders#split_part_prefix))<br/> ne sera pas ajouté au chemin du fichier.|
| [sheet_name_prefix](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/sheet_name_prefix) |Préfixe pour l'index de la feuille de calcul.|
| [sheet_index_prefix](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/sheet_index_prefix) |Préfixe pour l'index de la feuille de calcul.|
| [split_part_prefix](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/split_part_prefix) | Préfixe pour l'index de la partie divisée.|
| [save_options_template](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/save_options_template) | Le modèle pour créer une instance d'options de sauvegarde dans [`LowCodeSaveOptionsProviderOfPlaceHolders.get_save_options`](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/get_save_options).|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`get_save_options(self, part)`](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/get_save_options/#aspose.cells.lowcode.splitpartinfo) | Obtient les options d'enregistrement à partir desquelles obtenir les paramètres de sortie pour la partie actuellement divisée.|
| [`finish(self, part)`](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/finish/#aspose.cells.lowcode.lowcodesaveoptions) |  |



###  Voir également
* module [`aspose.cells.lowcode`](..)
* classe [`LowCodeSaveOptionsProviderOfPlaceHolders`](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders)
