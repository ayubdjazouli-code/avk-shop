# AVK SHOP — Pistes fournisseurs et plan sans stock

Ce document est une liste de prospection, pas une validation de fournisseur. Les prix publics du catalogue du site sont des **prix de vente envisagés**, et non des prix d'achat fournisseurs confirmés.

## Modèle choisi : vendre sans stock

AVK teste d'abord le **print-on-demand (POD)** : le client commande un vêtement personnalisé, le prestataire le produit puis l'expédie. Cela évite d'acheter un stock à l'avance, mais le coût unitaire est généralement plus élevé qu'une production en volume.

## Comparaison des deux pistes prioritaires

| Prestataire | Ce que les pages officielles indiquent | Coût / automatisation | Point de vigilance |
|---|---|---|---|
| [Printful](https://www.printful.com/fr) | Catalogue de plus de 450 produits personnalisables, sans minimum de commande ; bons de livraison en marque blanche avec logo ou message. | Offre gratuite annoncée ; facturation à chaque commande pour le produit, l'impression, la livraison et les taxes éventuelles. Intégrations e-commerce disponibles. | Vérifier le prix final de chaque vêtement et la livraison vers la France ; commander un échantillon avant publication. |
| [DropShipPrint](https://dropshipprint.fr/fr/) | Impression textile à la demande, sans minimum, production annoncée en France et expédition en marque blanche selon la formule. | Offre gratuite : paiement à la commande, mais le colis indique DropShipPrint comme expéditeur. Offre Shop 1 annoncée à 19 € TTC avec expédition à votre nom. API Shopify annoncée à 29 € TTC. | Le raccordement d'un site personnalisé comme AVK nécessite un développement/API ou un processus manuel. L'offre gratuite n'est pas en marque blanche. Confirmer les tarifs produits, livraison et délais. |

Sources officielles consultées : [tarifs DropShipPrint](https://dropshipprint.fr/fr/tarifs), [FAQ DropShipPrint](https://dropshipprint.fr/fr/faq), [fonctionnement DropShipPrint](https://dropshipprint.fr/fr/how-it-works), [tarifs Printful](https://help.printful.com/hc/fr/articles/50261163157905-Combien-co%C3%BBte-Printful).

## Recommandation de départ

1. Comparer en priorité Printful et DropShipPrint sur **un t-shirt**, **un hoodie** et **un sweat**.
2. Créer seulement 2 ou 3 designs AVK simples pour le premier test.
3. Commander un échantillon de chaque prestataire retenu : vérifier tissu, coupe, impression, emballage et délai réel.
4. Calculer la marge avant de fixer le prix public : prix payé au prestataire + livraison + frais de paiement + éventuels retours + taxes.
5. Ne publier aucun article comme disponible tant que son prix, ses tailles, son délai et son échantillon ne sont pas validés.

## Important : état technique du site AVK

Le site actuel est une vitrine HTML hébergée dans un dépôt GitHub. Son panier est une démonstration locale et le paiement est volontairement désactivé. Il n'est **pas connecté** à Printful ou DropShipPrint et ne transmet aucune commande à un fournisseur.

Pour automatiser réellement les ventes, il faudra choisir une solution de boutique compatible ou développer une intégration sécurisée. Ne jamais mettre de clé API secrète dans le code HTML public du site. Avant toute ouverture des paiements, il faudra aussi préparer les informations légales, CGV, politique de confidentialité, livraison, retours et rétractation.

## Comparatif complémentaire vérifié le 19 novembre 2026

Trois pistes POD à tester avant de sélectionner les références du catalogue :

| Fournisseur | Intérêt | Coûts et limites à garder en tête |
|---|---|---|
| [TPOP](https://www.tpop.com/pricing) | Prestataire français, POD sans stock, colis à la marque, intégrations notamment Shopify et WooCommerce. | Compte POD gratuit annoncé ; livraison France affichée à partir de 3,95 € HT pour certains produits (t-shirts, tote bags, casquettes) et 5,20 € HT pour certains sweats/hoodies. Délais annoncés : production 2 à 4 jours puis 2 à 3 jours ouvrés en France. Vérifier le tarif exact du modèle et les intégrations disponibles pour AVK. |
| [Printful](https://www.printful.com/fr/print-on-demand-france) | Catalogue large, production/expédition à la commande, API et intégrations e-commerce. | Pas d'abonnement obligatoire annoncé pour démarrer ; le coût dépend du produit, du marquage, de la livraison et des taxes. Le site AVK étant un HTML personnalisé, il faudra une intégration côté serveur ou une gestion manuelle sécurisée. |
| [DropShipPrint](https://dropshipprint.fr/fr/products/list) | Catalogue textile et accessoires, personnalisation à la demande, piste française. | Le catalogue public affiche par exemple des t-shirts dès 9,80 € HT, des casquettes dès 9,40 € HT et des hoodies dès 18,70 € HT. Ce sont des prix d'appel : impression, options, livraison et TVA doivent être confirmées avant calcul de marge. |

Sources de contrôle : [tarifs et livraison TPOP](https://www.tpop.com/page/shipping), [offres TPOP](https://www.tpop.com/pricing), [catalogue DropShipPrint](https://dropshipprint.fr/fr/products/list), [fonctionnement Printful en France](https://www.printful.com/fr/print-on-demand-france).

**À retenir :** le coût affiché d'un produit vierge ou personnalisé n'est pas le coût complet rendu chez le client. Comparer pour chaque référence le prix produit + impression + livraison + TVA + frais de paiement, puis commander un échantillon. Les délais annoncés sont indicatifs et doivent être confirmés au moment de la commande.

## Autres pistes à garder pour plus tard

| Fournisseur | Intérêt pour AVK | À vérifier |
|---|---|---|
| [Black Industry — espace professionnel](https://blackindustry.com/pages/espace-professionnel) | Textile vierge : t-shirts, sweats, hoodies et pantalons. | Compte pro, tarifs HT, stocks, minimums et expédition directe au client final. |
| [STYCLOV](https://www.europages.fr/entreprises/france/streetwear.html) | T-shirts oversize et basiques streetwear. | Prix exact, minimum de commande, tailles, livraison et retours. |
| [Amikal Design](https://www.amikal-design.com/) | Textile vierge et personnalisé. | Devis revendeur, prix unitaires, frais de marquage et délais. |
| [Uniforméo](https://uniformeo.com/) | Textile, casquettes, sacs et accessoires personnalisables. | Accès pro, tarifs HT, minimums et frais de personnalisation. |

Les grossistes en lots et les fournisseurs qui exigent un minimum de commande sont moins adaptés au démarrage sans stock.

## Contrôles obligatoires avant la première vente

- Commander et contrôler un échantillon.
- Obtenir les prix complets, frais de livraison et délais par écrit.
- Vérifier les tailles, coloris, stocks et politique de retours.
- Confirmer les droits d'utilisation des visuels et la revente.
- Vérifier si les colis sont expédiés en marque blanche et avec quel nom d'expéditeur.
- Confirmer le suivi colis et la procédure en cas de perte ou de défaut.
- Calculer la marge réelle avant d'afficher un prix.
- Ne pas encaisser de commande tant que le paiement, la livraison et les obligations légales ne sont pas prêts.

## Prix de vente envisagés sur le catalogue AVK

- T-shirts : 19,90 à 24,90 €
- Hoodies et sweats : 34,90 à 42,90 €
- Jogging et cargo : 29,90 à 34,90 €
- Casquette et bonnet : 14,90 à 16,90 €
- Petits accessoires : 9,90 à 24,90 €

Ces montants sont des hypothèses de positionnement, pas des marges garanties. Ils devront être recalculés à partir des prix fournisseurs réellement obtenus.
