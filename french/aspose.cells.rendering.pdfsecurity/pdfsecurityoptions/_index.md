---
title: PdfSecurityOptions classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 10
url: /fr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/
is_root: false
---
##  PdfSecurityOptions classe
Options de cryptage et autorisations d'accès pour un document PDF.
PDF/A ne permet pas le réglage de la sécurité.



Le type PdfSecurityOptions expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [__init__](/cells/python-net/fr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/__init__/#) | Le constructeur de PdfSecurityOptions|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [user_password](/cells/python-net/fr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/user_password) | Obtient ou définit le mot de passe utilisateur requis pour ouvrir le document PDF chiffré.|
| [owner_password](/cells/python-net/fr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/owner_password) | Obtient ou définit le mot de passe du propriétaire du document PDF chiffré.|
| [print_permission](/cells/python-net/fr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/print_permission) | Indique s’il faut autoriser l’impression du document.|
| [modify_document_permission](/cells/python-net/fr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/modify_document_permission) |Indique s'il faut autoriser la modification du contenu du document par des opérations autres que celles contrôlées<br/> par [`PdfSecurityOptions.annotations_permission`](/cells/python-net/fr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#annotations_permission), [`PdfSecurityOptions.fill_forms_permission`](/cells/python-net/fr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#fill_forms_permission) et [`PdfSecurityOptions.assemble_document_permission`](/cells/python-net/fr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#assemble_document_permission).|
| [extract_content_permission_obsolete](/cells/python-net/fr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/extract_content_permission_obsolete) | Autorisation de copier ou d'extraire du contenu Obsolète selon la référence PDF.|
| [annotations_permission](/cells/python-net/fr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/annotations_permission) | Indique s'il faut autoriser l'ajout ou la modification d'annotations de texte, remplir les champs du formulaire interactif.|
| [fill_forms_permission](/cells/python-net/fr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/fill_forms_permission) | Indique s'il faut autoriser le remplissage des champs de formulaires interactifs existants (y compris les champs de signature),<br/> même si [`PdfSecurityOptions.modify_document_permission`](/cells/python-net/fr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#modify_document_permission) est clair.|
| [extract_content_permission](/cells/python-net/fr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/extract_content_permission) | Indique s'il faut autoriser la copie ou l'extraction du texte et des graphiques du document<br/> par des opérations autres que celle contrôlée par [`PdfSecurityOptions.accessibility_extract_content`](/cells/python-net/fr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#accessibility_extract_content).|
| [accessibility_extract_content](/cells/python-net/fr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/accessibility_extract_content) | Indique s'il faut autoriser l'extraction de texte et de graphiques (pour faciliter l'accessibilité aux utilisateurs handicapés ou à d'autres fins).|
| [assemble_document_permission](/cells/python-net/fr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/assemble_document_permission) | Indique s'il faut autoriser l'assemblage du document (insérer, faire pivoter ou supprimer des pages et créer des signets ou des images miniatures),<br/> même si [`PdfSecurityOptions.modify_document_permission`](/cells/python-net/fr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#modify_document_permission) est clair.|
| [full_quality_print_permission](/cells/python-net/fr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/full_quality_print_permission) | Indique s'il faut autoriser l'impression du document vers une représentation à partir de<br/>laquelle une copie numérique fidèle du contenu PDF pourrait être générée.|



###  Voir également
* module [`aspose.cells.rendering.pdfsecurity`](..)
