# Malfunzionamento del dispositivo.

SC: 3
Attori coinvolti: Gestore delle segnalazioni  (../Attori%20coinvolti%20nel%20sistema/Gestore%20delle%20segnalazioni%2019a1100dcfbd81f8a69ee2817fe5d4f9.md), Conducente del veicolo   (../Attori%20coinvolti%20nel%20sistema/Conducente%20del%20veicolo%2019a1100dcfbd819996a8c51584c9ffde.md), Assistenza stradale (../Attori%20coinvolti%20nel%20sistema/Assistenza%20stradale%2019a1100dcfbd8134b3ffee46388e2e1e.md), Tecnici di installazione specializzati  (../Attori%20coinvolti%20nel%20sistema/Tecnici%20di%20installazione%20specializzati%2019a1100dcfbd81fbb49fce0468817e0a.md)
Servizi associati: Misurazione di sostanze stupefacenti  (../Requisiti%20Funzionali/Misurazione%20di%20sostanze%20stupefacenti%2019a1100dcfbd8100bf0dfc27fcb71188.md), Misurazione del tasso alcolemico  (../Requisiti%20Funzionali/Misurazione%20del%20tasso%20alcolemico%2019a1100dcfbd81478aa7f117bfc0bce8.md), Blocco dell’avvio del veicolo  (../Requisiti%20Funzionali/Blocco%20dell%E2%80%99avvio%20del%20veicolo%2019a1100dcfbd816d8568c80ceac15f92.md)
Tipo: Eccezionale

## Precondizione

Il conducente deve aver installato i dispositivi per la misurazione del livello di alcohol e di sostanze stupefacenti.

Il conducente soffia nell’etilometro. Il sistema misura il livello di alcol.

Il gestore deve aver ricevuto le credenziali di accesso alla dashboard

La centralina rileva che uno dei sensori non riesce a rilevare il livello di alcol o di sostanze stupefacenti a causa di un malfunzionamento del dispositivo.

## Flusso di eventi

La centralina blocca l’accensione del veicolo ed invia una segnalazione al gestore che contatterà l’assistenza stradale e i tecnici specializzati che sostituiranno i sensori.

## Cosa può andare storto

Il gestore del sistema non riesce a visualizzare lo stato dei sensori.

Il gestore non contatta l’assistenza stradale.

Viene messa a rischio la sicurezza del conducente. 

## Criticità

Come far sì che il sistema sia sempre funzionate?

 Integrare una soluzione di allarme in caso di dati non rilevati correttamente?

Come garantire la sicurezza del conducente?