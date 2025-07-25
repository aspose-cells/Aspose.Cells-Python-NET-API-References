---
title: PdfSecurityOptions classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 10
url: /it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/
is_root: false
---
##  PdfSecurityOptions classe
Opzioni per la crittografia e le autorizzazioni di accesso per un documento PDF.
PDF/A non consente l'impostazione di sicurezza.



Il tipo PdfSecurityOptions espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [`__init__(self)`](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/__init__/#) |Il costruttore di PdfSecurityOptions|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [user_password](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/user_password) | Ottiene o imposta la password utente richiesta per aprire il documento crittografato PDF.|
| [owner_password](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/owner_password) | Ottiene o imposta la password del proprietario per il documento crittografato PDF.|
| [print_permission](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/print_permission) | Indica se consentire la stampa del documento.|
| [modify_document_permission](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/modify_document_permission) | Indica se consentire la modifica del contenuto del documento tramite operazioni diverse da quelle controllate<br/> tramite [`PdfSecurityOptions.annotations_permission`](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#annotations_permission), [`PdfSecurityOptions.fill_forms_permission`](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#fill_forms_permission) e [`PdfSecurityOptions.assemble_document_permission`](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#assemble_document_permission).|
| [extract_content_permission_obsolete](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/extract_content_permission_obsolete) | Autorizzazione a copiare o estrarre il contenuto Obsoleto secondo il riferimento PDF.|
| [annotations_permission](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/annotations_permission) | Indica se consentire l'aggiunta o la modifica di annotazioni di testo e la compilazione di campi di moduli interattivi.|
| [fill_forms_permission](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/fill_forms_permission) | Indica se consentire la compilazione dei campi del modulo interattivo esistente (inclusi i campi della firma),<br/> anche se [`PdfSecurityOptions.modify_document_permission`](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#modify_document_permission) è libero.|
| [extract_content_permission](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/extract_content_permission) | Indica se consentire la copia o l'estrazione di testo e grafica dal documento<br/> da operazioni diverse da quella controllata da [`PdfSecurityOptions.accessibility_extract_content`](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#accessibility_extract_content).|
| [accessibility_extract_content](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/accessibility_extract_content) |Indica se consentire l'estrazione di testo e grafica (a supporto dell'accessibilità per gli utenti con disabilità o per altri scopi).|
| [assemble_document_permission](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/assemble_document_permission) | Indica se consentire l'assemblaggio del documento (inserimento, rotazione o eliminazione di pagine e creazione di segnalibri o immagini in miniatura),<br/> anche se [`PdfSecurityOptions.modify_document_permission`](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#modify_document_permission) è libero.|
| [full_quality_print_permission](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/full_quality_print_permission) | Indica se consentire la stampa del documento su una rappresentazione da<br/> che potrebbe essere generata una copia digitale fedele del contenuto PDF.|



###  Guarda anche
* modulo [`aspose.cells.rendering.pdfsecurity`](..)
