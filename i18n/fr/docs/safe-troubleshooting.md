# Diagnostic sûr pour le trading sur l'appareil

<!-- language-navigation -->
[English](../../../docs/safe-troubleshooting.md) | [Français](safe-troubleshooting.md) | [Deutsch](../../de/docs/safe-troubleshooting.md) | [Nederlands](../../nl/docs/safe-troubleshooting.md) |
[Español](../../es/docs/safe-troubleshooting.md) | [Español (España)](../../es-ES/docs/safe-troubleshooting.md) | [Italiano](../../it/docs/safe-troubleshooting.md) |
[Português (Portugal)](../../pt/docs/safe-troubleshooting.md) | [Português (Brasil)](../../pt-BR/docs/safe-troubleshooting.md) | [Polski](../../pl/docs/safe-troubleshooting.md)
<!-- /language-navigation -->

Un signalement clair est plus utile qu'un export intégral du compte. Consignez
le comportement avant de modifier les paramètres ou de réinstaller l'application,
car cela peut supprimer des éléments de diagnostic locaux utiles.

## Champs utiles pour un signalement

```text
Version/build de l'application :
Version Android et modèle de l'appareil :
Mode et état d'exécution :
Heure approximative de l'événement et fuseau horaire :
Écran ou action :
Comportement attendu :
Comportement observé :
Reproductible ? Si oui, étapes minimales :
Texte d'erreur éventuel, sans identifiants de compte :
```

N'incluez pas de clés API, de clés privées, de phrases de récupération, de jetons
d'accès, de jetons d'achat Google Play, de documents bancaires ou fiscaux, ni
d'identifiants complets d'ordres de la plateforme d'échange. Masquez les noms de
compte, les soldes et le contenu des notifications sur les captures publiques
lorsqu'ils ne sont pas nécessaires. Vérifiez les exports avant de les partager ;
un fichier JSON n'est pas anonyme simplement parce qu'il ne ressemble pas à une photo.

## Observer d'abord

- Distinguez un affichage encore en cours de chargement d'un zéro confirmé, d'une
  donnée indisponible ou d'une exécution en pause. Notez l'état exact sans le paraphraser.
- Indiquez si la position a été ouverte à l'extérieur ou par l'application et quel
  appareil la gérait. Observation sert à surveiller, pas à contrôler l'exécution.
- Vérifiez directement sur Coinbase si la question concerne un ordre ou une position
  réels. Ne répétez pas une action sur un ordre simplement parce que l'affichage tarde.
- Notez la connectivité, les redémarrages, les changements d'exécution en arrière-plan
  et l'heure des mises à jour. Ce sont des indices de diagnostic, pas une preuve de cause.
- Ne passez pas d'opérations uniquement pour reproduire un problème d'interface.
  Commencez si possible avec Paper ou une reproduction sans trading.

## Où l'envoyer

Utilisez [l'assistance Citrine](https://citrineedge.com/fr/support/) pour une aide
liée à votre compte. Le dépôt public sert aux corrections du manuel, pas à
l'assistance privée au trading. Consultez le [signalement de sécurité](../SECURITY.md)
pour les vulnérabilités présumées. Ne publiez jamais d'identifiants, même si un
compte non vérifié vous les demande.

[Retour au manuel](../README.md)
