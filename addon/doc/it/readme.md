# Windows 10 App Essentials #

* Autori: Joseph Lee, Derek Riemer e altri utenti Windows 10.
* Download [versione stabile][1]
* Download [versione in sviluppo][2]

This add-on is a collection of app modules for various Windows 10 apps, as
well as enhancements and fixes for certain windows 10 controls.

Segue l'elenco di tutti gli appmodule contenuti nel componente aggiuntivo,
si veda la relativa sezione per ulteriori informazioni:

* Allarmi e sveglia.
* Calendario
* Calcolatrice (moderna).
* Cortana
* Feedback Hub
* Barra dei giochi
* Posta
* Mappe
* Microsoft Edge
* Modern keyboard (emoji panel/hardware input suggestions in Version 1709
  and later)
* Persone
* Impostazioni (Impostazioni Windows, Windows+i)
* Skype (universal app)
* Store
* Meteo
* Vari moduli per controlli come le mattonelle del menu avvio.

Note: this add-on requires Windows 10 Version 1703 (build 15063) or later
and NVDA 2017.3 or later. For best results, use the add-on with latest
Windows 10 stable build (build 16299) and latest stable version of
NVDA. Also, after changing update settings for the add-on, be sure to save
NVDA settings.

## Generale

* Nei menu di contesto per le mattonelle del menu avvio, vengono
  riconosciuti in maniera corretta i sottomenu.
* Certain dialogs are now recognized as proper dialogs, including Insider
  Preview dialog (settings app).
* NVDA può annunciare il numero dei suggerimenti quando si esegue una
  ricerca, almeno nella maggior parte dei casi. Questa funzione è
  controllata dall'opzione "leggi le informazioni sulla posizione
  dell'oggetto" nella finestra presentazioni oggetti di NVDA.
* In alcuni menu di contesto, come in Edge, le informazioni sulla posizione
  come 1 su 2 non vengono più annunciate.
* The following UIA events are recognized: Controller for, drag start, drag
  cancel, drag complete, element selected, live region change, notification,
  system alert, window opened. With NVDA set to run with debug logging
  enabled, these events will be tracked, and for UIA notification event, a
  debug tone will be heard.
* Aggiunta la possibilità di controllare automaticamente o manualmente la
  presenza di aggiornamenti di questo componente aggiuntivo mediante la
  finestra di dialogo Windows10 Essentials presente al menu preferenze di
  NVDA. Di default le versioni stabili eseguiranno un controllo settimanale,
  mentre quelle in sviluppo giornaliero.
* In alcune app, viene letto il testo che appare nelle regioni live. Ciò
  include notifiche in Edge,  i risultati nella calcolatrice ed altro. Si
  noti che talvolta potrebbe accadere che venga annunciato due volte lo
  stesso elemento.
* Notifications from newer app releases on Windows 10 Version 1709 (build
  16299) and later are announced. Due to technical limitations, this feature
  works properly with NVDA 2018.1 and later.

## Allarmi e sveglia

* I valori per selezionare l'ora adesso vengono annunciati. Questo comprende
  anche la sezione inerente la scelta dell'orario sul quando riavviare per
  terminare gli aggiornamenti di Windows Update

## Calcolatrice

* Quando viene premuto invio o Esc, NVDA annuncia il risultato del calcolo.
* For calculations such as unit converter and currency converter, NVDA will
  announce results as soon as calculations are entered.

## calendario

* Insider Hub (centro di supporto in Anniversary Update): solo per quegli
  utenti che usano una versione Insider di Windows, servendosi del centro
  Feedback Insider per aggiornamenti.

## Cortana

* Le risposte di tipo testuale di Cortana vengono lette nella maggior parte
  dei casi, se non dovesse funzionare riaprire il menu avvio e ripetere la
  ricerca.
* NVDA rimarrà in silenzio mentre si parla a Cortana  con la voce.
* NVDA annuncerà la conferma di un promemoria quando ne viene inserito uno.

## Feedback Hub

* For newer app releases, NVDA will no longer announce feedback categories
  twice.

