# Citrine-Modi und Checkliste für die erste Sitzung

<!-- language-navigation -->
[English](../../../docs/modes-and-first-session.md) | [Français](../../fr/docs/modes-and-first-session.md) | [Deutsch](modes-and-first-session.md) | [Nederlands](../../nl/docs/modes-and-first-session.md) |
[Español](../../es/docs/modes-and-first-session.md) | [Español (España)](../../es-ES/docs/modes-and-first-session.md) | [Italiano](../../it/docs/modes-and-first-session.md) |
[Português (Portugal)](../../pt/docs/modes-and-first-session.md) | [Português (Brasil)](../../pt-BR/docs/modes-and-first-session.md) | [Polski](../../pl/docs/modes-and-first-session.md)
<!-- /language-navigation -->

## Zuständigkeit wählen, nicht nur den Kontostand

| Modus | Ausgangspunkt | Sendet echte Orders? | Geeigneter Einsatz |
| --- | --- | --- | --- |
| Paper | Ein frei gewählter hypothetischer Kontostand | Nein | Arbeitsbereich kennenlernen und eine simulierte Sitzung ohne importierten API-Schlüssel verfolgen |
| Shadow | Daten eines authentifizierten Kontos, anschließend eine eigene simulierte Sitzung | Nein | Eine kontobezogene Simulation mit den Marktbedingungen vergleichen |
| Observation | Ansicht des tatsächlichen Kontos | Nein, auch keine manuellen Schließungen oder Schutzverwaltung | Das Konto beobachten, ohne dieses Gerät zum Ausführungsgerät zu machen |
| Standard | Tatsächliches Konto | Ja, wenn Complete und berechtigter Handelszugang aktiv sind | Echte Einstiege und unterstützte Positionsverwaltung ausführen |

In den Portfoliodetails heißt Observation **Beobachtung**. In den Einstellungen
gibt es drei Schalter: **Modus Observation**, **Modus Shadow** und **Modus Paper**.
Standard ist der Basismodus, wenn keiner dieser Modi aktiv ist; einen eigenen
Standard-Schalter gibt es nicht.

Backtesting ist eine historische Wiedergabe, kein fünfter Echtkonto-Modus.
Die geführte Demo (Guided Demo) stellt die Oberfläche anhand eines Beispielkontos
vor und erfordert keinen Trade.

## Vor einer Paper-Sitzung

- Öffnen Sie **Anleitung** unter **Support**, um die geführte Demo zu starten, wenn Ihnen
  der Arbeitsbereich noch nicht vertraut ist.
- Wählen Sie Startkapital und Zuteilung bewusst. Behalten Sie diese Werte bei,
  wenn Sie später Sitzungen vergleichen möchten.
- Lesen Sie Modus und Laufzeitstatus. Ein sichtbares Diagramm allein bedeutet
  weder, dass eine Sitzung läuft, noch, dass die Einstiegsbedingungen erfüllt sind.
- Prüfen Sie die Edge-Details, Ergebnisdetails und zugehörigen Erklärungen,
  anstatt eine einzelne Zahl ohne Kontext zu interpretieren.
- Bewahren Sie für Vergleiche Zeitraum, Modus und Export der Sitzung auf.

## Vor der Nutzung mit verbundenem Konto

- Stellen Sie sicher, dass Sie ein berechtigtes Coinbase-Advanced-Konto für
  unterstützte BTC- und ETH-Perpetual-Kontrakte der Coinbase Derivatives Exchange
  (CDE) verwenden, keine Spotprodukte oder Produkte der Coinbase International
  Exchange (INTX).
- Prüfen Sie die [aktuelle Verfügbarkeit nach Land](https://citrineedge.com/de/availability/),
  bevor Sie ein Konto verbinden. In Kanada ist der Zugang auf berechtigte Konten
  in unterstützten Provinzen oder Territorien beschränkt.
- Folgen Sie der [aktuellen Schlüsseleinrichtung](https://citrineedge.com/de/coinbase-api-setup/).
  Importieren Sie Zugangsdaten in die App, niemals in ein Issue, eine Nachricht
  oder ein Supportformular.
- Die Berechtigung View ermöglicht Kontozugriff. Echter Handel benötigt zusätzlich
  Trade. Citrine benötigt weder Transfer noch Receive oder Auszahlungsberechtigungen.
- Prüfen Sie Validierung, gewählten Modus, Zuteilung, verfügbare Mittel, Kapazität
  und jeden Status mit Handlungsbedarf. Eine als bereit markierte Edge-Bedingung
  verspricht keine sofortige Orderübermittlung.
- Halten Sie das Android-Gerät mit Strom versorgt, verbunden und für den
  Hintergrundbetrieb der App eingerichtet. Ein zusätzliches Gerät ist optional,
  nicht vorgeschrieben.
- Halten Sie direkten Coinbase-Zugang für Kontoprüfungen oder dringende Eingriffe bereit.

## Pause und Beenden sind verschieden

**Handel pausieren** hält neue Einstiege an; die unterstützte Verwaltung echter Positionen
kann weiterlaufen. **Citrine beenden** stoppt die lokale Laufzeit. Offene Positionen
werden dadurch nicht automatisch geschlossen und bestehende Börsenorders nicht storniert.

Von Coinbase angenommener und dort gehosteter Schutz ist etwas anderes als die
Verwaltung auf dem Gerät. Observation verwaltet keinen Schutz. Prüfen Sie nach
einer Unterbrechung den tatsächlichen Laufzeit- und Börsenzustand, statt von einer
Wiederaufnahme des Handels auszugehen.

[Vollständiger Produktleitfaden](https://citrineedge.com/de/guide/) |
[Sicherheitsverantwortung](https://citrineedge.com/de/security/) |
[Zurück zum Handbuch](../README.md)
