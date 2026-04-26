# Sviluppo del sistema di blocco del veicolo

ID task: 6
Date di inizio e fine reali: December 9, 2024
Date di inizio e fine stimate: January 6, 2025
Importanza: Alta
Priorità: Alta
Status: Done
Durata: 1 settimana 
Predecessori: Sviluppo del modulo del rilevamento delle sostanze stupefacenti, sviluppo del modulo di rilevamento delle sostanze alcoliche 
Responsabili: Chafry Kawtar, Valentina Fusari, Jacopo Pio

## Descrizione

1. **Sviluppo software per l'acquisizione dati nella centralina IOT**:
    - Scrivere il codice per acquisire i dati grezzi dai sensori.
    - Eventualmente, implementare algoritmi per rilevare la presenza di sostanze con maggiore precisione (se il sensore non elabora tutto in autonomia).
2. **Sviluppo software per l’elaborazione dei dati nella centralina IOT**:
- Scrivere il codice che permette di calibrare le soglie massime di misurazione.
- Scrivere il codice che confronta i dati ottenuti con i limiti legali impostati
1.  **Sviluppo software per il blocco del veicolo nella centralina IOT (invio del segnale tramite CAN bus).**