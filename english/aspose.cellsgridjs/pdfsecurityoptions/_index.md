---
title: PdfSecurityOptions class
second_title: Aspose.Cells.GridJs for Python via .NET API References
description: 
type: docs
weight: 190
url: /aspose.cellsgridjs/pdfsecurityoptions/
is_root: false
---

## PdfSecurityOptions class

Options for encrypting and access permissions for a PDF document.
PDF/A does not allow security setting.



The PdfSecurityOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/cells/python-net/aspose.cellsgridjs/pdfsecurityoptions/__init__/#) | The constructor of PdfSecurityOptions |


### Properties
| Property | Description |
| :- | :- |
| [user_password](/cells/python-net/aspose.cellsgridjs/pdfsecurityoptions/user_password) | Gets or sets the user password required for opening the encrypted PDF document. |
| [owner_password](/cells/python-net/aspose.cellsgridjs/pdfsecurityoptions/owner_password) | Gets or sets the owner password for the encrypted PDF document. |
| [print_permission](/cells/python-net/aspose.cellsgridjs/pdfsecurityoptions/print_permission) | Indicates whether to allow to print the document. |
| [modify_document_permission](/cells/python-net/aspose.cellsgridjs/pdfsecurityoptions/modify_document_permission) | Indicates whether to allow to modify the contents of the document by operations other than those controlled <br/>by [`PdfSecurityOptions.annotations_permission`](/cells/python-net/aspose.cellsgridjs/pdfsecurityoptions#annotations_permission), [`PdfSecurityOptions.fill_forms_permission`](/cells/python-net/aspose.cellsgridjs/pdfsecurityoptions#fill_forms_permission) and [`PdfSecurityOptions.assemble_document_permission`](/cells/python-net/aspose.cellsgridjs/pdfsecurityoptions#assemble_document_permission). |
| [annotations_permission](/cells/python-net/aspose.cellsgridjs/pdfsecurityoptions/annotations_permission) | Indicates whether to allow to add or modify text annotations, fill in interactive form fields. |
| [fill_forms_permission](/cells/python-net/aspose.cellsgridjs/pdfsecurityoptions/fill_forms_permission) | Indicates whether to allow to fill in existing interactive form fields (including signature fields), <br/>even if [`PdfSecurityOptions.modify_document_permission`](/cells/python-net/aspose.cellsgridjs/pdfsecurityoptions#modify_document_permission) is clear. |
| [extract_content_permission](/cells/python-net/aspose.cellsgridjs/pdfsecurityoptions/extract_content_permission) | Indicates whether to allow to copy or otherwise extract text and graphics from the document <br/>by operations other than that controlled by [`PdfSecurityOptions.accessibility_extract_content`](/cells/python-net/aspose.cellsgridjs/pdfsecurityoptions#accessibility_extract_content). |
| [accessibility_extract_content](/cells/python-net/aspose.cellsgridjs/pdfsecurityoptions/accessibility_extract_content) | Indicates whether to allow to extract text and graphics (in support of accessibility to users with disabilities or for other purposes). |
| [assemble_document_permission](/cells/python-net/aspose.cellsgridjs/pdfsecurityoptions/assemble_document_permission) | Indicates whether to allow to assemble the document (insert, rotate, or delete pages and create bookmarks or thumbnail images), <br/>even if [`PdfSecurityOptions.modify_document_permission`](/cells/python-net/aspose.cellsgridjs/pdfsecurityoptions#modify_document_permission) is clear. |
| [full_quality_print_permission](/cells/python-net/aspose.cellsgridjs/pdfsecurityoptions/full_quality_print_permission) | Indicates whether to allow to print the document to a representation from <br/>which a faithful digital copy of the PDF content could be generated. |



### See Also
* module [`aspose.cellsgridjs`](..)
