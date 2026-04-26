# D. Design

Last edited by: Valentina Fusari
Last edited time: February 14, 2025 4:54 PM

**Per specifiche su ciò che va riportato in tabella aprire le varie sotto-pagine!**

Questa sezione si riferisce al design del vostro sistema nelle due sfumature di design decisions e design di basso livello (class diagram).

[Design decisions](D%20Design/Design%20decisions%2019a1100dcfbd81189662ce37094cb462.csv)

---

## Class Diagram

![class_diagram.png](D%20Design/class_diagram.png)

### Descrizione del class Diagram

Il Class Diagram fornisce una rappresentazione concettuale della struttura del sistema, evidenziando le entità principali, le loro responsabilità e le relazioni che le collegano. Questo diagramma è particolarmente utile per comprendere come i dati e le funzionalità siano organizzati e condivisi nel sistema.

Il Class Diagram descrive:

- **La struttura del sistema IoT integrato nel veicolo**: include entità come i sensori (es. etilometro, sensore di saliva), la centralina IoT per l’elaborazione locale, e il server centrale per l'archiviazione e la gestione delle segnalazioni.
- **Le relazioni tra componenti principali**: il diagramma mostra le associazioni tra sensori, centralina e server, che insieme realizzano il flusso completo dalla raccolta dei dati all'invio delle notifiche.
- **L’orientamento alla modularità**: l'uso di ereditarietà e associazioni permette di rappresentare un sistema estensibile, dove è possibile aggiungere nuovi tipi di sensori o funzioni senza modificare la struttura complessiva.

Questo diagramma si concentra sull’aspetto logico del sistema, descrivendo **le entità software** (classi) e i loro comportamenti principali.

[Classi](D%20Design/Classi%2019a1100dcfbd8194af87c48fef863b8f.csv)