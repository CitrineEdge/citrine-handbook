# Citrine-modi en checklist voor de eerste sessie

<!-- language-navigation -->
[English](../../../docs/modes-and-first-session.md) | [Français](../../fr/docs/modes-and-first-session.md) | [Deutsch](../../de/docs/modes-and-first-session.md) | [Nederlands](modes-and-first-session.md) |
[Español](../../es/docs/modes-and-first-session.md) | [Español (España)](../../es-ES/docs/modes-and-first-session.md) | [Italiano](../../it/docs/modes-and-first-session.md) |
[Português (Portugal)](../../pt/docs/modes-and-first-session.md) | [Português (Brasil)](../../pt-BR/docs/modes-and-first-session.md) | [Polski](../../pl/docs/modes-and-first-session.md)
<!-- /language-navigation -->

## Kies de verantwoordelijkheid, niet alleen het saldo

| Modus | Uitgangspunt | Verstuurt echte orders? | Geschikt gebruik |
| --- | --- | --- | --- |
| Paper | Een hypothetisch saldo dat u kiest | Nee | De werkomgeving leren kennen en een gesimuleerde sessie volgen zonder API-sleutel te importeren |
| Shadow | Gegevens van een geauthenticeerd account, gevolgd door een eigen gesimuleerde sessie | Nee | Een simulatie met accountgegevens vergelijken met de marktomstandigheden |
| Observation | Weergave van het echte account | Nee, ook geen handmatige sluitingen of beheer van bescherming | Het account volgen zonder dit apparaat orders te laten uitvoeren |
| Standard | Echt account | Ja, wanneer Complete en toegestane handelstoegang actief zijn | Echte instappen en toegestaan positiebeheer uitvoeren |

In de portfoliodetails staan Standard en Observation als **Standaard** en
**Observatie**; de modusschakelaar heet **Modus Observation**.

Backtesting is een historische simulatie, geen vijfde modus voor een echt account.
De begeleide demo (Guided Demo) introduceert de interface met een voorbeeldaccount
en vereist geen transactie.

## Vóór een Paper-sessie

- Open **Handleiding** via **Ondersteuning** om de begeleide demo te starten als de werkomgeving
  nog onbekend is.
- Kies bewust een beginsaldo en toewijzing. Houd die waarden aan als u later
  sessies wilt vergelijken.
- Lees de modus en uitvoeringsstatus. Alleen een zichtbare grafiek betekent
  niet dat een sessie draait of dat aan de instapvoorwaarden is voldaan.
- Bekijk de Edge-details, resultaatdetails en bijbehorende uitleg in plaats
  van één getal zonder context te interpreteren.
- Bewaar de datums, modus en export van de sessie voor vergelijkingen.

## Vóór gebruik met een verbonden account

- Controleer of u een toegelaten Coinbase Advanced-account gebruikt voor
  ondersteunde BTC- en ETH-perpetualcontracten van Coinbase Derivatives Exchange
  (CDE), niet voor spotproducten of producten van Coinbase International Exchange (INTX).
- Controleer de [actuele beschikbaarheid per land](https://citrineedge.com/nl/availability/)
  voordat u een account verbindt. In Canada is toegang beperkt tot accounts die
  aan de voorwaarden voldoen in ondersteunde provincies of territoria.
- Volg de [actuele sleutelinstructies](https://citrineedge.com/nl/coinbase-api-setup/).
  Importeer inloggegevens in de app, nooit in een issue, bericht of ondersteuningsformulier.
- De machtiging View biedt accounttoegang. Voor echte handel is ook Trade nodig.
  Citrine heeft geen machtigingen voor Transfer, Receive of opnames nodig.
- Controleer validatie, geselecteerde modus, toewijzing, beschikbare middelen,
  capaciteit en statussen die aandacht vragen. Een Edge-voorwaarde die als gereed
  staat, belooft niet dat er onmiddellijk een order wordt verstuurd.
- Houd het Android-apparaat van stroom voorzien, verbonden en ingesteld op
  achtergrondwerking van de app. Een extra apparaat is een optie, geen vereiste.
- Houd directe toegang tot Coinbase beschikbaar voor accountcontroles of urgente actie.

## Pauzeren en afsluiten zijn verschillend

**Handel pauzeren** houdt nieuwe instappen tegen; toegestaan beheer van echte posities
kan doorgaan. **Citrine afsluiten** stopt de lokale uitvoering. Het sluit open posities
niet automatisch en annuleert geen bestaande beursorders.

Door Coinbase geaccepteerde en gehoste bescherming is iets anders dan beheer op
het apparaat. Observation beheert geen bescherming. Controleer na een onderbreking
de daadwerkelijke uitvoeringsstatus en beursstatus in plaats van aan te nemen
dat de handel is hervat.

[Volledige producthandleiding](https://citrineedge.com/nl/guide/) |
[Beveiligingsverantwoordelijkheden](https://citrineedge.com/nl/security/) |
[Terug naar het handboek](../README.md)
