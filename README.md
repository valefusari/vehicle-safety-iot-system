# ByteSquad_2425 (3)

## ByteSquad

## Membri del Team

| Matricola | Nome | Cognome | Email Istituzionale |  |
| --- | --- | --- | --- | --- |
| 292125 | Valentina | Fusari | valentina.fusari@student.univaq.it |  |
| 294374 | Kawtar | Chafry  | kawtar.chafry@student.univaq.it |  |
| 291630 | Jacopo Antonio | Pio | jacopoantonio.pio@student.univaq.it |  |

---

### **Progetto 3: Sistema di monitoraggio alcolico e delle sostanze per la sicurezza stradale**

Il progetto si propone di prevenire gli incidenti stradali causati dall’assunzione di alcol e sostanze stupefacenti, attraverso l’implementazione di un sistema IoT innovativo e integrato.

### **Descrizione del sistema**

Il sistema rileva i livelli di alcol e sostanze stupefacenti del conducente tramite sensori IoT specifici. Questi sensori, collegati al **CAN bus** del veicolo tramite un **CAN adapter (gateway CAN)**, trasmettono i dati alla **centralina IoT** installata nel veicolo. La centralina analizza i dati ricevuti e confronta i valori con i limiti legali:

- **Valori entro i limiti**: La centralina permette l’avvio del veicolo inviando un segnale di sblocco al sistema di accensione tramite CAN bus.
- **Valori sopra i limiti**: La centralina blocca l’avvio del veicolo e invia una segnalazione in tempo reale al **server centrale**.

### **Funzioni principali**

1. **Blocco preventivo del veicolo**:
    - In caso di superamento dei limiti, il sistema impedisce l’avvio del motore, garantendo la sicurezza del conducente e degli altri utenti della strada.
2. **Segnalazione in tempo reale**:
    - La centralina IoT è dotata di un modulo GPS integrato e comunica con il server centrale tramite rete mobile o satellitare.
    - Attraverso una **dashboard, a cui si può accedere tramite credenziali**, i gestori delle segnalazioni possono:
        - **Visualizzare segnalazioni attive** in tempo reale, con i dettagli del veicolo e dell’anomalia.
        - **Localizzare con precisione la posizione del veicolo**, grazie all’integrazione con le **API di Google Maps**, che mostrano la posizione su una mappa interattiva.
        - Contattare rapidamente le forze dell’ordine , i servizi di emergenza stradale e tecnici di installazione specializzati per garantire assistenza immediata.
        - Visualizzare lo storico delle segnalazioni
3. **Gestione dei malfunzionamenti**:
    - Qualora uno dei sensori rilevasse un malfunzionamento, il sistema invia una segnalazione al server centrale e, per precauzione, blocca comunque il veicolo. Il conducente potrà essere soccorso e i sensori sostituiti da tecnici specializzati presso centri autorizzati.
    - I tecnici si occuperanno di risolvere anche gli eventuali problemi relativi alla dashboard e alla rete IOT.
    - In caso di malfunzionamento della centralina IOT il conducente può contattare personalmente l’assistenza stradale e\o i servizi di emergenza che a loro volta contatteranno i tecnici specializzati.

### **Componenti non sviluppati internamente**

Tutti i dispositivi hardware (sensori e centralina IoT) verranno acquistati sul mercato e calibrati/configurati presso centri specializzati al momento dell’installazione tenendo conto dei limiti legali di alcool e droga di ciascun paese. Questo garantisce affidabilità e compatibilità con il sistema. I sensori andranno poi ricalibrati periodicamente ogni 12 mesi.

### **Responsabilità del conducente**

Il conducente si assume la responsabilità legale di utilizzi impropri del sistema, ad esempio nel caso in cui il test venga eseguito da un’altra persona che non presenta alterazioni.

Grazie alla combinazione di:

- **Sensori IoT avanzati**,
- **Comunicazione tramite CAN adapter e rete CAN bus**,
- **Trasmissione dati tramite rete mobile o satellitare**,
- **Modulo GPS integrato**,
- **Dashboard interattiva con integrazione delle API di Google Maps**,

il sistema garantisce un monitoraggio continuo, affidabile e sicuro, contribuendo significativamente alla riduzione degli incidenti stradali legati all’abuso di alcol e sostanze.

Il sistema verrà installato solo nelle macchine di conducenti che sono stati sorpresi con un tasso alcolemico sopra i limiti legali oppure sotto effetto di sostanze stupefacenti alla guida.

DELTA

Descrizione iniziale, Use Case Diagram( matching 1 a 1 con i requisiti funzionali) , Descrizione più dettagliate  dei requisiti funzionali, Component Diagram(correzione sintassi), Class Diagram(aggiunta di classi), inserimento prototipo con demo.

---

## Indice

[A. Analisi di Rischi](ByteSquad_2425%20(3)/A%20Analisi%20di%20Rischi%2019a1100dcfbd81c48faae5a21267acdd.md)

[B. Analisi dei Requisiti](ByteSquad_2425%20(3)/B%20Analisi%20dei%20Requisiti%2019a1100dcfbd811daf7ff0e70377d77a.md)

[C. Architettura Software](ByteSquad_2425%20(3)/C%20Architettura%20Software%2019a1100dcfbd81cab050fbd82086eea9.md)

[D. Design](ByteSquad_2425%20(3)/D%20Design%2019a1100dcfbd81c99a3dcc7db1da0b35.md)

[E. Project Planning](ByteSquad_2425%20(3)/E%20Project%20Planning%2019a1100dcfbd81edb064f1e6137632f8.md)

[F. Prototipo](ByteSquad_2425%20(3)/F%20Prototipo%2019a1100dcfbd81d2b450e558f1b48f78.md)

---

[Untitled](ByteSquad_2425%20(3)/Untitled%2019a1100dcfbd817e825fe09a74040577.csv)

[Untitled](ByteSquad_2425%20(3)/Untitled%2019a1100dcfbd811294b6fc06d08e6123.csv)
