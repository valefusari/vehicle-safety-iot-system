# Alert (Astratta)

ID Classe: 7
Requisiti Funzionali: Connettività e Segnalazione in tempo reale (../../B%20Analisi%20dei%20Requisiti/Requisiti%20Funzionali/Connettivit%C3%A0%20e%20Segnalazione%20in%20tempo%20reale%2019a1100dcfbd81b09db3cfb166eabfa3.md)

## Descrizione

Classe astratta che contiene le informazioni sugli alert. 

Il metodo astratto getTipoAlert() indica se l’alert è dovuto al malfunzionamento dei sensori o della centralina oppure al superamento dei livelli di alcol consentiti e/o alla presenza di sostanze stupefacenti. In base al valore restituito da questo metodo la descrizione dell’alert cambierà.