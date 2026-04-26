# Corretto uso del dispositivo e intervento dell’assistenza stradale e forze dell’ordine - esito positivo

SC: 5
Attori coinvolti: Gestore delle segnalazioni  (../Attori%20coinvolti%20nel%20sistema/Gestore%20delle%20segnalazioni%2019a1100dcfbd81f8a69ee2817fe5d4f9.md), Assistenza stradale (../Attori%20coinvolti%20nel%20sistema/Assistenza%20stradale%2019a1100dcfbd8134b3ffee46388e2e1e.md), Conducente del veicolo   (../Attori%20coinvolti%20nel%20sistema/Conducente%20del%20veicolo%2019a1100dcfbd819996a8c51584c9ffde.md), Forze dell’ordine (../Attori%20coinvolti%20nel%20sistema/Forze%20dell%E2%80%99ordine%2019a1100dcfbd8127b193c3b8ccd1e849.md)
Servizi associati: Misurazione del tasso alcolemico  (../Requisiti%20Funzionali/Misurazione%20del%20tasso%20alcolemico%2019a1100dcfbd81478aa7f117bfc0bce8.md), Connettività e Segnalazione in tempo reale (../Requisiti%20Funzionali/Connettivit%C3%A0%20e%20Segnalazione%20in%20tempo%20reale%2019a1100dcfbd81b09db3cfb166eabfa3.md), Misurazione di sostanze stupefacenti  (../Requisiti%20Funzionali/Misurazione%20di%20sostanze%20stupefacenti%2019a1100dcfbd8100bf0dfc27fcb71188.md), Blocco dell’avvio del veicolo  (../Requisiti%20Funzionali/Blocco%20dell%E2%80%99avvio%20del%20veicolo%2019a1100dcfbd816d8568c80ceac15f92.md), Controllo misurazione (../Requisiti%20Funzionali/Controllo%20misurazione%2019a1100dcfbd8168a563ed39b9a87fcc.md), Visualizzazione delle segnalazioni (../Requisiti%20Funzionali/Visualizzazione%20delle%20segnalazioni%2019a1100dcfbd81b6b91ff33b7e840ca4.md)
Tipo: Normale

## Precondizione

Il conducente deve aver installato i sensori sulla macchina 

Il conducente ha inserito la chiave nel quadro e il veicolo è pronto per l’avvio.

Il gestore deve aver ricevuto le credenziali di accesso alla dashboard

## Flusso di eventi

Il conducente soffia nell’etilometro e misura il livello di sostanze stupefacenti tramite i sensori a saliva.

Il sistema misura il livello di alcol e di sostanze stupefacenti.
Il sistema confronta il risultato con il limite legale.

Il livello è sopra il limite, il sistema non consente l’avvio del veicolo.

Il sistema invia una segnalazione al gestore che contatterà l’assistenza stradale e le forze dell’ordine

## Cosa può andare storto

Uno dei sensori (etilometro o saliva) installati non funzionano impedendo l’avvio del veicolo.

Il gestore non riesce a contattare l’assistenza stradale e le forze dell’ordine.

Il gestore non riesce a visualizzare le segnalazioni dei sensori.

## Criticità

come far intervenire il prima possibile la sicurezza stradale?

Integrare una soluzione di allarme in caso di dati non rilevati correttamente ?

Come assicurarsi che la segnalazione arrivi al gestore ?