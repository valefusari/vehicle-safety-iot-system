# Corretto uso del dispositivo - esito negativo

SC: 4
Attori coinvolti: Conducente del veicolo   (../Attori%20coinvolti%20nel%20sistema/Conducente%20del%20veicolo%2019a1100dcfbd819996a8c51584c9ffde.md)
Servizi associati: Misurazione del tasso alcolemico  (../Requisiti%20Funzionali/Misurazione%20del%20tasso%20alcolemico%2019a1100dcfbd81478aa7f117bfc0bce8.md), Misurazione di sostanze stupefacenti  (../Requisiti%20Funzionali/Misurazione%20di%20sostanze%20stupefacenti%2019a1100dcfbd8100bf0dfc27fcb71188.md), Controllo misurazione (../Requisiti%20Funzionali/Controllo%20misurazione%2019a1100dcfbd8168a563ed39b9a87fcc.md)
Tipo: Normale

## Precondizione

Il conducente deve aver installato i sensori sulla macchina 

Il conducente ha inserito la chiave nel quadro e il veicolo è pronto per l’avvio.

## Flusso di eventi

Il conducente soffia nell’etilometro e misura il livello di sostanze stupefacenti tramite i sensori a saliva.

Il sistema misura il livello di alcol e di sostanze stupefacenti.
Il sistema confronta il risultato con il limite legale.

Il livello è sotto il limite e il sistema consente l’avvio del veicolo.

## Cosa può andare storto

Uno dei sensori (etilometro o saliva) installati non funzionano impedendo l’avvio del veicolo.

## Criticità

Integrare una soluzione di allarme in caso di dati non rilevati correttamente ?

Come far intervenire il prima possibile la sicurezza stradale?