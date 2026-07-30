# Évaluation de l'Impact de l'Adoption du Mobile Money chez les Éleveurs Laitiers

Ce dépôt présente le tableau de bord Power BI développé dans le cadre de mon mémoire de stage, analysant l'impact causal du portefeuille numérique sur les comportements économiques des éleveurs.

##  Cascade de Sélection & Vue Globale
[![KPI Globaux](KPI_overview.png)](KPI_overview.png)

L'échantillon suit les étapes de sélection suivantes :
* **Échantillon total** : 1 208 éleveurs
* **Équipés en téléphone portable** : 864 éleveurs
* **Adoptants du Mobile Money** : 480 éleveurs

##  Résultats de l'Effet Causal (Méthode PSM - ATT)
[![Impact Causal](Causal_Impact.png)](Causal_Impact.png)

Le modèle d'Appariement sur Score de Propension (PSM) met en évidence les impacts suivants :

###  Impacts Positifs & Significatifs
* **Capital Bétail (Stock de richesse)** : **+1.11 \*\*** (Significatif au seuil de 5%) — L'adoption favorise l'épargne sur pied et l'accumulation du cheptel.
* **Employabilité (Salarier des bergers)** : **+0.103 \*\*** (Significatif au seuil de 5%) — Augmentation de 10,3 points de la probabilité d'embaucher des bergers salariés.

###  Impacts Non Significatifs (Effets Neutres)
* **Revenu Laitier Courant** : **+16 022 FCFA (ns)** — Pas d'effet à court terme sur les gains financiers directs.
* **Livraison Laiterie (collecte_ldb)** : **+0.028 (ns)** — L'outil ne modifie pas la régularité des livraisons à la Laiterie du Berger.

##  Production et Ventes de Lait
[![Statistiques Descriptives](Descriptive_stats.png)](Descriptive_stats.png)

## 🛠️ Outils utilisés pour corriger le biais de sélection et pour la PSM
* **Power BI Desktop** (Modélisation de données et Visualisation KPI)
* **DAX** (Création des mesures et filtres d'étapes)
* **Stata / R / 
