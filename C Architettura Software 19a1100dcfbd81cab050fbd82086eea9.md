# C. Architettura Software

Last edited by: Valentina Fusari
Last edited time: February 14, 2025 4:54 PM

*Riportare qui la struttura statica e dinamica del vostro sistema in termini di component, sequence e state diagrams.*

**Per specifiche su ciò che va riportato in tabella aprire le varie sotto-pagine!**

## Component Diagram

![Component_Diagram.png](C%20Architettura%20Software/Component_Diagram.png)

### Descrizione del component

### **1. Veicolo**

All'interno del veicolo troviamo i seguenti elementi:

- **UI Etilometro e UI Sensore a Saliva** (COTS)
    - Interfacce utente per la misurazione.
- **Etilometro e Sensore a Saliva** (COTS)
    - Dispositivi che effettuano la misurazione dei parametri del conducente.
    - Comunicano tramite un **gateway CAN** con la rete del veicolo.
- **CAN Bus (External Component)**
    - Componente di comunicazione che trasferisce i dati tra i sensori, la **Centralina IoT**, e la **Centralina del Veicolo**.
    - Differenti protocolli CAN sono utilizzati per:
        - Invio dati dei sensori alla centralina.
        - Invio del segnale di avvio/blocco motore alla centralina del veicolo.
- **Centralina IoT (COTS)**
    - Riceve i dati dei sensori e li elabora.
    - Comunica con il sistema centrale tramite **HTTP** per inviare segnalazioni e dati rilevanti.

---

### **2. Sistema Centrale**

Situato fuori dal veicolo, riceve ed elabora i dati:

- **Server Centrale**
    - Archivia ed elabora i dati ricevuti dai sensori.
- **Dashboard**
    - Interfaccia utente per la visualizzazione dei dati e delle segnalazioni.

---

### **Flusso dei Dati**

1. Il conducente effettua una misurazione tramite etilometro o sensore a saliva.
2. I dati vengono inviati tramite gateway CAN alla **Centralina IoT** attraverso il **CAN Bus**.
3. La **Centralina IoT** analizza i dati e decide:
    - Se i valori sono sotto la soglia → Invia un segnale di avvio motore alla **Centralina del Veicolo**.
    - Se i valori superano la soglia → Blocca il motore e invia un alert al **Sistema Centrale**.
4. Il **Sistema Centrale** aggiorna la **Dashboard**, consentendo al gestore di visualizzare eventuali anomalie.

[Componenti](C%20Architettura%20Software/Componenti%2019a1100dcfbd81d9a843cbc1eabaaa60.csv)

---

[Sequence Diagrams](C%20Architettura%20Software/Sequence%20Diagrams%2019a1100dcfbd81669667fc237c5f60d0.csv)

# State Diagram (sensore)

![Sensori_state.png](C%20Architettura%20Software/Sensori_state.png)

# State Diagram (centralina IOT)

![State_centralina.drawio.png](C%20Architettura%20Software/State_centralina.drawio.png)