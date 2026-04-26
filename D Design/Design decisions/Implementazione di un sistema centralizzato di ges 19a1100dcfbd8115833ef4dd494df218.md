# Implementazione di un sistema centralizzato di gestione

ID Design decision: 4

## Descrizione

Decisione: Includere un sistema centrale con dashboard per la gestione delle segnalazioni e delle analisi.

La soluzione prevede l'integrazione di una dashboard centralizzata che consente al gestore di monitorare in tempo reale i dati inviati dalla centralina IoT e dai sensori, visualizzare le segnalazioni di allerta (come l'eccesso di alcol o sostanze stupefacenti nel conducente) e intervenire tempestivamente. In caso di superamento del limite legale, il gestore potrà contattare l'assistenza stradale, che grazie al segnale GPS inviato dalla centralina, sarà in grado di localizzare rapidamente il veicolo e intervenire.

## Alternative vagliate

Un'alternativa sarebbe stata un sistema che si limita al solo rilevamento delle sostanze stupefacenti e del tasso alcolemico, con l'eventuale blocco dell'avvio del veicolo in caso di risultati positivi. Sebbene questa soluzione possa sembrare più semplice da implementare e monitorare, presenta diversi svantaggi:

1. **Limitato intervento in caso di emergenza**: Senza l'invio delle segnalazioni a una dashboard centralizzata, in caso di superamento dei limiti legali, il conducente potrebbe trovarsi intrappolato all'interno del veicolo senza la possibilità di ricevere assistenza immediata. Questo potrebbe rappresentare un rischio significativo, soprattutto in situazioni di emergenza.
2. **Mancanza di monitoraggio remoto**: In assenza di una dashboard, il sistema non consente un monitoraggio continuo e remoto dei dati, limitando la capacità di intervenire tempestivamente.