# Sichere Fehlerdiagnose beim Trading auf dem Gerät

<!-- language-navigation -->
[English](../../../docs/safe-troubleshooting.md) | [Français](../../fr/docs/safe-troubleshooting.md) | [Deutsch](safe-troubleshooting.md) | [Nederlands](../../nl/docs/safe-troubleshooting.md) |
[Español](../../es/docs/safe-troubleshooting.md) | [Español (España)](../../es-ES/docs/safe-troubleshooting.md) | [Italiano](../../it/docs/safe-troubleshooting.md) |
[Português (Portugal)](../../pt/docs/safe-troubleshooting.md) | [Português (Brasil)](../../pt-BR/docs/safe-troubleshooting.md) | [Polski](../../pl/docs/safe-troubleshooting.md)
<!-- /language-navigation -->

Ein klarer Bericht hilft mehr als ein vollständiger Konto-Dump. Halten Sie das
Verhalten fest, bevor Sie Einstellungen ändern oder die App neu installieren.
Dabei könnten hilfreiche lokale Nachweise verloren gehen.

## Hilfreiche Berichtsangaben

```text
App-Version/Build:
Android-Version und Gerätemodell:
Modus und Laufzeitstatus:
Ungefähre Ereigniszeit und Zeitzone:
Bildschirm oder Aktion:
Erwartetes Verhalten:
Beobachtetes Verhalten:
Wiederholbar? Falls ja, die kürzesten Schritte:
Etwaiger Fehlertext ohne Kontokennungen:
```

Fügen Sie keine API-Schlüssel, privaten Schlüssel, Seed-Phrasen, Zugriffstokens,
Google-Play-Kauftokens, Bank- oder Steuerunterlagen oder vollständigen
Börsenorderkennungen bei. Schwärzen Sie Kontonamen, Kontostände und
Benachrichtigungsinhalte in öffentlichen Screenshots, soweit sie nicht nötig sind.
Prüfen Sie Exporte vor dem Teilen. Eine JSON-Datei ist nicht allein deshalb
anonym, weil sie nicht wie ein Foto aussieht.

## Zuerst beobachten

- Unterscheiden Sie eine noch ladende Anzeige von einer bestätigten Null, einer
  nicht verfügbaren Eingabe oder einer pausierten Laufzeit. Erfassen Sie den
  genauen Status statt einer Umschreibung.
- Notieren Sie, ob eine Position extern oder von der App eröffnet wurde und
  welches Gerät sie verwaltete. Observation beobachtet und steuert keine Ausführung.
- Prüfen Sie Coinbase direkt, wenn es um echte Orders oder Positionen geht.
  Wiederholen Sie keine Orderaktion nur wegen einer verzögerten Anzeige.
- Notieren Sie Verbindung, Geräteneustarts, Änderungen am Hintergrundbetrieb und
  den Zeitpunkt von App-Updates. Das sind Diagnosehinweise, keine Ursachenbeweise.
- Handeln Sie nicht nur, um einen Oberflächenfehler nachzustellen. Beginnen Sie
  möglichst mit Paper oder einer Reproduktion ohne Handel.

## Wohin senden?

Nutzen Sie für kontobezogene Hilfe den [Citrine-Support](https://citrineedge.com/de/support/).
Das öffentliche Dokumentationsrepository dient Handbuchkorrekturen, nicht privatem
Trading-Support. Bei vermuteten Schwachstellen siehe
[Sicherheitsmeldungen](../SECURITY.md). Veröffentlichen Sie niemals Zugangsdaten,
auch nicht auf Aufforderung eines nicht verifizierten Kontos.

[Zurück zum Handbuch](../README.md)
