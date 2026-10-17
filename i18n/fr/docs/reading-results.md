# Lire les backtests, les frais et le financement (funding)

<!-- language-navigation -->
[English](../../../docs/reading-results.md) | [Français](reading-results.md) | [Deutsch](../../de/docs/reading-results.md) | [Nederlands](../../nl/docs/reading-results.md) |
[Español](../../es/docs/reading-results.md) | [Español (España)](../../es-ES/docs/reading-results.md) | [Italiano](../../it/docs/reading-results.md) |
[Português (Portugal)](../../pt/docs/reading-results.md) | [Português (Brasil)](../../pt-BR/docs/reading-results.md) | [Polski](../../pl/docs/reading-results.md)
<!-- /language-navigation -->

Une comparaison pertinente commence par un instrument, des dates, un fuseau
horaire, des fonds initiaux, une allocation et des hypothèses de coûts identiques.
Paper, Shadow, la relecture historique et l'exécution réelle n'ont ni des données
d'entrée ni des exécutions identiques.

## Une fiche de comparaison

Consignez ces éléments à côté des deux résultats avant de comparer un montant final en dollars :

| Donnée | Pourquoi elle compte |
| --- | --- |
| Produit et sens | Les contrats BTC et ETH ne sont pas interchangeables ; le comptant et les contrats à terme sont des produits différents |
| Début, fin et fuseau horaire | Une limite temporelle différente peut inclure une autre entrée, clôture ou échéance de financement |
| Fonds initiaux et allocation | Une capacité différente peut modifier le nombre de contrats |
| Opérations clôturées et exposition encore ouverte | Le total des opérations terminées n'équivaut pas à un compte contenant une position ouverte |
| Prix d'exécution et frais | La simulation et les exécutions réelles peuvent différer ; les frais du compte et les frais par défaut ne sont pas interchangeables |
| Couverture et signe du financement | Un crédit, un débit, un zéro vérifié et une information indisponible ont des significations différentes |
| Base comptable et période | Un élément de solde déclaré par la plateforme d'échange n'est pas automatiquement le résultat d'une session |

## Ne pas déduire deux fois les mêmes frais

Calcul purement hypothétique : supposons un PnL brut des opérations clôturées de
**+$24**, des frais de trading de **$4** et un financement inclus constituant un
crédit de **+$1**. Si le résultat réalisé déclaré est déjà net de ces frais, il
est de **+$20**. Ajouter le crédit de financement donne **+$21**. Déduire encore
les $4 reviendrait à les compter deux fois.

Cet exemple explique le principe du rapprochement ; ce n'est pas une formule
universelle pour tous les écrans ou relevés de plateforme. Lisez la base indiquée,
les coûts inclus, la couverture du financement et l'exposition ouverte éventuelle.
Le financement constitue un élément comptable distinct et n'entre pas
nécessairement dans le résultat des opérations clôturées.

## Une donnée manquante n'est pas un zéro

Un zéro numérique peut représenter un zéro connu. Une couverture de financement
manquante ne prouve pas l'absence de débit ou de crédit. La relecture historique
utilise les données de financement disponibles et admissibles ; consultez les
détails avant de comparer le résultat au règlement de la plateforme d'échange.
Ne déduisez pas un financement exact de la différence entre deux soldes arrondis.

## Le drawdown n'est pas seulement la pire opération

Le drawdown maximal mesure la baisse depuis un sommet antérieur de la série
de valeur du compte ou de solde choisie. Une série hypothétique
**$1000 -> $1030 -> $1018** présente une baisse du sommet au creux de **$12**,
bien qu'elle se termine au-dessus du solde initial. Plusieurs opérations
perdantes peuvent contribuer à un même drawdown.

La base d'échantillonnage compte. Une série fondée sur les clôtures diffère d'une
valorisation continue incluant les positions ouvertes et peut ne pas montrer son
point bas pendant une opération. Utilisez la base décrite dans les détails des
résultats Citrine ; ne considérez pas un chiffre fondé sur les clôtures comme la
perte réelle maximale possible et ne supposez pas qu'un ordre stop garantit un
prix d'exécution particulier.

## Lorsque deux exécutions diffèrent

Comparez d'abord les quantités et les heures d'exécution, puis les prix, l'origine
des frais, le financement et l'exposition ouverte. Conservez les exports originaux
sans modification. Pour l'assistance, décrivez l'écart et ne fournissez que les
informations effectivement demandées ; ne publiez pas d'exports de compte complets.

[Méthodologie de backtesting](https://citrineedge.com/fr/backtesting/) |
[Diagnostic en toute sécurité](safe-troubleshooting.md) |
[Retour au manuel](../README.md)
