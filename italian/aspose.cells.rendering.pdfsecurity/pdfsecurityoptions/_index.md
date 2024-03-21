---
title: PdfSecurityOptions classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 10
url: /it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/
is_root: false
---
##  PdfSecurityOptions classe
Opzioni per la crittografia e le autorizzazioni di accesso per un documento PDF.
PDF/A non consente l'impostazione della sicurezza.



Il tipo PdfSecurityOptions espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [__init__](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/__init__/#) | Il costruttore di PdfSecurityOptions|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [user_password](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/user_password) | Ottiene o imposta la password utente richiesta per l'apertura del documento crittografato PDF.|
| [owner_password](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/owner_password) | Ottiene o imposta la password del proprietario per il documento crittografato PDF.|
| [print_permission](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/print_permission) | Indica se consentire la stampa del documento.|
| [modify_document_permission](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/modify_document_permission) |Indica se consentire di modificare il contenuto del documento mediante operazioni diverse da quelle controllate<br/> tramite [`PdfSecurityOptions.annotations_permission`](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#annotations_permission), [`PdfSecurityOptions.fill_forms_permission`](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#fill_forms_permission) e [`PdfSecurityOptions.assemble_document_permission`](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#assemble_document_permission).|
| [extract_content_permission_obsolete](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/extract_content_permission_obsolete) | Autorizzazione a copiare o estrarre contenuti Obsoleto secondo il riferimento PDF.|
| [annotations_permission](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/annotations_permission) | Indica se consentire di aggiungere o modificare annotazioni di testo, compilare campi del modulo interattivo.|
| [fill_forms_permission](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/fill_forms_permission) | Indica se consentire la compilazione dei campi del modulo interattivo esistente (compresi i campi della firma),<br/> anche se [`PdfSecurityOptions.modify_document_permission`](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#modify_document_permission) è chiaro.|
| [extract_content_permission](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/extract_content_permission) | Indica se consentire di copiare o altrimenti estrarre testo e grafica dal documento<br/> da operazioni diverse da quella controllata da [`PdfSecurityOptions.accessibility_extract_content`](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#accessibility_extract_content).|
| [accessibility_extract_content](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/accessibility_extract_content) | Indica se consentire l'estrazione di testo e grafica (a supporto dell'accessibilità agli utenti con disabilità o per altri scopi).|
| [assemble_document_permission](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/assemble_document_permission) | Indica se consentire l'assemblaggio del documento (inserire, ruotare o eliminare pagine e creare segnalibri o immagini in miniatura),<br/> anche se [`PdfSecurityOptions.modify_document_permission`](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#modify_document_permission) è chiaro.|
| [full_quality_print_permission](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/full_quality_print_permission) | Indica se consentire la stampa del documento da cui ottenere una rappresentazione<br/>da cui potrebbe essere generata una copia digitale fedele del contenuto di PDF.|



###  Guarda anche
* modulo [`aspose.cells.rendering.pdfsecurity`](..)
