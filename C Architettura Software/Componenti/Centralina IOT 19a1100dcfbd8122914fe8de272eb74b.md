# Centralina IOT

ID Componente: 5
Requisiti Funzionali: Connettività e Segnalazione in tempo reale (../../B%20Analisi%20dei%20Requisiti/Requisiti%20Funzionali/Connettivit%C3%A0%20e%20Segnalazione%20in%20tempo%20reale%2019a1100dcfbd81b09db3cfb166eabfa3.md), Visualizzazione storico delle segnalazioni (../../B%20Analisi%20dei%20Requisiti/Requisiti%20Funzionali/Visualizzazione%20storico%20delle%20segnalazioni%2019a1100dcfbd8157b9eef30462da37e6.md)
Requisiti Non Funzionali: Bassa Latenza  (../../B%20Analisi%20dei%20Requisiti/Requisiti%20Non%20Funzionali/Bassa%20Latenza%2019a1100dcfbd81af842beff3d9394ae4.md), Affidabilità (../../B%20Analisi%20dei%20Requisiti/Requisiti%20Non%20Funzionali/Affidabilit%C3%A0%2019a1100dcfbd8176aa89ef8953ad5813.md), Fault Tollerance (fail safe) (../../B%20Analisi%20dei%20Requisiti/Requisiti%20Non%20Funzionali/Fault%20Tollerance%20(fail%20safe)%2019a1100dcfbd8145b207efe8c527a05d.md)

## Descrizione

### **Teltonika FMB140 con CAN adapter**

1. **GPS integrato**
    - Offre tracciamento in tempo reale.
    - Permette di localizzare il veicolo fermo con precisione.
2. **Supporto nativo al CAN bus**
    - Integra un modulo CAN che consente di leggere e inviare segnali al bus del veicolo.
    - Rileva dati come lo stato del motore, velocità, giri, e altro.
3. **Compatibilità per il blocco motore**
    - Supporta la funzionalità **Immobilizer** tramite il CAN bus, che permette di inviare un segnale per bloccare l'accensione del motore.
    - Questa funzione è configurabile e può essere attivata automaticamente (ad esempio, in caso di superamento dei limiti alcolemici) o manualmente dal gestore tramite la dashboard.
4. **Connettività affidabile**
    - Supporta reti mobili 2G/3G/4G, garantendo la trasmissione dei dati in tempo reale al sistema centrale.
5. **Batteria di backup**
    - Include una batteria interna che mantiene il dispositivo operativo in caso di interruzione dell'alimentazione principale.
6. **Integrazione con altri sensori**
    - Può essere facilmente collegato ai tuoi sensori di alcol e sostanze tramite il sistema IoT.
    - Supporta protocolli per comunicare con dispositivi aggiuntivi.

Aggiungendo anche il CAN adapter si può avere una maggiore compatibilità con più tipi di veicoli dato che i veicoli potrebbero utilizzare protocolli CAN differenti.