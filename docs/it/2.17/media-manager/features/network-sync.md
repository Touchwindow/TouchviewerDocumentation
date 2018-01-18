# Sincronizzazione
![](/img/sync_empty_1.png)

Touchviewer è gestibile sia in locale che in remoto. È progettato per distribuire contenuti su un network di postazioni interattive installate in location differenti. Tutti i client Touchviewer possono essere configurati per inviare o ricevere aggiornamenti in maniera manuale o pianificata. L'intera architettura è basata su un sistema di sincronizzazione estremamente performante che garantisce velocità e affidabilità in tutte le operazioni di aggiornamento con e verso il server remoto.

### Configurazione pubblicazione
![](/img/sync_publish_open_2.png)

Da qui è possibile scegliere la destinazione per la pubblicazione dei contenuti. La destinazione può essere una cartella del PC, una cartella di rete mappata o il servizio di cloud storage Dropbox.

Escludendo le miniature (consigliato per archivi con molti contenuti) si velocizza il processo di publiccazione. Le miniature verranno ricreate al momento della sincronizzazione sul dispositivo che scarica gli aggiornamenti.

Nel caso si scelga il servizio cloud __DROPBOX__ bisogna inserire tutti di dati dell'account per l'autenticazione al servizio.


### Configurazione aggiornamento
![](/img/sync_update_open_6.png)

Definire la sorgente da cui scaricare gli aggiornamenti. La sorgente può essere una cartella del PC, una cartella di rete (selezionare Robocopy), uno spazio storage del servizio Strongspace o una cartella Dropbox.

__Attenzione__ gli aggiornamenti verranno scaricati nell'archivio attualmente aperto.

![](/img/sync_update_folder_7.png)

Una volta selezionata la sorgente da cui scaricare gli aggiornamenti è possibile impostare la modalità di sincronizzazione:

* _Aggiorna i contenuti all'avvio del software_  Ad ogni avvio di Touchviewer la procedura esegue un controllo di aggiornamenti disponibili ed esegue il downloadqualora siano presenti nuovi contenuti o contenuti modificati nell cartella sorgente. Spuntando ___Chiedi conferma prima di aggiornare___ verrà mostrata una notifica in cui verrà chiesto se si vuole aggiornare l'archivio. In caso di risposta negativa l'aggiornamento verrà richiesto al prossimo avvio del Touchviewer.
* _Non aggiornare automaticamente_ Richiede l'azione manuale di aggiornamento mediante il pulsante __Aggiorna__.
