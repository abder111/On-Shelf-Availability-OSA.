Introduction
=================================================


Le système de détection On-Shelf Availability (OSA) est une solution avancée de vision par ordinateur conçue pour identifier automatiquement les espaces vides sur les rayons, détecter les étagères et reconnaître les produits présents dans un environnement commercial.

Dans le secteur de la grande distribution et du commerce de détail, les ruptures de stock représentent un enjeu majeur pouvant entraîner jusqu'à 4% de pertes de ventes annuelles. Notre solution technologique permet aux détaillants d'optimiser la gestion des stocks, d'améliorer l'expérience client et de maximiser les ventes en assurant une disponibilité optimale des produits.

Le système OSA utilise des algorithmes d'intelligence artificielle de pointe pour analyser en temps réel l'état des rayons et fournir des informations précieuses aux gestionnaires de magasins.

Objectifs du Système
--------------------

Le système a été développé avec des objectifs précis pour répondre aux besoins spécifiques du secteur de la distribution :

- **Détecter les espaces vides sur les étagères** : Identification automatique des zones nécessitant un réapprovisionnement
- **Identifier et localiser les étagères** : Cartographie précise de l'espace commercial pour un suivi optimal
- **Reconnaître les produits présents** : Classification des articles présents sur les rayons
- **Détecter les produits individuels** : Comptage précis des unités pour une gestion fine des stocks
- **Générer des rapports en temps réel** : Documentation détaillée sur l'état des stocks pour faciliter la prise de décision
- **Alerter le personnel** : Notifications automatiques en cas de rupture de stock pour une action rapide

Architecture du Système
-----------------------

Le système OSA repose sur une architecture modulaire comprenant quatre modèles de détection principaux qui fonctionnent en séquence pour assurer une analyse complète et précise des rayonnages.

.. code-block::

    ┌─────────────────┐     ┌────────────────┐     ┌─────────────────┐     ┌───────────────────────────┐
    │                 │     │                │     │                 │     │                           │
    │  Détection des  │────▶│ Détection des  │────▶│ Détection des   │────▶│ Détection des produits    │
    │    étagères     │     │     vides      │     │    produits     │     │     individuels           │
    │   (shelf.pt)    │     │   (void.pt)    │     │  (products.pt)  │     │ (individual_products.pt)  │
    │                 │     │                │     │                 │     │                           │
    └─────────────────┘     └────────────────┘     └─────────────────┘     └───────────────────────────┘
             │                     │                       │                           │
             ▼                     ▼                       ▼                           ▼
    ┌───────────────────────────────────────────────────────────────────────────────────────────────┐
    │                                   Traitement des données                                      │
    └───────────────────────────────────────────────────────────────────────────────────────────────┘
                                              │
                                              ▼
    ┌───────────────────────────────────────────────────────────────────────────────────────────────┐
    │                                 Génération des rapports                                       │
    └───────────────────────────────────────────────────────────────────────────────────────────────┘


Support
-------

- Pour toute question, me contactez abderrahmanessafi133@gamil.com .


