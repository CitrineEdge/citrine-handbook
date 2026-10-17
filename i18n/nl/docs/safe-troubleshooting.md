# Veilig problemen onderzoeken bij handel op het apparaat

<!-- language-navigation -->
[English](../../../docs/safe-troubleshooting.md) | [Français](../../fr/docs/safe-troubleshooting.md) | [Deutsch](../../de/docs/safe-troubleshooting.md) | [Nederlands](safe-troubleshooting.md) |
[Español](../../es/docs/safe-troubleshooting.md) | [Español (España)](../../es-ES/docs/safe-troubleshooting.md) | [Italiano](../../it/docs/safe-troubleshooting.md) |
[Português (Portugal)](../../pt/docs/safe-troubleshooting.md) | [Português (Brasil)](../../pt-BR/docs/safe-troubleshooting.md) | [Polski](../../pl/docs/safe-troubleshooting.md)
<!-- /language-navigation -->

Een duidelijke melding is nuttiger dan een volledige accountdump. Leg het gedrag
vast voordat u instellingen wijzigt of de app opnieuw installeert; daarmee kan
bruikbaar lokaal bewijsmateriaal verdwijnen.

## Nuttige velden voor een melding

```text
Appversie/build:
Android-versie en apparaatmodel:
Modus en uitvoeringsstatus:
Geschatte tijd van de gebeurtenis en tijdzone:
Scherm of actie:
Verwacht gedrag:
Waargenomen gedrag:
Herhaalbaar? Zo ja, de kortste stappen:
Eventuele fouttekst, zonder accountidentificatie:
```

Voeg geen API-sleutels, privésleutels, herstelzinnen, toegangstokens,
Google Play-aankooptokens, bank-/belastinggegevens of volledige
beursorderidentificaties toe. Maak accountnamen, saldi en meldingsinhoud
onleesbaar op openbare schermafbeeldingen wanneer die niet nodig zijn. Controleer
exports voor het delen; een JSON-bestand is niet anoniem alleen omdat het niet
op een foto lijkt.

## Eerst observeren

- Onderscheid een nog ladende weergave van een bevestigde nul, niet-beschikbare
  invoer of gepauzeerde uitvoering. Leg de exacte status vast in plaats van die
  te parafraseren.
- Noteer of een positie extern of door de app is geopend en welk apparaat die
  beheerde. Observation is voor monitoring, niet voor het aansturen van uitvoering.
- Controleer Coinbase rechtstreeks bij vragen over een echte order of positie.
  Druk niet herhaaldelijk op een orderactie alleen omdat de weergave vertraagd is.
- Noteer verbinding, herstarts, wijzigingen in achtergrondwerking en het tijdstip
  van app-updates. Dit zijn aanwijzingen voor diagnose, geen bewijs van een oorzaak.
- Plaats geen transacties uitsluitend om een interfaceprobleem te reproduceren.
  Begin waar mogelijk met Paper of een reproductie zonder handel.

## Waarheen sturen?

Gebruik [Citrine-ondersteuning](https://citrineedge.com/nl/support/) voor
accountspecifieke hulp. De openbare documentatierepository is voor correcties
aan het handboek, niet voor privéondersteuning bij handel. Zie
[Beveiligingsmeldingen](../SECURITY.md) voor vermoedelijke kwetsbaarheden.
Plaats nooit inloggegevens openbaar, zelfs niet als een ongeverifieerd account
erom vraagt.

[Terug naar het handboek](../README.md)
