# Diagnostica sicura per il trading sul dispositivo

<!-- language-navigation -->
[English](../../../docs/safe-troubleshooting.md) | [Français](../../fr/docs/safe-troubleshooting.md) | [Deutsch](../../de/docs/safe-troubleshooting.md) | [Nederlands](../../nl/docs/safe-troubleshooting.md) |
[Español](../../es/docs/safe-troubleshooting.md) | [Español (España)](../../es-ES/docs/safe-troubleshooting.md) | [Italiano](safe-troubleshooting.md) |
[Português (Portugal)](../../pt/docs/safe-troubleshooting.md) | [Português (Brasil)](../../pt-BR/docs/safe-troubleshooting.md) | [Polski](../../pl/docs/safe-troubleshooting.md)
<!-- /language-navigation -->

Una segnalazione chiara è più utile di un dump completo del conto. Registra il
comportamento prima di cambiare le impostazioni o reinstallare l'app, operazioni
che possono eliminare prove locali utili.

## Campi utili della segnalazione

```text
Versione/build dell'app:
Versione Android e modello del dispositivo:
Modalità e stato di esecuzione:
Ora approssimativa dell'evento e fuso orario:
Schermata o azione:
Comportamento previsto:
Comportamento osservato:
È ripetibile? Se sì, passaggi minimi:
Eventuale testo di errore, senza identificativi del conto:
```

Non includere chiavi API, chiavi private, frasi di recupero, token di accesso,
token di acquisto Google Play, documenti bancari o fiscali o identificativi
completi degli ordini sulla piattaforma. Oscura nomi dei conti, saldi e contenuti
delle notifiche nelle schermate pubbliche quando non sono necessari. Controlla
le esportazioni prima di condividerle; un file JSON non è anonimo solo perché
non assomiglia a una fotografia.

## Prima osserva

- Distingui una schermata ancora in caricamento da uno zero confermato, un dato
  non disponibile o un'esecuzione in pausa. Riporta lo stato esatto senza parafrasarlo.
- Annota se una posizione è stata aperta esternamente o dall'app e quale
  dispositivo la gestiva. Observation monitora, non controlla l'esecuzione.
- Controlla direttamente Coinbase per domande su ordini o posizioni reali.
  Non ripetere un'azione sull'ordine solo perché la visualizzazione è in ritardo.
- Annota connettività, riavvii, modifiche al funzionamento in background e orario
  degli aggiornamenti. Sono indizi diagnostici, non prove di una causa.
- Non effettuare operazioni soltanto per riprodurre un problema dell'interfaccia.
  Inizia con Paper o una riproduzione senza trading, quando possibile.

## Dove inviarla

Usa l'[assistenza Citrine](https://citrineedge.com/it/support/) per aiuto specifico
sul conto. Il repository pubblico della documentazione serve per correggere il
manuale, non per l'assistenza privata al trading. Vedi
[Segnalazioni di sicurezza](../SECURITY.md) per sospette vulnerabilità.
Non pubblicare mai credenziali, nemmeno se richieste da un account non verificato.

[Torna al manuale](../README.md)
