# Leggere backtest, commissioni e funding

<!-- language-navigation -->
[English](../../../docs/reading-results.md) | [Français](../../fr/docs/reading-results.md) | [Deutsch](../../de/docs/reading-results.md) | [Nederlands](../../nl/docs/reading-results.md) |
[Español](../../es/docs/reading-results.md) | [Español (España)](../../es-ES/docs/reading-results.md) | [Italiano](reading-results.md) |
[Português (Portugal)](../../pt/docs/reading-results.md) | [Português (Brasil)](../../pt-BR/docs/reading-results.md) | [Polski](../../pl/docs/reading-results.md)
<!-- /language-navigation -->

Un confronto significativo parte dallo stesso strumento, dalle stesse date,
dallo stesso fuso orario, dai medesimi fondi iniziali, allocazione e ipotesi sui
costi. Paper, Shadow, riproduzione storica ed esecuzione reale non hanno dati
di ingresso o esecuzioni identici.

## Una scheda di confronto

Annota questi elementi accanto a entrambi i risultati prima di confrontare l'importo finale in dollari:

| Dato | Perché conta |
| --- | --- |
| Prodotto e direzione | I contratti BTC ed ETH non sono intercambiabili; spot e futures sono prodotti diversi |
| Inizio, fine e fuso orario | Un limite temporale diverso può includere un altro ingresso, una chiusura o un evento di funding |
| Fondi iniziali e allocazione | Una capacità diversa può cambiare il numero di contratti |
| Operazioni chiuse ed eventuale esposizione aperta | Il totale delle operazioni concluse non equivale a un conto che contiene una posizione aperta |
| Prezzi di esecuzione e commissioni | Esecuzioni simulate e reali possono differire; commissioni del conto e predefinite non sono intercambiabili |
| Copertura e segno del funding | Un accredito, un addebito, uno zero verificato e un'informazione non disponibile significano cose diverse |
| Base contabile e periodo | Una componente del saldo riportata dalla piattaforma non è automaticamente il risultato di una sessione |

## Non sottrarre due volte la stessa commissione

Calcolo puramente ipotetico: supponiamo che il PnL lordo delle operazioni chiuse
sia **+$24**, le commissioni di trading siano **$4** e il funding incluso sia un
accredito di **+$1**. Se il risultato realizzato riportato è già al netto di
tali commissioni, è **+$20**. Aggiungendo l'accredito di funding si ottiene
**+$21**. Sottrarre nuovamente i $4 significherebbe contarli due volte.

L'esempio spiega il principio di riconciliazione; non è una formula universale
per ogni schermata o estratto della piattaforma. Leggi la base dichiarata del
risultato, i costi inclusi, la copertura del funding e l'eventuale esposizione
aperta. Il funding è una componente contabile distinta e non deve necessariamente
far parte del risultato delle operazioni chiuse.

## Un dato mancante non è zero

Uno zero numerico può rappresentare uno zero noto. La copertura mancante del
funding non dimostra l'assenza di addebiti o accrediti. La riproduzione storica
usa i dati di funding disponibili e idonei; esamina i dettagli prima di confrontare
il risultato con il regolamento contabile della piattaforma. Non dedurre il funding esatto
dalla differenza tra due saldi arrotondati.

## Il drawdown non è solo la peggiore operazione

Il drawdown massimo misura un calo da un picco precedente nella serie scelta
del patrimonio del conto o del saldo. Una serie ipotetica
**$1000 -> $1030 -> $1018** presenta un calo dal picco al minimo di **$12**,
anche se termina sopra il saldo iniziale. Più operazioni in perdita possono
contribuire a un singolo drawdown.

La base di campionamento conta. Una serie basata sulle chiusure è diversa da una
valutazione continua del patrimonio che include le posizioni aperte e potrebbe
non mostrarne il minimo durante un'operazione. Usa la base descritta nei dettagli
dei risultati di Citrine; non considerare un valore basato sulle chiusure come
la massima perdita reale possibile e non presumere che gli ordini stop garantiscano
un particolare prezzo di esecuzione.

## Quando due esecuzioni differiscono

Confronta prima quantità e orari di esecuzione, poi prezzi, origine delle
commissioni, funding ed esposizione aperta. Conserva inalterate le esportazioni
originali. Per l'assistenza, descrivi la discrepanza e fornisci soltanto le
informazioni effettivamente richieste; non pubblicare esportazioni complete di conti.

[Metodologia di backtesting](https://citrineedge.com/it/backtesting/) |
[Diagnostica sicura](safe-troubleshooting.md) |
[Torna al manuale](../README.md)