## Barra dei giochi

* NVDA will announce appearance of Game Bar window. Due to technical
  limitations, NVDA cannot interact fully with Game Bar.

## Posta

* Quando si scorrono gli elementi in un elenco messaggi, è possibile
  utilizzare i comandi di navigazione tabella per controllare le
  intestazioni.
* Durante la composizione di un messaggio, verranno emessi segnali acustici
  nel caso ci siano dei suggerimenti per menzioni dopo la chiocciola

## Mappe

* NVDA emette dei segnali acustici per le posizioni presenti nella mappa.
* Quando si usa la visualizzazione per strade e l'opzione "utilizza
  tastiera" è attiva, NVDA annuncerà gli indirizzi delle vie mentre si
  scorre la mappa con le frecce.

## Microsoft Edge

* Vengono annunciate correttamente le notifiche dei download dei file.

## Modern keyboard

* Supporto per l'immissione di emoji animate (Fall creators Update). Per
  ottenere i migliori risultati si consiglia di servirsi delle voci OneCore,
  ossia quelle già presenti in Windows10.
* Support for hardware keyboard input suggestions in Version 1803 build
  17040 and later.
* In post-1709 builds, NVDA will announce the first selected emoji when
  emoji panel opens.

## Persone

* Durante la ricerca di contatti, verrà emesso un segnale acustico nel caso
  appaiono dei risultati di ricerca.

## Impostazioni

* Vengono annunciate automaticamente le informazioni di avanzamento delle
  operazioni di Windows Update.
* Le informazioni delle barre di avanzamento non vengono più lette due
  volte.
* Il gruppo impostazioni viene riconosciuto quando ci si sposta tra i
  controlli usando la navigazione ad oggetti.
* Per alcune caselle combinate, NVDA non commetterà più errori nel
  riconoscere le etichette o annunciare i cambiamenti dei valori.
* Audio Volume progress bar beeps are no longer heard in Version 1803 build
  17035 and later.

## Skype

* Viene annunciato quando un utente sta scrivendo, così come accade in Skype
  per desktop.
* Implementazione parziale della funzionalità di lettura rapida delle chat
  con ctrl+NVDA+numeri da 1 a 9, come accade in Skype Desktop.
* è possibile premere il tasto alt in combinazione con i numeri per
  spostarsi tra conversazioni (1), elenco contatti  (2), bots (3) e campo
  editazione della chat se visibile (4). Si noti che questi comandi
  funzioneranno a dovere se è stato installato l'aggiornamento di Skype di
  marzo 2017.
* Vengono lette le etichette delle caselle combinate in anteprima Skype
  novembre 2016
* Nella maggior parte dei casi, NVDA non leggerà più i messaggi Skype di
  continuo quando se ne sta controllando uno
* Various issues when using Skype with braille displays fixed, including
  inability to review message history items in braille.
* From message history list, pressing NVDA+D on a message item will now
  allow NVDA to announce detailed information about a message such as
  channel type, sent date and time and so on.

## Store

* Dopo aver controllato la presenza di aggiornamenti di app, i nomi delle
  app nell'elenco degli aggiornamenti viene correttamente etichettato.
* Mentre si scaricano contenuti quali app o film, NVDA ne leggerà il nome e
  l'avanzamento del download.

## Meteo

* Schede come "previsioni" e "mappe" vengono riconosciute correttamente
  (patch da Derek Riemer). 
* durante la lettura di una previsione, utilizzare le frecce sinistra e
  destra per spostarsi tra gli elementi. Utilizzare le frecce su e giù per
  leggere i singoli elementi. Per esempio, premendo la freccia destra
  potrebbe venir annunciato "lunedì: 29 gradi, parzialmente nuvoloso, ..."
  premendo la freccia giù dirà "lunedì", Quindi premerla di nuovo per
  leggere il prossimo elemento (ad esempio la temperatura). Ciò funziona per
  previsioni orarie e giornaliere.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=w10

[2]: https://addons.nvda-project.org/files/get.php?file=w10-dev
