# Modalità Citrine e lista di controllo della prima sessione

<!-- language-navigation -->
[English](../../../docs/modes-and-first-session.md) | [Français](../../fr/docs/modes-and-first-session.md) | [Deutsch](../../de/docs/modes-and-first-session.md) | [Nederlands](../../nl/docs/modes-and-first-session.md) |
[Español](../../es/docs/modes-and-first-session.md) | [Español (España)](../../es-ES/docs/modes-and-first-session.md) | [Italiano](modes-and-first-session.md) |
[Português (Portugal)](../../pt/docs/modes-and-first-session.md) | [Português (Brasil)](../../pt-BR/docs/modes-and-first-session.md) | [Polski](../../pl/docs/modes-and-first-session.md)
<!-- /language-navigation -->

## Scegli la responsabilità, non solo il saldo

| Modalità | Punto di partenza | Invia ordini reali? | Uso appropriato |
| --- | --- | --- | --- |
| Paper | Un saldo ipotetico scelto da te | No | Conoscere l'area di lavoro e seguire una sessione simulata senza importare una chiave API |
| Shadow | Dati di un conto autenticato, seguiti da una propria sessione simulata | No | Confrontare una simulazione basata sul conto con le condizioni di mercato |
| Observation | Vista del conto reale | No, nemmeno chiusure manuali o gestione delle protezioni | Monitorare il conto senza rendere questo dispositivo un dispositivo di esecuzione |
| Standard | Conto reale | Sì, quando Complete e l'accesso al trading idoneo sono attivi | Eseguire ingressi reali e la gestione delle posizioni consentita |

Nei dettagli del portafoglio, Observation appare come **Osservazione**. Nelle
impostazioni ci sono tre interruttori: **Modalità Observation**, **Modalità Shadow**
e **Modalità Paper**. Standard è la modalità di base quando nessuna di queste
modalità è attiva; non ha un interruttore dedicato.

Il backtesting è una riproduzione storica, non una quinta modalità per conti reali.
La demo guidata (Guided Demo) presenta l'interfaccia con un conto di esempio e
non richiede un'operazione di trading.

## Prima di una sessione Paper

- Apri **Tutorial** da **Assistenza** per avviare la demo guidata se non conosci l'area di lavoro.
- Scegli consapevolmente saldo iniziale e allocazione. Mantieni questi valori
  se intendi confrontare le sessioni in seguito.
- Leggi la modalità e lo stato di esecuzione. La sola presenza di un grafico non
  significa che una sessione sia in corso o che le condizioni per un ingresso siano soddisfatte.
- Esamina i dettagli Edge, i dettagli del risultato e le relative spiegazioni,
  anziché interpretare un unico numero fuori contesto.
- Conserva date, modalità ed esportazione della sessione per i confronti.

## Prima dell'uso con un conto collegato

- Verifica di usare un conto Coinbase Advanced idoneo per i contratti perpetui
  BTC ed ETH supportati di Coinbase Derivatives Exchange (CDE), non prodotti
  spot o prodotti di Coinbase International Exchange (INTX).
- Controlla la [disponibilità attuale per paese](https://citrineedge.com/it/availability/)
  prima di collegare un conto. In Canada l'accesso è limitato ai conti che soddisfano
  i requisiti nelle province o nei territori supportati.
- Segui la [configurazione attuale della chiave](https://citrineedge.com/it/coinbase-api-setup/).
  Importa le credenziali nell'app, mai in una segnalazione, in un messaggio o in
  un modulo di assistenza.
- Il permesso View consente l'accesso al conto. Per il trading reale serve anche
  Trade. Citrine non richiede permessi Transfer, Receive o di prelievo.
- Controlla convalida, modalità selezionata, allocazione, fondi disponibili,
  capacità e ogni stato che richiede attenzione. Una condizione Edge indicata
  come pronta non promette l'invio immediato di un ordine.
- Mantieni il dispositivo Android alimentato, connesso e configurato per il
  funzionamento dell'app in background. Un dispositivo aggiuntivo è un'opzione,
  non un requisito.
- Mantieni disponibile l'accesso diretto a Coinbase per controlli del conto o azioni urgenti.

## Pausa e uscita sono azioni diverse

**Pausa trading** sospende i nuovi ingressi; la gestione consentita delle posizioni reali
può continuare. **Esci da Citrine** arresta l'esecuzione locale. Non chiude
automaticamente le posizioni aperte né annulla gli ordini già presenti sulla piattaforma.

Le protezioni accettate e ospitate da Coinbase sono diverse dalla gestione sul
dispositivo. Observation non gestisce le protezioni. Dopo un'interruzione,
verifica lo stato effettivo dell'esecuzione e della piattaforma invece di
presumere che il trading sia ripreso.

[Guida completa al prodotto](https://citrineedge.com/it/guide/) |
[Responsabilità di sicurezza](https://citrineedge.com/it/security/) |
[Torna al manuale](../README.md)
