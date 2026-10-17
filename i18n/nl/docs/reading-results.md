# Backtests, kosten en funding lezen

<!-- language-navigation -->
[English](../../../docs/reading-results.md) | [Français](../../fr/docs/reading-results.md) | [Deutsch](../../de/docs/reading-results.md) | [Nederlands](reading-results.md) |
[Español](../../es/docs/reading-results.md) | [Español (España)](../../es-ES/docs/reading-results.md) | [Italiano](../../it/docs/reading-results.md) |
[Português (Portugal)](../../pt/docs/reading-results.md) | [Português (Brasil)](../../pt-BR/docs/reading-results.md) | [Polski](../../pl/docs/reading-results.md)
<!-- /language-navigation -->

Een zinvolle vergelijking begint met hetzelfde instrument, dezelfde datums,
tijdzone, beginmiddelen, toewijzing en kostenaannames. Paper, Shadow, historische
simulaties en echte uitvoering hebben geen identieke invoer of uitvoeringen.

## Een vergelijkingsblad

Noteer dit bij beide resultaten voordat u een eindbedrag in dollars vergelijkt:

| Invoer | Waarom dit belangrijk is |
| --- | --- |
| Product en richting | BTC- en ETH-contracten zijn niet uitwisselbaar; spot en futures zijn verschillende producten |
| Begin-/eindtijd en tijdzone | Een andere grens kan een extra instap, sluiting of fundingmoment omvatten |
| Beginmiddelen en toewijzing | Andere capaciteit kan het aantal contracten veranderen |
| Gesloten transacties en eventuele open blootstelling | Het totaal van afgeronde transacties is niet hetzelfde als een account met een open positie |
| Uitvoeringsprijzen en kosten | Gesimuleerde en echte uitvoeringen kunnen verschillen; accountkosten en standaardkosten zijn niet uitwisselbaar |
| Fundingdekking en teken | Een bijschrijving, afschrijving, geverifieerde nul en niet-beschikbare informatie betekenen verschillende dingen |
| Boekhoudkundige grondslag en periode | Een door de beurs gerapporteerde saldocomponent is niet automatisch het resultaat van één sessie |

## Trek dezelfde kosten niet tweemaal af

Uitsluitend hypothetische rekenkunde: stel dat de bruto-PnL van gesloten transacties
**+$24** is, de handelskosten **$4** zijn en de inbegrepen funding een bijschrijving
van **+$1** is. Als het gerapporteerde gerealiseerde handelsresultaat al netto na
die kosten is, bedraagt het **+$20**. Met de fundingbijschrijving wordt dat
**+$21**. De $4 nogmaals aftrekken zou dubbel tellen.

Dit voorbeeld legt het afstemmingsprincipe uit; het is geen universele formule
voor elk scherm of beursoverzicht. Lees de vermelde grondslag, inbegrepen kosten,
fundingdekking en eventuele open blootstelling. Funding is een eigen
boekhoudkundige component en hoeft geen deel uit te maken van het resultaat van
gesloten transacties.

## Ontbrekend is niet nul

Een numerieke nul kan een bekende nul weergeven. Ontbrekende fundingdekking
bewijst niet dat er geen afschrijving of bijschrijving was. Historische simulaties
gebruiken beschikbare fundinggegevens die aan de voorwaarden voldoen; bekijk de
resultaatdetails voordat u met de beursafrekening vergelijkt. Leid geen exacte
funding af uit het verschil tussen twee afgeronde saldi.

## Drawdown is niet alleen de slechtste transactie

Maximale drawdown meet een daling vanaf een eerdere piek in de geselecteerde
reeks van accountvermogen of saldo. Een hypothetische reeks
**$1000 -> $1030 -> $1018** heeft een daling van piek naar dal van **$12**,
hoewel de eindwaarde boven het beginsaldo ligt. Meerdere verliesgevende
transacties kunnen bijdragen aan één drawdown.

De meetbasis is belangrijk. Een reeks op basis van sluitingen verschilt van
doorlopend gewaardeerd accountvermogen met open posities en toont mogelijk niet
het dieptepunt tijdens een transactie. Gebruik de basis die in de
Citrine-resultaatdetails staat. Beschouw een op sluitingen gebaseerd getal niet
als het grootst mogelijke echte verlies en neem niet aan dat stoporders een
bepaalde uitvoeringsprijs garanderen.

## Wanneer twee uitvoeringen verschillen

Vergelijk eerst aantallen en uitvoeringstijdstippen, daarna prijzen, herkomst van
kosten, funding en open blootstelling. Bewaar de oorspronkelijke exports ongewijzigd.
Beschrijf voor ondersteuning het verschil en verstrek alleen daadwerkelijk
gevraagde informatie; plaats geen volledige accountexports openbaar.

[Backtestmethodologie](https://citrineedge.com/nl/backtesting/) |
[Veilig problemen onderzoeken](safe-troubleshooting.md) |
[Terug naar het handboek](../README.md)
