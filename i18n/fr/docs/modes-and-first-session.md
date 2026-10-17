# Modes Citrine et vérifications pour la première session

<!-- language-navigation -->
[English](../../../docs/modes-and-first-session.md) | [Français](modes-and-first-session.md) | [Deutsch](../../de/docs/modes-and-first-session.md) | [Nederlands](../../nl/docs/modes-and-first-session.md) |
[Español](../../es/docs/modes-and-first-session.md) | [Español (España)](../../es-ES/docs/modes-and-first-session.md) | [Italiano](../../it/docs/modes-and-first-session.md) |
[Português (Portugal)](../../pt/docs/modes-and-first-session.md) | [Português (Brasil)](../../pt-BR/docs/modes-and-first-session.md) | [Polski](../../pl/docs/modes-and-first-session.md)
<!-- /language-navigation -->

## Choisir les responsabilités, pas seulement le solde

| Mode | Point de départ | Envoie des ordres réels ? | Usage adapté |
| --- | --- | --- | --- |
| Paper | Un solde hypothétique de votre choix | Non | Découvrir l'espace de travail et suivre une session simulée sans importer de clé API |
| Shadow | Données d'un compte authentifié, puis session simulée propre au mode | Non | Comparer une simulation fondée sur les données du compte aux conditions du marché |
| Observation | Vue du compte réel | Non, y compris pour les clôtures manuelles ou la gestion des protections | Surveiller le compte sans faire de cet appareil un appareil d'exécution |
| Standard | Compte réel | Oui, lorsque Complete et l'accès au trading éligible sont actifs | Exécuter des entrées réelles et la gestion des positions prise en charge |

Le backtesting est une relecture historique, pas un cinquième mode de compte réel.
La démo guidée (Guided Demo) présente l'interface avec un compte d'exemple et ne
nécessite aucune opération de trading.

## Avant une session Paper

- Ouvrez **Tutoriel** depuis **Assistance** pour lancer la démo guidée si vous ne connaissez
  pas encore l'espace de travail.
- Choisissez délibérément le solde initial et l'allocation. Conservez ces valeurs
  si vous comptez comparer les sessions par la suite.
- Lisez le mode et l'état d'exécution. Un graphique affiché ne signifie pas à lui
  seul qu'une session fonctionne ou que les conditions d'une entrée sont réunies.
- Consultez les détails Edge, les détails du résultat et leurs explications,
  plutôt que d'interpréter un seul nombre hors contexte.
- Conservez les dates, le mode et l'export de la session pour les comparaisons.

## Avant l'utilisation avec un compte connecté

- Vérifiez que vous utilisez un compte Coinbase Advanced éligible pour les contrats
  perpétuels BTC et ETH pris en charge de Coinbase Derivatives Exchange (CDE),
  et non des produits au comptant ou de Coinbase International Exchange (INTX).
- Vérifiez la [disponibilité actuelle par pays](https://citrineedge.com/fr/availability/)
  avant de connecter un compte. Au Canada, l'accès est limité aux comptes remplissant
  les conditions dans les provinces ou territoires pris en charge.
- Suivez la [configuration actuelle de la clé](https://citrineedge.com/fr/coinbase-api-setup/).
  Importez les identifiants dans l'application, jamais dans un ticket, un message
  ou un formulaire d'assistance.
- L'autorisation View permet l'accès au compte. Le trading réel nécessite aussi
  Trade. Citrine n'a pas besoin des autorisations Transfer, Receive ou de retrait.
- Vérifiez la validation, le mode sélectionné, l'allocation, les fonds disponibles,
  la capacité et tout état nécessitant votre attention. Une condition Edge indiquée
  comme prête ne garantit pas qu'un ordre sera envoyé immédiatement.
- Gardez l'appareil Android alimenté, connecté et configuré pour le fonctionnement
  de l'application en arrière-plan. Un appareil dédié est une option, pas une obligation.
- Gardez un accès direct à Coinbase pour vérifier le compte ou agir en urgence.

## Pause et quitter sont deux actions différentes

**Suspendre le trading** suspend les nouvelles entrées ; la gestion des positions réelles prise
en charge peut continuer. **Quitter Citrine** arrête l'exécution locale. Cette action
ne clôture pas automatiquement les positions ouvertes et n'annule pas les ordres
existants sur la plateforme d'échange.

Une protection acceptée et hébergée par Coinbase est différente de la gestion sur
l'appareil. Observation ne gère pas les protections. Après une interruption,
vérifiez l'état réel de l'exécution et de la plateforme d'échange sans supposer
que le trading a repris.

[Guide produit complet](https://citrineedge.com/fr/guide/) |
[Responsabilités de sécurité](https://citrineedge.com/fr/security/) |
[Retour au manuel](../README.md)
