---
title: Enumerazione ReConnectionMethodType
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 130
url: /it/aspose.cells.externalconnections/reconnectionmethodtype/
is_root: false
---
##  Enumerazione ReConnectionMethodType
Specifica cosa deve fare l'applicazione del foglio di calcolo quando una connessione fallisce.



Il tipo ReConnectionMethodType espone i seguenti membri:

###  Campi
| Campo| Descrizione|
| :- | :- |
| REQUIRED | Durante l'aggiornamento, utilizzare le informazioni di connessione esistenti e se risultano non valide<br/> quindi ottenere informazioni di connessione aggiornate, se disponibili dal file di connessione esterno.|
| ALWAYS | Ad ogni aggiornamento ottieni informazioni di connessione aggiornate dal file di connessione esterno,<br/> se disponibile e utilizzarlo al posto delle informazioni di connessione esistenti.<br/>In questo caso l'aggiornamento dei dati fallirà se il file di connessione esterno non è disponibile.|
| NEVER | Non ricevere mai informazioni di connessione aggiornate dal file di connessione esterno<br/> anche se è disponibile e anche se le informazioni di connessione esistenti non sono valide|



###  Guarda anche
* modulo [`aspose.cells.externalconnections`](..)
