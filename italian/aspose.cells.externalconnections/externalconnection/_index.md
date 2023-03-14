---
title: classe ExternalConnection
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 50
url: /it/aspose.cells.externalconnections/externalconnection/
is_root: false
---
##  classe ExternalConnection
Specifica una connessione dati esterna



Il tipo ExternalConnection espone i membri seguenti:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [id](/cells/python-net/it/aspose.cells.externalconnections/externalconnection/id) | Ottiene l'ID della connessione.|
| [power_query_formula](/cells/python-net/it/aspose.cells.externalconnections/externalconnection/power_query_formula) | Ottiene la definizione della formula di query di alimentazione.|
| [type](/cells/python-net/it/aspose.cells.externalconnections/externalconnection/type) | Ottiene o imposta il tipo DataSource della connessione esterna.|
| [source_file](/cells/python-net/it/aspose.cells.externalconnections/externalconnection/source_file) | Utilizzato quando l'origine dati esterna è basata su file. Quando una connessione a tali dati<br/> source non riesce, l'applicazione del foglio di calcolo tenta di connettersi direttamente a questo file. Forse<br/> espresso in URI o notazione del percorso file specifica del sistema.|
| [sso_id](/cells/python-net/it/aspose.cells.externalconnections/externalconnection/sso_id) | Identificatore per Single Sign On (SSO) utilizzato per l'autenticazione tra un intermediario<br/> server spreadsheetML e l'origine dati esterna.|
| [save_password](/cells/python-net/it/aspose.cells.externalconnections/externalconnection/save_password) | True se la password deve essere salvata come parte della stringa di connessione; altrimenti Falso.|
| [save_data](/cells/python-net/it/aspose.cells.externalconnections/externalconnection/save_data) | True se i dati esterni recuperati tramite la connessione per popolare una tabella devono essere salvati<br/> con la cartella di lavoro; altrimenti, falso.|
| [refresh_on_load](/cells/python-net/it/aspose.cells.externalconnections/externalconnection/refresh_on_load) | True se questa connessione deve essere aggiornata all'apertura del file; altrimenti, falso.|
| [reconnection_method_type](/cells/python-net/it/aspose.cells.externalconnections/externalconnection/reconnection_method_type) | Specifica cosa deve fare l'applicazione del foglio di calcolo quando una connessione fallisce.<br/>Il valore predefinito è ReConnectionMethodType.Required.|
| [reconnection_method](/cells/python-net/it/aspose.cells.externalconnections/externalconnection/reconnection_method) | Specifica cosa deve fare l'applicazione del foglio di calcolo quando una connessione fallisce.<br/>Il valore predefinito è ReConnectionMethodType.Required.|
| [only_use_connection_file](/cells/python-net/it/aspose.cells.externalconnections/externalconnection/only_use_connection_file) | Indica se l'applicazione per fogli di calcolo deve utilizzare sempre e solo il file<br/> informazioni sulla connessione nel file di connessione esterno indicato dall'attributo odcFile<br/> quando la connessione viene aggiornata. Se falso, l'applicazione del foglio di calcolo<br/> deve seguire la procedura indicata dall'attributo reconnectionMethod|
| [odc_file](/cells/python-net/it/aspose.cells.externalconnections/externalconnection/odc_file) | Specifica il percorso completo del file di connessione esterno da cui proveniva questa connessione<br/> creato. Se una connessione non riesce durante un tentativo di aggiornamento dei dati e reconnectionMethod=1,<br/> quindi l'applicazione del foglio di calcolo riproverà utilizzando le informazioni dal file di connessione esterno<br/> invece dell'oggetto connessione incorporato nella cartella di lavoro.|
| [is_new](/cells/python-net/it/aspose.cells.externalconnections/externalconnection/is_new) | True se la connessione non è stata aggiornata per la prima volta; altrimenti, falso.<br/> Questo stato può verificarsi quando l'utente salva il file prima che sia terminata la restituzione di una query.|
| [name](/cells/python-net/it/aspose.cells.externalconnections/externalconnection/name) | Specifica il nome della connessione. Ogni connessione deve avere un nome univoco.|
| [keep_alive](/cells/python-net/it/aspose.cells.externalconnections/externalconnection/keep_alive) | Vero quando l'applicazione del foglio di calcolo deve sforzarsi di mantenere la connessione<br/>aprire. Se falso, l'applicazione dovrebbe chiudere la connessione dopo aver recuperato il file<br/> informazione.|
| [refresh_internal](/cells/python-net/it/aspose.cells.externalconnections/externalconnection/refresh_internal) | Specifica il numero di minuti tra gli aggiornamenti automatici della connessione.|
| [connection_id](/cells/python-net/it/aspose.cells.externalconnections/externalconnection/connection_id) | Specifica l'identificatore univoco di questa connessione.|
| [connection_description](/cells/python-net/it/aspose.cells.externalconnections/externalconnection/connection_description) | Specifica la descrizione utente per questa connessione|
| [is_deleted](/cells/python-net/it/aspose.cells.externalconnections/externalconnection/is_deleted) |Indica se la connessione alla cartella di lavoro associata è stata eliminata. vero se il<br/> la connessione è stata cancellata; altrimenti, falso.|
| [credentials_method_type](/cells/python-net/it/aspose.cells.externalconnections/externalconnection/credentials_method_type) | Specifica il metodo di autenticazione da utilizzare quando si stabilisce (o si ristabilisce) la connessione.|
| [credentials](/cells/python-net/it/aspose.cells.externalconnections/externalconnection/credentials) | Specifica il metodo di autenticazione da utilizzare quando si stabilisce (o si ristabilisce) la connessione.|
| [background_refresh](/cells/python-net/it/aspose.cells.externalconnections/externalconnection/background_refresh) | Indica se la connessione può essere aggiornata in background (in modo asincrono).<br/>true se l'utilizzo preferito della connessione consiste nell'aggiornare in modo asincrono in background;<br/> false se l'utilizzo preferito della connessione consiste nell'aggiornare in modo sincrono in primo piano.|
| [parameters](/cells/python-net/it/aspose.cells.externalconnections/externalconnection/parameters) | Ottiene [ConnectionParameterCollection](/cells/python-net/it/aspose.cells.externalconnections/connectionparametercollection) per una query ODBC o Web.|



###  Guarda anche
* modulo [aspose.cells.externalconnections](..)
* classe [ConnectionParameterCollection](/cells/python-net/it/aspose.cells.externalconnections/connectionparametercollection)
