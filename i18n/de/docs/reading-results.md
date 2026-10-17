# Backtests, Gebühren und Funding lesen

<!-- language-navigation -->
[English](../../../docs/reading-results.md) | [Français](../../fr/docs/reading-results.md) | [Deutsch](reading-results.md) | [Nederlands](../../nl/docs/reading-results.md) |
[Español](../../es/docs/reading-results.md) | [Español (España)](../../es-ES/docs/reading-results.md) | [Italiano](../../it/docs/reading-results.md) |
[Português (Portugal)](../../pt/docs/reading-results.md) | [Português (Brasil)](../../pt-BR/docs/reading-results.md) | [Polski](../../pl/docs/reading-results.md)
<!-- /language-navigation -->

Ein aussagekräftiger Vergleich beginnt mit demselben Instrument, Zeitraum,
derselben Zeitzone, denselben Startmitteln, derselben Zuteilung und denselben
Kostenannahmen. Paper, Shadow, historische Wiedergabe und echte Ausführung
haben keine identischen Eingaben oder Ausführungen.

## Ein Vergleichsblatt

Notieren Sie diese Angaben neben beiden Ergebnissen, bevor Sie den Endbetrag in Dollar vergleichen:

| Angabe | Warum sie wichtig ist |
| --- | --- |
| Produkt und Richtung | BTC- und ETH-Kontrakte sind nicht austauschbar; Spot und Futures sind unterschiedliche Produkte |
| Beginn, Ende und Zeitzone | Eine andere Zeitgrenze kann einen weiteren Einstieg, Ausstieg oder Funding-Vorgang einschließen |
| Startmittel und Zuteilung | Unterschiedliche Kapazität kann die Kontraktanzahl verändern |
| Geschlossene Trades und offene Risiken | Die Summe abgeschlossener Trades entspricht nicht einem Konto mit offener Position |
| Ausführungspreise und Gebühren | Simulation und echte Ausführungen können abweichen; Kontogebühren und Standardgebühren sind nicht austauschbar |
| Funding-Abdeckung und Vorzeichen | Eine Gutschrift, eine Belastung, eine bestätigte Null und nicht verfügbare Informationen bedeuten Verschiedenes |
| Rechnungsgrundlage und Zeitraum | Ein von der Börse gemeldeter Kontostandbestandteil ist nicht automatisch das Ergebnis einer Sitzung |

## Dieselbe Gebühr nicht zweimal abziehen

Nur hypothetische Arithmetik: Angenommen, das Brutto-PnL geschlossener Trades
beträgt **+$24**, die Handelsgebühren **$4** und das enthaltene Funding eine
Gutschrift von **+$1**. Ist das gemeldete realisierte Handelsergebnis bereits
nach Abzug dieser Gebühren angegeben, beträgt es **+$20**. Mit der Funding-Gutschrift
ergibt sich **+$21**. Ein erneuter Abzug der $4 würde sie doppelt berücksichtigen.

Das Beispiel erklärt das Abgleichprinzip, ist aber keine allgemeingültige Formel
für jeden Bildschirm oder Börsenbeleg. Lesen Sie die angegebene Ergebnisgrundlage,
enthaltene Kosten, Funding-Abdeckung und etwaige offene Risiken. Funding ist
ein eigener Rechnungsbestandteil und muss nicht im Ergebnis geschlossener Trades
enthalten sein.

## Fehlend ist nicht null

Eine numerische Null kann eine bekannte Null darstellen. Fehlende Funding-Abdeckung
beweist nicht, dass es keine Belastung oder Gutschrift gab. Historische Wiedergabe
nutzt geeignete verfügbare Funding-Daten; prüfen Sie die Ergebnisdetails vor dem
Vergleich mit der Börsenabrechnung. Leiten Sie kein exaktes Funding aus der
Differenz zweier gerundeter Kontostände ab.

## Drawdown ist nicht nur der schlechteste Trade

Der maximale Drawdown misst den Rückgang von einem vorherigen Höchststand der
gewählten Eigenkapital- oder Kontostandsreihe. Die hypothetische Reihe
**$1000 -> $1030 -> $1018** hat einen Rückgang vom Hoch zum Tief von **$12**,
obwohl sie über dem Ausgangskontostand endet. Mehrere Verlusttrades können zu
einem Drawdown beitragen.

Die Erfassungsgrundlage ist wichtig. Eine ausstiegsbasierte Reihe unterscheidet
sich von einer laufenden Bewertung einschließlich offener Positionen und zeigt
möglicherweise nicht deren Tief während eines Trades. Verwenden Sie die in den
Citrine-Ergebnisdetails beschriebene Grundlage. Betrachten Sie einen
ausstiegsbasierten Wert weder als größtmöglichen Echtverlust noch nehmen Sie an,
dass Stop-Orders einen bestimmten Ausführungspreis garantieren.

## Wenn zwei Läufe abweichen

Vergleichen Sie zuerst Mengen und Ausführungszeitpunkte, dann Preise,
Gebührenherkunft, Funding und offene Risiken. Bewahren Sie Originalexporte
unverändert auf. Beschreiben Sie dem Support die Abweichung und übermitteln Sie
nur die tatsächlich angeforderten Informationen; veröffentlichen Sie keine
vollständigen Kontoexporte.

[Backtesting-Methodik](https://citrineedge.com/de/backtesting/) |
[Sichere Fehlerdiagnose](safe-troubleshooting.md) |
[Zurück zum Handbuch](../README.md)
