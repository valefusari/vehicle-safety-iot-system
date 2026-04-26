# Sviluppo rete IOT

ID task: 11
Date di inizio e fine reali: November 25, 2024
Date di inizio e fine stimate: December 16, 2024
Importanza: Media
Priorità: Media
Status: Done
Durata: 3 settimane
Predecessori: Progettazione del sistema
Responsabili: Chafry Kawtar, Valentina Fusari, Jacopo Pio

## Descrizione

1. **Progettazione della centralina IoT (Teltonika FMB140)**:
    - Configurare la centralina IoT con supporto per il CAN bus per la comunicazione con i sensori.
    - Assicurarsi della connettività mobile per la trasmissione dei dati in tempo reale (2G/3G/4G).
2. **Sviluppo dell'interfaccia di comunicazione (Gateway CAN)**:
    - Implementare un modulo gateway per raccogliere i dati dai sensori non compatibili con CAN bus e inviarli alla centralina IoT tramite il bus CAN.
    - Sviluppo del codice affinché la centralina IOT possa inviare i dati al server centrale)
3. **Integrazione con la piattaforma di gestione remota**:
    - Configurare un server centrale o una piattaforma cloud per ricevere i dati dai veicoli.