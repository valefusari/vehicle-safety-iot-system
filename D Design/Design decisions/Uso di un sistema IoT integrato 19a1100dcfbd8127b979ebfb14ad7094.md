# Uso di un sistema IoT integrato

ID Design decision: 2

## Descrizione

### **Uso di un sistema IoT integrato**

- **Decisione:** È stata scelta la centralina **Teltonika FMB140 con CAN Adapter**.
- **Motivazione:**
    - Supporto nativo al **CAN Bus** per la comunicazione con i sensori Dräger (Interlock 7000 e DrugTest 5000).
    - Possibilità di **blocco motore** tramite invio segnale per impedire l’accensione del veicolo in caso di positività.
    - **Connettività 4G** per l'invio dei dati in tempo reale al sistema di monitoraggio.
    - Batteria di **backup** integrata per garantire continuità operativa anche in caso di perdita di alimentazione.
    - Ha un GPS integrato che aiuta il gestore a individuare la posizione del veicolo rapidamente, migliorando i tempi di intervento dell’assistenza stradale.

## Alternative vagliate

1.  Un sistema in cui i **sensori** prendevano le misurazioni, verificavano direttamente il superamento dei limiti legali e inviavano il segnale di blocco al motore o ai sistemi di gestione.

**Motivazioni per cui il sistema con la centralina IoT è più efficiente:**

1. **Centralizzazione dei Dati e Controllo**
    - La **centralina IoT** funge da **hub centralizzato** che raccoglie dati da più sensori contemporaneamente (es. alcol, droghe, parametri del veicolo).
    - Questo permette una **gestione unificata** delle informazioni e delle decisioni.
    - In un sistema diretto, ogni sensore opererebbe in modo isolato, mentre con una centralina IoT si ha una **visione completa** e centralizzata delle condizioni del veicolo.
2. **Efficienza nella Trasmissione dei Dati**
    - La centralina IoT **ottimizza** la trasmissione dei dati verso un sistema remoto o una piattaforma di monitoraggio.
    - Supporta **protocolli di comunicazione avanzati** (CAN bus) e garantisce che i dati siano inviati in **tempo reale**, in modo affidabile e sicuro.
    - Nell’alternativa diretta, i singoli sensori avrebbero bisogno di moduli di comunicazione separati, aumentando i costi e il consumo energetico.
3. **Riduzione della Complessità nei Sensori**
    - I sensori (come il Dräger Interlock 7000) si concentrano esclusivamente sulla **rilevazione dei valori**, lasciando alla centralina IoT il compito di:
        - Verificare il superamento dei **limiti legali**.
        - Prendere decisioni (es. inviare il segnale di blocco motore).
        - Trasmettere i dati a un sistema remoto.
    - Questo approccio riduce la **complessità del sensore**, diminuendo il rischio di errori e semplificando la manutenzione.
4. **Riduzione dei Costi di Implementazione a Lungo Termine**
    - Sebbene l’implementazione di una centralina IoT possa sembrare inizialmente più costosa, offre:
        - **Manutenzione centralizzata** invece di dover intervenire su ogni dispositivo separatamente.
        - Aggiornamenti software centralizzati, migliorando l’efficienza nel tempo.